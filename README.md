# Workshop-Project-1-Instagram-Clone

Instagram Clone is a full-stack web application that replicates some of the core features of Instagram, allowing users to create posts, like, unlike, comment on posts, and perform various interactions with the posts.

## Overview

The Instagram Clone project consists of both the backend and frontend components. The backend, built with Express and MongoDB, provides API endpoints for creating, retrieving, updating, and deleting posts. The frontend, developed using React, allows users to interact with the posts by creating new posts, liking, unliking, and commenting.

## Backend

The backend is an Express application that utilizes MongoDB to store post data. It exposes various routes for performing actions on posts, such as fetching all posts, getting a single post, creating a post, updating a post, deleting a post, liking a post, unliking a post, commenting on a post, and getting comments and likes on a post.

## Frontend

The frontend is a React application that communicates with the backend API to fetch and manipulate post data. It provides a simple user interface where users can create new posts, like, unlike, and comment on existing posts. The application updates in real-time as users interact with the posts.

## Project Structure

**backend:** Express backend for handling API requests and interacting with MongoDB.

**server.js:** Backend server code for handling posts.

**.env:** Configuration file for environment variables.

**frontend:** React application for the user interface.

**App.js:** Main component for the React application.

**App.css:** Styling for the React components.

**index.html:** HTML template for the React application.

## Dependencies

- Node.js
- Express
- MongoDB
- Mongoose
- React
- Axios
- CORS
