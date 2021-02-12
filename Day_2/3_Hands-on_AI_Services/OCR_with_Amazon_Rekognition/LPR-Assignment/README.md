# MSA 8650
**Fall 2020 - Computer Vision Project**

In this project we explore three different methodologies to read vehicle license plates. The process usually comprises two steps:
1.	Finding the license plate in the image, i.e. creating a bounding box to crop the image around the plate; and 
2.	Perform optical character recognition (OCR) on the cropped image.

For this project we provide a dataset of about 1,800 license plates with an image of the vehicle, a gray-scale image of the license plate, and the license number. The data were collected using a commercial license plate reader (LPR) in the Atlanta area.

We use three different technologies to extract the registration number from the license plate image (IR-patch):
1.	Use OpenCV image processing tools to manipulate and enhance the image for performing OCR with the open source package Tesseract
2.	Use of cloud AI services, such as Amazon Rekognition on AWS
3.	Use a Convolutional Neural Networks (CNN): use pre-trained, build on pre-trained, or build from scratch.
    - e.g. LPRNet. https://arxiv.org/abs/1806.10447v1 

The notebooks provide some guidance on starting this project.
Data are available to students enrolled in this course.