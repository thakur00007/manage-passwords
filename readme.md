# Password Manager

This project is a Password Manager application with a frontend, backend, and Docker setup.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Password Manager is a secure application that allows users to store and manage their passwords. It includes a frontend for user interaction, a backend for handling data, and a Docker setup for easy deployment.

## Features
- Secure password storage
- User authentication
- Password generation
- Responsive UI

## Technologies
- **Frontend:** React, Redux, CSS
- **Backend:** Node.js, Express, MongoDB
- **Docker:** Docker, Docker Compose

## Setup

### Prerequisites
- Docker
- Docker Compose

### Installation
1. Clone the repository:
  ```sh
  git clone https://github.com/yourusername/password-manager.git
  cd password-manager
  ```

2. Create a `.env` file in the root directory and add the necessary environment variables:
  ```env
  MONGO_URI=mongodb://mongo:27017/password-manager
  JWT_SECRET=your_jwt_secret
  ```

3. Start the application using Docker Compose:
  ```sh
  docker-compose up --build
  ```

## Usage
Once the application is running, you can access the frontend at `http://localhost:3001` and the backend API at `http://localhost:5001`.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.



