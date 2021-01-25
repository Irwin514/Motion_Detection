This folder contains all the codes required for one of the optional aspects of the MECH 6631/472 project.
The entire work, done, was carried out by members of the group:

*UNDERGRADUATE:
VIVEK PATEL [Student ID: 27532377]
IRWIN LOPEZ [Student ID: 29372431]
REMI EHOUNOU [Student ID: 40007669]

*MASTERS:
NKEMDILIM OKECHUKWU UMEZUDE [Student ID: 40087834]

--------------------------------------------------------------------------------------------------

The codes here are for motion detection around the printer:

- The program monitors the activities around the 3D-printer in real-time and updates every 4 seconds.
it also sends the updates to a '.txt' file called 'MotionResult.txt' for aftermath analysis.
The program works based on image subtraction (via the function called 'subtract_image' in techlead.cpp),
and image area calculation (via the function called 'image_pixelcount' in techlead.cpp).
There are 5 options for veried sensitivity levels. with option 1 being the most sensitive.