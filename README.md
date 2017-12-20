# Smart-Door-Lock-with-Face-Recognition
It is the Python based project and works on face recognition.
In this project i have used SQLite database for storing the details of the persons.
The images of the persons are stored in a folder named "attfaces" and the recording is stored in "record".
For face detection haar cascade is used and for image recognition LBPH algorithm is used.
First run the facerec.py it will open the webcam and detect the faces if detected face is in the database then it will say the name of that person else it will ask to add the person in the data base.
The person can be added in the block list if we enter "No" and if we enter "Yes" then that person will be added in the authenticate persons' list.
for servilience when no one is at home there is a other python program named "recorddata.py" so when administrator goes out side he will run the "recorddata.py" so when some one comes and rings the door bell then it will automatic take pictures of that person so that admin can see that who had came.
