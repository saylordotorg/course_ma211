**Unit 3: Spectral Theory, Matrices, and Inner Product** <span
id="3"></span> 
**We have seen that matrix A corresponds to a linear transformation, T,
i.e. T(x) =Ax.  If the matrix is square, then those nonzero vectors, any
of which are transformed to a multiple of themselves, are called
eigenvectors of the matrix, and the mutliples by which they are
transformed are called eigenvalues (*eigen*is the German word for
characteristic).  The set of eigenvalues is called the spectrum of A and
plays an important role in linear algebra.  In this unit, you will study
the spectrum of a square matrix in detail.*  
  
 *The first thing that we will see is that the eigenvalues of an nxn
matrix correspond to the roots of an n<sup>th</sup> degree polynomial,
called the characteristic polynomial of A.  As you know from algebra,
roots of a polynomial can have multiplicity larger than 1.  For
eigenvalues, the multiplicity of a root is called the algebraic
multiplicity of the eigenvalue, while the dimension of the set of
vectors for which it is an eigenvalue is called the geometric
multiplicity of the eigenvalue.  If these two multiplicities are the
same for all eigenvalues, then you will see that A is similar to a
matrix with nonzero entries only along the main diagonal, that is
A=S<sup>-1</sup>DS for an invertible matrix S.  In fact, the diagonal
entries of D are the eigenvalues of A, and the columns of S are a basis
of R<sup>n</sup> consisting of eigenvectors.  Since solving polynomial
equations can be difficult, you will study methods of estimating
eigenvalues just by looking at the matrix.*  
  
 *You will then consider situations where the eigenvalues are known to
be real and the matrix S, which diagonalizes A, can take a special form.
 If the matrix A is symmetric, that is a<sub>ij</sub>=a<sub>ji</sub> 
for all i,j, then you will see that A can be diagonalized, that is, all
roots of the characteristic polynomial are real numbers.  Further, you
will learn how to choose the basis of eigenvalues, which comprise S so
that the rows and columns each are unit vectors and are mutually
perpendicular.  Such matrices are called orthogonal and have the
property that S<sup>-1</sup>=S<sup>T</sup>, where S<sup>T</sup> is the
matrix obtained from S by interchanging its rows and columns.  Since not
all square matrices are diagonalizable, you will need one of the most
important theorems in the spectral theory of matrices: Schur’s Theorem,
which is useful for analyzing the structure of matrices.*  
  
 *In linear algebra, you usually want to see whether or not Ax = b has
any solutions.  Often Ax = b has no solution because there are more
equations than unknowns, that is, the linear system is inconsistent and
b is not in the column space of A.  In this case, you can try to find an
approximation using a very important technique of the least square
approximation.  Another thing you want to do is to characterize when Ax
= b has a solution, that is, construct conditions for solvability of the
system.  One way of doing this is by using Fredholm’s Alternative, which
is discussed in this unit.  Fredholm’s Alternative is important, because
it can be generalized to more general vector spaces, where the concept
of rank of a determinant is not defined.  Finally, this unit discusses
an important result known as the singular value decomposition, which
gives a factorization of a matrix.* *

**Unit 3 Time Advisory**  
This unit should take you approximately 19 hours to complete.  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Subunit 3.1: 8 hours

******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Sub-subunit 3.1.1: 2 hours  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Sub-subunit 3.1.2: 1 hour  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Sub-subunit 3.1.3: 5 hours

******<span class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Reading: 0.5 hour  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Assignment: 4.5 hours

******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Subunit 3.2: 11 hours  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Sub-subunit 3.2.1: 2 hours  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Sub-subunit 3.2.2: 2 hours  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Sub-subunit 3.2.3: 1 hour  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Sub-subunit 3.2.4: 6 hours

******<span class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Reading: 2 hours  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    </span>******Assignment: 4 hours

**Unit3 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   find the algebraic multiplicity of an eigenvalue;
-   find the geometric multiplicity of an eigenvalue;
-   write and identify the characteristic equation for a matrix;
-   explain what it means for matrices to be similar;
-   determine whether a matrix is diagonalizable, and diagonalize
    matrices;
-   find the matrix exponential;
-   find the characteristic equation, eigenvalues, and corresponding
    eigenvectors of a given matrix;
-   estimate the eigenvalues for matrices;
-   state the eigenvalue problem from an algebraic perspective;
-   state the eigenvalue problem from a geometric perspective;
-   determine whether a given matrix is defective;
-   calculate the eigenvalues and corresponding eigenvectors for a
    linear transformation;
-   define *orthogonal matrices*;
-   determine whether a given matrix is orthogonal;
-   find eigenvalues of a symmetric and a skew-symmetric matrix;
-   find an orthonormal basis of eigenvectors for the matrix;
-   ­determine whether a given matrix is symmetric;
-   determine whether a given matrix is skew-symmetric;
-   define an orthonormal set of vectors;
-   use the Gram-Schmidt process to find an orthonormal basis;
-   find the least squares solution to a minimization problem; and
-   provide a factorization for a matrix using singular value
    decomposition.

**3.1 Spectral Theory** <span id="3.1"></span> 
**3.1.1 Eigenvalues and Eigenvectors of a Matrix** <span
id="3.1.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 12: Spectral Theory:” “Section 12.1: Eigenvalues and
    Eigenvectors of a Matrix”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    12: Spectral Theory:” “Section 12.1: Eigenvalues and Eigenvectors of
    a Matrix” (PDF)  
        
     Instructions: Please click on the link above, and read Section 12.1
    on pages 215–231.  Spectral Theory refers to the study of
    eigenvalues and eigenvectors of a matrix, which is introduced in
    Section 12.1.  This reading should take you approximately 2 hours to
    complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.1.2 The Estimation of Eigenvalues** <span id="3.1.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 12: Spectral Theory:” “Section 12.3: The Estimation of
    Eigenvalues”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    12: Spectral Theory:” “Section 12.3: The Estimation of Eigenvalues”
    (PDF)  
        
     Instructions: Please click on the link above and read Section 12.3
    on pages 236–237.  Section 12.3 introduces Gerschgorin’s Theorem,
    which provides a way to estimate where the eigenvalues are just from
    looking at the matrix.  This reading should take you approximately
    30 minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 12: Spectral Theory:” “Section 12.4: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    12: Spectral Theory:” “Section 12.4: Exercises” (PDF)  
        
     Instructions: Please click on the above link to open the PDF. 
    Scroll down to page 237, and complete problems 3, 5, 8, 11, 13, 20,
    25, 28, 43, 48, and 54.  Next, click on
    “[Solutions](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 76–84.  This assessment should
    take you approximately 4 hours and 30 minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2 Matrices and Inner Product** <span id="3.2"></span> 
**3.2.1 Symmetric and Orthogonal Matrices** <span id="3.2.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 13: Matrices and the Inner Product:” “Section 13.1:
    Symmetric and Orthogonal Matrices”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    13: Matrices and the Inner Product:” “Section 13.1: Symmetric and
    Orthogonal Matrices” (PDF)  
        
     Instructions: Please click on the link above, and read Section 13.1
    on pages 245–255.  Section 13.1 will introduce symmetric and
    orthogonal matrices.  This reading should take you approximately 2
    hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.2 Fundamental Theory and Generalizations** <span
id="3.2.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 13: Matrices and the Inner Product:” “Section 13.2:
    Fundamental Theory and Generalizations”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    13: Matrices and the Inner Product:” “Section 13.2: Fundamental
    Theory and Generalizations” (PDF)  
        
     Instructions: Please click on the link above, and read Section 13.2
    on pages 255–262.  Sections 13.2 will discuss several results
    including the Gram-Schmidt process and the Schur’s Theorem.  This
    reading should take you approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.3 Least Square Approximation** <span id="3.2.3"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 13: Matrices and the Inner Product:” “Section 13.3: Least
    Square Approximation”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    13: Matrices and the Inner Product:” “Section 13.3: Least Square
    Approximation” (PDF)  
        
     Instructions: Please click on the link above, and read Section 13.3
    on pages 263–266.  Sections 13.3 discusses a very important
    technique known as the Least Square Approximation.  This reading
    should take you approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**3.2.4 Additional Results** <span id="3.2.4"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 13: Matrices and the Inner Product:” “Section 13.4: The
    Right Polar Factorization,” “Section 13.5: The Singular Value
    Decomposition,” “Section 13.6: Approximation in the Frobenius Norm,”
    and “Section 13.7: Moore Penrose Inverse”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    13: Matrices and the Inner Product:” “Section 13.4: The Right Polar
    Factorization,” “Section 13.5: The Singular Value Decomposition,”
    “Section 13.6: Approximation in the Frobenius Norm,” and “Section
    13.7: Moore Penrose Inverse” (PDF)  
        
     Instructions: Please click on the link above, and read the
    indicated sections on pages 267–274.  Sections 13.4–13.7 will
    introduce several important topics and results.  Please work through
    these sections carefully.  These readings should take you
    approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 13: Matrices and the Inner Product:” “Section 13.8:
    Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    13: Matrices and the Inner Products:” “Section 13.8: Exercises”
    (PDF)  
        
     Instructions: Please click on the link above to open the PDF. 
    Scroll down to page 274, and work on problems 2, 5, 10, 14, 19, 24,
    28, 32, 37, 39, 43, 48, 52, and 57.  Next, click on
    “[Solutions](http://www.saylor.org/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 88–106.  This assessment
    should take you approximately 4 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


