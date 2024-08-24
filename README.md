# To-Do List App

## Project Description

The To-Do List App is a simple and interactive application built using React.js and Vite. It allows users to add, remove, and manage tasks efficiently. The app uses local storage to persist tasks across browser sessions and leverages React hooks for state management. Font Awesome icons are used to enhance the user interface.

## Technologies Used

- React.js
- Vite
- Font Awesome (for icons)
- Local Storage (for data persistence)

## Setup and Run Instructions

### Prerequisites

- Node.js (version 14 or later recommended)
- npm (Node Package Manager)

### Setup Instructions

1. **Clone the Project Repository:**
   - Open your terminal or command prompt.
   - Run the following command to clone the repository:
     ```bash
     git clone https://github.com/yourusername/todo-list-app.git
     ```
   - Replace `yourusername` with your GitHub username and `todo-list-app` with the name of your repository.

2. **Navigate to the Project Directory:**
   - Change directory to your project folder:
     ```bash
     cd todo-list-app
     ```

3. **Install Dependencies:**
   - Run the following command to install the project dependencies:
     ```bash
     npm install
     ```

4. **Start the Development Server:**
   - Run the following command to start the Vite development server:
     ```bash
     npm run dev
     ```

5. **Open the Application:**
   - Open your browser and go to `http://localhost:3000` to view the application.

### Running the Project

1. **Locate the Main File:**
   - The main file is `src/main.jsx`, where the React application is initialized.

2. **Start the Application:**
   - Use the Vite development server as described above to view and interact with the app.

## Key Features and Functionalities Implemented

1. **Task Management:**
   - Add new tasks to the list.
   - Mark tasks as complete or incomplete.
   - Remove tasks from the list.


2. **Local Storage Integration:**
   - Tasks are saved to local storage to ensure data persistence across sessions.
   - Load and save tasks using `localStorage`.


3. **React Hooks:**
   - Utilized React hooks (`useState`, `useEffect`) for managing component state and side effects.


4. **UI and Icons:**
   - Font Awesome icons used for task actions (e.g., add, delete).
   - Responsive and user-friendly interface.


5. **Vite for Development:**
   - Fast development environment with Vite for quick builds and hot reloading.


## Components Overview

- **App.js**: Main component where tasks are managed and displayed.
- **TodoInput.js**: Component for inputting new tasks.
- **TodoList.js**: Component for rendering the list of tasks.
- **TodoCard.js**: Component for each individual task, including actions like delete.

## Authors

- [Muhammad Wasif Shakeel](https://github.com/mwasifshkeel)

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Acknowledgements

- [React.js](https://reactjs.org/) - For building the user interface.
- [Vite](https://vitejs.dev/) - For fast development and build tooling.
- [Font Awesome](https://fontawesome.com/) - For the icon library used in the project.
- [MDN Web Docs](https://developer.mozilla.org/en-US/) - For providing comprehensive documentation on web technologies.

