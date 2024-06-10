# classmanager
A Student-Teacher Portal built using HTML, CSS, Python and Django

Class Manager is a Student-Teacher Portal where techers and student can sign up and teachers can add students in their class.

Class Manager contains more features like:
1. Teachers can add or edit their student's marks after adding them in the class.
2. Teachers can also write notice which will be sent to all students in their class.
3. Teachers can upload assignments which will be sent to all students in their class and students can download the assignments.
4. Students can also submit their assignment but once submitted can't be changed later.
5. Teachers can also see all the mark given by them to a student through their marks profile and can edit them if necessary.
6. Students can see marks given to them by teachers in marks section.
7. Student can see the list of all teachers in the portal and can message any of them.
8. Teachers can see all the messages written by students in Inbox.
9. User can search any student through search option at the top of the student list page. Same goes for teachers list.
10. User can see their profile through profile option.
11. User can add profile picture and edit their profile through edit profile.
12. User can also change their password if necessary.



### Home Page

![classmanager](https://user-images.githubusercontent.com/59278577/85334196-73729680-b4f8-11ea-90b6-a42336e1d7dd.PNG)
![classmanager-homepage](https://user-images.githubusercontent.com/59278577/85334362-c2203080-b4f8-11ea-973c-e9ff6b481810.PNG)
![classmanager-homepage1](https://user-images.githubusercontent.com/59278577/85334481-f398fc00-b4f8-11ea-88fc-ba3371076930.PNG)

### Login Page

![classmanager-loginpage](https://user-images.githubusercontent.com/59278577/85334573-1deab980-b4f9-11ea-86b9-4e1367e78057.PNG)

### Profile Page
User can edit their profile by clicking on Edit profile

### Marks given by teacher
Here, teachers can see all the marks given by them to a particular student of her class and can update them.

### Marks list obtained by Student

Students can check marks assigned to the in each and every subject.

### Assignments uploaded by teacher
Students can download assignment given by their teacher and can submit their work too.


### Assignment submission by students
Teacher can check submissions made by their students  and can give them marks for that.


Class Manager uses the multi-user concept of Django where student and teacher are different types of user and have different functionalities.

## ACCESS THE PROJECT
pip install django
python manage.py migrate
.\venv\scripts\activate  
python manage.py createsuperuser
python manage.py runserver
Github link : https://github.com/kentigerc/class-manager.git
