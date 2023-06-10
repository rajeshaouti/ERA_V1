<h1 align="center">ERA_V1</h1>

<h2 align="center">Assignment-Backpropagation and Advanced Architectures</h2>

---
**Convolutions Architecture that achieves 99.4% accuracy for Mnist dataset**
---


**APPROACH AND SOLUTION**
----
The solution to identifying the right architecture that achieves the accuracy of 99.4% with less than 20K parameters and in 20 epochs.


  Description : Go deeper, Remove Padding, increase parameters

  parameters = 19.3k

  number of epochs -20

  accuracy - 99.47 % -

----------------------------------------
**Code Link**

colab - https://colab.research.google.com/drive/1wE8RInOLprMtUqculEUXdOfVBOm0y0ig#scrollTo=b_Dza23IC_Bv

-------------------

**ASK OF THE ASSIGNMENT**


1.  We have considered many many points in our last 4 lectures. Some of these we have covered directly and some indirectly. They are:
    1.  How many layers,
    2.  MaxPooling,
    3.  1x1 Convolutions,
    4.  3x3 Convolutions,
    5.  Receptive Field,
    6.  SoftMax,
    7.  Learning Rate,
    8.  Kernels and how do we decide the number of kernels?
    9.  Batch Normalization,
    10.  Image Normalization,
    11.  Position of MaxPooling,
    12.  Concept of Transition Layers,
    13.  Position of Transition Layer,
    14.  DropOut
    15.  When do we introduce DropOut, or when do we know we have some overfitting
    16.  The distance of MaxPooling from Prediction,
    17.  The distance of Batch Normalization from Prediction,
    18.  When do we stop convolutions and go ahead with a larger kernel or some other alternative (which we have not yet covered)
    19.  How do we know our network is not going well, comparatively, very early
    20.  Batch Size, and effects of batch size
    21.  etc (you can add more if we missed it here)
2.  Refer to this code:  [COLABLINK (links to an external site)](https://colab.research.google.com/drive/1uJZvJdi5VprOQHROtJIHy0mnY2afjNlx)
    -  **WRITE IT AGAIN SUCH THAT IT ACHIEVES**  
        1.  99.4% validation accuracy
        2.  Less than 20k Parameters
        3.  You can use anything from above you want.
        4.  Less than 20 Epochs
        5.  No fully connected layer

