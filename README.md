# Moviex Project Documentation
## Overview
The Moviex project is a full-stack application built using NodeJs, ExpressJs, and ReactJs/Vite. It utilizes MongoDB as its database and implements authentication using Json Web Tokens (JWT) and bcryptjs.

## Project Structure
The project is organized into the following directories:
- `.gitignore`: Contains files and directories to be ignored by Git.
- `backend`: Houses the server-side code, including the ExpressJs application.
- `frontend`: Contains the client-side code, built using ReactJs and Vite.

## Dependencies
The project relies on the following dependencies:
- `axios`: A promise-based HTTP client for making requests.
- `bcryptjs`: A library for hashing and verifying passwords.
- `cookie-parser`: A middleware for parsing cookies.
- `cors`: A middleware for enabling Cross-Origin Resource Sharing (CORS).
- `dotenv`: A library for loading environment variables from a `.env` file.
- `express`: A popular NodeJs web framework.
- `jsonwebtoken`: A library for generating and verifying JSON Web Tokens (JWT).
- `mongoose`: An Object Data Modeling (ODM) library for MongoDB.
- `vite`: A development server and build tool for modern web applications.

## Scripts
The project includes the following npm scripts:
- `dev`: Starts the application in development mode using `nodemon`.
- `start`: Starts the application in production mode.
- `build`: Installs dependencies, installs frontend dependencies, and builds the frontend application.

## Technology Stack
- **Authentication**: bcryptjs
- **Database**: Mongoose (MongoDB)
- **APIs**: Axios
- **Framework**: ExpressJs
- **UI**: ReactJs/Vite

## Configuration
The project's configuration is defined in the `package.json` file, which includes metadata, scripts, dependencies, and devDependencies.

## Development and Production Environments
The project can be run in both development and production environments using the `dev` and `start` scripts, respectively. The `NODE_ENV` environment variable is set to either `development` or `production` depending on the script used.

## Building the Frontend Application
The frontend application can be built using the `build` script, which installs dependencies, installs frontend dependencies, and builds the frontend application using Vite.