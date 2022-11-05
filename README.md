

 Face Regognitions Base Smart Attendance System
  <br>
</h1>

<h4 align="center">A Smart Face Recognitions Attendance Full-Stack Web App  <a href="https://youtu.be/1ZzRX6haBOc" target="_blank">DEMO </a>.</h4>





<p align="center">
 
![screenshot](https://github.com/csejay3chauhan/microsodt-engage-22-project/blob/master/small%20demo%20gif.gif)
</p>


## About
* Django web framework is used for the development of the whole web app. 
* OpenCv and face_recognition API's were used for the development of Face Recognizzer. 
* The Face Recognizer can detect multiple face at a time and mark their attendance into Database.
* The Faculty can also search for attendance of a student using Multiparameter Search, by specifying the student ID, date of attendance, period of Attendance.
* The credentials for the Faculty are provided by the superuser who has access to the whole database. 
* Only the superuser can update the attendance of a student.
 
## FACE RECOGANITON BASE SMART ATTENDANCE SYSTEM

* The project follows three-layered architecture, which is described below.
  - Presentation Layer : This layer is responsible for the user interface. All the components that users see and interact with within the application are in this layer.

  - Application Layer : Application layer controls the overall functionality of the system. Functionality such as logging into the system, facial detection, and recognition is all done in this layer.
  - Data Layer :  In this layer, Data and Information are stored and retrieved in the database. The names, images of students as datasets, teacheers are stored in the database. Once the face is matched, marking of attendance in the database. 
 <img src="https://github.com/csejay3chauhan/microsodt-engage-22-project/blob/master/static/images/layers.png" witdh="90% "> 
* Note: Python version 3.10.4 is use for this Project And dlib package required for installation of face_recognition api is also uploaded

## Key Features

- The Web app consume very less memory
- The web app very good accuracy 
- The App has A login/singup page so it can be used only authorised people 
- Its run very smothly & it is also good working on less capacity devices (tested)
- it response time is very low it is so fast .
- The attendance can be filter or search by the teacher & HOD
- The searching has a many options ton get a perfect result.
- The Audio message is included.it is soft voice and notify us.
- The attendance is export/Download in the CSV file.
- The attendance is also Download in PDF form.
- if the attendance is once taken in same student then again not mark . it will mark in next day/next lecture.
- Easy in the modification
- if Unknown/not registered person take the attendance it show the red mark and it will not display the attendance.
- No limits at image Size .
- it the search section we can search attendance in multiple ways .
 

## How To Use/Run

To run the web app on your local computer, install the required libraries ([requirements.txt]).

```python
pip install -r requirements.txt
```

**Note: If dlib is not installed then you can install the file 
"dlib-19.22.99-cp39-cp39-win_amd64.whl" which is attached with the code file** [download](https://github.com/csejay3chauhan/microsodt-engage-22-project/blob/master/dlib-19.22.99-cp39-cp39-win_amd64.whl)
```python
pip install dlib-19.22.99-cp39-cp39-win_amd64.whl
```

and run the following command in the command prompt:
```python
python manage.py runserver
``` 

**To create your own credential for logging into the application and also access database this for next step**
```python
python manage.py createsuperuser
```
After running the above command and creating the credentials, you can use the same credentials for logging in.

**Open the login page**
```python
http://127.0.0.1:8000/login/
```
**Then fill the details (this is Defalt if u didint created then use it but better option is to use your own Which is previously created)**

```python
Username: admin
Password: admin
```



**Note: Use <img src="https://img.shields.io/badge/Microsoft_Edge-0078D7?style=for-the-badge&logo=Microsoft-edge&logoColor=white"> 
, <img src="https://img.shields.io/badge/Firefox_Browser-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white"> , <img src="https://img.shields.io/badge/Google_chrome-4285F4?style=for-the-badge&logo=Google-chrome&logoColor=white">  for best view use 80% screen resolution.**




## Download

- To Clone the Repo
```
$ git clone https://github.com/csejay3chauhan/microsodt-engage-22-project.git
```
- [Download](https://drive.google.com/drive/folders/1npXtn7KT_cWE4gXdbDIrHVz8hqa1Cia-) Screenshots of the project
- [Download](https://drive.google.com/drive/folders/159pOGSotTmN7HTLe4NfDgUQy9I-9p9Bm) Flowcharts & Diagram
- [Download](https://drive.google.com/drive/folders/1IG8ILKySj9dhp2jKQ7lxauh48haLgkco) Demo Video
- [Download](https://drive.google.com/drive/folders/1IG8ILKySj9dhp2jKQ7lxauh48haLgkco) PPT Download
- [Download](https://github.com/csejay3chauhan/microsodt-engage-22-project.git) This Project by clicking Download


## Packages

This WebApp uses the following Open source packages:

- Python
- Django
- Opencv-contrib-python
- OpenCv
- matplotlib
- Face_recogniton
- pillow
- ace-recognition-models
- dlib
- cmake
- certifi
- numpy
- pandas
- pipreqs
- requests
- sqlparse
- pyttsx3
- reportlab
- datetime
- os




