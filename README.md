# My To-Do List Web Application

## Description
This is a simple, interactive To-Do List web application built using HTML, CSS, and JavaScript. The application allows users to add, complete, and delete tasks, helping them to keep track of their daily activities.

### Prevew/Live Site
https://biswa-source45.github.io/To-Do-List/
## Components

### 1. HTML (`index.html`)
- **Structure**: The `index.html` file forms the basic structure of the web page. It includes the following key sections:
  - **Header**: Contains the title "My To-Do List" and a brief description of the application.
  - **Main Content**:
    - **Task Input Section**: An input field (`<input>`) where users can enter new tasks, and an "Add Task" button (`<button>`) to submit the task.
    - **Task List Section**: An unordered list (`<ul>`) where all the added tasks are displayed.
  - **Footer**: Displays information about the author and technologies used.

- **Linking Styles and Scripts**: The HTML file links to an external CSS file for styling (`style.css`) and a JavaScript file for functionality (`script.js`).

### 2. CSS (`style.css`)
- **Styling**: The `style.css` file is responsible for the visual presentation of the application.
  - **Body**: Sets the font, margin, padding, and background color, and ensures that the content is vertically centered.
  - **Header and Footer**: Styled with a dark background and white text to stand out against the main content.
  - **Task Input Section**: The input field and button are centered and styled with padding, borders, and rounded corners to enhance usability.
  - **Task List**: Each task is displayed in a styled list item with a subtle shadow, making the tasks visually distinct. Completed tasks are shown with a strikethrough and a lighter color.
  - **Buttons**: The "Add Task" and "Delete" buttons are styled with distinct colors and rounded edges to make them easily clickable.

### 3. JavaScript (`script.js`)
- **Functionality**: The `script.js` file adds interactivity to the To-Do List.
  - **Adding Tasks**: Captures the input from the task input field and appends it as a new list item in the task list. It also handles validation to ensure the task input is not empty before adding.
  - **Toggling Task Completion**: Allows users to mark tasks as completed by clicking on a checkbox. Completed tasks are visually updated with a strikethrough.
  - **Deleting Tasks**: Enables users to remove tasks from the list using a "Delete" button next to each task.

## Usage
To use this To-Do List application:
1. Open the `index.html` file in your web browser.
2. Enter a task in the input field and click "Add Task" to add it to your list.
3. Click the checkbox next to a task to mark it as completed.
4. Click the "Delete" button to remove a task from the list.

## Author
Biswabhusan Sahoo  
pesuing: BCA
IG-https: //www.instagram.com/ll.b_i_s_w_a.ll?igsh=MW9yY2NqaWh2am9kNA==
Linkedin: https://www.linkedin.com/in/biswabhusan-sahoo-22b704292/?trk=opento_sprofile_topcard
## License
This project is open source and available under the [MIT License](LICENSE).
