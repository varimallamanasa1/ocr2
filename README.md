# OCR
OCR text extraction for complex images

This project attempts to extract text from Images using Object Character Recognition. Additionally, it attemps to flag images as appropriate or inappropriate given the text extracted from the image. This was a project for CS 6220 Big Data Systems and Analytics.

To run the project please clone the repository and run python app.py. This will pull up our website on the given local host and allow the user to upload an image and download the extracted text as a txt file. Note you will first need to have all the required modules downloaded first to run this.


This project aims to improve the performance of pytesseract: https://pypi.org/project/pytesseract/ in terms of being able to accurately extract text from computer generated images. Pytesseract is an optical character recognition (OCR) tool for python to extract text from images. We used pytesseract in about 4 lines of our project code and did not attempt to alter its process but instead apply computer vision and text correction techniques to improve its performance.
