# Drop Sand Simulator
## Overview
A particle physics simulation project that demonstrates granular material behavior, specifically focusing on sand particle interactions.

## Features
- Real-time sand particle simulation
- Gravity and particle collision physics
- Interactive environment where users can add sand particles
- Visual representation of particle movement and interactions

## Requirements
- Docker installed on your system
- Basic understanding of container technology

## Running with Docker

### 1. Build the Docker Image
```bash
git clone https://github.com/cod3hunter/drop-sand-simulator.git

cd drop-sand-simulator

docker build -t sand-simulator .
```

### 2. Run the Container
```bash
docker run -p 80:80 sand-simulator
```

### 3. Access the Application
Open your web browser and navigate to `http://localhost` to start using the simulator.

## Troubleshooting
If you encounter any issues, ensure:
- Docker daemon is running
- Port 80 is not in use by another application
- You have sufficient permissions to run Docker commands
