# MovieLand

MovieLand is a React web application that allows users to search for movies using the OMDb API and displays the search results. Users can enter a movie title in the search bar and click the search icon to retrieve a list of movies matching the search query. The application displays movie cards for each search result, showing the movie title, release year, poster image, and type.

![MovieLand Preview](./screenshot.png)

## Features

- Search for movies: Enter a movie title in the search bar and click the search icon to retrieve movies matching the search query.
- Display movie cards: Movie cards are displayed for each search result, showing the movie title, release year, poster image, and type.
- Handling no search results: If no movies are found for the search query, a message is displayed indicating that no movies were found.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/MovieLand.git
```

2. Navigate to the project directory:

```bash
cd MovieLand
```

3. Install the dependencies:

```bash
npm install
```

4. Obtain an API key from [OMDb API](http://www.omdbapi.com/) by signing up for a free account.

5. Replace the placeholder API key in `App.js` with your own API key:

```javascript
const API_URL = "http://www.omdbapi.com/?i=tt3896198&apikey=YOUR_API_KEY";
```

6. Start the development server:

```bash
npm start
```

7. Open your web browser and visit [http://localhost:3000](http://localhost:3000) to see MovieLand in action.

## Usage

- Upon opening the application, the page will display movie cards for the default search query, "Uncharted".
- Enter a movie title in the search bar and click the search icon to retrieve movies matching the search query.
- Movie cards will be displayed for each search result, showing the movie title, release year, poster image, and type.
- If no movies are found for the search query, a message will be displayed indicating that no movies were found.

## Live preview




## Contributing

Contributions are welcome! If you have any suggestions, bug reports, or feature requests, please open an issue on the [GitHub repository](https://github.com/your-username/MovieLand/issues).

## Acknowledgements

- The [OMDb API](http://www.omdbapi.com/) for providing movie data.
- [React](https://reactjs.org/) for the JavaScript library used to build the application.
- [Create React App](https://create-react-app.dev/) for bootstrapping the project structure.
- [Bootstrap](https://getbootstrap.com/) for the responsive CSS framework used in the UI.

---

