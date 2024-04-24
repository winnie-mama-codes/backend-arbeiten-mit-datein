# Working with data

The purpose of this exercise is to practice basic file I/O and Express endpoints.

## What you will be doing

Your task is to create a simple server for noting down and listing animal sightings.

## Tasks

### Task 1

- Add the `express` dependency
- Create `.gitignore` and make sure node_modules is not included in git
- Create `server.js` and add a simple Express server without endpoints listening on port 7771

### Task 2

- Add a GET endpoint for retrieving the contents of `sightings.txt`
    - `GET http://localhost:7771/`
    - read all the text and respond with it

### Task 3

- Add a POST endpoint that receives "species" from the request
    - `POST http://localhost:7771/`
    - In the body of the POST request, receive an animal species
    - Add the todays date and the received species into `sightings.txt`

- *Hint:* you can use `new Date()` to get a date object of the current date
    - Formatting dates can be complex, maybe ask Copilot or ChatGPT?
    - Or, of course, research on MDN

