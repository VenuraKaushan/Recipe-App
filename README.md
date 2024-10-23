# Recipe Web Application

This project is a Recipe web application built using ReactJS for the frontend and NodeJS for the backend. The application allows users to log in/register, explore recipes, save their favorites, and view detailed information about each recipe.

## Features

- User registration and login functionality.
- Browse and filter recipes by categories.
- View a list of favorite recipes and remove them if desired.
- Modal display for detailed recipe information.
- Secure user sessions with JWT.

## Technologies Used

- **Frontend**: ReactJS, Next.js
- **Backend**: NodeJS, Express
- **Database**: MongoDB or PostgreSQL
- **Other**: Axios (for API calls), OAuth (Google authentication)

## Prerequisites

Before running the project, ensure you have the following installed on your machine:

- Node.js (version 14.x or higher)
- npm or yarn

## Getting Started

### For the Backend
1. Navigate to the backend directory and install the required dependencies:
    ```bash
    cd backend
    npm install
    npm start
    ```

### For the Frontend
1. Navigate to the frontend directory and install the required dependencies:
    ```bash
    cd frontend
    npm install
    npm run dev
    ```

## Usage
- Use the registration page to create a new account or log in to an existing account.
- Browse the recipe categories and select a category to view available recipes.
- Click on a recipe to view its details and save it to your favorites.
- Access your favorite recipes from the dedicated page.

## Project Structure
- **backend**: Contains the Express server code and API routes for user and recipe management.
- **frontend**: Contains the ReactJS code for the user interface, including login, registration, and recipe displays.
