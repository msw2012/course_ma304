---
layout: default
title: "MA304: Topics in Applied Mathematics"
course_description: "An introduction to mathematical topics not included in the standard coursework, delivered by topics and projects chosen by the student."
next: ../Unit01
previous: ../../../
---
Course Syllabus for "MA304: Topics in Applied Mathematics"
----------------------------------------------------------

Mathematics was coined the “queen of sciences” by the “prince of
mathematicians,” Carl Friedrich Gauss, one of the greatest
mathematicians of all time.  Indeed, the name of Gauss is associated
with essentially all areas of mathematics, and in this respect, there is
really no clear boundary between “pure mathematics” and “applied
mathematics.”  To ensure financial independence, Gauss decided on a
stable career in astronomy, which is one of the oldest sciences and was
perhaps the most popular one during the eighteenth and nineteenth
centuries.  In his study of celestial motion and orbits and a diversity
of disciplines later in his career, including (in chronological order):
geodesy, magnetism, dioptrics, and actuarial science, Gauss has
developed a vast volume of mathematical methods and tools that are still
instrumental to our current study of applied mathematics. During the
twentieth century, with the exciting development of quantum field
theory, with the prosperity of the aviation industry, and with the
bullish activity in financial market trading, and so forth, the
sovereignty of the “queen of sciences” has turned her attention to the
theoretical development and numerical solutions of partial differential
equations (PDEs).  Indeed, the non-relativistic modeling of quantum
mechanics is described by the Schrödinger equation; the fluid flow
formulation, as an extension of Newtonian physics by incorporating
motion and stress, is modeled by the Navier-Stokes equation; and option
stock trading with minimum risk can be modeled by the Black-Scholes
equation.  All of these equations are PDEs.  In general, PDEs are used
to describe a wide variety of phenomena, including: heat diffusion,
sound wave propagation, electromagnetic wave radiation, vibration,
electrostatics, electrodynamics, fluid flow, and elasticity, just to
name a few.  For this reason, the theoretical and numerical development
of PDEs has been considered the core of applied mathematics, at least in
the academic environment. On the other hand, over the past decade, we
have been facing a rapidly increasing volume of “information” contents
to be processed and understood.  For instance, the popularity and
significant impact of the open education movement (OEM) has contributed
to an enormous amount of educational information on the web that is
difficult to sort out, due to unavoidable redundancy, occasional
contradiction, extreme variation in quality, and even erroneous
opinions.  This motivated the founding of the “Saylor Foundation
courseware” to provide perhaps one of the most valuable, and certainly
more reliable, high-quality educational materials, with end-to-end
solutions, that are free to all.  With the recent advances of various
high-tech fields and the popularity of social networking, the trend of
exponential growth of easily accessible information is certainly going
to continue well into the twenty-first century, and the bottleneck
created by this information explosion will definitely require innovative
solutions from the scientific and engineering communities, particularly
those technologists with better understanding of and a strong background
in applied mathematics.  In this regard, mathematics extends its
influence and impact by providing innovative theory, methods, and
algorithms to virtually every discipline, far beyond sciences and
engineering, for processing, transmitting, receiving, understanding, and
visualizing data sets, which could be very large or live in some
high-dimensional space. Of course the basic mathematical tools, such as
PDE methods and least-squares approximation introduced by Gauss, are
always among the core of the mathematical toolbox for applied
mathematics.  But other innovations and methods must be integrated in
this toolbox as well.  One of the most essential ideas is the notion of
“frequency” of the data information.  Joseph Fourier, a contemporary of
Gauss, instilled this important concept to our study of physical
phenomena by his innovation of trigonometric series representations,
along with powerful mathematical theory and methods, to significantly
expand the core of the toolbox for applied mathematics.  The frequency
content of a given data set facilitates the processing and understanding
of the data information.  Another important idea is the “multi-scale”
structure of data sets.  Less than three decades ago, with the birth of
another exciting mathematical subject, called “wavelets,” the data set
of information can be put in the wavelet domain for multi-scale
processing as well.  On the other hand, it is unfortunate that some
essential basic mathematical tools for information processing are not
commonly taught in a regular applied mathematics course in the
university.  Among the commonly missing ones, the topics that will be
addressed in this Saylor course MA304 include: information coding, data
dimensionality reduction, data compression, and image manipulation. The
objective of this course is to study the basic theory and methods in the
toolbox of the core of applied mathematics, with a central scheme that
addresses “information processing” and with an emphasis on manipulation
of digital image data.  Linear algebra in the Saylor Foundation’s MA211
and MA212 are extended to “linear analysis” with applications to
principal component analysis (PCA) and data dimensionality reduction
(DDR).  For data compression, the notion of entropy is introduced to
quantify coding efficiency as governed by Shannon’s Noiseless Coding
theorem.  Discrete Fourier transform (DFT) followed by an efficient
computational algorithm, called fast Fourier transform (FFT), as well as
a real-valued version of the DFT, called discrete cosine transform (DCT)
are discussed, with application to extracting frequency content of the
given discrete data set that facilitates reduction of the entropy and
thus significant improvement of the coding efficiency.  DFT can be
viewed as a discrete version of the Fourier series, which will be
studied in some depth, with emphasis on orthogonal projection, the
property of positive approximate identity of Fejer’s kernels, Parseval’s
identity and the concept of completeness.  The integral version of the
sequence of Fourier coefficients is called the Fourier transform (FT). 
Analogous to the Fourier series, the formulation of the inverse Fourier
transform (IFT) is derived by applying the Gaussian function as a
sliding time-window for simultaneous time-frequency localization, with
optimality guaranteed by the Uncertainty Principle.  Local
time-frequency basis functions are also introduced in this course by
discretization of the frequency-modulated sliding time-window function
at the integer lattice points.  Replacing the frequency modulation by
modulation with the cosines avoids the Balian-Low stability restriction
on the local time-frequency basis functions, with application to
elimination of blocky artifact caused by quantization of tiled DCT in
image compression.  Gaussian convolution filtering also provides the
solution of the heat (partial differential) equation with the real-line
as the spatial domain.  When this spatial domain is replaced by a
bounded interval, the method of separation of variables is applied to
separate the PDE into two ordinary differential equations (ODEs). 
Furthermore, when the two end-points of the interval are insulated from
heat loss, solution of the spatial ODE is achieved by finding the
eigenvalue and eigenvector pairs, with the same eigenvalues to govern
the exponential rate of decay of the solution of the time ODE. 
Superposition of the products of the spatial and time solutions over all
eigenvalues solves the heat PDE, when the Fourier coefficients of the
initial heat content are used as the coefficients of the terms of the
superposition.  This method is extended to the two-dimensional
rectangular spatial domain, with application to image noise reduction. 
The method of separation of variables is also applied to solving other
typical linear PDEs.  Finally, multi-scale data analysis is introduced
and compared with the Fourier frequency approach, and the architecture
of multiresolution analysis (MRA) is applied to the construction of
wavelets and formulation of the multi-scale wavelet decomposition and
reconstruction algorithms.  The lifting scheme is also introduced to
reduce the computational complexity of these algorithms, with
applications to digital image manipulation for such tasks as progressive
transmission, image edge extraction, and image enhancement.

### Learning Outcomes

Upon successful completion of this course, the student will be able
to:  

-   Compute singular values of rectangular and singular square matrices.
-   Perform singular value decomposition of rectangular matrices.
-   Solve an arbitrary system of linear equations.
-   Compute linear least-squares estimation.
-   Compute principal components.
-   Reduce data dimension.
-   Compute DFT of vectors.
-   Compute inverse DFT.
-   Compute DCT of vectors.
-   Compute inverse DCT.
-   Compute two-dimensional DCT of matrix data array.
-   Compute histogram of data sets.
-   Formulate probability distribution based on histograms.
-   Compute entropy from probability distribution.
-   Construct Huffman trees and Huffman codes.
-   Perform color transform.
-   Outline the JPEG image compression scheme.
-   Explain video compression. 
-   Compute Fourier series.
-   Compute Fourier cosine series.
-   Describe the importance of the Dirichlet and Fejer kernels.
-   Apply the property of positive approximate identity to prove
    convergence theorems.
-   Compute mean-square error of approximation by partial sums of
    Fourier series.
-   Solve the Basel problem and its extension to higher even powers.
-   Compute the Fourier transform of some simple functions.
-   Compute the Fourier transform of the affine transformation of some
    simple functions.
-   Compute the convolution of some simple functions with certain
    filters.
-   Describe and apply the important Fourier transform property of
    mapping the convolution operation to product of the Fourier
    transform of the individual functions.
-   Explain and apply the concept of localized Fourier and inverse
    Fourier transforms.
-   Formulate the Fourier transform of a general Gaussian function.
-   Explain the Uncertainty Principle.
-   Compute the Gabor transform of some simple functions.
-   Formulate local time-frequency basis functions from a given sliding
    time-window function.
-   Formulate local cosine basis functions from a given sliding
    time-window function.
-   Apply the Gaussian to solve the heat equation with the entire
    d-dimensional Euclidean space as the spatial domain, where d is any
    positive integer.
-   Apply the method of separation of variables to separate a given
    linear PDE into a finite family of ODEs.
-   Solve the corresponding eigenvalue problems for the spatial ODEs.
-   Apply the Fourier series of the input function to formulate the
    superposition solution of boundary value problems.
-   Give the relationship between scale and frequency for a given
    wavelet filter.
-   Perform matrix extension to compute wavelet filters.
-   Compute multi-scale data representation by applying the wavelet
    decomposition algorithm for the Haar wavelet.
-   Identify the order of vanishing moments of a given wavelet.
-   Apply the wavelet decomposition and reconstruction algorithms to
    multi-scale data analysis.
-   Apply wavelets to digital image manipulation.

### Course Requirements

In order to take this course, you must:  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have access to a computer.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have continuous broadband Internet access.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have the ability/permission to install plug-ins (e.g. Adobe
Reader or Flash) and software.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have the ability to download and save files and documents to a
computer.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have the ability to open Microsoft Office files and documents
(.doc, .ppt, .xls, etc.).  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have competency in the English language.  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have read the [Saylor Student
Handbook](http://www.saylor.org/site/wp-content/uploads/2012/05/Saylor-StudentHandbook.pdf).  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have completed the following courses from [“The Core
Program”](http://www.saylor.org/majors/mathematics/) of the mathematics
major: [MA101: Single-Variable Calculus
I](http://www.saylor.org/courses/ma101/); [MA102: Single-Variable
Calculus II](http://www.saylor.org/courses/ma102/); [MA103:
Multivariable Calculus](http://www.saylor.org/courses/ma103/); [MA211:
Linear Algebra](http://www.saylor.org/courses/ma211/); [MA221:
Differential Equations](http://www.saylor.org/courses/ma221/); and
[MA241: Real Analysis I](http://www.saylor.org/courses/ma241/)  
  
 <span
style="color: rgb(85, 85, 85); font-family: 'Myriad Pro', 'Gill Sans', 'Gill Sans MT', Calibri, sans-serif; font-size: 16px; line-height: 24px; -webkit-text-size-adjust: none;">√
   </span>Have completed the following courses from the [“Advanced
Mathematics”](http://www.saylor.org/majors/mathematics/) section of the
mathematics major: [MA212: Linear Algebra
II](http://www.saylor.org/courses/ma212/); [MA243: Complex
Analysis](http://www.saylor.org/courses/ma243/); and [MA222:
Introduction to Partial Differential
Equations.](http://www.saylor.org/courses/ma222/)

### Course Information

Welcome to MA304: Topics in Applied Mathematics.  Below, please find
some information on the course and its requirements.  
    
 **Primary Resources:** This course is comprised of a range of different
free, online materials.  However, the course makes primary use of the
following materials:  

-   MIT: Professor Gilbert Strang’s [Linear Algebra
    Lectures](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/)
-   MIT: Professor Gilbert Strang’s [Computational Science and
    Engineering I
    Lectures](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/)
-   University of California, Davis: Isaiah Lankham, Bruno Nachtergaele,
    and Anne Schilling’s *[Linear Algebra: As an Introduction to
    Abstract
    Mathematics](http://www.math.ucdavis.edu/~anne/linear_algebra/index.html)*

**Requirements for Completion:** In order to complete this course, you
will need to work through each unit and all of its assigned materials. 
You will also need to complete:  

-   The Final Exam

Note that you will only receive an official grade on your Final Exam. 
However, in order to adequately prepare for this exam, you will need to
work through the resources in each unit.  
    
 In order to “pass” this course, you will need to earn a 70% or higher
on the Final Exam.  Your score on the exam will be tabulated as soon as
you complete it.  If you do not pass the exam, you may take it again.  
    
 **Time Commitment:** Each unit includes a “time advisory” that lists
the amount of time you should spend on each subunit.  These should help
you plan your time accordingly.  It may be useful to take a look at
these time advisories and to determine how much time you have over the
next few weeks to complete each unit, and then to set goals for
yourself.  For example, Unit 1 should take you 12.5 hours.  Perhaps you
can sit down with your calendar and decide to complete subunit 1.1 (a
total of 3.75 hours) on Monday night; subunit 1.2 (a total of 3.75
hours) on Tuesday night; etc.  
    
 **Tips/Suggestions:** As noted in the “Course Requirements,” there are
several mathematics pre-requisites for this course.  If you are
struggling with the mathematics as you progress through this course,
consider taking a break and revisiting the applicable course listed as a
pre-requisite.  
              

