# NASA Pictures Web App

This is a web application that displays NASA's Picture of the Day using the NASA API.

## Getting Started

To run the application locally, follow these steps:

1. Clone the repository: `git clone <https://github.com/poulsen1114/nasa-apod.git>`
2. Open the `index.html` file in your web browser.

## Features

- Displays NASA's Picture of the Day.
- Allows adding pictures to favorites.
- Allows removing pictures from favorites.

## Dependencies

The following dependencies are used in this project:

- None

## Usage

### HTML

- The `index.html` file contains the HTML structure of the web application.

### CSS

- The `styles.css` file contains the CSS styles for the web application.

### JavaScript

- The `script.js` file contains the JavaScript code for the web application.

### NASA API

- The application uses the NASA API to fetch the pictures of the day.
- The API key used in this project is a demo key (`DEMO_KEY`). Replace it with your own API key to access the API.

## Functionality

The main functionality of the application is implemented through the following JavaScript functions:

- `showContent(page)`: Shows the content based on the selected page.
- `createDOMNodes(page)`: Creates DOM nodes for displaying the results or favorites.
- `updateDOM(page)`: Updates the DOM with the results or favorites.
- `getNasaPictures()`: Fetches the NASA pictures from the API and updates the DOM.
- `saveFavorite(itemUrl)`: Saves a picture to the favorites.
- `removeFavorite(itemUrl)`: Removes a picture from the favorites.

## Contributing

Contributions to this project are welcome. You can contribute by following these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
