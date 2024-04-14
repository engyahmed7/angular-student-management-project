# Angular CRUD with JSON Server

This project is a simple CRUD (Create, Read, Update, Delete) application built with Angular for the frontend and JSON Server for the backend.

## Features

- Add new students with their details such as name, mobile number, age, email, address, and gender.
- View a list of all students.
- View details of a specific student.
- Update student information.
- Delete a student from the database.

## Technologies Used

- Angular: A popular framework for building client-side web applications.
- JSON Server: A simple and fast backend for prototyping and mocking RESTful APIs.
- HTTP Client: Angular's built-in module for making HTTP requests to the backend server.

## Prerequisites

Before running this project, ensure that you have the following installed:

- Node.js and npm (Node Package Manager)
- Angular CLI (Command Line Interface)
- JSON Server

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Install dependencies using `npm install`.
4. Start the JSON Server by running `json-server --watch mock-api-data.json` to serve the mock API.
5. In a separate terminal, start the Angular development server with `ng serve`.
6. Open your web browser and visit `http://localhost:4200` to view the application.

## Usage

- To add a new student, click on the "+" icon in the bottom right corner of the screen. This will open the "Add Student" form where you can fill in the required details.
- To view a list of all students, navigate to the "Home" page.
- To view details of a specific student, click on their email in the student list.
- To update a student's information, click on the "Update" button next to their details.
- To delete a student, click on the "Delete" button and confirm the action in the modal dialog.
