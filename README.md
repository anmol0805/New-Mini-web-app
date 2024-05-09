# For Backend practise , I built a mini web app.
# Mini Web App - User Authentication & Posts

This repository contains the source code for a mini web application built using Node.js, Express.js, MongoDB, EJS, and Tailwind CSS. The app allows users to register, log in, create posts, like/unlike posts, and edit their existing posts.

## Features

- User registration and authentication with bcrypt for password hashing and JSON Web Tokens (JWT) for session management
- Create, read, update, and like/unlike posts
- User profile page displaying user information and their posts
- Clean and modern UI with Tailwind CSS
- Data storage and retrieval with MongoDB and Mongoose

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine
- MongoDB installed and running locally or a MongoDB connection string

### Installation

1. Clone the repository:

```
git clone https://github.com/your-username/mini-web-app.git
```

2. Navigate to the project directory:

```
cd mini-web-app
```

3. Install dependencies:

```
npm install
```

4. Set up MongoDB connection in `models/user.js` and `models/post.js`
5. Start the server:

```
npm start
```

6. Open your web browser and visit `http://localhost:3000`

## Usage

1. Register a new user or log in with existing credentials
2. On the user profile page, create a new post by typing in the textarea and clicking "Create New Post"
3. Interact with posts by liking/unliking or editing the content
4. Logout when done

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
