# Django_project
Quiz Application
What is it? ⛹️‍♂️
The project is a complete Exam Portal system built for educational institutions like schools and colleges. The portal serves as a single platform that can be used by all the professors and students, having their own set of work to be done. Following are the three levels of users along with the supported features that can be done by them in the portal:

admin 🛠

maintains the entire portal system through the django-admin site.
has access to the entire database consisting of all the data stored.
professor 👔

MCQ questions can be created/edited by professors which then further can be added to one or more question paper created by them.
The professor can create different groups of students as per their wish.
Exams can be created which can have a Question paper alloted to it by them.
student 🧑‍

Can attempt exams allotted to them within the time constraints set by the professor
Can view their marks and solutions after completing the exam.
Have a list of all the exams completed and yet to be attempted in a single page
Cloning the Application in local ⬇️
Following software needs to be setup in the system for using the application in local

git
python
pip
Clone the repo by running the following command in any terminal

git clone https://github.com/SubhradeepSS/Exam_Portal.git
Open the project in any source code editor.

Open terminal and run

pip install -r requirements.txt
This installs all the packages required for running the application locally

Running the Application 🚚
Local 💻
For running the project, navigate to the project directory and follow the following instructions:

Type the following in the command line:

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
# this will ask for username, email(optional) and password. 
# Enter some credentials to be used later for django admin functionality.
python manage.py runserver
Log on to django admin site using the superuser credentials

Click on Groups section and create 2 groups - Professor and Student
Click on Users section and create some users, and also make each user belong to one of the groups- Professor/Student as per role
Logout of the admin site and go to http://127.0.0.1:8000/ where the home page of the project will be rendered.
Now any student/professor can login using their own credentials.

Deployment 🚀
View deployed site here.

Credentials:
User Type	Username	Password
admin	admin	admin
student	student_1	password_student_1
prof	prof_1	password_prof_1
The admin can create more users(professors/students) from the django admin panel and can add them to corresponding groups, after which they can login through the site.

Built With 💕
Django
Django REST Framework
Python
HTML
CSS
JavaScript
Bootstrap
Postman
Visual Studio Code
Heroku
API info 👷
The APIs were built using Django and Django RESTFramework, which were further tested out using Postman. Some of the APIs tested can be found out here.

Next steps 🔥
 Support for separate subjects and courses alloted to professors and students.
 Improved exam proctoring using AI based plagiarism checker, video and audio recording.
 Discussion forum for students sorted in different class groups as well as subjects, where one particular student can consult the concerned faculty or other fellow students.
 Proper result and analysis reports of exams(subjectwise) in dashboard for the students.
 Professor's view of complete date of students enrolled in their subjects.
Contributing 👩‍💻
Any contributions made to the project are greatly appreciated.

Fork the Project
Create your Feature Branch (git checkout -b feature/AmazingFeature)
Commit your Changes (git commit -m 'Add some AmazingFeature')
Push to the Branch (git push origin feature/AmazingFeature)
Open a Pull Request
