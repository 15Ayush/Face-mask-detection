# Face-mask-detection

Face detection has emerged as a very interesting problem in image processing
and computer vision. It has a range of applications from facial motion capture to
face recognition which at the start needs the face to be detected with a very
good accuracy. Face detection is more relevant today because it not only used
on images but also in video applications like real time surveillance and face
detection in videos. High accuracy image classification is possible now with the
advancements of Convolutional networks. Pixel level information is often
required after face detection which most face detection methods fail to provide.
Obtaining pixel level details has been a challenging part in semantic
segmentation. Semantic segmentation is the process of assigning a label to each
pixel of the image. In our case the labels are either face or non-face. Semantic
segmentation is thus used to separate out the face by classifying each pixel of
the image as face or background. Also, most of the widely used face detection
algorithms tend to focus on the detection of frontal faces


After the breakout of the worldwide pandemic COVID-19, there arises a severe
need of protection mechanisms, face mask being the primary one. The basic aim
of the project is to detect the presence of a face mask on human faces on live
streaming video as well as on images. We have used deep learning to develop
our face detector model. The architecture used for the object detection purpose
is Single Shot Detector (SSD) because of its good performance accuracy and
high speed. Alongside this, we have used basic concepts of transfer learning in
neural networks to finally output presence or absence of a face mask in an
image or a video stream. Experimental results show that our model performs
well on the test data with 100% and 99% precision and recall, respectively.



## RUN warn.py file after Mask_Detector.ipynb ##
