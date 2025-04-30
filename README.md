# ✨ Full Stack Realtime Chat App ✨

![Demo App](/frontend/public/screenshot-for-readme.png)

A complete MERN stack chat application with real-time messaging capabilities, user authentication, and a modern UI.

## Live Demo
**ACCESSING:** [https://mern-hack-chat.onrender.com](https://mern-hack-chat.onrender.com)

## Highlights

- 🌟 **Tech stack:** MERN (MongoDB, Express, React, Node.js) + Socket.io + TailwindCSS + Daisy UI
- 🎃 **Authentication & Authorization** with JWT
- 👾 **Real-time messaging** with Socket.io
- 🚀 **Online user status** indicators
- 👌 **Global state management**
- 🐞 **Error handling** both on the server and on the client
- ⏳ And much more!

## Getting Started

### Prerequisites

- Node.js and npm installed
- MongoDB account
- Cloudinary account for image uploads

### Setup .env file

Create a `.env` file in the root directory with the following variables:

```
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_secret_key_for_jwt

CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```

### Installation

1. Clone the repository
   ```shell
   git clone https://github.com/yourusername/mern-hack-chat.git
   cd mern-hack-chat
   ```

2. Install dependencies
   ```shell
   npm install
   ```

3. Build the app
   ```shell
   npm run build
   ```

4. Start the app
   ```shell
   npm start
   ```

## Using the Application

### Step 1: Access the Web Application
Navigate to [https://mern-hack-chat.onrender.com](https://mern-hack-chat.onrender.com) in your browser (or http://localhost:5001 if running locally).

### Step 2: Create an Account
1. On the landing page, click the "Sign Up" button
2. Fill in the registration form with your:
   - Username
   - Email
   - Password
   - Profile picture (optional)
3. Click "Create Account" to register
4. You'll receive a confirmation that your account has been created

### Step 3: Sign In
1. After creating your account, you'll be redirected to the login page
2. Enter your credentials (email and password)
3. Click "Sign In"
4. Upon successful authentication, you'll be directed to the main chat interface

### Step 4: Start Chatting
1. On the left sidebar, you'll see a list of other users
2. Click on any user to start a conversation
3. Type your message in the input field at the bottom
4. Press Enter or click the send button to send your message
5. Enjoy real-time communication with other users!

## Features

### Real-time Messaging
- Messages are delivered instantly using Socket.io
- Message read receipts
- Typing indicators

### User Status
- Online/offline status indicators
- Last seen timestamps

### Profile Management
- Update profile picture
- Edit username and other profile details

### Security
- JWT-based authentication
- Password encryption
- Protected routes

## Troubleshooting

- **MongoDB Connection Issues:** Verify your MongoDB connection string in the `.env` file
- **Image Upload Problems:** Ensure your Cloudinary credentials are correct
- **Socket Connection Issues:** Check your network connection and firewall settings

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Socket.io for real-time communication capabilities
- TailwindCSS and Daisy UI for the modern interface
- MongoDB for the flexible database solution
- The MERN stack community for inspiration and support