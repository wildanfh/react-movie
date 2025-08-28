# Movie Search App

This project is a React-based web application that allows users to
search for movies using The Movie Database (TMDb) API. It also fetches
trending movies and keeps track of search counts using Appwrite backend
services.

## Features

-   Search for movies using TMDb API
-   Debounced search input for better performance
-   Display trending movies fetched from Appwrite backend
-   Track and update search count via Appwrite
-   Loading spinner and error handling
-   Responsive UI with reusable components (Search, Spinner, MovieCard)

## Installation

1.  Clone this repository.

2.  Install dependencies using `npm install`.

3.  Create a `.env` file in the root directory and add your TMDb API
    key:

    ``` bash
    VITE_TMDB_API_KEY=your_api_key_here
    ```

4.  Run the development server:

    ``` bash
    npm run dev
    ```

## File Structure

    - App.jsx -> Main application component
    - components/
      - Search.jsx -> Search input component
      - Spinner.jsx -> Loading spinner
      - MovieCard.jsx -> Movie display card
    - hooks/
      - useDebounceValue.js -> Custom debounce hook
    - appwrite.js -> Appwrite backend service functions

## Usage

-   Open the app in your browser.
-   Use the search bar to find movies.
-   View trending movies from Appwrite.
-   Check the movie list with posters and details.

## License

This project is open source and available under the MIT License.
