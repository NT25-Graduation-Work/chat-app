# *DO NOT EDIT THIS REPO*
# *CLONE AND EDIT IN YOUR REPO*

<br />
  <h1 align="center">Chat-app 🦜</h1>

  <p align="center">
    A chat app built with Node.js, Socket.io, React.js, and Tailwind CSS.
    <br />
    <br />
    <a href="http://chat-app-on.herokuapp.com/">View Demo</a>
    ·
    <a href="https://github.com/lucasmrl/chat-app/issues">Report Bug</a>
    ·
    <a href="https://github.com/lucasmrl/chat-app/issues">Request Feature</a>
  </p>
</p>

<!-- ABOUT THE PROJECT -->

## About The Project

![Chat-app🦜](https://github.com/lucasmrl/chat-app/blob/master/screenshot.png?raw=true)

A real-time app to exchange messages with connected users. Built for learning purposes. This was the first time using **Socket.io**, so I decided to follow their tutorial to create a chat app and I added a few of the suggested features.

### Built With

- Node.js
- Socket.io
- React.js
- Tailwind CSS

<!-- GETTING STARTED -->

## Getting Started

To get a local copy up and running follow these simple steps.

### Prerequisites

yarnが必要です(npm不可)

- yarn
  ```sh
  volta install yarn@latest
  ```

  [How to install Volta](https://github.com/NT25-Graduation-Work/how-to/wiki/Node.js)

### Installation

1. リポジトリをclone
   ```sh
   git clone https://github.com/(your username)/chat-app-server.git
   ```
2. [リポジトリ直下](./)で依存関係をインストール
   ```sh
   cd chat-app-server
   yarn
   ```
3. クライアントを取得し、依存関係をインストール
   ```sh
   yarn run get-client
   ```
4. 開発環境を起動(クライアントとサーバー両方):
   ```sh
   yarn run dev
   ```

### Deploy (Example using Heroku)

- uncomment lines 10-13 from "server.js"
  ```sh
   // app.use(express.static(path.join(__dirname, "client/build")));
   // app.get("/*", function (req, res) {
   //   res.sendFile(path.join(__dirname, "client/build", "index.html"));
   // });
  ```

<!-- USAGE EXAMPLES -->

## Features

- Support for nickname
- Message to connected users when someone connects or disconnects
- List with online users
- Private messages
- Mobile friendly

## Future improvements

- Add “{user} is typing” functionality.
- Support for changing avatar image
- Option to create/join different "rooms"
- Add rich text editor
- Add support for videos, images, and GIFs.

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE` for more information.
