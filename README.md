# Monsters Rolodex

## Project Overview

Monsters Rolodex is a simple React application that displays a searchable list of monsters. Users can filter the monsters by name using a search box.

## Live Demo

Check out the live demo of the project here: [Monsters Rolodex on Netlify](https://your-monsters-rolodex.netlify.app)

## Features

- Fetches monster data from an external API
- Displays a list of monsters with their names
- Provides a search functionality to filter monsters by name
- Responsive design for various screen sizes

## Technologies Used

- React
- JavaScript (ES6+)
- CSS
- Fetch API for data retrieval

## Component Structure

1. **App**: The main component that manages the state and renders child components.
2. **SearchBox**: A reusable component for the search input field.
3. **CardList**: A component that renders the list of monster cards.

## How It Works

1. On component mount, the application fetches monster data from 'https://jsonplaceholder.typicode.com/users'.
2. The fetched data is stored in the component's state.
3. Users can type in the search box to filter the monsters.
4. The list of monsters updates in real-time as the user types.

## Setup and Installation

1. Clone the repository
2. Run `npm install` to install dependencies
3. Run `npm start` to start the development server
4. Open `http://localhost:3000` in your browser

## Deployment

This project is deployed on Netlify. You can view it live at the link provided in the "Live Demo" section above.

## Future Improvements

- Add more details for each monster
- Implement pagination for a larger dataset
- Add sorting functionality
- Enhance the UI with animations

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check issues page if you want to contribute.

## License

[MIT](huntershola007@gmail.com)