CONCORDIA UNIVERSITY
FACULTY OF ENGINEERING AND COMPUTER SCIENCE

Course Outline:
MECH 472  Mechatronics and Automation

--------------------------------------------------------------------------------------------------

The codes here are for motion detection around the printer:

- The program monitors the activities around the 3D-printer in real-time and updates every 4 seconds.
it also sends the updates to a '.txt' file called 'MotionResult.txt' for aftermath analysis.
The program works based on image subtraction (via the function called 'subtract_image' in techlead.cpp),
and image area calculation (via the function called 'image_pixelcount' in techlead.cpp).
There are 5 options for veried sensitivity levels. with option 1 being the most sensitive.
