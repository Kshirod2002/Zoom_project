![Image](https://github.com/user-attachments/assets/cb9ee480-3b7e-419e-80f9-6e2e8971c694)
Render: https://zoom-project-frontend-gyov.onrender.com

# Zoom Clone Project

This project is a simplified clone of the Zoom video conferencing platform, built using Node.js, Socket.IO, WebRTC, and other related technologies. It aims to replicate the core functionalities of Zoom,
allowing users to create and join video meetings.

## Table of Contents

-   [Features](#features)
-   [Technologies Used](#technologies-used)
-   [Prerequisites](#prerequisites)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Environment Variables](#environment-variables)
-   [Contributing](#contributing)
-   [License](#license)

## Features

-   **Create Meeting Rooms:** Users can create unique meeting rooms.
-   **Join Meeting Rooms:** Users can join existing meeting rooms using room IDs.
-   **Video and Audio Communication:** Real-time video and audio communication using WebRTC.
-   **Screen Sharing (Optional):** Users can share their screens with other participants.
-   **Chat Functionality (Optional):** Real-time text chat within meeting rooms.
-   **Mute/Unmute Audio and Video:** Users can control their audio and video input.
-   **User List:** Displaying list of users within the meeting.

## Technologies Used

-   **Node.js:** JavaScript runtime environment.
-   **Express.js:** Web application framework for Node.js.
-   **Socket.IO:** Real-time, bidirectional event-based communication.
-   **WebRTC:** Real-time communication for browsers and mobile applications.
-   **HTML5, CSS3, JavaScript:** Front-end development.

## Prerequisites

-   Node.js (v14 or later)
-   npm (Node Package Manager)

## Installation

1.  Clone the repository:

    ```bash
    git clone <repository_url>
    cd <backend>
    ```

2.  Install dependencies:

    ```bash
    npm install
    ```

3.  Create a `.env` file in the root directory and add your environment variables (see [Environment Variables](#environment-variables)).

4.  Start the server:

    ```bash
    npm start
    ```

## Usage

1.  Open your browser and navigate to `http://localhost:3000`.
2.  Create a new meeting room or join an existing one using the provided room ID.
3.  Allow access to your camera and microphone when prompted.
4.  Start video conferencing with other participants.

## Environment Variables

Create a `.env` file in the root directory and add the following variables:
