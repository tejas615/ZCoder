# ZCoder Platform

An interactive platform for developers to build and manage coding profiles, save/share coding problems, follow contest calendars, and engage with a community feed.

## Features

- **User Profiles**: Store personal info such as tech stack and competitive ratings.
- **Problem Management**: Save, update, and share coding problems; choose between public or private visibility.
- **Discussion**: Comment on public problems within the community.
- **Contest Tracker**: View upcoming programming contests and integrate them into a personal calendar.
- **Community Feed**: Follow popular public problems across the community.

## Tech Stack

- **Frontend**: React.js  
- **Backend**: Node.js + Express.js  
- **Database**: MongoDB  
- **Styling**: CSS  

*(MERN stack — Mongo, Express, React, Node)*

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)  
- npm (Node Package Manager)

### Installation

1. **Clone the repo**
    ```bash
    git clone https://github.com/tejas615/ZCoder.git
    cd ZCoder
    ```

2. **Install dependencies**
    ```bash
    npm install          # installs root dependencies
    cd server && npm install
    cd ../client && npm install
    cd ..
    ```

3. **Configure environment variables**

    Create a `.env` file inside `/server`:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    PORT=5000  # or your preferred port
    ```

4. **Run the application**

    Open two terminal sessions:

    **Backend:**
    ```bash
    cd server
    npm start        # or node server.js
    ```

    **Frontend:**
    ```bash
    cd client
    npm start
    ```

    The backend runs on `http://localhost:5000` by default, and the React app runs on `http://localhost:3000`.

## Usage

- Register or log in to create and customize your developer profile.
- Add coding problems via the Problem module.
- Interact with public problems through likes, comments, and ratings.
- Follow upcoming contests listed in your personal calendar.


