# Getting Started with Create React App and Node.js Server

## Introduction

This repository is a starter template for a web application built with React.js for the frontend and Node.js for the backend. Below are instructions to get you started with running the development servers for both the frontend and backend components.

## Available Scripts

### Frontend (React)

In the project directory, you can run:

#### `npm start`

This command runs the app in the development mode.
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.
The page will reload when you make changes.
You may also see any lint errors in the console.

Check the file `\src\App.js` to see the routes.

### Backend (Node.js)

If you navigate to `\server`, you can run:

#### `npm run dev`

This command runs the server in the development mode.
Open [http://localhost:8000](http://localhost:8000) to view it in your browser.

Please note that traditionally, the server should not be within the frontend directory. However, for learning purposes, it's common to have them together. If needed, this structure can be modified in the future.

## .env File

To use a database, you need to create a `.env` file in the root directory of the project and add the following:

```CONNECT_DB=your_mongoDB_connection_string```
