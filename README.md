# Minor Project for 7th Semester BTech

## Topic : Face Detection and Recognition using OpenCv


## Project Flow

## Steps required before the execution of application

### Step-1) Download or clone my Repository to your device
### Step-2) Type pip install -r requirements.txt in command prompt(this will install required package for project)
### Step-3) Create a TrainingImage folder in a project folder.
### Step-4) Open attendance.py and automaticAttendance.py, change all the path according to your system
### Step-5) Run attendance.py file using the command python3 attendance.py on the terminal of the code editor or command prompt.
### After doing step 5 , the application is opened and the steps mentioned below will be followed.

## Steps required after the execution of application

### Step-1) After you run the project you have to register your face so  that system can identify you, so click on register new student
### Step-2) After you click a small window will pop up in that you have to enter you ID and name and then click on Take Image button
### Step-3) After clicking the Take Image button , A camera window will pop up and it will detect your Face and take around 50 Images(you can change the number of images it can take) and stored in the folder named TrainingImage. the more you give the image to the system, the better it will perform while recognising the face.
### Step-4) Then you have to click on the Train Image button. It will train the model and convert all the images into numeric format so that the computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
### Step-5) It will take some time(depends on the system).
### Step-6) After training models click on Automatic Attendance ,you have to enter the subject name and then it can fill attendance by your face using our trained model.
### Step-7) it will create .csv file for every subject you enter and separate every .csv file according the subject
### Step-8) You can view the attendance after clicking the View Attendance button. It will show records in tabular format.




## Sample UI Obtained 

### Step 1 : The application is opened.


![face1](https://github.com/user-attachments/assets/f8473fc3-84f6-4e31-b90b-29233eae7dd9)


### Step 2 : Registration of new student


![face2](https://github.com/user-attachments/assets/ecd32592-d1a6-4e30-9535-a607eaf6ce4e)



### Step 3 : Training of new face


![face3](https://github.com/user-attachments/assets/3e7e5192-a607-4d41-a72e-f537d22ae392)



### Step 4: Filling of attendance


![face4](https://github.com/user-attachments/assets/ebc6e788-a125-4692-950d-8175ff01f3a7)



### Step 5: Attendance is recording


![face5](https://github.com/user-attachments/assets/690ce6a9-abea-4583-ba39-022f2a497a5e)



### Step 6: Attendance is displayed


![face6](https://github.com/user-attachments/assets/d81eb3e7-497a-4ab9-828f-040053015d7d)



### Step 7: Overall attendance is displayed


![face7](https://github.com/user-attachments/assets/4cf27cae-e33b-4fdd-bc49-4ccb4accf048)



### Hence these steps clearly demonstrate the entire working of the application from the registering of new students to displaying the overall attendance of each student in a particular subject.

## INSTALLED MODULES
Python 3 will be required for the app to run. other modules can also be found in requirements.txt:

#### numpy==1.16.1
#### opencv-contrib-python==4.2.0.34
#### opencv-python==4.2.0.34
#### openpyxl==3.0.3
#### pandas==1.0.3
#### Pillow==7.1.1
#### pyttsx3==2.71
