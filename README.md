# Social-Bond-API

## Description

This is a Social Network API built using Mongoose and is ready to be hooked up to a front end

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Instructions](#instructions)
- [Walktrough Video](#video)

## Installation

In order to install this project you must clone this project on to your local machine.

## Usage

This project usage is for anyone that needs a back-end for their social network type site

## Instructions

- Step 1: Clone this repository

* ![step-1](images/step-1.png)

- Step 2: Install dependencies with 'npm install'

* ![step-2](images/step-2.png)

- Step 3: Type 'npm start' once more to start the server

* ![step-3](images/step-3.png)

- Step 4: Open Insomnia core or any alternative

* ![step-4](images/step-4.png)

* Step 10: You can create, read, update, and delete users and thoughts, and add and delete reactions and friends using these urls:

  - http://localhost:3001/api/user
  - http://localhost:3001/api/user/:id (required to delete, update, or just to read one category)
    - To post a user - JSON being sent will be this: { "username": "`username`", "email": "`email@example.com`" }
  - http://localhost:3001/api/user/:userId/friends/:friendsId (required to delete and add a friend)
  - http://localhost:3001/api/thoughts
    - To create a thought - JSON being send will be formated like this: { "thoughtText": "`This is an example thought`", "username": "`username of person creating the thought`" }
  - http://localhost:3001/api/thoughts/:id (required to delete, update, or just to read one tag)
  - http://localhost:3001/api/thougts/:thoughtsId/reactions (required to add a reaction to a thought)
    - To create a reaction - JSON being send will be formated like this: { "reactionBody": "`This is an example reaction`", "username": "`username of person creating the reaction`" }
  - http://localhost:3001/api/thoughts/:thoughtsId/reactions/:reactionsId (required to delete a reaction from a thought)

  # video

  ![Watch here](https://drive.google.com/file/d/1kkagFMZf-SVEdCSifjb1wihBrb5Z2-cl/view)
