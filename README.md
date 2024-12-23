
# Express.js Text Storage API

This project is a simple Node.js application using Express.js to create a text storage API. It provides two endpoints: one to store text and another to retrieve the stored text.

## Features

- **POST /store**: Stores the text sent in the request body.
- **GET /store**: Retrieves the stored text.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   
2. Navigate to the project directory
    cd your-repo-name
3.  Install dependencies:
    npm install

    ## Usage
1. Start the server:
 node app.js
2. The server will run on http://localhost:3000.
3. Use the following API endpoints:
POST /store: Send raw text in the request body to store it.
GET /store: Retrieve the stored text.

## Stored text
curl -X POST http://localhost:3000/store -H "Content-Type: text/plain" -d "Hello, world!"

## Retrieve Text
curl http://localhost:3000/store

## Requirements
Node.js
npm (Node Package Manager)

