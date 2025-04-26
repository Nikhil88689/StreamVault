# Netflix Clone

A full-stack Netflix clone built with the MERN stack (MongoDB, Express, React, Node.js).

![Netflix Clone](https://github.com/your-username/mern-netflix-clone/raw/main/screenshot.png)

## Features

- User authentication (signup, login, logout)
- Browse movies and TV shows
- Watch trailers
- Search functionality
- Responsive design
- Protected routes for authenticated users

## Tech Stack

### Frontend
- React (with Vite)
- React Router for navigation
- Tailwind CSS for styling
- Zustand for state management
- React Player for video playback
- React Hot Toast for notifications
- Axios for API requests

### Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for authentication
- bcrypt.js for password hashing

### APIs
- The Movie Database (TMDB) API for movie and TV show data

## Installation and Setup

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn
- MongoDB Atlas account

### Environment Variables
Create a `.env` file in the root directory with the following variables:
```
PORT=5000
MONGO_URI=your_mongodb_connection_string
NODE_ENV=development
JWT_SECRET=your_jwt_secret
TMDB_API_KEY=your_tmdb_api_key
```

### Installation

1. Clone the repository
   ```
   git clone https://github.com/your-username/mern-netflix-clone.git
   cd mern-netflix-clone
   ```

2. Install server dependencies
   ```
   npm install
   ```

3. Install client dependencies
   ```
   cd frontend
   npm install
   ```

4. Run the development server
   ```
   # From the root directory
   npm run dev
   ```

5. Run the frontend
   ```
   # In a separate terminal, from the frontend directory
   npm run dev
   ```

### Production Build
```
npm run build
npm start
```

## Project Structure

```
netflix-clone/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   └── App.jsx
│   ├── index.html
│   └── package.json
├── .env
├── .gitignore
├── package.json
└── README.md
```

## Usage

1. Register a new account or login with existing credentials
2. Browse movies and TV shows on the homepage
3. Click on a title to view details and watch the trailer
4. Use the search functionality to find specific content
5. Access your search history from the profile menu

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the ISC License - see the LICENSE file for details.

## Acknowledgements

- [TMDB](https://www.themoviedb.org/) for providing the movie and TV show data
- [Netflix](https://www.netflix.com/) for the UI inspiration 
