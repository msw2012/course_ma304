**Unit 2: Data Compression** <span id="2"></span> 
*A natural continuation of DDR studied in Unit 1 is the subject of data
compression.  To prepare for this investigation, we will introduce the
discrete Fourier transform (DFT).  For efficient computation, we will
introduce the fast Fourier transform (FFT) for computing the n-point
DFT, for n equal to an integer power of 2.  A real-valued version of the
DFT, called discrete cosine transform (DCT), is derived for application
to image compression.  The importance of DFT and DCT is their
functionality to extracting frequency content of discrete data.  A given
data set may be considered as an information source, and the histogram
of the source gives rise to its probability distribution, which in turn
is used to define the entropy of the source.  In this unit, you will
study information coding, including Shannon’s Noiseless Coding theorem
and construction of the Huffman code, for reversible (or lossless)
compression of the data.  To significantly improve the compression
efficiency, DCT followed by an appropriate quantization may be applied
to reduce the entropy.  This procedure is irreversible, but certainly
most effective, particularly for image and video compression.  In this
regard, you will study the JPEG image compression standard and the video
compression scheme.  This discussion includes the necessity of color
transform.*

**Unit 2 Time Advisory**  
  

**Unit2 Learning Outcomes**  
Upon successful completion of this unit, the student will be able to:  
-   Compute the DFT of column vectors.
-   Compute DCT of column vectors.
-   Compute the histogram of a data set.
-   Compute the probability distribution of an information source based
    on its histogram.
-   Compute the entropy of an information source based on the
    probability distribution.
-   Build Huffman trees based on the probability distribution.
-   Construct Huffman code-tables.
-   Compute two-dimensional DCT of a matrix.
-   Apply given quantization tables to the DCT matrix.
-   Perform color transformation.
-   Outline the JPEG compression scheme.

**2.1 Discrete and Fast Fourier Transform (FFT)** <span
id="2.1"></span> 
-   **Lecture: MIT: Professor Gilbert Strang’s Linear Algebra: “Lecture
    17: Orthogonal Matrices and Gram-Schmidt”**
    Link: MIT: Professor Gilbert Strang’s Linear Algebra: [“Lecture 17:
    Orthogonal Matrices and
    Gram-Schmidt”](http://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/lecture-17-orthogonal-matrices-and-gram-schmidt/)
    (YouTube)  
        
     Instructions: Please click on the link above, and view the entire
    video to learn about Orthogonal matrices, Gram-Schmidt
    orthogonalization process. You may also click on the tab for
    “Transcript,” and download the transcript to read along with the
    video lecture.   
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

-   **Lecture: YouTube: Stanford University’s “Lecture 1: The Fourier
    Transform and Its Applications,” “Lecture 6: The Fourier Transform
    and Its Applications,” “Lecture 8: The Fourier Transform and Its
    Applications,” and “Lecture 8: Discrete Time Fourier Transform”**
    Links: YouTube: Stanford University’s [“Lecture 1: The Fourier
    Transform and Its
    Applications”](http://www.youtube.com/watch?index=0&feature=PlayList&v=gZNm7L96pfY&list=PLB24BC7956EE040CD)
    (YouTube), [“Lecture 6: The Fourier Transform and Its
    Applications”](http://www.youtube.com/watch?v=4lcvROAtN_Q&feature=relmfu)
    (YouTube), [“Lecture 8: The Fourier Transform and Its
    Applications”](http://www.youtube.com/watch?v=wUT1huREHJM&feature=relmfu)
    (YouTube), and [“Lecture 8: Discrete Time Fourier
    Transform”](http://www.youtube.com/watch?v=Q8wuqYsdnSs&feature=related)
    (YouTube)  
        
     Instructions: Please click on the links above, and view the entire
    video lectures for an overview of the Fourier transform, including
    DFT, FFT, DCT, and in particular the use of Tiled DCT for image
    compression, and applications.  Please note that this resource also
    covers the topics outlined in sub-subunits 2.1.1 and 2.1.3.  
        
     Viewing these lectures and pausing to take notes should take
    approximately 4 hours to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.1.1 Definition of DFT** <span id="2.1.1"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.1.*

**2.1.2 Lanczos’ Matrix Factorization** <span id="2.1.2"></span> 
-   **Reading: Lanczos’ Matrix Factorization**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.1.3 FFT for Fast Computation** <span id="2.1.3"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.1.*

**2.2 Discrete Cosine Transform (DCT)** <span id="2.2"></span> 
-   **Reading: Discrete Cosine Transform (DCT)**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.2.1 Derivation of DCT from DFT** <span id="2.2.1"></span> 
**2.2.2 8-point DCT** <span id="2.2.2"></span> 
**2.2.3 2-dimensional DCT** <span id="2.2.3"></span> 
**2.3 Information Coding** <span id="2.3"></span> 
-   **Reading: Information Coding**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.3.1 Probability Distribution** <span id="2.3.1"></span> 
**2.3.2 Histogram** <span id="2.3.2"></span> 
**2.3.3 Entropy** <span id="2.3.3"></span> 
**2.3.4 Binary Codes** <span id="2.3.4"></span> 
**2.4 Data Compression Schemes** <span id="2.4"></span> 
-   **Lecture: YouTube: National Program on Technology Enhanced Learning
    (NPTEL)’s “Lecture 19: Data Compression”**
    Link: YouTube: National Program on Technology Enhanced Learning
    (NPTEL)’s [“Lecture 19: Data
    Compression”](http://www.youtube.com/watch?v=5wRPin4oxCo&feature=related)
    (YouTube)  
        
     Instructions: Please click on the link above, and view the entire
    lecture for an overview of data compression.  Please note that this
    video also covers the topics outlined in sub-subunits 2.3.3, 2.4.1,
    and 2.4.3.  
     Viewing this lecture and pausing to take notes should take
    approximately 1 hour to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4.1 Lossless and Lossy Compression** <span id="2.4.1"></span> 
*Note: This topic is covered by the lecture assigned below subunit 2.4.*

-   **Lecture: YouTube: National Programme on Technology Enhanced
    Learning (NPTEL)’s “Lecture 17: Lossy Image Compression: DCT” and
    “Lecture 18: DCT Quantization and Limitations"**
    Links: YouTube: National Programme on Technology Enhanced Learning
    (NPTEL)’s [“Lecture 17: Lossy Image Compression:
    DCT”](http://www.youtube.com/watch?v=sckLJpjH5p8&feature=relmfu)
    (YouTube) and [“Lecture 18: DCT Quantization and
    Limitations”](http://www.youtube.com/watch?v=cqqsjvLKpuw&feature=relmfu)
    (YouTube)  
        
     Instructions: Please click on the links above, and view these video
    lectures to learn about lossy image compression.  The first video is
    on DCT, and the second video is on quantization of DCT and its
    limitations.  
     Viewing these videos and pausing to take notes should take
    approximately 2 hours and 30 minutes to complete.   
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4.2 Kraft Inequality** <span id="2.4.2"></span> 
-   **Reading: Kraft Inequality**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.4.3 Huffman Coding Scheme** <span id="2.4.3"></span> 
*Note: This topic is covered by the lecture assigned below subunit 2.4.*

-   **Web Media: YouTube: CSLearning101’s “Huffman Coding Tutorial”**
    Link: YouTube: CSLearning101’s [“Huffman Coding
    Tutorial”](http://www.youtube.com/watch?v=HEbs2kkVfV4) (YouTube)  
        
     Instructions: Please click on the link above, and view the entire
    video to learn about Huffman Coding.  
     Viewing this video and pausing to take notes should take
    approximately 15 minutes to complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.

**2.4.4 Noiseless Coding Theorem** <span id="2.4.4"></span> 
-   **Reading: Noiseless Coding Theorem**
    The Saylor Foundation does not yet have materials for this portion
    of the course. If you are interested in contributing your content to
    fill this gap or aware of a resource that could be used here, please
    submit it here.

    [Submit Materials](/contribute/)

**2.5 Image and Video Compression Schemes and Standards** <span
id="2.5"></span> 
-   **Reading: John Loomis’s “JPEG Tutorial”**
    Link: John Loomis’s [“JPEG
    Tutorial”](http://www.johnloomis.org/ece563/notes/compression/jpeg/tutorial/jpegtut1.html)
    (HTML)  
      
     Instructions: Please click on the link above, and read the entire
    webpage to study a tutorial on JPEGs.  Please note that this reading
    also covers the topics outlined in sub-subunits 2.5.1 through
    2.5.7.  
     Studying this reading should take approximately 30 minutes to
    complete.  
        
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above.  

-   **Lecture: YouTube: National Program on Technology Enhanced Learning
    (NPTEL)’s “Lecture 16: Introduction to Image and Video Coding,”
    “Lecture 23: Video Coding: Basic Building Blocks,” “Lecture 24:
    Motion Estimation Techniques,” and “Lecture 26: Video Coding
    Standards”**
    Links: YouTube: National Program on Technology Enhanced Learning
    (NPTEL)’s [“Lecture 16: Introduction to Image and Video
    Coding”](http://www.youtube.com/watch?v=SnstUsMJ4V4&feature=related)
    (YouTube), [“Lecture 23: Video Coding: Basic Building
    Blocks”](http://www.youtube.com/watch?v=OdYlNAFYq44&feature=relmfu)
    (YouTube), [“Lecture 24: Motion Estimation
    Techniques”](http://www.youtube.com/watch?v=Tm4C2ZFd3zE&feature=relmfu)
    (YouTube), and [“Lecture 26: Video Coding
    Standards”](http://www.youtube.com/watch?v=f9n-7mgNsNQ&feature=relmfu)
    (YouTube)  
      
     Instructions: Please click on the links above, and view these
    videos (about 1 hour each) to learn about video compressions methods
    and standards.  Please note that these video lectures also cover the
    topics outlined in sub-subunits 2.5.1 through 2.5.7.  
     Viewing these videos and pausing to take notes should take
    approximately 5 hours to complete.  
      
     Terms of Use: Please respect the copyright and terms of use
    displayed on the webpage above videos.

**2.5.1 Image Compression Scheme** <span id="2.5.1"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.5. *

**2.5.2 Quantization** <span id="2.5.2"></span> 
*Note: This topic is covered by the lectures assigned below subunit 2.5*

**2.5.3 Huffman, DPCM, and Run-Length Coding** <span id="2.5.3"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.5. *

**2.5.4 Decoder** <span id="2.5.4"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.5. *

**2.5.5 I, P, and B Video Frames** <span id="2.5.5"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.5. *

**2.5.6 Macro-Blocks** <span id="2.5.6"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.5. *

**2.5.7 Motion Search and Compensation** <span id="2.5.7"></span> 
*Note: This topic is covered by the lectures assigned below subunit
2.5. *


