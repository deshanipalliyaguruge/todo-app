# Todo Application

A simple Todo application built with Spring Boot, Thymeleaf, and MySQL. It allows users to add, complete, delete, and view tasks.

!![Interface.png](src/main/resources/static/images/Screenshot-2025-02-12-115034.png)


## Features

- Add a task
- Mark a task as completed
- Delete a task
- View the list of tasks

## Prerequisites

Before running the project, ensure you have the following installed:

- Java 17 or later
- MySQL Server
- Maven

## Setup and Installation

### 1. Clone or Download the Repository

```sh
https://github.com/your-repo/todo-app.git
cd todo-app
```

Alternatively, you can download the ZIP file and extract it.

### 2. Configure MySQL Database

By default, the application is set up to create the database automatically if it does not exist. If you prefer, you can change the database name to any other name that does not already exist on your local machine.

Update `src/main/resources/application.properties` with your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/todo-app?createDatabaseIfNotExist=true
spring.datasource.username=your_mysql_username
spring.datasource.password=your_mysql_password
```

### 3. Build and Run the Application

Use Maven to build and start the application:

```sh
mvn spring-boot:run
```

### 4. Access the Application

Once the application is running, open your browser and go to:

```
http://localhost:8080/tasks
```

## Usage

- Enter a task title and click **Add** to create a new task.
- Click **Toggle** to mark a task as completed or incomplete.
- Click **Delete** to remove a task.

## Technologies Used

- Spring Boot
- Thymeleaf
- MySQL
- Hibernate
- Bootstrap (for styling)



