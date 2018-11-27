---
layout: default
title: "MA211: Linear Algebra"
course_description: "An introduction to the study of linear equations and vectors through the theory and practice of analyzing linear relations and their behavior under linear transformations."
next: ../Unit05
previous: ../Unit03
---
**Unit 4: Vector Spaces and Linear Transformations** <span
id="4"></span> 
**This unit discusses vector spaces and linear transformations.  The
first topic you will study in this unit is that of an abstract vector
space.  You will see that a vector space is a collection of vectors that
satisfies a set of axioms.  Next, you will study ideas such as
subspaces, linear independence, and bases in the context of vector
spaces.  Remember to think of R or C if you are confused.  Next, you
will construct abstract fields and vector spaces.  You will begin this
by first reviewing some basic algebra relating to polynomials.  This is
both interesting and important, because it provides the basis for
constructing different kinds of fields.  Finally, you will look at inner
product spaces, which are vector spaces that also have an inner product,
before moving on to linear transformations, which is the second topic of
study in this unit.*  
  
 *Linear transformations have many applications within mathematics as
well as in fields outside of mathematics, such as physics.  You will
study the basic definitions of linear transformations and properties and
relations between these and matrices.  **

**Unit 4 Time Advisory**  
This unit should take you approximately 29.5 hours to complete.  
  
 ☐    Subunit 4.1: 19 hours
☐    Sub-subunit 4.1.1: 4 hours

☐    Reading: 2 hours  
  
 ☐    Assignment: 2 hours

☐    Sub-subunit 4.1.2: 7.5 hours

☐    Reading: 3.5 hours  
  
 ☐    Assignment: 4 hours

☐    Sub-subunit 4.1.3: 7.5 hours

☐    Reading: 3.5 hours  
  
 ☐    Assignment: 4 hours

☐    Subunit 4.2: 10.5 hours
☐    Sub-subunit 4.2.1: 0.5 hour  
  
 ☐    Sub-subunit 4.2.2: 1.5 hours  
  
 ☐    Sub-subunit 4.2.3: 1 hour  
  
 ☐    Sub-subunit 4.2.4: 2 hours  
  
 ☐    Sub-subunit 4.2.5: 5.5 hours

☐    Reading: 1.5 hours  
  
 ☐    Assignment: 4 hours

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   define *vector spaces*;
-   state the axioms of a vector space;
-   prove the Euclidean algorithm;
-   define *linear independence*;
-   determine if a given subset of a vector space is a subspace;
-   determine if a set of vectors is a basis for a vector space;
-   find the dimension of a subspace;
-   state and prove the exchange theorem;
-   define and provide examples of inner product spaces;
-   state and prove the Cauchy-Schwarz inequality;
-   apply the Gram-Schmidt process to inner product spaces;
-   determine if a transformation is linear;
-   determine if a function from one vector space to another is a linear
    transformation;
-   find matrix representations for a given linear transformation;
-   find the range and kernel of a transformation;
-   use linear transformations to prove that vector spaces are
    isomorphic;
-   explain which matrices are diagonalizable;
-   determine if given sets of vectors are orthogonal and find
    orthogonal projections;
-   solve least squares problems; and
-   find the Fourier approximation for a known function.

**4.1 Vector Spaces** <span id="4.1"></span> 
**4.1.1 Algebraic Considerations, Linear Independence, and Bases** <span
id="4.1.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 16: Vector Spaces:” “Section 16.1: Algebraic
    Considerations” and “Section 16.2.1: Linear Independence and
    Bases”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    16: Vector Spaces:” “Section 16.1: Algebraic Considerations” and
    “Section 16.2.1: Linear Independence and Bases” (PDF)  
        
     Instructions: Please click on the link above, and read Section 16.1
    on page 323 and section 16.2.1 on pages 325–330.  Section 16.1 will
    provide the definition of a vector space, and Section 16.2.1 will
    discuss subspaces, linear dependence, and bases.  These readings
    should take you approximately 2 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 16: Vector Spaces:” “Section 16.2: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    16: Vector Spaces:” “[Section 16.2:
    Exercises](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf)”
    (PDF)  
        
     Instructions:  Please click on the link above to open the PDF. 
    Scroll down to page 330, and complete problems 1, 2, 3, and 4. 
    Next, click on
    “[Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 124–125.  This assessment
    should take you approximately 2 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.1.2 Vector Spaces and Fields** <span id="4.1.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 16: Vector Spaces:” “Section 16.3: Vector Space and
    Fields”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    16: Vector Spaces:” “Section 16.3: Vector Space and Fields” (PDF)  
        
     Instructions: Please click on the link above, and read Section 16.3
    on pages 330–343.  Section 16.3 will discuss vector space and
    fields.  This reading should take you approximately 3 hours and 30
    minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 16: Vector Spaces:” “Section 16.4: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    16: Vector Spaces:” “Section 16.4: Exercises” (PDF)  
        
     Instructions:  Please click on the link above to open the PDF. 
    Scroll down to page 243, and work on problems 2, 4, 10, 12, 16, 20,
    24, and 29.  Next, click on
    “[Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 125–135.  This assessment
    should take you approximately 4 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.1.3 Inner Product Spaces** <span id="4.1.3"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 16: Vector Spaces:” “Section 16.5: Inner Product Spaces”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    16: Vector Spaces:” “Section 16.5: Inner Product Spaces” (PDF)  
        
     Instructions: Please click on the link above, and read Section 16.5
    on pages 348–361.  Section 16.5 will discuss vector spaces with
    inner products.  This reading should take you approximately 3 hours
    and 30 minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 16: Vector Spaces:” “Section 16.6: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    16: Vector Spaces:” “Section 16.6: Exercises” (PDF)  
        
     Instructions:  Please click on the above link to open the PDF.
     Scroll down to page 361, and complete problems 1, 4, 7, 12, 15, 17,
    and 22.  Next, click on
    “[Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 135–150.  This assessment
    should take you approximately 4 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.2 Linear Transformations** <span id="4.2"></span> 
**4.2.1 Matrix Multiplication and L(V,W)** <span id="4.2.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 17: Linear Transformations:” “Section 17.1: Matrix
    Multiplication as a Linear Transformation” and “Section 17.2: L(V,W)
    as a Vector Space”**
    Link: Professor Kenneth Kuttler’s [*Elementary Linear
    Algebra:*](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf)“Chapter
    17: Linear Transformations:” “Section 17.1: Matrix Multiplication as
    a Linear Transformation” and “Section 17.2: *L(V,W)* as a Vector
    Space” (PDF)  
        
     Instructions: Please click on the link above, and read the
    indicated sections on pages 367 and 368.  Sections 17.1 and 17.2
    will discuss linear transformations and vector spaces.  These
    readings should take you approximately 30 minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.2.2 Eigenvalues And Eigenvectors Of Linear Transformations** <span
id="4.2.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 17: Linear Transformations:” “Section 17.3: Eigenvalues and
    Eigenvectors of Linear Transformations”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    17: Linear Transformations:” “Section 17.3: Eigenvalues and
    Eigenvectors of Linear Transformations” (PDF)  
        
     Instructions: Please click on the above link, and read Section 17.3
    on pages 369–373.  Section 17.3 will discuss finding eigenvalues and
    eigenvectors of linear transformations.  This reading should take
    you approximately 1 hour and 30 minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.2.3 The Block Diagonal Matrices** <span id="4.2.3"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 17: Linear Transformations:” “Section 17.4: Block Diagonal
    Matrices”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    17: Linear Transformations:” “Section 17.4: Block Diagonal Matrices”
    (PDF)  
        
     Instructions: Please click on the link above, and read Section 17.4
    on pages 373–377.  Sections 17.4 will discuss linear
    transformations, which will result by multiplication by n × n
    matrices.  This reading should take you approximately 1 hour to
    complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.2.4 The Matrix of a Linear Transformation** <span
id="4.2.4"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 17: Linear Transformations:” “Section 17.5: The Matrix of a
    Linear Transformation”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    17:  Linear Transformations:” “Section 17.5: The Matrix of a Linear
    Transformatio” (PDF)  
        
     Instructions: Please click on the link above, and read Section 17.5
    on pages 377–386.  Section 17.4 will discuss matrices of linear
    transformations.  This reading should take you approximately 2 hours
    to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.2.5 The Matrix Exponential, Differential Equations** <span
id="4.2.5"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 17: Linear Transformations:” “Section 17.6: The Matrix
    Exponential, Differential Equations”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    17: Linear Transformations:” “Section 17.6: The Matrix Exponential,
    Differential Equations” (PDF)  
        
     Instructions: Please click on the link above, and read Section 17.6
    on pages 386–391.  Section 17.6 will introduce fundamental matrices,
    matrices whose entries are differentiable functions.  This reading
    should take you approximately 1 hour and 30 minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 17: Linear Transformations:” “Section 17.7: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    17: Linear Transformations:” “Section 17.7: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF.
     Scroll down to page 391, and work on problems 1, 3, 8, 12, 15, 18,
    and 21.  Next, click on
    “[Solutions](https://resources.saylor.org/archived/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 151–157.  This assessment
    should take you approximately 4 hours to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


