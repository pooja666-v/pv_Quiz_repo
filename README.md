# pv_Quiz_repo
Quiz application using Django Framework.

Steps to Excecute the project:
  > Install Python(3.7.6)
  > Open terminal to install Django
  > Install Django using pip command(pip install Django==3.0.5)
  > Download the Zip file of Quizproject and extract the files.
  > Move to the project folder in terminal.
  > Install the requirements of the project using "pip install -r requirements.txt" command.
  > Then run following command to execute the project.
  > py manage.py makemigrations
  > py manage.py migrate
  > py manage.py createsuperuser (Admin)
  > py manage.py runserver
  > Now copy the URL that generated on terminal and paste it in broswer.
 
 
 Features:
    Admin:
         > Admin can see Total Number of students,Teachers,questions and courses on dashboard.
         > Can view, update student and teacher, and can approve teacher.
         > Admin can view Questions and courses.
    Teacher:
         > Teacher has to register(Admin has to approve the teacher).
         > After approval teacher can login to add questions and courses.
         > Teacher can see toalnumber of students, courses and questions.
         > Teacher can add, view and delete courses and questions.
     Student:
         > Student has to register and then login to the site to take quiz.
         > After login, Can see how many exams and questions are there in applicataion.
         > Can give exam any time.
         > Can view marks and time taken to complete the exam.
         
