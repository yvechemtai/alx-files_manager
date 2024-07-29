# Files Manager

## Overview

This project is a summary of the back-end trimester at Holberton School, focusing on authentication, NodeJS, MongoDB, Redis, pagination, and background processing. The objective is to build a simple platform to upload and view files, incorporating user authentication via tokens, listing files, uploading new files, changing file permissions, viewing files, and generating thumbnails for images.

## Project Details

- **Language:** JavaScript (ES6)
- **Back-end Technologies:** NodeJS, ExpressJS
- **Databases:** MongoDB, Redis
- **Background Processing:** Kue

## Team

- **CTO:** Guillaume, CTO at Holberton School
- **Your Team:** Silas Mungiria

## Timeline

- **Start Date:** Feb 8, 2024, 6:00 AM
- **End Date:** Feb 15, 2024, 6:00 AM
- **Checker Release Date:** Feb 10, 2024, 12:00 AM
- **Manual QA Review:** Must be done after completing the project
- **Auto Review:** Will be launched at the deadline

## Tasks

1. **Redis Utils:** Create a class for managing Redis connections and operations.
2. **MongoDB Utils:** Create a class for managing MongoDB connections and operations.
3. **First API:** Set up the Express server and define basic endpoints for checking status and retrieving statistics.
4. **Create a New User:** Implement an endpoint for creating new users with email and password.
5. **Authenticate a User:** Implement endpoints for user authentication, token generation, and token-based user retrieval.
6. **First File:** Implement an endpoint for uploading files and storing them in the database and disk.
7. **Get and List Files:** Implement endpoints for retrieving individual files and listing files with pagination.
8. **File Publish/Unpublish:** Implement endpoints for setting files as public or private.
9. **File Data:** Implement an endpoint for retrieving the content of a file.

## Usage

1. Clone the repository: `git clone https://github.com/mugambi12/alx-files_manager`
2. Install dependencies: `npm install`
3. Start the server: `npm start`

## Requirements

- **Node Version:** 12.x.x
- **Operating System:** Ubuntu 18.04 LTS
- **Allowed Editors:** vi, vim, emacs, Visual Studio Code
- **Linting:** ESLint

## Additional Notes

- Ensure all files end with a new line.
- Perform linting using ESLint.
- For running the server, set the PORT environment variable or use the default port 5000.

## Resources

- Node.js Getting Started
- Express Getting Started
- MongoDB Documentation
- Redis Documentation
- Bull Documentation
- Image Thumbnail Documentation
- Mime-Types Documentation

## Learning Objectives

Upon completion of this project, you should be able to:

- Create an API with Express.
- Implement user authentication.
- Store data in MongoDB and Redis.
- Setup and use background workers.

---
