# Face-and-Smile-Detector
•	Turn the webcam on.
•	 Repeat infinitely (until break):
•	 Get the last frame.
•	 Do some color transformations.
•	 Get the output of our detect function.
•	 Load the cascade for the face.
•	 Load the cascade for the eyes.
•	 Create a function that takes as input the image in black and white (gray) and the original image (frame), and that will return the same image with the detector rectangles. 
•	 Apply the detectMultiScale method from the face cascade to locate one or several faces in the image.
•	For each detected face:
o	 Paint a rectangle around the face.
o	 Get the region of interest in the black and white image.
o	 Get the region of interest in the colored image.
o	 Apply the detectMultiScale method to locate one or several eyes in the image.
•	For each detected eye:
o	 Paint a rectangle around the eyes, but inside the referential of the face.
o	 Return the image with the detector rectangles.
•	For each detected smile:
o	 Paint a rectangle around the smile, but inside the referential of the face.
o	 Return the image with the detector rectangles.
•	 Display the outputs.
•	If  type on the keyboard: q
•	Stop the loop.
•	Turn the webcam off.
•	Destroy all the windows inside which the images re displayed.
