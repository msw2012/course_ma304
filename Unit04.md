**Unit 4: Time-Frequency Analysis** <span id="4"></span> 
*The Fourier transform (FT) introduced in this unit is the analogue of
the sequence of Fourier coefficients of the Fourier series discussed in
Unit 3 in that the normalized integral over the “circle” in the
definition of Fourier coefficients is replaced by the integral over the
real line to define the FT.  While the Fourier series is used to recover
the given function it represents from the sequence of Fourier
coefficients, it is non-trivial to justify the validity of the seemingly
obvious formulation of the inverse Fourier transform (IFT) for the
recovery of a function from its FT.  This unit will introduce the
notions of localized FT (LFT) and localized IFT (LIFT).  We will also
establish an identity that governs the relationship between LFT and
LIFT, when the sliding frequency-window function for the LIFT is complex
conjugate of the Fourier transform of the sliding time-window function
in for the LFT.  Because the Fourier transform of a Gaussian function
remains to be a Gaussian function, any Gaussian function can be used as
a time-sliding window for simultaneous time-frequency localization.* 
*This same identity is also applied to justify the validity of the
formulation of the IFT by taking the variance of the sliding Gaussian
time-window to zero.  Another important consequence of this identity is
the Uncertainty Principle, which states that the Gaussian is the only
window function that provides optimal simultaneous time-frequency
localization with area of the time-frequency window equal to 2.* 
*Discretization of any frequency-modulated sliding time-window of the
LFT at the integer lattice yields a family of local time-frequency basis
functions.  Unfortunately, the Balian-Low restriction excludes any
sliding time-window function, including the Gaussian, to attain finite
area of the time-frequency window, while providing stability for the
family of local time-frequency basis functions, called a “frame.”  This
unit ends with a discussion of a way for avoiding the Balian-Low
restriction by replacing the frequency-modulation of the sliding
time-window function with modulation by certain cosine functions.  More
precisely, a family of stable local cosine basis functions, sometimes
called Malvar “wavelets,” is introduced to achieve good time-frequency
localization.  As an application, undesirable blocky artifact of highly
compressed JPEG pictures, as discussed in Unit 2, can be removed by
replacing the 8-point DCT with certain appropriate discretized local
cosine basis function for each of the 8 by 8 image tiles.*  

**Unit4 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
    
-   Compute the Fourier transform of some simple functions**.**
-   Compute the Fourier transform of the affine transformation of some
    given functions.
-   Compute the convolution of some simple functions with certain
    filters.
-   Compute the Gabor transform of some simple functions.
-   Formulate local time-frequency basis functions from a given sliding
    time-window function.
-   Formulate local cosine basis functions from a given sliding
    time-window function.

**4.1 Fourier Transform** <span id="4.1"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering: “Lecture 33: Filters, Fourier Integral Transform” and
    “Lecture 34: Fourier Integral Transform (Part 2)”**
    Links: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering: [“Lecture 33: Filters, Fourier Integral
    Transform”](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-33-filters-fourier-integral-transform/)
    (YouTube) and [“Lecture 34: Fourier Integral Transform (Part
    2)”](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-34-fourier-integral-transform-part-2/)
    (YouTube)  
        
     Instructions: Please click on the links above, and view these video
    lectures to learn more about the essence of the Fourier Transform
    and filtering.  Please note that these videos cover the topics
    outlined for sub-subunits 4.1.1 and 4.1.2.  
     Viewing these lectures and pausing to take notes should take
    approximately 2 hours and 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above.

**4.1.1 Definition and Essence of the Fourier Transform** <span
id="4.1.1"></span> 
-   **Reading: University of Minnesota: Professor Peter Olver’s
    Introduction to Partial Differential Equations: “Chapter 8: Fourier
    Transforms”**
    Links:University of Minnesota: Professor Peter Olver’s
    *[Introduction to Partial Differential
    Equations:](http://www.math.umn.edu/~olver/pdn.html)* “Chapter 8:
    Fourier Transforms” (PDF)  
        
     Instructions: Please click on the link above, and then select the
    link to “Chapter 8: Fourier Transforms” to download the PDF file. 
    Study pages 283–298 on the concept and properties of the Fourier
    Transform.  Note that this reading covers the topics outlined for
    sub-subunits 4.1.1 and 4.1.2.  
     Studying this reading should take approximately 1 hour to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above. 

**4.1.2 Properties of the Fourier Transform** <span id="4.1.2"></span> 
*Note: This topic is covered by the reading and lectures assigned below
sub-subunit 4.1.1.*

**4.1.3 Sampling Theorem** <span id="4.1.3"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering: “Lecture 36: Sampling Theorem”**
    Links: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering: [“Lecture 36: Sampling
    Theorem”](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-36-sampling-theorem/)
    (YouTube)  
        
     Instructions: Please click on the link above, and view this lecture
    to learn about the application of the Fourier transform and Fourier
    series to deriving and understanding the essence of the Sampling
    Theorem.  
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.1.4 Applications of the Fourier Transform** <span
id="4.1.4"></span> 
-   **Lecture: YouTube: Stanford University: Department of Electrical
    Engineering’s “Lecture 1: The Fourier Transforms and Its
    Applications,” “Lecture 6: The Fourier Transforms and Its
    Applications,” and “Lecture 8: The Fourier Transforms and Its
    Applications”**
    Links: YouTube: Stanford University: Department of Electrical
    Engineering’s [“Lecture 1: The Fourier Transforms and Its
    Applications”](http://www.youtube.com/watch?index=0&feature=PlayList&v=gZNm7L96pfY&list=PLB24BC7956EE040CD)
    (YouTube), [“Lecture 6: The Fourier Transforms and Its
    Applications”](http://www.youtube.com/watch?v=4lcvROAtN_Q&feature=relmfu)
    (YouTube), and [“Lecture 8: The Fourier Transforms and Its
    Applications”](http://www.youtube.com/watch?v=wUT1huREHJM&feature=relmfu)
    (YouTube)  
      
     Instructions: Please click on the links above, and view the video
    lectures to learn about applications of the Fourier Transforms.  
     Viewing these video lectures and pausing to take notes should take
    approximately 3 hours and 30 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpages above. 

**4.2 Convolution Filter and Gaussian Kernel** <span id="4.2"></span> 
**4.2.1 Convolution Filter** <span id="4.2.1"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering: “Lecture 32: Convolution (Part 2), Filtering”**
    Link: MIT: Professor Gilbert Strang’s Computational Science and
    Engineering: [“Lecture 32: Convolution (Part 2),
    Filtering”](http://ocw.mit.edu/courses/mathematics/18-085-computational-science-and-engineering-i-fall-2008/video-lectures/lecture-32-convolution-part-2-filtering/)
    (YouTube)  
        
     Instructions:  Please click on the above link above, and view the
    video lecture on the convolution filter.  
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour and 15 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**4.2.2 Fourier Transform of the Gaussian** <span id="4.2.2"></span> 
-   **Reading: Fourier Transform of the Gaussian**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**4.2.3 Inverse Fourier Transform** <span id="4.2.3"></span> 
-   **Reading: Inverse Fourier Transform**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**4.3 Localized Fourier Transform** <span id="4.3"></span> 
-   **Reading: Localized Fourier Transform**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**4.3.1 Short-time Fourier Transform (STFT)** <span id="4.3.1"></span> 
**4.3.2 Gabor Transform** <span id="4.3.2"></span> 
**4.3.3 Inverse of Localized Fourier Transform** <span
id="4.3.3"></span> 
**4.4 Uncertainty Principle** <span id="4.4"></span> 
-   **Reading: Uncertainty Principle**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**4.4.1 Time-Frequency Localization Window Measurement** <span
id="4.4.1"></span> 
**4.4.2 Gaussian as Optimal Time-Frequency Window** <span
id="4.4.2"></span> 
**4.4.3 Derivation of the Uncertainty Principle** <span
id="4.4.3"></span> 
**4.5 Time-Frequency Bases** <span id="4.5"></span> 
-   **Reading: Time-Frequency Bases**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**4.5.1 Balian-Low Restriction** <span id="4.5.1"></span> 
**4.5.2 Frames** <span id="4.5.2"></span> 
**4.5.3 Localized Cosine Basis** <span id="4.5.3"></span> 
**4.5.4 Malvar Wavelets** <span id="4.5.4"></span> 
