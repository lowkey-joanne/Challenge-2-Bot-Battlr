# Bot-Battlr

## Project Overview

**Bot-Battlr** is a React-based web application that allows users to view, interact with, and manage a collection of bots. The application provides functionalities such as viewing bot details, adding bots to an army, and deleting bots from the collection. The project includes routing for different bot views and utilizes React hooks for state management and side effects.

## Features

- **Bot Collection:** View a list of all available bots.
- **Bot Details Page:** View detailed information about a specific bot.
- **Your Bot Army:** Manage and view your selected bots.
- **Bot Management:** Add or remove bots from your collection.

## Technologies Used

- React
- React Router DOM
- Fetch API
- CSS for styling
- React Icons for UI components

## Project Structure

- **`src/`**: Contains the source code for the application.
  - **`components/`**: Contains React components.
    - **`Navbar.js`**: Navigation bar component.
    - **`YourBotArmy.js`**: Displays the user's selected bots.
    - **`Bot.js`**: Represents a single bot in the collection.
    - **`BotCollection.js`**: Displays the list of all bots.
    - **`BotPage.js`**: Detailed view of a specific bot.
    - **`BotSpecs.js`**: Detailed specifications of a bot.
  - **`App.js`**: Main application component that sets up routes and state.
  - **`index.js`**: Entry point for the React application.
  - **`App.css`**: Application-wide styles.

## Installation and Setup

### Prerequisites

- Node.js and npm installed on your machine.

### Steps to Run Locally

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/rlowkey-joanne/bot-battlr.git
   cd bot-battlr
   ```

2. **Install Dependencies:**

   ```bash
   npm install
   ```

3. **Start the Development Server:**

   ```bash
   npm start
   ```

   The application should now be running at `http://localhost:3000`.

## API Endpoint

The application fetches bot data from a local server running on port 8001. Make sure to have the following API endpoint available:

- **GET** `/bots` - Fetches a list of all bots.
- **DELETE** `/bots/:id` - Deletes a bot by ID.

## Usage

- **Home Page:** View and interact with the collection of bots.
- **Bot Page:** Click on a bot to view detailed information and add it to your army.
- **Your Bot Army:** View and manage the bots you have selected.

## Contributing

Feel free to submit issues, feature requests, or pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

