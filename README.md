# ThreadIt

![ThreadIt GIF](https://cdn.dribbble.com/users/1894420/screenshots/11700268/online-video-chat.gif)

## Overview

ThreadIt is a social media platform inspired by Reddit, implemented using the MERN stack. It offers a variety of functionalities that allow users to connect, share content, and moderate communities.

## Features

1. **User Registration**: 
   - Register with your details. Ensure that the contact number and age are numeric, while other fields are text.

2. **Login and Home Page**:
   - After logging in, you will be directed to the home page where you can follow other users through the "More People to Follow" section.

3. **Subgreddit Creation**:
   - Create a new subgreddit with moderator privileges.

4. **Join Subgreddit**:
   - Request to join other subgreddits. Upon acceptance, you can view posts, reports, user lists, stats, and requests. You can also create posts, upvote, downvote, and comment.

5. **Leave Subgreddit**:
   - You can leave a subgreddit at any time. However, once left, you cannot request to join again. You will still be able to view posts, reports, user lists, stats, and requests.

6. **Explore Subgreddits**:
   - View all subgreddits under the "All SubGReddit" tab. Search by name or description (with fuzzy search enabled) and sort them as needed. Navigate to their home pages via the "view" option.

7. **Post Interactions**:
   - Comment on posts if you are a moderator or member.
   - Save posts for future reference.

8. **User Reports**:
   - Report other users. As a moderator, you have the option to ignore the report, block the user, or delete the post.

9. **Statistics**:
   - View various statistics related to the subgreddit and user activity.

10. **Dependencies**:
    - Some libraries may need to be installed, such as `bcrypt` and `jsonwebtoken`.

## Getting Started

### Running with Docker

Ensure Docker is installed on your system.

1. Build the Docker images:
    ```bash
    sudo docker-compose build
    ```

2. Start the application:
    ```bash
    sudo docker-compose up
    ```

3. The web app should now be running on `localhost:3000`.

### Running Frontend and Backend Individually

#### Frontend

1. Navigate to the frontend directory:
    ```bash
    cd frontend
    ```

2. Install the required packages:
    ```bash
    npm install
    ```

3. Start the frontend server:
    ```bash
    npm start
    ```

#### Backend

1. Navigate to the backend directory:
    ```bash
    cd backend
    ```

2. Install the required packages:
    ```bash
    npm install
    ```

3. Start the backend server:
    ```bash
    nodemon server.js
    ```
    - If `nodemon` is not installed, you can start the server with:
    ```bash
    node server.js
    ```

## Contributing

If you'd like to contribute to ThreadIt, please fork the repository and use a feature branch. Pull requests are warmly welcome.
