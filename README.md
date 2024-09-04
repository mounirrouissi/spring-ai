# Fullstack Spring Boot React OpenAI Project for Chat and Image Generation

## Overview
This project is a fullstack application that integrates Spring Boot for the backend, React for the frontend, and OpenAI's API for chat and image generation capabilities. It provides a user-friendly interface for interacting with AI-powered chat and image generation features.

## Features
- Real-time chat functionality using OpenAI's GPT model
- AI-powered image generation using DALL-E
- Spring Boot backend for robust API management
- React frontend for a responsive and interactive user interface

## Prerequisites
- Java JDK 11 or later
- Node.js and npm
- Maven
- OpenAI API key

## Setup and Installation

### Backend (Spring Boot)
1. Clone the repository
2. Navigate to the `backend` directory
3. Configure your OpenAI API key in `application.properties`
4. Run `mvn spring-boot:run` to start the backend server

### Frontend (React)
1. Navigate to the `frontend` directory
2. Run `npm install` to install dependencies
3. Run `npm start` to start the React development server

## Usage
1. Open your browser and go to `http://localhost:3000`
2. Use the chat interface to interact with the AI
3. Use the image generation feature to create AI-generated images

## API Endpoints
- `/api/chat`: POST request for chat interactions
- `/api/image`: POST request for image generation

## Configuration
- Backend configuration: `backend/src/main/resources/application.properties`
- Frontend configuration: `frontend/.env`

## Contributing
Please read CONTRIBUTING.md for details on our code of conduct and the process for submitting pull requests.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments
- OpenAI for providing the API
- Spring Boot and React communities for excellent documentation and resources
