# Social Wave - A Threads Clone

Social Wave is a feature-rich social media application inspired by Threads, built using the MERN stack (MongoDB, Express.js, React, Node.js) along with Socket.io for real-time communication and Chakra UI for an elegant, responsive design.

## Features
-  **Tech Stack**: MERN + Socket.io + Chakra UI
-  **Authentication & Authorization**: Secure user authentication with JWT.
-  **Create Post**: Share your thoughts with the world.
-  **Delete Post**: Remove posts when needed.
-  **Like/Unlike Post**: Engage with posts by liking or unliking.
-  **Comment on Posts**: Share your views by commenting on posts.
-  **Follow/Unfollow Users**: Stay connected with people you care about.
-  **Freeze Account**: Temporarily deactivate your account when required.
-  **Dark/Light Mode**: Toggle between dark and light modes for a personalized experience.
-  **Responsive Design**: Enjoy seamless user experience on any device.
-  **Chat App with Image Support**: Chat with users and share images in real time.
-  **Seen/Unseen Status for Messages**: Know when your messages have been read.
-  **Notification Sounds**: Stay alert with real-time notification sounds.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vivekraj2704/Social-Wave.git
    cd social-wave
    ```

2. Install dependencies for both client and server:
    ```bash
    npm install
    cd client
    npm install
    ```

3. Set up environment variables. Create a `.env` file in the root directory with the following:
    ```bash
    PORT=...
    MONGO_URI=...
    JWT_SECRET=...
    CLOUDINARY_CLOUD_NAME=...
    CLOUDINARY_API_KEY=...
    CLOUDINARY_API_SECRET=...
    ```

## Running the Application

### Build the App:
```bash
npm run build
