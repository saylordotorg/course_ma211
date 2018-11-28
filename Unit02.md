---
layout: default
title: "MA211: Linear Algebra"
course_description: "An introduction to the study of linear equations and vectors through the theory and practice of analyzing linear relations and their behavior under linear transformations."
next: ../Unit03
previous: ../Unit01
---
**Unit 2: Determinants, Rank, and Linear Transformations** <span
id="2"></span> 
**Despite the complicated definition of determinants, they are very
useful because they allow you to determine, using only one number,
whether or not a matrix is invertible.  They also are helpful for
computing eigenvalues, which you will learn about later.  In this unit,
you will learn about ways to find the determinants and to use
determinants to compute the inverse of a matrix.*  
  
 *You will learn about the rank of the matrix, a very important concept
in linear algebra.  You will begin by studying the row-reduced echelon
form of a matrix and proving that the row-reduced echelon form for a
given matrix is unique.  This is useful, because you can logically
deduce important conclusions about the original matrix by examining its
unique row-reduced echelon form.  You will then learn that the rank of a
matrix is related to the number of linearly independent columns or rows
of that matrix; it describes the dimensionality of the space.  It is
also very important in the use of matrices to solve a system of linear
equations, because it tells you whether Ax = 0 has zero, one, or an
infinite number of solutions.*  
  
 *Finally, you will learn how matrices also arise in geometry,
especially while studying certain types of linear transformations.  You
will learn that a m*x*n matrix can be used to transform vectors in
F<sup>n</sup> to vectors in F<sup>m</sup> via matrix multiplication.  As
you will see, these types of transformation arise quite naturally in
linear algebra and are important for applications in mathematics,
physics, and engineering. **

**Unit 2 Time Advisory**  
This unit should take you approximately 25 hours to complete.  
  
 ******<span id="238_time_advisory" class="showltimeadivisoryspan"
style="display: inline; ">☐    Subunit 2.1: 7 hours</span>******

******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Sub-subunit 2.1.1: 1 hour</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Sub-subunit 2.1.2: 6 hours</span>******

******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Reading: 1 hour</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Assignment: 5 hours</span>******

******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Subunit 2.2: 11 hours</span>******

******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Sub-subunit 2.2.1: 1 hour</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Sub-subunit 2.2.2: 1 hour</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Sub-subunit 2.2.3: 1 hour</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Sub-subunit 2.2.4: 2 hours</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Sub-subunit 2.2.5: 6 hours</span>******

******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Reading: 2 hours</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Assignment: 4 hours</span>******

******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Subunit 2.3: 7 hours</span>******

******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Reading: 3 hours</span>******  
  
 ******<span class="showltimeadivisoryspan"
style="display: inline; ">******<span id="238_time_advisory"
class="showltimeadivisoryspan" style="display: inline; ">☐  
 </span>******Assignment: 4 hours</span>******

 

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   define and compute the ijth minor of a nxn matrix;
-   define and compute the ijth cofactor of a nxn matrix;
-   find the determinant by expanding along rows and columns;
-   use the method of Laplace expansion;
-   state properties of determinants;
-   find determinants using row operations;
-   find the inverse of a matrix;
-   state and use Cramer’s rule to find a solution to a system of
    equations;
-   define *elementary matrices*;
-   define *rank* (determinant rank, row rank, column rank);
-   find the rank of a matrix;
-   obtain the row-reduced echelon form for a matrix;
-   define and verify linear independence;
-   determine whether a given set of vectors is linearly independent;
-   define span, basis, and dimension for a vector space;
-   extend an independent set of vectors to form a basis;
-   define and find the kernel of a matrix;
-   define, compute, and find the null space of a matrix;
-   state and apply the rank-nullity theorem;
-   identify the relation between rank and existence of solutions to
    linear systems;
-   determine whether a given set is a subspace;
-   compute the dimension of a space;
-   define and compute linear transformations;
-   construct the matrix of a linear transformation;
-   construct the matrix for a projection;
-   construct the matrix for a rotation;
-   find the general solution to a linear system;
-   discuss row equivalence and use row and column space to solve linear
    systems;
-   define *spanning set* and determine the span of a set of vectors;
-   show that a set of vectors is a basis;
-   define and compute column space, row space, nullspace, and rank;
-   describe how the determinant changes as a result of elementary row
    operations;
-   compute the determinant using cofactor expansions;
-   compute the determinant row reduction; and
-   compute the determinant using Cramer’s rule.

**2.1 Determinants** <span id="2.1"></span> 
**2.1.1 Basic Techniques and Properties** <span id="2.1.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 6: Determinants:” “Section 6.1: Basic Techniques and
    Properties”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    6: Determinants:” “Section 6.1: Basic Techniques and Properties”
    (PDF)  
        
     Instructions: Please click on the link above, and read Section 6.1
    on pages 97–104.  Section 6.1 will provide an introduction to
    determinants and techniques for finding them.  This reading should
    take you approximately 1 hour to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.1.2 Applications** <span id="2.1.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 6: Determinants:” “Section 6.2: Applications”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    6: Determinants:” “Section 6.2: Applications” (PDF)  
        
     Instructions: Please click on the link above, and read Section 6.2
    on pages 104–109.  Section 6.2 will introduce some applications,
    including Cramer’s rule.  This reading should take you approximately
    1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 6: Determinants:” “Section 6.3: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    6: Determinants:” “Section 6.3: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF.
     Scroll down to page 109, and complete problems 1, 3, 4, 5, 9, 11,
    13, 16, 20, 21, 24, 26, 28, 32, and 36.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 28–38.  This assessment should
    take you approximately 5 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2 Rank of a Matrix** <span id="2.2"></span> 
**2.2.1 Elementary Matrices** <span id="2.2.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 8: Rank of a Matrix:” “Section 8.1: Elementary Matrices”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    8: Rank of a Matrix:” “Section 8.1: Elementary Matrices” (PDF)  
        
     Instructions: Please click on the link above, and read Section 8.1
    on pages 129–134.  Section 8.1 will introduce the elementary
    matrices, which result from doing a row operation to the identity
    matrix.  This reading should take you approximately 1 hour to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.2 The Row Reduced Echelon Form of a Matrix** <span
id="2.2.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 8: Rank of a Matrix:” “Section 8.2: The Row Reduced Echelon
    Form of a Matrix”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    8: Rank of a Matrix:” “Section 8.2: The Row Reduced Echelon Form of
    a Matrix” (PDF)  
        
     Instructions: Please click on the link above, and read Section 8.2
    on pages 135–139.  Section 8.2 will review the description of the
    row-reduced echelon form.  This reading should take you
    approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.3 The Rank of a Matrix** <span id="2.2.3"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 8: Rank of a Matrix:” “Section 8.3: The Rank of a Matrix”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    8: Rank of a Matrix:” “Section 8.3: The Rank of a Matrix” (PDF)  
        
     Instructions: Please click on the link above, and read Section 8.3
    on pages 139–142.  Section 8.3 will define rank and explain how to
    find the rank.  This reading should take you approximately 1 hour to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.2.4 Linear Independence and Bases** <span id="2.2.4"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 8: Rank of a Matrix:” “Section 8.4: Linear Independence and
    Bases”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    8: Rank of a Matrix:” “Section 8.4: Linear Independence and Bases”
    (PDF)  
        
     Instructions: Please click on the link above, and read Section 8.4
    on pages 142–152.  Section 8.4 will introduce linear independence
    and bases.  This reading should take you approximately 2 hours to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.2.5 Fredholm Alternative** <span id="2.2.5"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 8: Rank of a Matrix:” “Section 8.5: Fredholm Alternative”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    8: Rank of a Matrix:” “Section 8.5: Fredholm Alternative” (PDF)  
        
     Instructions: Please click on the link above, and read Section 8.5
    on pages 153–156.  Section 8.5will introduce the Fredholm
    Alternative for the case of real matrices here.  This reading should
    take you approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 8: Rank of a Matrix:” “Section 8.6: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    8: Rank of a Matrix:” “Section 8.6: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF. 
    Scroll down to page 156, and complete problems 2, 5, 7, 10, 12, 16,
    18, 25, 32, 34, 45, 50, and 54.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 38–49.  This assessment should
    take you approximately 4 hours to complete.    
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**2.4 Linear Transformations** <span id="2.4"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 9: Linear Transformations:” “Section 9.1: Linear
    Transformations” and “Section 9.2: Constructing the Matrix of a
    Linear Transformation”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    9: Linear Transformations:” “Section 9.1: Linear Transformations”
    and “Section 9.2: Constructing the Matrix of a Linear
    Transformation” (PDF)  
        
     Instructions: Please click on the link above, and read Sections 9.1
    and 9.2 on pages 163–173.  Section 9.1 and Section 9.2 will
    introduce linear transformations.  These readings should take you
    approximately 3 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 9: Linear Transformations:” “Section 9.3: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    9: Linear Transformations:” “Section 9.3: Exercises” (PDF)  
        
     Instructions: Please click on the above link to open the PDF. 
    Scroll down to page 173, and work on problems 2, 7, 9, 14, 17, 20,
    23, 28, 32, 47, and 51.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 49–59.  This assessment should
    take you approximately 4 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


