# Notes App

A notes app front end built with HTML, CSS, JavaScript and Bootstrap. It lists, creates, updates and deletes notes (a title and a description) through a REST API.

## How it works

The app calls a local REST API at http://localhost:3000/tasks:

- GET /tasks - list all notes
- POST /tasks - create a note
- PUT /tasks/:id - update a note
- DELETE /tasks/:id - delete a note

## Run

The API is not part of this repo. Start a local server that exposes a tasks collection with id, title and description fields (for example json-server), then open index.html in a browser.
