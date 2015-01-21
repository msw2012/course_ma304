**Unit 5: PDE Methods** <span id="5"></span> 
*When the variance of the Gaussian convolution filter is replaced by ct,
where c is a fixed positive constant and t is used as the time
parameter, then the convolution filtering of any input function f(x)
describes the heat diffusion process with initial temperature given by
f(x).  More precisely, if u(x, t) denotes the temperature at the
position x and time t, then u(x,t), obtained by the Gaussian convolution
of the initial temperature f(x), is the solution of the  heat diffusion
PDE with initial condition u(x, 0) = f(x), where the constant c is the
heat conductivity constant.  However, this elegant example has little
practical value, because the spatial domain is the entire x-axis,but it
serves the purpose as a convincing motivation for the study of linear
PDE methods, to be studied in this unit.  To solve the same heat
diffusion PDE as in this example, but with initial heat source given on
a bounded interval and with insulation at the two end-points to avoid
any heat loss, the method of “separation of variables” is introduced. 
This method* *separates the PDE into two ordinary differential equations
(ODEs) that can be easily solved by appealing to the eigenvalue problem,
studied in Unit 1, for linear differential operators with eigenfunctions
given by the cosine function in x and with frequency governed by the
eigenvalues, which also dictate the rate of exponential decay in the
time variable t.  Superposition of the product of these corresponding
eigenfunctions with coefficients given by the Fourier coefficients of
the Fourier series representation of the initial heat content, studied
in Unit 3, solves this heat equation.* * In this unit, you will study an
extension of the method of separation of variables to the study of
boundary value problems on a rectangular spatial domain as well as the
solution of other popular linear PDEs.  The diffusion process can be
applied to image noise reduction.*

**Unit5 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
    
-   Apply the method of separation of variables to separate a given
    linear PDE into a finite family of ODEs.
-   Solve the corresponding eigenvalue problems for the spatial ODEs.
-   Apply the Fourier series of the input function to formulate the
    superposition solution of the boundary value problem.

**5.1 From Gaussian Convolution to Diffusion Process** <span
id="5.1"></span> 
-   **Reading: From Gaussian Convolution to Diffusion Process**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**5.1.1 Gaussian as Solution for Delta Heat Source** <span
id="5.1.1"></span> 
**5.1.2 Gaussian Convolution as Solution of Heat Equation for the
Real-Line** <span id="5.1.2"></span> 
**5.1.3 Gaussian Convolution as Solution of Heat Equation on the
Euclidean Space** <span id="5.1.3"></span> 
**5.2 The Method of Separation of Variables** <span id="5.2"></span> 
-   **Reading: University of Minnesota: Peter Olver’s Introduction to
    Partial Differential Equations: “Chapter 4: Separation of Variables:
    Introduction and the Diffusion and Heat Equations”**
    Link: University of Minnesota: Professor Peter Olver’s
    *[Introduction to Partial Differential
    Equations:](http://www.math.umn.edu/~olver/pdn.html)* “Chapter 4:
    Separation of Variables: Introduction and the Diffusion and Heat
    Equations” (PDF)  
        
     Instructions: Please click on the link above, and then select the
    link for “Chapter 4: Separation of Variables” to download the text. 
    Study Chapter 4 on pages 103–109 to learn about the method of
    separation of variables (for the special case of one spatial
    variable), particularly for solving the heat equation.  
     Studying this reading should take approximately 1 hour and 30
    minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    Linear Partial Differential Equations and Fourier Theory**
    Link: Cambridge University Press: Professor Marcus Pivato’s *[Linear
    Partial Differential Equations and Fourier
    Theory](http://www.saylor.org/content/general/Cambridge_PDE.pdf)*
    (PDF)  
      
     Instructions: Pleaseclick on the link above to download the PDF of
    the text.  Study Part I (on some motivating examples) and Part II
    (on the more general theory), particularly to learn about the
    abstract theory as a companion to the study of the reading by
    Professor Olver.  
     Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.2.1 Separation of Time and Spatial Variables** <span
id="5.2.1"></span> 
-   **Reading: Separation of Time and Spatial Variables**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**5.2.2 Superposition Solution** <span id="5.2.2"></span> 
-   **Reading: Superposition Solution**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**5.3 Fourier Series Solution** <span id="5.3"></span> 
-   **Reading: University of Minnesota: Peter Olver’s Introduction to
    Partial Differential Equations: Chapter 4: Separation of Variables:
    Introduction and the Diffusion and Heat Equations”**
    Link: University of Minnesota: Professor Peter Olver’s
    *[Introduction to Partial Differential
    Equations:](http://www.math.umn.edu/~olver/pdn.html)* “Chapter 4:
    Separation of Variables: Introduction and the Diffusion and Heat
    Equations” (PDF)  
        
     Instructions: Please click on the link in above, and then select
    the link to download “Chapter 4: Separation of Variables.”  Study
    the Fourier series solution on pages 109–140.  
     Studying this reading should take approximately 2 hours to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Reading: Cambridge University Press: Professor Marcus Pivato’s
    Linear Partial Differential Equations and Fourier Theory**
    Link: Cambridge University Press: Professor Marcus Pivato’s *[Linear
    Partial Differential Equations and Fourier
    Theory](http://www.saylor.org/content/general/Cambridge_PDE.pdf)*
    (PDF)  
      
     Instructions: Please click on the link above to access the PDF. 
    Study Part III (on Fourier series solutions) and Part IV (on
    Boundary value solutions).  
     Studying this reading should take approximately 3 hours to
    complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**5.3.1 Fourier Series Representation for Spatial Solution** <span
id="5.3.1"></span> 
*Note: This topic is covered by the lectures assigned below subunit 5.3*

**5.3.2 Extension to Higher Dimensional Spatial Domain** <span
id="5.3.2"></span> 
-   **Reading: Extension to Higher Dimensional Spatial Domain**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**5.4 Boundary Value Problems** <span id="5.4"></span> 
-   **Reading: Boundary Value Problems**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**5.4.1 The Neumann Boundary Value Problem** <span id="5.4.1"></span> 
**5.4.2 Anisotropic Diffusion** <span id="5.4.2"></span> 
**5.4.3 Solution in Terms of Eigenvalue Problems** <span
id="5.4.3"></span> 
**5.5 Application to Image De-noising** <span id="5.5"></span> 
-   **Reading: Application to Image De-noising**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**5.5.1 Diffusion as Quantizer for Image Compression** <span
id="5.5.1"></span> 
**5.5.2 Diffusion for Noise Reduction** <span id="5.5.2"></span> 
**5.5.3 Enhanced JPEG Image Compression** <span id="5.5.3"></span> 
