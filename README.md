# Video Call Application

## Overview

This project is a real-time video calling application that enables users to connect with each other through video and audio communication over the internet. It demonstrates core concepts of real-time communication, peer-to-peer networking, and modern web technologies.

## Features

* Real-time video and audio communication
* Peer-to-peer connection
* Simple and clean user interface
* Low latency streaming
* Cross-browser compatibility

## Tech Stack

* Frontend: HTML, CSS, JavaScript
* Backend: Node.js
* WebRTC for real-time communication
* Socket.io for signaling

## How It Works

1. Users join a room using a unique room ID.
2. The signaling server (Socket.io) helps establish a connection between peers.
3. WebRTC handles direct peer-to-peer video/audio streaming.
4. Once connected, users can see and hear each other in real time.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ShreyaChaubey5/videoCall.git
   ```
2. Navigate to the project directory:

   ```bash
   cd videoCall
   ```
3. Install dependencies:

   ```bash
   npm install
   ```
4. Start the server:

   ```bash
   npm start
   ```
5. Open your browser and go to:

   ```
   http://localhost:3000
   ```

## Usage

* Open the application in two different tabs or devices.
* Enter the same room ID.
* Allow camera and microphone access.
* Start video calling.

## Project Structure

```
videoCall/
│── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│── server.js
│── package.json
```

## Future Improvements

* Add chat functionality
* Screen sharing support
* User authentication
* Group video calls

## Learning Outcomes

* Understanding WebRTC fundamentals
* Handling real-time communication
* Working with Socket.io
* Building full-stack applications

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License

This project is open-source and available under the MIT License.
