# UWC2.0-TheFinalists
A repository for the UWC 2.0 project
## How to run the code

Once BE and FE folder are pulled to your machine, you should activate two concurrent terminals. One runs in the BE directory and the other runs in the fe directory.

### BE directory

#### `npm install`
This allows you to install the necessary dependencies for the server to run
### `node server.js`
This will execute the server.js and you can access that via `http://localhost:8000`.

### FE directory
Similarly, you can run the following commands to run a client-side web app.
#### `npm install`
This allows you to install the necessary dependencies for the server to run
#### `npm start`
This will execute the index.js and you can access the project via `http://localhost:3000`.

## In case there's something run on the two ports, you can run:

#### `lsof -i tcp:3000` or `lsof -i tcp:8000`

This will returns a list of process runs on port 3000 (Assume that you use Linux)

#### `kill -9 PID`

This will end the process with the PID you can obtain from the previos commands. Now you can try the methods above to run the project.

Thank you.

If you have any problems, feel free to contact any member of the team to get your problem resolved.



