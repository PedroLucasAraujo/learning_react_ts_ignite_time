# Ignite Time

This project was developed during a course I took to deepen my knowledge of **React Hooks**. It showcases advanced techniques such as `useReducer`, `useContext`, and state immutability with Immer, providing a practical application of these concepts in a Pomodoro Timer tool.

![ignite_timer_cover](https://github.com/user-attachments/assets/b1978f73-3878-444d-a474-1f7fc1a8cb1e)


## Features

- **Time Tracking**: Track the time remaining for each Pomodoro cycle with real-time updates on the screen.
- **Cycle Management**: Start, interrupt, and complete Pomodoro cycles.
- **History Tracking**: View all completed cycles with details about start/end times and interruptions. The data is persisted in the `localStorage`.
- **Customizable**: Set custom durations for work and break intervals.
- **Responsive UI**: Built with modern UI principles using **Styled-components**, ensuring a clean and responsive design across all devices.

## Tech Stack

This project was built with a range of modern web technologies:

- **React**: A JavaScript library for building user interfaces, particularly single-page applications.
- **Styled-components**: CSS-in-JS library used to style the components with dynamic styling based on props.
- **React Hook Form**: Utilized for handling form inputs and validations, improving the overall user experience with forms.
- **Zod**: Schema declaration and validation library integrated with React Hook Form for seamless validation.
- **React Router DOM**: Implements dynamic routing in the app, allowing users to navigate between different pages effortlessly.
- **Context API & useReducer**: For state management across the application, allowing centralized control of the Pomodoro timer logic.
- **Immer**: Helps manage immutability within the state management, making state updates predictable and easy to follow.

## How It Works

1. **Start a Cycle**: Enter the task and start the Pomodoro timer for a set period.
2. **Manage Cycles**: You can pause, interrupt, or complete a cycle. The timer will reflect the changes in real-time.
3. **View History**: Once a cycle is completed or interrupted, it is stored in the application history and can be viewed at any time.

## Screenshots

_You can include some screenshots here to demonstrate the app's functionality._

## Running the Project Locally

Follow these steps to run the application on your local machine:

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/pomodoro-app.git

2. Navigate to the project directory:

   ```bash
   cd pomodoro-app

3. Install the dependencies::

   ```bash
   npm install // yarn install
   
4. Running the Application:

   ```bash
   npm run dev // yarn dev
   
---

### License

This project is licensed under the MIT License - see the LICENSE file for details.

---



