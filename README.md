
# Task Manager Spring Boot API
This is a Task Manager API built using Spring Boot.

## Overview
The Task Manager API provides endpoints to manage tasks including creating, updating, deleting, and retrieving tasks. It supports various operations such as marking tasks as done, setting tasks as in-progress, and retrieving tasks by ID.

## Technologies Used
- Spring Boot 3
- Java 21
- PostgreSQL
- Gradle
- Unit Testing: JUnit 5, Mockito
- Docker

## Features
- Create tasks
- Retrieve all tasks
- Retrieve tasks by ID
- Update tasks
- Delete tasks
- Mark status of tasks as to-do, in-progress or done
- Filter tasks by status

## API Endpoints
- `GET /tasks`: Retrieve all tasks.
- `GET /tasks/{id}`: Retrieve a task by ID.
- `POST /tasks`: Create a new task.
- `PUT /tasks/{id}`: Update an existing task.
- `DELETE /tasks/{id}`: Delete a task by ID.
- `PUT /tasks/{id}/DONE`: Mark a task status as to-do.
- `PUT /tasks/{id}/IN_PROGRESS`: Set a task status as in-progress.
- `PUT /tasks/{id}/DONE`: Mark a task status as done.
- `GET /tasks/filter/{status}`: Filter by status.

## Requirements
- Java Development Kit 21
- Docker

## Setup
1. Clone the repository
    ```
   git clone https://github.com/san-rai/task-manager-api.git
   ```
2. Start the application
    ```
    docker-compose up -d
    ```
3. Stop the application
    ```
    docker-compose down
    ```
