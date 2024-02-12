## Step-by-Step Guide to Setup the Project

This guide will walk you through the process of setting up the project on a new device.

1. Install Node.js:
   - If Node.js is not already installed on your device, download and install it from [here](https://nodejs.org/).

2. Clone the Repository
   - Download the zip file from the provided URL.

3. Install Dependencies:
   - Once inside the project directory, install the project dependencies using npm:
     npm install
This command will read the `package.json` file in your project directory and install all the dependencies listed under the `dependencies` and `devDependencies` sections.

4. Start the Development Server:
   - After the dependencies are installed, start the development server using npm:
     npm start

   This command will start the development server. Once the server is running, you can access your application in your web browser at [http://localhost:3000](http://localhost:3000).
   
## Json-server setup

## Installation

1.	Install JSON Server: Install JSON Server globally on your system using npm.
            npm install -g json-server

2.	json file path: The project has a directory structure where there is a src directory, and within that, there's a data directory. Put db.json file at there.

### Starting the JSON Server

1. To start the JSON Server with the `db.json` file:

Navigate to the `data` directory:
cd src/data

        src\data  :  json-server --watch db.json --port 3000

2.	 Start the application:
To start the application, run the following command in your terminal:
npm start

## Screen Recordings
1. Added screen recordings for both user and admin user type for reference purpose under "Screen Recordings" folder.