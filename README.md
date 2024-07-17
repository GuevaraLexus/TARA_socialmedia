
# TARA Social Media App

Welcome to **TARA**, a modern social media application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). TARA allows users to connect, share updates, and engage with friends through a sleek and user-friendly interface.

## Live Demo

Check out the live demo of the app [here](https://tara-socialmedia.netlify.app).

## Features

- **User Authentication**: Secure sign-up and login with JWT authentication.
- **User Profiles**: Create and manage personal profiles with bio, profile picture, and more.
- **Friend Requests**: Send, accept, and manage friend requests.
- **Posts**: Create, edit, delete, and like posts.
- **Comments**: Engage with posts by adding comments.
- **Real-time Notifications**: Get notified of friend requests, likes, and comments in real-time.
- **Responsive Design**: Fully responsive design to provide a seamless experience across all devices.

## Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **Styling**: CSS, Bootstrap

## Installation

To run the app locally, follow these steps:

1. **Clone the repository**:
    \`\`\`sh
    git clone https://github.com/yourusername/tara-socialmedia.git
    \`\`\`

2. **Navigate to the project directory**:
    \`\`\`sh
    cd tara-socialmedia
    \`\`\`

3. **Install dependencies**:
    \`\`\`sh
    npm install
    cd client
    npm install
    cd ..
    \`\`\`

4. **Create a `.env` file in the root directory and add the following environment variables**:
    \`\`\`
   for server
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET_KEY=your_jwt_secret_key
    PORT=your_localhost_port
    AUTH_EMAIL=your_email_for_sending_email_verification
    AUTH_PASSWORD=your_APP_password
    APP_url=your_localhost_but_will_be_changed_during_deployment

   for client
    REACT_APP_CLOUDINARY_ID=your_cloudinary_id
    \`\`\`

6. **Run the application**:
    \`\`\`sh
    npm run dev
    \`\`\`

The app should now be running on [http://localhost:3000](http://localhost:3000).

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

If you have any questions or feedback, feel free to reach out to the project maintainer at [20210250m.guevara.lexus.bscs@gmail.com](mailto:your-email@example.com).

---

Thank you for checking out TARA! We hope you enjoy using the app as much as we enjoyed building it.
