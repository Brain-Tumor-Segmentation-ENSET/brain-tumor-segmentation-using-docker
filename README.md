# Brain Tumor Segmentation Project

This project tackles the critical challenge of automatic brain tumor segmentation from MRI images. It is containerized using Docker for easy deployment and scalability.

## Prerequisites

- Docker installed on your system.
- Git installed on your system.

## Getting Started

### Clone the Repository

Clone this repository to your local machine using:
```bash
git clone https://github.com/AhmedHoussamBouzine/brain-tumor-segmentation-using-docker.git
```
### Build the Docker Image

Build the Docker image using the following command:
```bash
docker build -t brain-tumor-segmentation .
```
### Run the Docker Container

Run the Docker container with the following command:

```bash
docker run -p 5005:5005 brain-tumor-segmentation

```
Use http://localhost:5005 to access the Flask application

## Contributing
Contributions are welcome! Fork this repository and submit pull requests for any improvements or bug fixes.