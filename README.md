# MovieRec

MovieRec is a web application that helps you find movies you'll enjoy. It allows users to search for movies, view trending movies, and get detailed information about each movie.

## Features

- **Search Movies**: Search for movies by title.
- **Trending Movies**: View a list of trending movies.
- **Movie Details**: Get detailed information about each movie including title, rating, language, and release year.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **Tailwind CSS**: A utility-first CSS framework for styling.
- **Appwrite**: A backend server for managing databases and authentication.
- **Vite**: A build tool for frontend projects.

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/movierec.git
    cd movierec
    ```

2. Install dependencies:
    ```sh
    npm install
    # or
    yarn install
    ```

3. Create a `.env` file in the root directory and add your API keys:
    ```env
    VITE_API_KEY=your_tmdb_api_key
    VITE_APPWRITE_PROJECT_ID=your_appwrite_project_id
    VITE_APPWRITE_DB_ID=your_appwrite_db_id
    VITE_APPWRITE_COLLECTION_ID=your_appwrite_collection_id
    ```

### Running the Application

1. Start the development server:
    ```sh
    npm run dev
    # or
    yarn dev
    ```

2. Open your browser and navigate to `http://localhost:3000`.

### Building for Production

To build the application for production, run:
```sh
npm run build
# or
yarn build
```

### Linting

To lint the code, run:
```sh
npm run lint
# or
yarn lint
```

## Project Structure

- `src/`: Contains the source code.
  - `components/`: React components.
  - `App.jsx`: Main application component.
  - `appwrite.js`: Appwrite configuration and functions.
  - `index.css`: Global styles.
  - `main.jsx`: Entry point of the application.
- `public/`: Static assets.
- `vite.config.js`: Vite configuration file.
- `eslint.config.js`: ESLint configuration file.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [The Movie Database (TMDb)](https://www.themoviedb.org/) for providing movie data.
- [Appwrite](https://appwrite.io/) for backend services.
