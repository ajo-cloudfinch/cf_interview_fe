# cf_fe_interview

> Front-end Interview

## What To Do ?

This is a small web application where users can see posts, users and Images. Being a front-end engineer, your task is to create
three different sections which will show posts, users and images respectively.

In the post section, Users can add a post, edit a post, view a post and delete the post.

# Adding A Post

Inorder to add a post, you need to make a call to 'https://jsonplaceholder.typicode.com/posts' - POST

Request Payload:-
userId: Number
title: String
body: String

# Listing Posts

Inorder to get all the post, you need to make a call to 'https://jsonplaceholder.typicode.com/posts' - GET

# Edit Post

Inorder to edit the post, you need to make a call to 'https://jsonplaceholder.typicode.com/posts/id' - PUT

Request Payload
id

# Delete Post

Inorder to delete the post, you need to make a call to https://jsonplaceholder.typicode.com/posts/id - DELETE

Request Payload
id

# List Users

Inorder to get all the users, you need to make a call to https://jsonplaceholder.typicode.com/users - GET

# List Images

Inorder to get all the images, you need to make a call to https://jsonplaceholder.typicode.com/photos - GET

## Requirements

- Design the application by spilitting into reusable components

- Make use of Vuetify Library for UI components

- Make use of Vuex - State Management and Axios for Data Fetch Purpose

## What we will look for ?

- Clean Code

- Implementation of Functionalities

- Clean UI Design using Vuetify