## Beyond Beyonder
xxxx

## Features


## Getting Started
Follow the steps below to set up and run Task Tracker on your local machine.

## Prerequisites
Before you begin, ensure you have the following dependencies installed on your system:

- [Node](https://nodejs.org/en "Node") | JavaScript runtime environment.
- [Npm](https://www.npmjs.com/ "Npm") | Node Package Manager.
- [NestJS](https://docs.nestjs.com/cli/overview "NestJS") | To generate and manage your NestJS application.

## Installation
Clone the repository to your local machine

1. Clone the repository to your local machine:
```sh
git clone https://github.com/CyrilBaah/beyondborders.git

```
2. Install the project dependencies:
```sh
npm install
```

## Running the Application
Start the Task Tracker application using the following command:
```sh
npm run start
```
The application will run on http://localhost:3000.

## Lint the Application
```sh
npm run lint
```

## Format the Application
```sh
npm run format
```

## Usage
1.To create a new task, send a POST request to http://localhost:3000/tasks with a JSON body containing the task title.

Example using cURL:
```sh
curl -X POST -H "Content-Type: application/json" -d '{"title": "Task 1"}' http://localhost:3000/tasks
```


```

## Using Docker
Refer to the Makefile to already prepare commands | [Makefile](https://github.com/CyrilBaah/beyondborders.git)