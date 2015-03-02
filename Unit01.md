---
layout: default
title: "MA304: Topics in Applied Mathematics"
course_description: "An introduction to mathematical topics not included in the standard coursework, delivered by topics and projects chosen by the student."
next: ../Unit02
previous: ../Intro
---
**Unit 1: Linear Analysis** <span id="1"></span> 
*In Unit 1, the theory of linear algebra studied in the Saylor
Foundation’s MA211 and MA212 are extended to linear analysis in that
matrices are extended to linear operators that include certain
differential operators.  In this unit, you will study the inner product
and its corresponding norm defined on a vector space, along with their
important properties that depend on the Cauchy-Schwarz inequality.  In
addition, you will review the eigenvalue problem, and you will study
singular values with an application to spectral decomposition.  This
leads to the discussion of singular value decomposition (SVD) of
rectangular matrices that allows us to generalize the inversion of
nonsingular matrices, studied in the Saylor course MA211, to the
“inversion” of rectangular and singular square matrices with
applications to solving arbitrary systems of linear equations and to the
introduction of the method of principal component analysis (PCA).  As an
application of PCA, the formulation and theory for data dimensionality
reduction (DDR) will also be studied in this first unit. *

**Unit1 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Compute inner products of two vectors, which include infinite
    sequences and functions, and compute the corresponding norms.
-   Apply the Cauchy-Schwarz inequality to find the angle between two
    vectors.
-   Compute eigenvalue and eigenvector pairs.
-   Compute singular values of arbitrary rectangular matrices.
-   Perform SVD.
-   Find first and second principle components of data matrices.
-   Explain the essence of data dimensionality reduction.
-   Reduce the dimension of data matrices for simple examples.

**1.1 Inner Product and Norm Measurements** <span id="1.1"></span> 
**1.1.1 Definition of Inner Product** <span id="1.1.1"></span> 
-   **Reading: Cambridge University Press: Marcus Pivato’s Linear
    Partial Differential Equations and Fourier Theory: “6A: Some
    Functional Analysis: Inner Products”**
    Link: Cambridge University Press: Marcus Pivato’s *Linear Partial
    Differential Equations and Fourier Theory:“[6A: Some Functional
    Analysis: Inner
    Products](http://assets.cambridge.org/97805211/99704/frontmatter/9780521199704_frontmatter.pdf)”(PDF)*  
      
     Instructions: Please click on the link above to access the PDF, and
    study Section 6A on pages 103–105, stopping at Section 6B, to learn
    about inner products.  
     Studying this reading should take approximately 15 minutes to
    complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s Linear Algebra: As an
    Introduction to Abstract Mathematics**
    Link: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s *[Linear Algebra: As an
    Introduction to Abstract
    Mathematics](http://www.math.ucdavis.edu/~anne/linear_algebra/index.html)*
    (PDF)  
      
     Instructions: Please click on the link above, and then select the
    link “PDF version of the book” to download the text.  Study Section
    9.1 on pages 117–119 for a definition and examples of inner product.
     You will be using this text throughout the course, so you may find
    it helpful to save the PDF to your desktop.  
     Studying this reading should take approximately 15 minutes to
    complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.2 Cauchy-Schwarz Inequality** <span id="1.1.2"></span> 
-   **Lecture: Khan Academy’s “Derivation of Cauchy-Schwarz
    Inequality”**
    Link:  Khan Academy’s [“Derivation of Cauchy-Schwarz
    Inequality”](http://www.khanacademy.org/math/linear-algebra/v/proof-of-the-cauchy-schwarz-inequality)
    (YouTube)  
      
     Instructions: Please click on the link above, and view the
    derivation of the Cauchy Schwarz inequality for the Euclidean
    space.  
     Viewing the lecture and pausing to take notes should take
    approximately 30 minutes to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Northern Illinois University: John A. Beachy’s “Theorem
    5.3: Cauchy-Schwarz Inequality” and Wikipedia’s “Cauchy-Schwarz
    Inequality”**
    Links: Northern Illinois University: John A. Beachy’s [“Theorem 5.3:
    Cauchy-Schwarz
    Inequality”](http://www.math.niu.edu/~beachy/courses/240/cauchy.html)
    (HTML) and Wikipedia’s [“Cauchy-Schwarz
    Inequality”](http://en.wikipedia.org/wiki/Cauchy%E2%80%93Schwarz_inequality)
    (HTML)  
        
     Instructions: Please click on the links above, and read these
    webpages in their entirety to study the proof of the Cauchy-Schwarz
    inequality for the general inner-product space.  Please note that
    these readings also apply to the topics outlined in sub-subunits
    1.1.3 and 1.1.4.  
     Studying the proofs in the reading materials takes approximately 30
    minutes to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**1.1.3 Norm Measurement and Angle between Vectors** <span
id="1.1.3"></span> 
-   **Reading: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s Linear Algebra: As an
    Introduction to Abstract Mathematics**
    Link: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s *[Linear Algebra: As an
    Introduction to Abstract
    Mathematics](http://www.math.ucdavis.edu/~anne/linear_algebra/index.html)*
    (PDF)  
      
     Instructions: Please click on the link titled “PDF version of the
    book” to access the text.  Study Sections 9.3 through 9.6 on pages
    119–135 for information on the general theory and properties of the
    inner product and its associated norm.  
     Studying this text should take approximately 1 hour and 15 minutes
    to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.1.4 Gram-Schmidt Orthogonalization Process** <span
id="1.1.4"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Linear Algebra: “Lecture
    17: Orthogonal Matrices and Gram-Schmidt”**
    Link: MIT: Professor Gilbert Strang’s Linear Algebra: [“Lecture 17:
    Orthogonal Matrices and
    Gram-Schmidt”](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-17-orthogonal-matrices-and-gram-schmidt/)
    (YouTube)  
      
     Instructions: Please click on the link above, and view this entire
    lecture to learn about orthogonal matrices, orthonormal families,
    and the Gram-Schmidt procedure for finding an orthonormal family
    from a given linearly independent family.  
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.2 Eigenvalue Problems** <span id="1.2"></span> 
**1.2.1 Linear Transformations** <span id="1.2.1"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Linear Algebra: “Lecture
    30: Linear Transformations and Their Matrices”**
    Link: MIT: Professor Gilbert Strang’s Linear Algebra: [“Lecture 30:
    Linear Transformations and Their
    Matrices”](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-30-linear-transformations-and-their-matrices/)
    (YouTube)  
        
     Instructions: Please click on the link above, and view the entire
    lecture on linear transformations.  
     Viewing this lecture and pausing to take notes and understanding
    the lecture should take approximately 1 hour to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

**1.2.2 Bounded Linear Functionals and Operators** <span
id="1.2.2"></span> 
-   **Reading: Bounded Linear Functionals and Operators**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.2.3 Eigenvalues and Eigenspaces** <span id="1.2.3"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering I: “Lecture 6: Eigen Values (Part 2) and Positive
    Definite (Part 1)”**
    Link: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering I: [“Lecture 6: Eigen Values (Part 2) and Positive
    Definite (Part
    1)”](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-6-eigen-values-part-2-and-positive-definite-part-1/)
    (YouTube)  
      
     Instructions: Please click on the link above, and view the entire
    video to learn about eigenvalues.  
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour and 15 minutes to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s Linear Algebra: As an
    Introduction to Abstract Mathematics: “Section 7: Eigenvalues and
    Eigenvectors”**
    Link: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s *[Linear Algebra: As an
    Introduction to Abstract
    Mathematics](http://www.math.ucdavis.edu/~anne/linear_algebra/index.html) *(PDF)  
      
     Instructions: Please click on the link above, and select the link
    to download the PDF file of the text.  Study Sections 7.2 and 7.3 on
    pages 83–86 to address eigenvalue problems.  
     Studying this reading should take approximately 15–20 minutes to
    complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above. 

**1.2.4 Self-Adjoint Positive Definite Operators** <span
id="1.2.4"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Linear Algebra: “Lecture
    27: Positive Definite Matrices”**
    Link: MIT: Professor Gilbert Strang’s Linear Algebra: [“Lecture 27:
    Positive Definite
    Matrices”](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-27-positive-definite-matrices-and-minima/)
    (YouTube)  
      
     Instructions: Please click on the link above, and view the entire
    lecture on positive definite matrices.  
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour and 15 minutes to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.3 Singular Value Decomposition (SVD)** <span id="1.3"></span> 
-   **Lecture: MIT: Gilbert Strang’s Linear Algebra: “Lecture 29:
    Singular Value Decomposition”**
    Link: MIT: Gilbert Strang’s Linear Algebra: [“Lecture 29: Singular
    Value
    Decomposition”](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-29-singular-value-decomposition/)
    (YouTube)  
      
     Instructions: Please click on the link above, and view the entire
    lecture to learn about singular value decomposition.  Please note
    that this video lecture also covers the topics outlined in
    sub-subunits 1.3.1 through 1.3.3.  
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

**1.3.1 Normal Operators and Spectral Decomposition** <span
id="1.3.1"></span> 
-   **Reading: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s Linear Algebra: As an
    Introduction to Abstract Mathematics**
    Link: University of California, Davis: Isaiah Lankham, Bruno
    Nachtergaele, and Anne Schilling’s *[Linear Algebra: As an
    Introduction to Abstract
    Mathematics](http://www.math.ucdavis.edu/~anne/linear_algebra/index.html)*
    (PDF)  
        
     Instructions: Please click on the link above, and select the link
    to download the PDF version of the text.  Study Sections 11.1–11.3
    on pages 144–149.  Please note that this reading also covers topics
    outlined in sub-subunits 1.3.2 and 1.3.3.  
     Studying this reading should take approximately 1 hour to
    complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

**1.3.2 Singular Values** <span id="1.3.2"></span> 
*Note: This topic is covered by the reading assigned below sub-subunit
1.3.1*

**1.3.3 Reduced Singular Value Decomposition** <span id="1.3.3"></span> 
*Note: This topic is partially covered by the reading assigned below
sub-subunit 1.3.1. *

-   **Reading: Reduced Singular Value Decomposition**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.3.4 Full Singular Value Decomposition** <span id="1.3.4"></span> 
-   **Reading: Full Singular Value Decomposition**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.4 Principal Component Analysis (PCA)** <span id="1.4"></span> 
**1.4.1 Frobenius Norm Measurement** <span id="1.4.1"></span> 
-   **Reading: Frobenius Norm Measurement**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.4.2 Principal Components for Data-Dependent Basis** <span
id="1.4.2"></span> 
-   **Reading: Principal Components for Data-Dependent Basis**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.4.3 Pseudoinverses** <span id="1.4.3"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Linear Algebra: “Lecture
    33: Left and Right Inverses: Pseudoinverse”**
    Link: MIT: Professor Gilbert Strang’s Linear Algebra: [“Lecture 33:
    Left and Right Inverses:
    Pseudoinverse”](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-33-left-and-right-inverses-pseudoinverse/)
    (YouTube)  
      
     Instructions: Please click on the link above, and view the entire
    lecture to learn about the topic of matrix pseudoinverses and its
    application to least-squares estimation.  
     Viewing this lecture, pausing to take notes, and studying the
    material in the lecture should take approximately 3 hours to
    complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**1.4.4 Minimum-Norm Least-Squares Estimation** <span
id="1.4.4"></span> 
-   **Reading: Minimum-Norm Least-Squares Estimation**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.5 Application to Data Dimensionality Reduction** <span
id="1.5"></span> 
-   **Reading: Application to Data Dimensionality Reduction**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**1.5.1 Representation of Matrices by Sum of Norm-1 Matrices** <span
id="1.5.1"></span> 
**1.5.2 Approximation by Matrices of Lower Ranks** <span
id="1.5.2"></span> 
**1.5.3 Motivation to Data-Dimensionality Reduction** <span
id="1.5.3"></span> 
**1.5.4 Principal Components as Basis for Dimension-Reduced Data** <span
id="1.5.4"></span> 
