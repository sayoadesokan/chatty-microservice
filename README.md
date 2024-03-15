# Chatty API

This repository contains the source code for a chatting microservice developed with Node.js, RabbitMQ, Nginx, and Docker. This microservice is built using Node.js and utilizes RabbitMQ for messaging, Nginx for reverse proxy, and Docker for containerization.

## Features

- Real-time messaging: Allows users to send and receive messages in real-time.
- Scalable architecture: Utilizes microservices architecture for scalability and modularity.
- Integration with RabbitMQ: Communicates with RabbitMQ for asynchronous messaging.
- Dockerized deployment: Containerized using Docker for easy deployment and scalability.
- Nginx reverse proxy: Utilizes Nginx as a reverse proxy for load balancing and routing requests.

## Setup Instructions

1. Clone the repository:

   ```
   git clone https://github.com/sayoadesokan/chatty-microservice
   ```

2. Navigate to the project directory:

   ```
   cd chatting-microservice
   ```

3. Install dependencies:

   ```
   npm install
   ```

4. Set up environment variables:

   - Create a `.env` file based on the provided `.env.example` file.
   - Fill in the necessary environment variables such as RabbitMQ URL, MongoDB URL, etc.

5. Start the microservice:

   ```
   npm start
   ```

6. Access the microservice:

   - Once the microservice is running, you can access it via the provided endpoints.
   - Use a WebSocket client or application to connect to the WebSocket server for real-time messaging.

## Architecture

The microservice architecture consists of the following components:

- **Node.js**: The main programming language used for developing the microservice.
- **RabbitMQ**: Message broker for asynchronous communication between microservices.
- **Nginx**: Reverse proxy server for load balancing and routing requests to microservices.
- **Docker**: Containerization technology used for packaging the microservice and its dependencies.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
