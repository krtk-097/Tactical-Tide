# Tactical Tide
An Online multiplayer chess game. You can play against your friend or against the computer.

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
  </ol>
</details>

## About The Project

![product-screenshot](https://github.com/krtk-097/Tactical-Tide/blob/main/backend/images/chess1.png)

There are 2 modes in this game.<br />
 1. Play with friend(Need to register first)<br />
 2. Play against computer(Used Minimax algorithm to generate move. Improved using alpha beta pruning)<br />


### Built With

* [NodeJS](https://nodejs.org/en/)
* [ExpressJS](https://expressjs.com/)
* [MongoDB](https://www.mongodb.com/1)
* [ReactJS](https://reactjs.org/)
* [Socket.io](https://socket.io/)
* [Chess.js](https://github.com/jhlywa/chess.js)

<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Installation

Fork, then download or clone the repo.
```bash
  git clone https://github.com/krtk-097/Tactical-Tide.git
```

For the **backend**, go to **backend** folder and install the dependencies once via the terminal.
```bash
  cd backend
  npm install
```

For the **frontend**, go to **frontend** folder and install the dependencies once via the terminal.

```bash
  cd frontend
  npm install
```

Now create *.env* file and fill all the details.
```env
MONGO_URI = PUT_YOUR_MONGODB_ATLAS_CONNECTION_STRING_HERE
JWT_SECRET = PUT_JWT_SECRET_HERE
GMAIL_USER = YOUR_GMAIL_ADDRESS
GMAIL_PASS = YOUR_GMAIL_PASS
```

Now you are ready to run the server and frontend.
<br />



