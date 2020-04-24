## BLOCK-readText

#### Timeline for the entire topic - 3 hours.

In this topic, you have to build a small web API from scratch for the following user stories.

_Note - This is not fullstack application, you only have to build the API using Node.js, Express.js and MongoDB. Please follow standard web practices._

```
1. There are two kinds of users in our system
  - students
  - mentors
2. A student should be able to signup using following information.
  - Name, Email Id, Password, Batch Number.
3. A student should be able to login using his/her email id and password.
4. Atleast 3 mentors should be automatically seeded into the database and so they don't have to signup. Mentor data should be seeded with the following information.
  - Name, Email Id, Password.
5. A mentor should be able to login using email and password.
6. The identification route for both the types of users has to be the same.
7. A mentor should be able to add a task in a resource called `Todo` with following info.
  - Name of todo, Whether its completed or not.
8. A mentor should be able to see all the tasks.
9. A student should be able to see all the tasks but should not be able to add a new task.
```

## BLOCK-writeTextAnswer

Here write the psuedo code you would follow to build the above API.

1. Create two different schemas for students and mentors

2. Student schema requires Name, Email, id, password and Batch Number

3. Only register student can login with a valid Email and Password

4. Mentor must be seeded in database so no need of signup

5. Only seeded and register mentors can login

6. The routes must be same for both student and mentor

7. Create a Model for todo contains name and iscompleted

8. Mentor can add a resource i.e name of the todo and or it's completed or not and he can see the tasks

9. student also can check the task cant add task
