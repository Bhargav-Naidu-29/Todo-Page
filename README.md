# Todo Application

## Project Description
This project is a simple **Todo List Application** built using HTML, CSS, and JavaScript. It allows users to dynamically add, delete, and manage tasks on a web page. The tasks are persistently stored in the browser's local storage, ensuring that even after the page is refreshed or the browser is closed, the tasks remain available. This project demonstrates basic DOM manipulation, event handling, and local storage usage in JavaScript.

## Features

1. **Add New Tasks**:
   - Users can input a task description and click the "Add" button to add the task to the list.

2. **Mark Tasks as Completed**:
   - Users can mark tasks as completed by checking the checkbox next to each task. Completed tasks are visually indicated with a strikethrough effect.

3. **Delete Tasks**:
   - Users can delete tasks using the trash icon next to each task.

4. **Persistent Storage**:
   - Tasks are saved in the browser's local storage, ensuring that the list is preserved across page reloads.

5. **Dynamic Task Management**:
   - Tasks are dynamically rendered in the DOM, making the interface interactive and responsive.

## Technologies Used

- **HTML**: To structure the web page.
- **CSS**: For styling and layout.
- **JavaScript**: To handle user interactions and dynamic updates.
- **Bootstrap**: For responsive design and styling consistency.
- **Font Awesome**: For using icons (trash icon for delete functionality).

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Bhargav-Naidu-29/Todo-Page.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Todo-Page
   ```

3. Open the `index.html` file in a web browser.

## How It Works

1. **Adding a Task**:
   - Enter a task description in the input field.
   - Click the "Add" button.
   - The task is appended to the list and saved in local storage.

2. **Marking as Completed**:
   - Check the checkbox next to a task.
   - The task gets a strikethrough style indicating completion.
   - The `isChecked` property in the local storage is updated.

3. **Deleting a Task**:
   - Click the trash icon next to a task.
   - The task is removed from the DOM and the local storage.

4. **Saving Tasks**:
   - Tasks are automatically saved to local storage. Clicking the "Save" button ensures manual save to local storage.

## Folder Structure

```
.
├── README.md          # Project description and instructions
├── index.html         # Main HTML file
├── todoCss.css        # Custom CSS file for styling
└── todoJs.js          # JavaScript file for functionality

```

## Demo
Click on the link for the demo of the project https://bhargav-naidu-29.github.io/Todo-Page/

