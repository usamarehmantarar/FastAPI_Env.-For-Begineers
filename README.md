# FastAPI Setup for Beginners - Lightweight & Fast

This documentation guides you through the setup and usage of a FastAPI application using Docker. The application is available as a Docker image on Docker Hub for easy deployment.

## Setup

1. **Clone the Repository:**
   - Clone the FastAPI application repository to your local machine.

2. **Navigate to the Project Directory:**
   - Open a terminal and change your working directory to the cloned project.

3. **Run the Application:**
   - Start the application by running the following Docker Compose command:
     ```bash
     docker compose up
     ```
   - Your FastAPI application will be available at [http://localhost:8000](http://localhost:8000).

## Docker Pull Command

If you prefer to pull the pre-built Docker image from Docker Hub, use the following command:

```bash
docker pull usamarehmantararml/api-env
```

## Usage

1. **Start the Application:**
   - Run the application using Docker Compose:
     ```bash
     docker compose up
     ```
   - The FastAPI application will be accessible at [http://localhost:8000](http://localhost:8000).

2. **Explore the API:**
   - Open the provided URL in your web browser or use a tool like [Swagger UI](http://localhost:8000/docs) or [ReDoc](http://localhost:8000/redoc) to explore and interact with the API endpoints.

3. **Interact with Endpoints:**
   - Use tools like [curl](https://curl.se/) or [HTTPie](https://httpie.io/) to make HTTP requests to the API endpoints.

## Docker Container

The FastAPI application is available as a Dockerized container on Docker Hub. Pull the image using the following command:

```bash
docker pull usamarehmantararml/api-env
```

Replace `[image_name]` with the appropriate Docker image name.

## Note

Ensure that Docker is installed on your machine before running the commands. Adjust firewall settings if necessary to allow access to the specified port.

Feel free to explore the FastAPI application and customize it according to your needs. For more details about FastAPI, refer to the official [FastAPI documentation](https://fastapi.tiangolo.com/).
