# To-do List Microservices Application

## Overview
The To-do List Microservices Application is a scalable and flexible project that allows users to manage their tasks efficiently. This application uses microservices architecture to enable independent deployment, scaling, and maintenance of individual services.

## Architecture
The architecture consists of multiple microservices, each responsible for specific functionality:

- **Task Service**: Handles the creation, retrieval, updating, and deletion of tasks.
- **Notification Service**: Sends notifications to users about task updates or reminders.

## Features
- Create, edit, delete, and view tasks.
- Receive task notifications.
- Clean and simple user interface.
- Microservices-based architecture for scalability.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/nileshkmahato/To_do_list_microservices_app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd To_do_list_microservices_app
   ```
3. Install dependencies for each microservice as per the instructions in their respective directories.
4. Start the microservices using Docker or your preferred method.

## Project Structure
```
To_do_list_microservices_app/
├── task-service/
├── notification-service/
└── README.md
```

## Technologies Used
- Microservices Architecture
- Docker for containerization
- RESTful APIs

## License
This project is created as an assignment.