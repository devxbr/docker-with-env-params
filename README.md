# Docker with Environment Parameters

This repository provides an example of how to use environment parameters with Docker and Docker Compose. It demonstrates how to pass environment variables from a `.env` file to a Docker container.

## Contents

- `.env` - Environment variables file
- `Dockerfile` - Dockerfile to create a Docker image
- `docker-compose.yaml` - Docker Compose configuration

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Usage

1. Clone the repository:

    ```sh
    git clone https://github.com/devxbr/docker-with-env-params.git
    cd docker-with-env-params
    ```

2. Create a `.env` file with your environment variables. Example:

    ```sh
    VARIABLE_NAME=value
    ```

3. Build and run the Docker container using Docker Compose:

    ```sh
    docker-compose up --build
    ```

4. The environment variables defined in the `.env` file will be accessible inside the container.

## Contributing

Feel free to submit issues or pull requests if you have suggestions or improvements.

## License

This project is licensed under the MIT License.
