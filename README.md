# Developers' Connector:

> A Social Platform for developers to communicate through posts

## Purpose

DevConnector is a platform designed to facilitate the sharing of ideas, skills, and knowledge among developers worldwide. It allows developers, both new and experienced, to interact with each other, share their expertise, and engage in discussions.

### User Authentication/Login System

Authentication is required for users to use the application. Users must have an account and profile to communicate with other developers and access the primary features of the application.

- Users have different permissions based on their roles, which determine their access to specific parts of the website.

### Dashboards

DevConnector provides dashboards that collect and display relevant information about users, including personal details, experiences, education, and GitHub profiles.

### Live Text Chat/Messaging between Developers

The platform includes a live text chat feature, allowing developers to engage in real-time conversations and share valuable information.

## Target Audience

The main target audience for DevConnector is individuals eager to learn programming and looking for opportunities to connect with experienced developers. It serves as a platform for knowledge exchange and skill development.

## Tech Stack

- MongoDB
- Express.js
- React
- Node.js
- React Redux
- Mongoose


## Description

DevConnector is a full-stack application built on the MERN stack, utilizing MongoDB, Express, React, and Node.js. It also incorporates various open-source libraries to expedite development and enhance authentication security.

MongoDB was chosen as the Database Management System due to its dynamic and flexible document schemas, allowing storage of diverse data for users and profiles. The integration of MongoDB's BSON (Binary JSON) with the core JavaScript technologies in the MERN stack ensures seamless data management.

The front-end of DevConnector is developed using React, handling the user interface, text, images, and networking requests to API endpoints. React's reusability of components improves code quality, efficiency, and scalability.

Express and Node.js are responsible for the backend business logic, including routing, middleware integration, and RESTful API endpoint handling.

React-Redux is used for global state control and theme management throughout the application.

Authentication will be implemented using JSON Web Tokens (JWT), allowing RESTful endpoints to be authenticated without session management. Additionally, a local username and password authentication strategy is being considered for a familiar login flow.

Mongoose, an Object Data Modeling (ODM) library for MongoDB and Node.js, will assist in managing data relationships, providing schema validation, and translating objects between Node.js code and MongoDB representation.

DevConnector is a single-page application with the dashboard component as the main wrapper element for rendering various views.

Unauthenticated users can only view developers' profiles through the dashboard. Protected routes restrict access to other application features and prompt authentication when attempting to access them.
