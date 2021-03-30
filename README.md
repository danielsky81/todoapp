# ToDo App

## The Brief

The bried required to build a simple online TODO list with a web interface that can be used in
all popular web browsers. The application has to Support multiple users and store data in
any type of databases, in-memory or server.

Based on that brief, the project was build using Flask with sqlite3 database for backend and Bootstrap for frontend.

## The UX

The ToDo App is aimed toe help user create a quick tasks that can be stored for future reference or removed once complited. The design is minimalistic with cluttter free approach.

## Features Left to Implement

Ideally the following feature should be implemented:

- data and time of task creation
- deadline for task
- color coding for tasks to add better visual appear to the app and allow quick visual scan of the content
- reach dashboard with profile image

## Steps required to run the app locally

Install flask with its all dependencies listed inside the requirements.txt file

```
$ pip install -r requirements.txt
```

Set 'SECRET_KEY' and 'SQLALCHEMY_DATABASE_URI' absolute path for the database