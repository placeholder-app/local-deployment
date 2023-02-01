# Getting Started

This is a base repository for setting up local <https://placeholder.app> development. It includes the baseplate for setting up a docker environment, as well as the frontend and backend repositories.

# Setup

## Cloning

Clone this repository locally.

```bash
git clone https://github.com/placeholder-app/local-deployment
```

## Initializing Submodules

The two submodules included need to be initialized and pulled.

```bash
cd local-deployment

git submodule init --recursive
git submodule update --recursive
```

## Deploying Docker

You must have docker-cli or Docker Desktop installed.

```bash
docker compose up
```

This should install and deploy the frontend and backend containers. Once running, you can visit them at:

1. <http://localhost:3000>
2. <http://localhost:8080>

# Dependencies

- Docker or Docker Desktop
- Git
