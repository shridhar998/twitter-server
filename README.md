
# Twitter Clone Project 🐦



Twitter clone project built with Node.js, Express.js, TypeScript, GraphQL, PostgreSQL, Supabase, Prisma ORM, and Redis for caching. Deployed on an AWS EC2 instance. 🚀

## Table of Contents

- [About](#about)
- [Features](#features)
- [Demo](#demo)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## About 📜

This Twitter clone project is a full-stack application that replicates the core features of Twitter, allowing users to post tweets, follow other users, like tweets, and engage in conversations. It's built with modern web technologies and designed to be scalable and maintainable.

## Features 🌟

- **User Authentication**: Users can sign up, log in, and reset their passwords.
- **Profile Management**: Users can update their profile information and profile pictures.
- **Tweeting**: Users can create, edit, and delete tweets.
- **Following**: Users can follow/unfollow other users.
- **Feeds**: Users can see tweets from users they follow.
- **Likes and Retweets**: Users can like and retweet tweets.
- **Notifications**: Users receive notifications for new followers, likes, and mentions.
- **Direct Messages**: Users can send private messages to each other.
- **Search**: Users can search for other users and tweets.

## Demo 📺

[Insert Demo Link Here]



## Getting Started 🚀

Follow these instructions to get the project up and running on your local machine.

### Prerequisites 📋

- Node.js
- PostgreSQL
- Supabase Account
- Redis
- AWS Account (for deployment)

### Installation 🛠️

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/twitter-clone.git
   cd twitter-clone
   ```

2. Install dependencies:

   ```shell
   npm install
   ```

3. Create a PostgreSQL database and set up Supabase for user authentication.

4. Set up environment variables by creating a `.env` file and filling in the necessary information:

   ```env
   DATABASE_URL=postgres://username:password@localhost:5432/your-database
   SUPABASE_URL=your-supabase-url
   SUPABASE_KEY=your-supabase-key
   REDIS_HOST=127.0.0.1
   REDIS_PORT=6379
   REDIS_PASSWORD=your-redis-password
   # Add any other environment variables here
   ```

5. Run database migrations:

   ```shell
   npm run prisma:apply
   ```

6. Start the server:

   ```shell
   npm start
   ```

7. Open your browser and navigate to `http://localhost:3000` to access the application.

## Usage 🚀

1. Sign up or log in to the application.
2. Create tweets, follow users, and engage with other users' content.
3. Explore the various features of the Twitter clone! 🥳

## Technologies Used 💻

- Node.js
- Express.js
- TypeScript
- GraphQL
- PostgreSQL
- Supabase
- AWS
- Redis
- Prisma

