# OnlineCourseApp Project
Welcome to the OnlineCourseApp project, where you'll leverage your Django skills to enhance the functionality of the existing Online Course application.

# Project Overview
This project provides a Django-based Online Course app with a focus on implementing key improvements, including the creation of Question, Choice, and Submission models. The enhancements cover the administration of a new course object with exam-related models via the admin site, updating course details templates to display questions and choices, and creating new templates for displaying exam results and submissions. Additionally, the project involves the implementation of views to handle exam result submission and evaluation.

# Getting Started
## Clone the Repository:
```
git clone https://github.com/chandramohan0/OnlineCourseApp.git
```
## Navigate to Project Directory:
```
cd OnlineCourseApp
```

## Install Dependencies:
```
pip install -r requirements.txt
```
## Run Migrations:
```
python manage.py makemigrations
python manage.py migrate
```

## Create Superuser (for admin site access):
```
python manage.py createsuperuser
```

## Run Development Server:
```
python manage.py runserver
```

## Access the Admin Site:
Open a web browser and go to http://localhost:8000/admin/. Use the superuser credentials to log in.

# Project Features

## 1. Create Models:

+ Question
+ Choice
+ Submission

## 2. Admin Site Updates:

+ Administer new course objects with exam-related models.

## 3. Template Enhancements:

+ Update course details template to display questions and choices.
+ Create a new exam result template to show the result of the submission.

## 4. Views Implementation:

+ Create a new exam result submission view.
+ Implement a new view to display and evaluate exam results.

# Contributing
1. Fork the repository.
2. Create a new branch for your contributions.
3. Make changes and submit a pull request.


# License
This project is licensed under the **MIT License** - see the [LICENSE.md](LICENSE.md) file for details.


# **ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)
