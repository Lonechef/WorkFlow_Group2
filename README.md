# Workflow Management System

This project is a Workflow Management System that allows users to create, view, select, and delete workflows. The front-end is built using React, and the back-end is powered by Spring Boot and MySQL.

## Features

- Create new workflows
- View all existing workflows
- Select a workflow
- Delete a workflow
- Input JSON data and submit it to the backend

## Technologies Used

### Frontend
- React
- Axios for API calls
- React Router for navigation
- CSS for styling

### Backend
- Spring Boot
- MySQL
- JPA for data persistence

## Setup and Installation

### Prerequisites

- Node.js and npm
- Java 11+
- MySQL

### Frontend Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/lonechef/WorkFLow_Group2.git
   cd workflow1
2. Install Dependencies
   npm install
   npm start
   
### API Endpoints

GET /api/workflows/summary: Fetch a summary of all workflows (ID and name).

DELETE /api/workflows/{id}: Delete a workflow by ID.

POST /api/userdata/create: Create new user data from JSON input.

Frontend Components

Page2.jsx: Displays the workflow cards, allows users to delete and select workflows, and submit JSON data.

Navbar.jsx: Navigation bar component.

### Backend Components

WorkflowController.java: REST controller for managing workflows.

WorkflowService.java: Service layer for workflow logic.

WorkflowRepository.java: JPA repository for workflow entities.

UserDataController.java: REST controller for managing user data.

UserDataService.java: Service layer for user data logic.

UserDataRepository.java: JPA repository for user data entities.
  

