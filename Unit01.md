---
layout: default
title: "MA211: Linear Algebra"
course_description: "An introduction to the study of linear equations and vectors through the theory and practice of analyzing linear relations and their behavior under linear transformations."
next: ../Unit02
previous: ../Intro
---
**Unit 1: Vector Products, Systems of Equations, and Matrices** <span
id="1"></span> 

**This unit begins with a review of vectors.  You will learn the
geometric meaning of vectors, which is especially significant in
R<sup>2</sup> and R<sup>3</sup>.  Next, you will learn the geometric
meaning of vector addition and scalar multiplication.  Finally, you will
apply study vectors in the context of physics to model force and other
physical vectors like velocity.*  
  
 *In the next chapter, you will begin learning about vector products. 
There are two ways of multiplying vectors, both of which are of great
importance in applications.  The first type of a product is called the
dot product, also called the scalar product or the inner product.  You
will then study the geometric significance of the dot product and
applications of dot product by studying the concepts of work and
projections.  Next, you will begin the study of cross products. The
cross product is the other way of multiplying vectors, and it is
different from the dot product in fundamental ways.  You will learn both
the geometric meaning of the cross product and the description in terms
of coordinates.  Both descriptions of the cross product are important;
the geometric description is necessary to understand the applications to
physics and geometry while the coordinate description is necessary to
actually compute the cross product.  You will then learn techniques,
which will allow you to discover vector identities and simplify
expressions involving cross and dot products in three dimensions.*  
  
 *Next, you will begin exploring systems of linear equations.  The basic
idea is to study situations where there are several different variables
that are related in multiple ways.  These linear equations could
describe budget constraints in a business, physical constraints in an
engineering problem, or any number of other situations.  The key is that
these constraints can be described by linear equations.  The geometric
interpretation of these constraints is that each equation describes a
line or plane where potential solutions to the problem must lie.  The
task then is to figure out what combination of variable values solves
all of the different linear equations at the same time.  Geometrically,
this is where all of the lines or planes intersect.  Just as is the case
with the problems that the equations may be modeling, the system of
equations will sometimes have no solution, will sometimes have a single
solution, and will sometimes have an infinite number of solutions.*
 *Finally, you will learn about matrices andhow to write a system of
linear equations as a matrix equation.  While this may have at first
appeared to be merely a way of putting your coefficients in a table,
matrices in fact have many interesting (but not immediately obvious!)
properties.**

**Unit 1 Time Advisory**  
This unit should take you approximately 28.5 hours to complete.

**☐    **Subunit 1.1: 6 hours

**☐    **Sub-subunit 1.1.1: 1 hour  
  
 **☐    **Sub-subunit 1.1.2: 2 hours  
  
 **☐    **Sub-subunit 1.1.3: 3 hours

**☐    **Subunit 1.2: 9 hours

**☐    **Sub-subunit 1.2.1: 4 hours

**☐    **Reading: 1.5 hours  
  
 **☐    **Assignment: 2.5 hours

**☐    **Sub-subunit 1.2.2: 1 hour  
  
 **☐    **Sub-subunit 1.2.3: 4 hours

**☐    **Reading: 0.5 hour  
  
 **☐    **Assignment: 3.5 hours

**☐    **Subunit 1.3: 5.5 hours

**☐    **Sub-subunit 1.3.1: 0.5 hour  
  
 **☐    **Sub-subunit 1.3.2: 5 hours

**☐    **Reading: 1.5 hours  
  
 **☐    **Assignment: 3.5 hours

**☐    **Subunit 1.4: 8 hours

**☐    **Reading: 3 hours

**☐    **Assignment: 5 hours

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, you will be able to:  
-   explain and perform algebraic operations done with elements in
    F<sup>n</sup>;
-   explain the geometric meaning of vectors;
-   explain the geometric meaning of vector addition;
-   compute the distance between points in R<sup>n</sup>;
-   compute the length of a vector;
-   explain the geometric meaning of scalar multiplication;
-   draw a picture of points in R<sup>2</sup> and R<sup>3</sup> given
    ordered pairs;
-   explain how vectors are used to define force and velocity;
-   prove the Cauchy-Schwarz inequality;
-   explain the geometric significance of the dot product;
-   explain the geometric significance of the cross product;
-   define and compute work;
-   find the projection of a vector v onto a vector u;
-   state properties of the inner product;
-   find the angle between two vectors;
-   define and compute the cross product, the dot product, and the box
    product;
-   explain the distributive law for the cross product;
-   compute the volume of the parallelepiped;
-   define the *Kronecker delta*;
-   find solutions to a system of linear equations, both algebraically
    and graphically; and
-   use the Gauss elimination.

**1.1 Fn and Vector Products** <span id="1.1"></span> 
**1.1.1 Vectors and their Geometric Meaning** <span id="1.1.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 2: Fn:” “Section 2.1: Algebra in Fn,” “Section 2.2:
    Geometric Meaning of Vectors,” and “Section 2.3: Geometric Meaning
    of Vector Addition”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    2: Fn:” “Section 2.1: Algebra in Fn.” “Section 2.2: Geometric
    Meaning of Vectors,” and “Section 2.3: Geometric Meaning of Vector
    Addition” (PDF)  
        
     Instructions: Please click on the link above, and read the
    indicated sections on pages 23–27.  Section 2.1 introduces you to
    algebraic operations done with elements of Fn*.*  In Section 2.2,
    you will explore the geometric meaning of vectors, and in Section
    2.3, you will study the geometric interpretation of vector
    addition.  These readings should take you approximately 1 hour to
    complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.1.2 Length of a Vector and Scalar Multiplication** <span
id="1.1.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 2: Fn:” “Section 2.4: Distance between Points in Length of
    a Vector” and “Section 2.5: Geometric Meaning of Scalar
    Multiplication”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    2: Fn*.*” “Section 2.4: Distance between Points In Rn Length of a
    Vector” and “Section 2.5: Geometric Meaning of Scalar
    Multiplication” (PDF)  
        
     Instructions: Please click on the link above, and read the
    indicated sections on pages 27–31.  In Section 2.4, you will study
    how distance is defined between two points in Rn.  In Section 2.5,
    you will explore the geometric meaning of scalar multiplication. 
    These readings should take you approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    "Chapter 2:" “Section 2.6: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    2: Fn.” “Section 2.6: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF.
     Scroll down to page 31 to Section 2.6, and complete problems 1, 2,
    4, and 5.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 5–6.  This assessment should
    take you approximately 1 hour to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.1.3 Vectors and Physics** <span id="1.1.3"></span> 
-   **Reading: Professor Kenneth Kuttler's Elementary Linear Algebra:
    "Chapter 2: Fn." "Section 2.7: Vectors and Physics"**

    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    2:” “Section 2.7: Vectors and Physics” (PDF)  
        
     Instructions: Please click on the link above, and read Section 2.7
    on pages 32–36.  In this section, you will learn about the concept
    of force.  This reading should take you approximately 1 hour to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler's Elementary Linear Algebra:
    "Chapter 2: Fn." "Section 2.8: Exercises"**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    2: Fn." “Section 2.8: Exercises”(PDF)  
      
     Instructions: Please click on the link above to open the PDF. 
    Scroll down to page 36, and complete problems 2, 3, 7, 9, 10, and
    11.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 6–8.  This assessment should
    take you approximately 2 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2 Vector Products** <span id="1.2"></span> 
**1.2.1 The Dot Product** <span id="1.2.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 3: Vector Products:” “Section 3.1: The Dot Product” and
    “Section 3.2: The Geometric Significance of the Dot Product”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    3: Vector Products:” “Section 3.1: The Dot Product” and “Section
    3.2: The Geometric Significance of the Dot Product” (PDF)  
        
     Instructions: Please click on the link above, and read the
    indicated sections on pages 39–47.  Section 3.1 will provide the
    definition and properties of the dot product.  Section 3.2 will
    discuss the geometric meaning of the dot product and then apply the
    ideas to the concepts of work and projection.  These readings should
    take you approximately 1 hour and 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 3: Vector Products:” “Section 3.3: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    3: Vector Products:” “Section 3.3: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF. 
    Scroll down to page 47, and work on problems 1, 2, 4, 6, 10, 14, 15,
    17, 20, and 21.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 8–10.  This assessment should
    take you approximately 2 hours and 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2.2 The Cross Product** <span id="1.2.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 3: Vector Products:” “Section 3.4: The Cross Product”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    3: Vector Product:” “Section 3.4: The Cross Product” (PDF)  
        
     Instructions: Please click on the link above, and read Section 3.4
    on pages 48–54.  Section 3.4 will provide the definition,
    properties, and the geometric meaning of the cross product.  This
    reading should take you approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.2.3 The Vector Identity Machine** <span id="1.2.3"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 3: Vector Products:” “Section 3.5: The Vector Identity
    Machine”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    3: Vector Products:” “Section 3.5: The Vector Identity Machine”
    (PDF)  
        
     Instructions: Please click on the link above, and read Section 3.5
    on pages 54–56.  Section 3.5 will introduce a technique that will
    allow you to discover vector identities and simplify expressions
    involving cross and dot products in three dimensions.  This reading
    should take you approximately 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 3: Vector Products:” “Section 3.6: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    3: Vector Products:” “Section 3.6: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF. 
    Scroll down to page 56, and complete problems 1, 4, 6, 7, 8, 9, 10,
    13, 16, 18, and 20.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 11–14.  This assessment should
    take you approximately 3 hours and 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.3 Systems of Equations** <span id="1.3"></span> 
**1.3.1 Systems of Equations, Geometry** <span id="1.3.1"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 4: Systems of Equations:” “Section 4.1: Systems of
    Equations, Geometry”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    4: Systems of Equations:” “Section 4.1: Systems of Equations,
    Geometry” (PDF)  
        
     Instructions: Please click on the link above, and read Section 4.1
    on pages 59–61.  Section 4.1 will explore how to find solution(s)
    for a system of linear equations by graphing.  This reading should
    take you approximately 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.3.2 Systems of Equations, Algebraic Procedures** <span
id="1.3.2"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 4: Systems of Equations:” “Section 4.2: Systems of
    Equations, Algebraic Procedures”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *Chapter
    4: Systems of Equations:” “Section 4.2: Systems of Equations,
    Algebraic Procedures” (PDF)  
        
     Instructions: Please click on the link above, and read Section 4.2
    on pages 61–72.  Section 4.2 will explore how to find solution(s)
    for a system of linear equations using elementary operations,
    Gaussian elimination, and other algebraic procedures.  This reading
    should take you approximately 1 hour and 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 4: Systems of Equations:” “Section 4.3: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    4: Systems of Equations:” “Section 4.3: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF. 
    Scroll down to page 72, and complete problems 1, 6, 12, 13, 17, 19,
    22, 30, 35, and 36.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 14–20.  This assessment should
    take you approximately 3 hours and 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.4 Matrices** <span id="1.4"></span> 
-   **Reading: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 5: Matrices:” “Section 5.1: Matrix Arithmetic”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    5: Matrices:” “Section 5.1: Matrix Arithmetic” (PDF)  
        
     Instructions: Please click on the link above, and read Section 5.1
    on pages 77–91.  Section 5.1 will provide an overview of matrices
    and matrix arithmetic.  This reading should take you approximately 3
    hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

-   **Assessment: Professor Kenneth Kuttler’s Elementary Linear Algebra:
    “Chapter 5: Matrices:” “Section 5.2: Exercises”**
    Link: Professor Kenneth Kuttler’s *[Elementary Linear
    Algebra:](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-4-26-12-Kuttler-OTC.pdf) *“Chapter
    5: Matrices:” “Section 5.2: Exercises” (PDF)  
        
     Instructions: Please click on the link above to open the PDF. 
    Scroll down to page 92, and complete problems 3, 5, 6, 7, 10, 12,
    16, 19, 24, 28, 32 37, 40, 44, 47, and 53.  Next, click on
    “[Solutions](https://resources.saylor.org/wwwresources/archived/site/wp-content/uploads/2012/04/Elementary-Linear-Algebra-Solutions-Manual-4-26-12-Kuttler-OTC.pdf)”
    (PDF) and check your answers on pages 19–28.  This assessment should
    take you approximately 5 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.


