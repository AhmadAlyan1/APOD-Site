# APOD Site

## Description

This project is a simple web application that allows users to log in and search for posts related to NASA's Astronomy Picture of the Day (APOD). It uses Express.js for the backend, Bootstrap for styling, and a REST API for handling comments.

## Features

- User login functionality
- Search for posts by date
- Display search results dynamically
- REST API to manage user comments

## Installation

1. Clone the repository:
   ```sh
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```sh
   cd ex5-rest-neviim-ex5_ahmad_alyan-main
   ```
3. Install dependencies:
   ```sh
   npm install
   ```

## Running the Project

1. Start the server:
   ```sh
   npm start
   ```
2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## API Configuration

Before running the project, make sure to set up your API key if required. Update your configuration file or environment variables with your API key to access the required data.

## API Endpoints

### Add a Comment

- **POST** `/api/comments`
- **Body:** `{ "userId": "1", "postId": "100", "comment": "Great post!" }`
- **Response:** Returns all comments.

### Get All Comments

- **GET** `/api/comments`
- **Response:** Returns all stored comments.

### Delete a Comment

- **DELETE** `/api/comments/:id/:post`
- **Response:** Returns updated list of comments after deletion.

## Technologies Used

- Node.js
- Express.js
- Bootstrap 5
- JavaScript

## License

This project is licensed under the MIT License.

## Author

Ahmad Alyan
