
# Todo App with React.js

This project is a simple Todo application built using React.js. The primary purpose of this project was to deepen my understanding of React, specifically in creating custom hooks and utilizing the `useContext` hook for state management.

## Features

- **Add Todos**: Users can add new tasks to the list.
- **Edit Todos:** Users can edit the content of an existing task. 
- **Delete Todos:** Users can remove tasks from the list once they're done.
- **Marking Todos as Complete:** Click on the checkbox next to a task to mark it as completed.
## Learning Objectives

### 1. Custom Hooks
In this project, I learned how to create and use custom hooks in React. Custom hooks allow you to extract and reuse logic across different components, making your code more modular and easier to maintain.

### 2. useContext Hook
The `useContext` hook was utilized to manage the state globally across the app. This eliminated the need for prop drilling and made it easier to share state between components that aren't directly related.

### 3. Local Storage
I also learned how to use the browser's local storage to persist data across sessions. This allows the todos to be saved and retrieved even after the user closes or refreshes the browser.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/todo-app.git
   ```

2. Navigate to the project directory:
   ```bash
   cd todo-app
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

The app should now be running on `http://localhost:5173/`.

## Usage

- **Adding Todos:** Type a task into the input field and press Enter or click the "Add" button.
- **Deleting Todos:** Click the "Delete" button next to a task to remove it.
- **Marking Todos as Complete:** Click on the checkbox next to a task to mark it as completed.
- **Filtering Todos:** Use the filter buttons to switch between viewing all tasks, only completed tasks, or only active tasks.

## Project Structure

- **/src**
  - **/components**: Contains the React components used in the app.
  - **/context**: Contains the context and provider used for managing the global state.
  - **App.js**: The main component that renders the application.


## Contributing

If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## License

This project is open-source and available under the [MIT License](LICENSE).

---

Feel free to modify any section as needed for your specific project!

