# Password-Management-System-using-Face-Recognition
A system which manages and saves the password for different sites which can be accessed using Face Recognition. We have currently implemented login to Facebook/Gmail using face through this script.

## How to run

Face Recognition.ipynb is the main script. It has the following parts - 

1. Adding faces and passwords. Please follow these steps to add faces - 
	1.1 You need to first run the add faces part of the script which will open the camera window. Show your face to the camera and it will detect it.
	1.2 Then move to the script page without closing the camera window which will ask you for details.
	1.3 After entering the details, the script will check if the user is not already existing.
	1.4 If not, then move to the next section called save the details which will save the details locally that you have entered.
	1.5 Now, you are good to go and can proceed with further cells for logging into the website you want.

2. Detect the faces

At first time you need to add you data. Then, the data will be saved locally and next time when you want to login you just need to run the detect faces part of the script which will open the window and detect your face, which will be shown on the screen. Then, close the screen by pressing 'q' on the keyboard and then it will prompt you to enter the site (currently facebook or gmail). Finally, a new page will open redirecting you to the site entered and logging you in automatically with details you have provided earliar.
