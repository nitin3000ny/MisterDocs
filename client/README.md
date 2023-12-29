# Collaborative Text Editor App

This is a collaborative text editor application built using Quill.js, Mongoose, React, Vite, and Socket.io. It allows multiple users to edit a document simultaneously, and the changes are synchronized in real-time.

## Features

- **Real-time Collaboration**: Multiple users can edit the document simultaneously, and changes are instantly reflected for all participants.

- **Automatic Data Saving**: The application automatically saves data to the database every 2 seconds, ensuring that changes are persistent.

- **Quill.js Integration**: The text editor is powered by Quill.js, providing a rich and user-friendly editing experience.

## Upcoming Features

- **User Authentication**: A login system will be implemented to allow users to have personalized accounts.

- **Document Sections**: Users will have a separate section for each saved document, providing a more organized editing experience.

- **CRUD Operations for Documents**: Users will be able to create, read, update, and delete documents.

## Prerequisites

Before running the application, ensure you have the following dependencies installed:

- Node.js and npm
- MongoDB
- Nodemon (for development)
- Vite

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/nitin3000ny/MisterDocs.git
   cd MisterDocs
1. Navigate to the client folder (frontend):
   ```bash
   cd client
2.Install frontend dependencies:
   ```bash
   npm install
   ```
3.Navigate to the server folder (backend):
   ```bash
   cd ../server
   ```
4.Install backend dependencies:
```bash
   npm install
```
5.Set up the MongoDB connection:
  Update the MongoDB connection string in server.js within the server folder to point to your MongoDB instance.

6.Configure CORS settings:
   Update the CORS origin in server.js to match the origin of your frontend application.

7.Run the server using Nodemon in the server folder:  
```bash
   npm run devStart
```
8.Run the frontend development server in the client folder:
```bash
   npm run dev
```
9.Open your frontend application:

10.Open it at the specified origin (e.g., http://localhost:3000).

Enjoy collaborative editing with multiple users!

Contributing
Feel free to contribute to the development of this application. Create a pull request, report issues, or suggest new features.   


