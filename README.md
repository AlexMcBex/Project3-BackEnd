# Project W3 - Back End

## Overview

This is the Back End of [Project ***W***3 Client](https://github.com/AlexMcBex/Project3-Client)

Project ***W***3 (temporary name) is a full-stack application that allows you to create your own goals list and share it with the world! (or keep it private if you prefer)
Each goal has 3 main components:
- ***W***hat: what you want to achieve
- ***W***hen: a deadline for your goal or, if you're not a fan of timers, when your goal starts
- ***W***hy: that's what makes your goal special and unique, the ***W***hy, your specific reason and motivation to achieve your goal!

You can browse other users' goals and motivate them by leaving a like or a comment and, if you really like their goal, you can copy it on your own list.

---


## Technologies used

- React js
- Node JS
- Javascript
- Express
- bcryptjs
- Bearer Token
- Mongo DB
- Mongoose
- Bootstrap
- Postman
---


## User Stories

    As a user I want the ability to sign up with email and password
    As a user I want the ability to sign in with email and password
    As a user I want the ability to sign out with email and password
    As a user I want the ability to create a goal in my to-do list
    As a user I want the ability to select the subcategory of my goal
    As a user I want the ability to give my goal a 'what' (name of goal )
    As a user I want the ability to give my goal a 'why' (description of goal)
    As a user I want the ability to give my goal a 'when' (deadline for completion)
    As a user I want the ability to mark a goal as completed when finished
    As a user I want the ability to mark my goal as public or private
    As a user I want the ability to see other user's public goals
    As a user I want the ability to see a list of my uncompleted and completed goals
    As a user I want the ability to edit and delete goals

## Route Tables for Documents
---
### Users

| URL       |   HTTP Verb|  Action |
| ----------- | ----------- | ----|
| /users/signup     | GET       | new      |
| /users/signup  |    POST      | create     |
| /users/login  |    GET      | login     |
| /users/login  |    POST      | create     |
| /users/logout  |    POST     | destroy     |
| /users/  |    GET     | index     |
| /users/:userId  |    GET     | show     |

### Goals

| URL       |   HTTP Verb|  Action |
| ----------- | ----------- | ----|
| /goals/  |    POST     | create     |
| /goals/:goalId  |    GET      | show     |
| /goals/  |    GET      | index     |
| /goals/:goalId |    PUT      | update     |
| /goals/:goalId |    DELETE      | destroy     |

### Comments

| URL       |   HTTP Verb|  Action |
| ----------- | ----------- | ----|
| /comment/:goalId     | POST       | create      |
| /comment/:goalId/:commentId  |    DELETE     | destroy     |

## Entity Relationship Diagram

![entityRelationshipDiagram](/img/ERD.png)


