# Entertainment_Hub

# IMDb-Inspired Full Stack Application

Welcome to the IMDb-inspired full stack application! This project is developed using the MERN (MongoDB, Express.js, React, Node.js) stack, and it provides users with a platform to search for movies and TV series, register and log in, add movies to their favorites list, leave reviews on their favorite movies, update their password, and view the latest popular movies.


## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Search Movies/TV Series:** Users can search for their favorite movies and TV series using the application. The app utilizes the TMDB API for fetching movie and TV series data.

- **User Registration and Login:** Users can register and log in to the application using their credentials. JWT (JSON Web Tokens) are used for secure authentication.

- **Home Page with Latest Popular Movies:** The home page displays the latest popular movies, allowing users to stay updated with trending content.

- **Favorite List:** Registered users can add movies and TV series to their favorites list. This feature allows users to keep track of their favorite content easily.

- **Leave Reviews:** Users can leave reviews and ratings for movies they've watched. Share your opinions and recommendations with other users.

- **Update Password:** Users can update their passwords for added security.

- **Delete Reviews:** Users have the ability to delete reviews they've previously left on movies.

- **Responsive Web Design:** The application is designed to work seamlessly on various devices, including desktops, tablets, and mobile phones.

## Getting Started

To get the IMDb-inspired full stack application up and running on your local machine, follow the steps below.

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js: Download and install Node.js from [nodejs.org](https://nodejs.org/).

- MongoDB: Install MongoDB and make sure it's running locally or provide connection details for a remote MongoDB instance.

### Installation

1. Clone this GitHub repository:

   ```bash
   git clone https://github.com/your-username/imdb-inspired-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd imdb-inspired-app
   ```

3. Install server dependencies:

   ```bash
   cd server
   npm install
   ```

4. Install client dependencies:

   ```bash
   cd ../client
   npm install
   ```

5. Create a `.env` file in the `server` directory and configure it with the following:

   ```env
   PORT=5000
   MONGODB_URI=your_mongodb_uri
   JWT_SECRET=your_jwt_secret
   TMDB_API_KEY=your_tmdb_api_key
   ```

   - `PORT`: Port on which the server will run.
   - `MONGODB_URI`: MongoDB connection URI.
   - `JWT_SECRET`: A secret key for JWT token generation.
   - `TMDB_API_KEY`: Your TMDB API key. You can obtain it by signing up at [themoviedb.org](https://www.themoviedb.org/).

6. Return to the `server` directory:

   ```bash
   cd ../server
   ```

7. Start the server:

   ```bash
   npm start
   ```

8. Open a new terminal, navigate to the `client` directory, and start the client:

   ```bash
   cd ../client
   npm start
   ```

Now, you should be able to access the IMDb-inspired application in your web browser at `http://localhost:3000`.

## Usage

1. **Registration/Login:** Create a user account by registering or log in with existing credentials.

2. **Home Page:** The home page displays the latest popular movies, keeping you updated with trending content.

3. **Search Movies/TV Series:** Use the search bar to find your favorite movies and TV series.

4. **Add to Favorites:** When logged in, you can add movies and TV series to your favorites list.

5. **Leave Reviews:** Share your thoughts by leaving reviews and ratings on movies you've watched.

6. **Update Password:** Maintain account security by updating your password.

7. **Delete Reviews:** Remove reviews you've previously left on movies.

## Technologies Used

- **Frontend:**
  - React.js
  - Axios
  - React Router
  - Material-UI

- **Backend:**
  - Node.js
  - Express.js
  - MongoDB
  - JWT for authentication
  - Axios for making API requests

- **External APIs:**
  - [TMDB API](https://www.themoviedb.org/documentation/api)
Enjoy exploring and using the IMDb-inspired full stack application! If you have any questions or encounter any issues, please feel free to open an issue or contact us. Happy movie watching and reviewing! 🍿🎬📺
