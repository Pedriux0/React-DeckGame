Deck Game
A simple React-based card game application that allows users to interact with a deck of cards. Users can deal cards, reset the deck, toss cards, regroup cards, and add wildcards.

Features
Deal Cards: Deal 1, 5, or 7 cards from the deck.

Reset Deck: Reset the deck to its original state.

Toss Card: Remove a selected card from the list.

Regroup Cards: Shuffle the currently selected cards.

Wildcard: Add a randomly generated card to the list.

Interactive Cards: Click on cards to select, swap, or toss them.

Technologies Used
React: A JavaScript library for building user interfaces.

Babel Standalone: Used for in-browser JSX transformation.

CSS: For styling the application.

Getting Started
Follow these steps to set up and run the project locally.

Prerequisites
Node.js: Ensure you have Node.js installed. You can download it from nodejs.org.

Git: Ensure you have Git installed. You can download it from git-scm.com.

Installation
Clone the Repository:

bash
Copy
git clone https://github.com/your-username/deck-game.git
cd deck-game
Install Dependencies:

This project uses Babel Standalone and React directly in the browser, so no additional dependencies are required.

Run a Local HTTP Server:

To avoid CORS issues, use a local HTTP server to serve the files.

If you have Node.js installed, you can use http-server:

bash
Copy
npx http-server
Alternatively, use the Live Server extension in VS Code or Python's built-in HTTP server.

Open the Application:

Open your browser and navigate to the provided URL (e.g., http://127.0.0.1:8080).

Folder Structure
Copy
deck-game/
├── index.html          # Main HTML file
├── App.jsx             # Main React component
├── App.css             # Styles for the application
├── components/         # React components
│   ├── Card.jsx        # Card component
│   └── Controls.jsx    # Controls component
How to Use
Deal Cards:

Click on the deck to deal 1 card.

Use the "Deal 5" or "Deal 7" buttons to deal multiple cards.

Reset the Deck:

Click the "Reset" button to return all cards to the deck.

Toss a Card:

Click on a card to select it, then click the "Toss" button to remove it.

Regroup Cards:

Click the "Regroup" button to shuffle the currently selected cards.

Add a Wildcard:

Click the "Wildcard" button to add a randomly generated card to the list.

Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.

Create a new branch (git checkout -b feature/YourFeatureName).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature/YourFeatureName).

Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
React: For providing a powerful library for building user interfaces.

Babel: For enabling in-browser JSX transformation.

Fisher-Yates Shuffle Algorithm: For shuffling the deck of cards.
