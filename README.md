# ToDo App

A simple to-do application build with flask and bootstrap.

## The Brief

Build a simple online to-do list with a web interface that can be used in
all popular web browsers. The application has to Support multiple users and store data in
any type of databases, in-memory or server.

## The UX

The to-do app is created for users who wants a simple and clutter free app that would quickly and efficiently allow them to add and remove tasks. The app should be accessible on all types of devices and all user integrations should be intuitive.

Based on the above definition, the app design is minimalistic with clean forms for signing in and signing up, that user can quickly and intuitively interact with. The app color theme consist of four colors. Beside the black and white, there are two additional colors in order to keep the interface simple and clean. The primary application color is blue which represents intelligence and responsibility but at the same time is cool and relaxing. It is used as a background overlay or as a background for actions that require either a 'positive' action of submitting a form or adding new task to the list. The secondary color, used mainly for 'negative' actions, like removing a task or closing a form is set to red which symbolized strength and power. It is used quite often in UX/UI development to get user attention and indicate a irreversible actions.

The app design has two distinguish templates where first is used for forms and second for dashboard. The templates used for forms consists of blue background with background image which gives the app clean and modern look that highlights the form as its main feature. The forms are intuitive and easy to use. The dashboard template has the same background image but with white background color and consists of two parts. First display user's username, number of tasks currently available and a 'Logout' button. The second which is the main feature of that block is the 'Add task' button that is well defined and described. The other block of the dashboard template is the list of tasks. Each task has a blue background with and image overlay. It consists of task description, date created and button that allows user to remove it from the list.

All buttons on the page have a hover feature which changes the look on user interaction. The hover clearly indicates that there is a function associated with it and its description indicates the action.

All of the pages are responsive and work well on all modern browsers and various devices.

## Features Left to Implement

Ideally the following feature should be implemented:

- deadline for tasks with build in calendar to allow for quick date pickup.
- color coding for different tasks purpose to add better visual appear to the app and allow quick visual scan of the tasks. The app could have two categories, for example reminder and to-do task.
- rich dashboard with profile image and ability to update the details, including image, password and email.
- ability to edit existing tasks.
- 404 page.

## Technology used

- Python - Used for application logic.
- Flask - A microframework for Python.
- Jinja2 - A templating language for Python.
- HTML5 - Core structure of the website.
- CSS - Main style of the website.
- Bootstrap framework
- Sqlite3 - database

In order to make the app secure, all user details are stored in the database with password being stored as hash which prevents it from being stolen in case of database being compromised. This was accomplished using the werkzeug python library.

## Steps required to run the app locally

Install flask with its all dependencies listed inside the requirements.txt file and run the project.

```
$ pip install -r requirements.txt
$ flask run
```

## Login details

### User 1

```
username: andrew
password: password
```

### User 2

```
username: daniel
password: password
```