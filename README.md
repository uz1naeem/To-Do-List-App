# To-Do List Project - README

## Project Overview
This project is a simple **To-Do List** web application that allows users to manage tasks efficiently. The application includes essential features like adding tasks, deleting tasks, checking off completed tasks, and saving data for future use. The list persists across page reloads using the **localStorage** feature, ensuring that tasks remain even if the browser is closed or refreshed.

## Features
- **Add a Task**: Users can add tasks by typing in the input field and clicking the "Add" button. 
- **Delete a Task**: Users can delete tasks by clicking the "×" button next to each task.
- **Mark/Unmark Task as Completed**: Clicking on a task will mark it as completed by crossing it off, giving a visual indicator. Clicking again will uncheck the task.
- **Persistent Data**: The application saves the current list of tasks using **localStorage**. This means tasks will be saved even if the page is refreshed or the user exits and reopens the browser.
  
## Technical Skills Demonstrated
1. **HTML**: The foundation of the web page structure.
   - Created elements like a header (`<h2>`), a search bar (`<input>`), and a list (`<ul>`).
   - Added an external link to the stylesheet and included JavaScript using the `<script>` tag.

2. **CSS**: Styling the user interface to make it clean, user-friendly, and visually appealing.
   - Used flexbox to align items within the input field and buttons.
   - Implemented gradients for the background and utilized shadows, rounded corners, and hover effects for an enhanced user experience.
   - Applied styling for task list items, including custom icons for unchecked and checked states.

3. **JavaScript**: The logic behind the application’s functionality.
   - **Task Management**: Added functionality to add, delete, and toggle tasks as completed.
   - **DOM Manipulation**: Used methods like `createElement()`, `appendChild()`, and `addEventListener()` to dynamically manipulate the task list in response to user actions.
   - **Event Handling**: Handled click events for adding tasks, marking tasks as completed, and deleting tasks.
   - **Local Storage**: Implemented **localStorage** to save and load the task list so it persists between sessions.
   - **Conditionals**: Prevented adding empty tasks and included user feedback using alerts.

## Purpose of the Project
I chose this project to practice and develop my **JavaScript** skills, particularly with **DOM manipulation** and **event handling**. The project also allowed me to work on **CSS** to ensure the application has a clean and responsive design. Through this project, I was able to reinforce concepts such as **data persistence** with localStorage, improve **user interaction handling**, and create a functional yet visually appealing web application.

## How to Use
1. **Add a task**: Type a task into the input field and click the "Add" button.
2. **Mark/Unmark as completed**: Click on any task to toggle its "checked" state (crossing it off the list).
3. **Delete a task**: Click the "×" next to the task to remove it from the list.
4. **Data Persistence**: The tasks are automatically saved and will be available the next time you open the page.

## Files Included
- `index.html`: The main structure of the To-Do List application.
- `style.css`: Styles the UI, provides the layout, and enhances the visual design.
- `script.js`: Contains the JavaScript functionality, including task management and localStorage integration.

---

Thank you for checking out my To-Do List project!
