# Python3-Specialization-Capstone
Capstone Project for Coursera's Python 3 Specialization 

Takes a zip file of newspaper PNG images and processes them, extracting text and faces. 
Uses OpenCV to detect faces, tesseract to do optical character recognition, and PIL to 
composite images together into contact sheets. The face detection classifier use is 
haarcascade_frontalface_default.xml. The small sample data file used for development
is small_img.zip and the big file is images.zip.

The last cell in the Jupyter notebook allows one to search through the images looking 
for the occurrences of keywords and faces.
