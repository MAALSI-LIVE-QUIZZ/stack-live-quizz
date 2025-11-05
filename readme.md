# Live quizz

## Description

This project is the main project to build the whole live quizz application.
It embeds all the build system to make the application work.

```
.
├── api-quizz
├── api-results
├── react-live-quizz
└── **stack-live-quizz**
```

It's at the same level as the 3 other projects:

- api-quizz: the backend API to manage quizz and players
- api-results: the backend API to manage results and statistics
- react-live-quizz: the frontend application to play the quizz

## How to run

To run the whole application, you need to have Docker and Docker Compose installed on your machine.

Then, you can run the following command in the root of this project:

```bash
docker compose up --build
```

## Technical stack

![Technical Stack](./specs/stack.png)

## User stories

![User Stories](./specs/user_stories.png)
