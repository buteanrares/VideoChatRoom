# Video chatroom web application written in HTML, CSS and NodeJS.

## Developed using WebRTC, a Google Firebase hosted signaling server (firestore) - registered as dependency; and built with Vite - registered as dev dependency. 

### Exchange video-audio streams with your friends in your browser with auto-generated UUID.

- To recreate this project on your local machine, follow these steps:
  0. Make sure you have [npm](https://www.npmjs.com/get-npm) and [NodeJS](https://nodejs.org/en/download/) installed
  1. Clone this repository `git clone https://github.com/buteanrares/VideoChatRoom`
  2. Delete custom node modules folder
  3. `npm install`
  4. Initialize [firestore](https://console.firebase.google.com/) in test mode
  5. Create a web project
  6. Create a collection called `calls`
  7. Copy your firebase credentials and replace them in main.js (line 6)
  ```javascript
  const firebaseConfig = {
    // YOUR FIREBASE CONFIG HERE
  };
  ```
  9. `npm run dev`
