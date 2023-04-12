
# ToDo List Web App

This is a simple TodoList Web App built using Node.js, Express.js, EJS, Mongoose, and MongoDB. It allows users to create multiple lists, add and remove items from those lists.



## Deployment

To deploy this project run

1. Clone the repository:

```bash
  git clone https://github.com/JustVibhor/TodoList.git
```

2. Install dependencies:
```bash
  npm install
```

3. Create a .env file in the root directory of the project with the following variables:
```bash
  MONGODB_URI=your-mongodb-uri
  SESSION_SECRET=your-session-secret
```

4. Start server
```bash
  npm app.js
```
The app should be running on http://localhost:3000.
## Usage

1. Start the server by running node app.js or npm start in the terminal.

2. Open the browser and go to http://localhost:3000/ to access the app.

3. To create a new list, add the list name at the end of the URL, like http://localhost:3000/<list-name>.

4. Add a new task by clicking the "+" button and filling out the form.

5. View your tasks on the homepage.

6. Mark a task as complete by clicking the checkbox next to it.

7. Delete a task by clicking the "Checkbox" button next to it.




## Contributing

Feel free to contribute to this project. You can create pull requests or report bugs by opening an issue.

