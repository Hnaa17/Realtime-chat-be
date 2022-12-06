<div id="top"></div>

<!-- HEADER -->
<div align="center">
  <a href="https://github.com/Hnaa17/Realtime-chat-be">
    <img src="https://user-images.githubusercontent.com/110190301/205793370-c13f73fe-92fc-458a-a9c9-4ae594bb8706.png" alt="Logo" width="80px">
    <img src="https://user-images.githubusercontent.com/110190301/205792200-46071cb9-5ea6-46f4-9f0b-81193199ee67.png" alt="Logo Title" width="200px">
  </a>
  
  <h3 align="center">Telegram App Backend</h3>

  <p align="center"> 
    Create a Node.js app for building Telegram RESTful APIs using Express.
  </p>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#project-built-with">Project Built With</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#requirements">Requirements</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#setup-env-example">Setup .env example</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->
## Project Built With
Telegram app was built with some framework/library below:
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [Socket.io](https://socket.io/)
- [JSON Web Token](https://jwt.io/)
- [PostgreSQL](https://www.postgresql.org/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
This is an example of how to list things you need to use the software and how to install them.
* [Node.js](https://nodejs.org/en/download/)

### Requirements
* [Node.js](https://nodejs.org/en/)
* [Socket.io](https://socket.io/)
* [Postman](https://www.getpostman.com/) for testing
* [Database](https://www.postgresql.org/)

### Installation
- Clone the Repo
```
git clone https://github.com/Hnaa17/Realtime-chat-be.git
```
- Install Module
```
npm install
```
- Make a new database
- <a href="#setup-env-example">Setup .env</a>
- Type ` npm run dev`
<p align="right">(<a href="#top">back to top</a>)</p>

### Setup .env example
Create .env file in your root project folder.
```env
# main environment
PORT = 8000

# postgres database environment
DB_USERNAME = postgres
DB_HOST = localhost
DB_DATABASE = database
DB_PASSWORD = password
DB_PORT = 5432

# jwt environment
SECRETE_KEY_JWT = SECRETE_KEY

```
<p align="right">(<a href="#top">back to top</a>)</p>

## License
Distributed under the [MIT](/LICENSE) License.
<p align="right">(<a href="#top">back to top</a>)</p>