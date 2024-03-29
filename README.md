# Simple Task Manager with Node.js and EJS

A simple task manager application built with Node.js and EJS (Embedded JavaScript templates). This task manager allows users to create, edit, view, and delete tasks

## Features
1. Task Creation: Easily add new tasks with a title and description.
2. Task Listing: View a list of all tasks with their details.
3. Task Deletion: Remove completed or unnecessary tasks.
4. Task Editing: Modify existing tasks to update titles or descriptions.


### Prerequisites
Before running the application, make sure you have the following installed:

- Node.js
- npm
- MongoDB (and have it running)

### Installation

1. Clone the repository
```bash
git clone https://github.com/amirhosseinforouhar/full-stack-task-manager.git
```
2. Navigate to the project directory:
```bash
cd full-stack-task-manager
```

3. Install dependencies
```bash
npm install

```

### Usage
1. Create a `.env` file in the root directory and set the following environment variables

```dotenv
PORT=5000
MONGO_CONNECTION_URI=yourConnectionURI

```
2. Start the application
```bash
npm start

```
3. Open your web browser and visit http://localhost:5000.
4. You will be able to create, view, edit, and delete tasks.


### Screenshots
![Sample Image](public/images/sample-1.png)
![Sample Image](public/images/sample-2.png)
![Sample Image](public/images/sample-3.png)