# CSC496_2019F Deep learning in computer vision

Instructor: <a href="https://sites.google.com/site/beixiao/">Bei Xiao</a>, American University
Location: DMTI Room 110
Time: Monday, Thursday 2:30pm-3:45pm
Office: DMTI Room 204
First Class: August 26th

Office hour: check syllabus 

# General Information

## Course Objective

This course provides an overview of “deep neural network” (AKA deep learning) and related methods with applications in computer vision. First, we will overview (continue after CSC 476) some fundamental topics in computer vision such as image formation, camera models, color, multiscale pyramids, and statistical modeling of images. Second, we will introduce basic machine learning methods and neural network architectures. Finally, we dive into a variety of deep learning-based applications in computer vision.  Students learn to implement, train, and debug off-the shelf and their own neural networks and gain a detailed understanding of the cutting-edge research in computer vision. Topics include visual data representation, mid-level vision, image parsing, image classification and synthesis with architectures such as convolutional neural networks (CNNs), recurrent neural networks (RNNs), generative-advisory networks (GANs), and Variational Autoencoders (VAEs).  


## Perquisites

1. Proficiency in Python. If you have plenty of coding experieces with MATLAB, C++, is fine too. 
2. College Calculus
3. Basic probability, statistics andlinear algebra. 


## Textbooks and references

1.	(Required) R. Szeliski, Computer Vision: Algorithms and Applications , available at 
(http://szeliski.org/Book/)

2.   (Required) I. Goodfellow, Deep learning (http://www.deeplearningbook.org)


### Other references (especially useful if you haven’t taken CSC476):

3.	Linear Algebra
    3.1 Stanford CS229 review (http://cs229.stanford.edu/section/cs229-linalg.pdf)
    3.2 Immersive Math, linear algebra (http://immersivemath.com/ila/index.html) 

4.  Python/Numpy tutorials (https://sites.engineering.ucsb.edu/~shell/che210d/numpy.pdf)

5.  Probability and statistics, seeing theory (https://seeing-theory.brown.edu/)
6.  Tensorflow and machine learning (https://www.tensorflow.org/tutorials/keras)

## Course Policy
### Attendence policy

Missing one class without written request will result in 2% reduction in attendance score.   However, students can be absent for class and arrange for make-up exams if they have written proof of religious holidays and documented disabilities. Athlete who would miss class due to sports events must send written form to instructor at least 24 hours before the class. 

### Homework late policy
Projects are due 11:59pm of the due date. You usually have two weeks to finish the assigned project.  

We do not accept late submissions for this course. Homework is typically due 11:59pm.  The submission deadline has a 24-hour soft cut-off; after midnight, submissions are penalized 5% per hour late round up to the next hour (automated by Blackboard).  So, you turned it in 2:59am. You will get 3 hours penalty with a 15% point reduction. There is no negotiation about this.  

### Exam Policy
Mid-term exam will be announced at least one week ahead of time. If you have special needs, you need to notify me at least 7 days before to arrange the test be performed off-class in the exam center. Missed exams and quizzes cannot be made up. 

### Email Policy
You can email me if you have questions regarding clarification of lectures and homeworks. But you must write to me at least 48 hours to expect an answer. No homework is accepted via Email. Everything must be uploaded onto Blackboard. Elaborate homework-related questions are restricted to office hours. 

## Grading 
65% homework projects, 10% mid-term exam, 15% Final project, 5% in-class quiz, 5% attendances.  We sometimes offer extra credits for additional features in homework and projects. 

## Course Schedule



Date | Lecture&Topic | Course Materials   | Assignments
------- | ---------------- | ---------- | ---------:
|Mon, August 26 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture1">Lecture 1: Course Introduction </a> | Szeliski 1, <a href="https://www.deeplearningbook.org/contents/part_basics.html">Goodfellow 2:Linear Algebra review| <a href="">Exercise 1: set up virtual box, Numpy primer</a>, <a href="https://realpython.com/jupyter-notebook-introduction/">jupyter notebook tutorial</a>|
|Thursday, August 29 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture2">Lecture 2: A simple visual system </a> | <a href="http://6.869.csail.mit.edu/fa13/lectures/chapter_01_simplesystem.pdf">Blockworld: a simple vision system</a>|<a href="https://github.com/fruittree/CSC496_2019F/blob/master/Tutorials/VirtualMachinesviaVagrantandVirtualBox_2019_CV.pdf">VirtualBox Tutorial</a>|
|Thursday, September 5 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture3">Lecture 3: pinhoel camera</a> | <a href="http://6.869.csail.mit.edu/fa13/Lectures/Lecture3/Lecture3cameras.pdf">Cameras</a>|<a href="https://github.com/fruittree/CSC496_2019F/blob/master/Homeworks/Homework1/CSC_496_Homework1.pdf">Homework 1:simple vision system</a>|
|Monday, September 9 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture4">Lecture 4: Lens; Filtering</a> | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture5/SignalProcessing.pdf">SignalProcessing</a>||
|Thursday, September 13 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture5">Lecture 5: Linear Filtering, 2D convolution</a> | |<a href="https://github.com/fruittree/CSC496_2019F/blob/master/Homeworks/Homework1/CSC_496_Homework2.pdf">Homework 2: Numpy/Scipy Exercises|
|Monday, September 16 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture6">Lecture 6: Signal Processing 2: Fourier transform</a> |Szeliski Chapter 3.2,3.3||
|Monday, September 23 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture7">Lecture 7: Convolution in Fourier Domain</a> | |<a href="https://github.com/fruittree/CSC496_2019F/blob/master/Homeworks/Homework3/CSC_496_Homework3.pdf">Homework 3: Pin-hole camera|
|Monday, September 26 | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture8">Lecture 8: Temporal Filters</a> | <a href="https://github.com/fruittree/CSC496_2019F/tree/master/Lectures/Lecture8/cvbookTemporal.pdf">TemporalProcessing</a>||<a href="https://github.com/fruittree/CSC496_2019F/blob/master/Homeworks/Homework3/CSC_496_Homework3.pdf">Homework 4:Motion Magnification|


