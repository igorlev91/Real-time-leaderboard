# Real-Time Leaderboard
![image](https://github.com/user-attachments/assets/ec454cf1-f4fc-477b-97a5-1d9f92061e29)

## Description

The Real-Time Leaderboard project is a backend service designed to manage and display real-time leaderboards for various games. It provides a comprehensive set of features for user authentication, game management, and score tracking. Users can sign up, log in, and submit their scores, which are then used to generate dynamic leaderboards. The service includes robust authentication and authorization mechanisms, ensuring secure access to protected routes. It leverages technologies like TypeScript, NestJS, TypeORM, PostgreSQL, and Redis to deliver high performance and scalability. Additionally.

## Project URL
https://roadmap.sh/projects/realtime-leaderboard-system


## Features

- User authentication and authorization
- User management (create, update, delete, find)
- Game management (create, update, delete, find)
- Score submission and retrieval
- Real-time leaderboard for games
- Protected routes with JWT authentication
- Refresh tokens for session management
- Redis integration for caching
- PostgreSQL database for persistent storage
- TypeORM for object-relational mapping
- User ranking for games
- Top players report for games
- leaderboard for games
- top players report for games within a date range
- top players across all leaderboards

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/igorlev91/Real-time-leaderboard
    ```
2. Navigate to the project directory:
    ```bash
    cd real-time-leaderboard
    ```
3. Setting Up a `.env` File

To configure the environment variables for the project, set up a `.env` file with the following parameters:

```env
DB_HOST=your_database_host
DB_PORT=your_database_port
DB_USERNAME=your_database_username
DB_PASSWORD=your_database_password
DB_DATABASE=your_database_name

JWT_SECRET=your_jwt_secret
ACCESSTOKEN_LIFETIME=access_token_lifetime_in_seconds
REFRESHTOKEN_LIFETIME=refresh_token_lifetime_in_seconds
REFRESH_TOKEN_SECRET=your_refresh_token_secret

REDIS_PASSWORD=your_redis_password
REDIS_HOST=your_redis_host
REDIS_PORT=your_redis_port
```

Make sure to replace the placeholders with your actual credentials and values for the environment variables.
    
3. Install the dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the development server:
    ```bash
    npm run start:dev
    ```
2. The application will be running at `http://localhost:3000`.

## Technology

- **TypeScript**
- **Node.js**
- **NestJS**
- **TypeORM**
- **PostgreSQL**
- **Redis**
- **Passport**
- **JWT**

## API Endpoints
