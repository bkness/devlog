# Devlog

A full-stack blogging platform for developers. Log in, write posts, and comment on the community feed. Sessions expire after one hour of inactivity.

> **About this project:** I built devlog entirely by hand, no AI, during my bootcamp. It's where I learned how a full-stack app fits together: REST routes (GET, POST, PUT, DELETE), MVC structure, sessions, and a relational database with Sequelize. It's archived as a finished learning project, and its free Railway hosting has ended.
>
> The rebuild is **[devlogger](https://github.com/bkness/devlogger)** (Next.js, Prisma, PostgreSQL), live at **[devlogger-bkness.vercel.app](https://devlogger-bkness.vercel.app)**.

## Features

- Create and manage blog posts
- Comment on posts from other developers
- JWT session-based authentication
- Mobile-responsive UI

## Tech Stack

**Client:** Handlebars, Bootstrap  
**Server:** Node.js, Express, Sequelize, MySQL

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/bkness/devlog.git
   cd devlog
   ```

2. Install dependencies:

   ```sh
   npm install
   ```

3. Create a `.env` file:

   ```
   DB_NAME=devlog_db
   DB_USER=root
   DB_PASSWORD=your_password
   SESSION_SECRET=your_secret
   ```

4. Seed the database and start the server:

   ```sh
   npm run seed
   npm start
   ```

## Usage

Visit [http://localhost:3001](http://localhost:3001) in your browser.

## Screenshots

### Login Screen
![Login Screen](https://github.com/bkness/model-view-controller/assets/123907755/7031f918-e83f-4561-b3ff-03ad791e587e)

### Dashboard Screen
![Dashboard Screen](https://github.com/bkness/model-view-controller/assets/123907755/cf4463f5-8ca5-4206-898a-e369b54d3598)

### Blog Post Screen
![Blog Post Screen](https://github.com/bkness/model-view-controller/assets/123907755/70a0efd9-2340-4d2a-9d34-b86ecae23686)

### Comment Section
![Comment Post Screen](https://github.com/bkness/model-view-controller/assets/123907755/21fa0918-7819-4beb-b44c-bdc2c0ec35ce)

### Mobile View
![Mobile View](https://github.com/bkness/model-view-controller/assets/123907755/84baefd4-d4d5-4fe3-99da-8b7134a55032)

## Contact

Brandon Kelly — [GitHub](https://github.com/bkness) · kbrandon863@gmail.com
