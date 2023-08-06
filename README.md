# Blog_Website_ReactJS

# Overview
This documentation provides an overview and detailed explanation of the Blog Website ReactJS project available at https://github.com/KlimentinaIvanova/Blog_Website_ReactJS. The Blog Website is a ReactJS-based web application that allows users to view and read blog posts on various topics. Registered users can also create and manage their blog posts. The project showcases the use of several technologies, such as React components, state management, Google OAuth for authentication, Material-UI/Core components for UI design, React Hooks for managing state and lifecycle, and integration with GNews API using Axios for fetching blog post data.


# Project Structure
The project's codebase follows a structured organization to enhance maintainability and readability.

# Components

The project utilizes various React components to build the UI. Components are reusable and self-contained, allowing easier management of different parts of the application.

# State Management

State management is implemented to keep track of application state and make data available across components. The specific state management approach used in the project should be documented here, such as Redux, React Context, or any custom implementation.

# Google OAuth

The project leverages Google OAuth for user authentication. Details on how Google OAuth is implemented and integrated into the application should be documented here.

# Material-UI/Core Components

Material-UI is a popular UI framework for React applications. This section should provide an overview of the Material-UI/Core components used in the project and how they enhance the application's user interface.

# React Hooks

React Hooks are used to manage state and lifecycle in functional components. This section should explain the different React Hooks used in the project and their purposes.

# GNews API and Axios Integration

The project integrates with the GNews API using Axios to fetch blog post data. Details on how the integration is set up, API endpoints used, and how the data is processed should be documented here.

# Prerequisites
Before running the project, ensure you have the following installed:

Node.js (version 12 or above)

npm (Node Package Manager)

# Setup

Clone the repository:


git clone https://github.com/KlimentinaIvanova/Blog_Website_ReactJS.git



Navigate to the project directory:



cd Blog_Website_ReactJS

Install the project dependencies:


npm install

Obtain Google OAuth credentials:

To enable Google OAuth for authentication, you'll need to set up a Google API project and obtain OAuth credentials (client ID and client secret). Follow the instructions provided by Google to create a new project and set up OAuth credentials.

To use the Google OAuth feature, you may need to sign in using your Google account. Follow the on-screen instructions to authenticate and access the application's features for authenticated users.

Exploring Blog Posts

Once you're logged in, you should be able to explore blog posts on various topics. The GNews API integration should provide a list of blog posts that you can view and read.

Once you have the credentials, create a .env file in the project root directory and add the following:


REACT_APP_GOOGLE_CLIENT_ID=your_google_client_id
Replace your_google_client_id with the actual client ID you obtained from the Google API project.

Usage
To run the development server, use the following command:


npm start

This will start the development server, and the website will be accessible at http://localhost:3000.
