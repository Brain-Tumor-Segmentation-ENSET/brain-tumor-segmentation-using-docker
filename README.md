# Brain Tumor Segmentation

This repository contains a Flask application for brain tumor segmentation using a pre-trained deep learning model. The application is containerized using Docker for easy deployment and scalability.

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
### Test:

Use the following command to upload an image for testing:
```bash
curl -X POST -F "image=@path_to_your_image.jpg" http://localhost:5005/upload

```

or you can create a frontend application to interact with the Flask API for uploading images. 

## Contributing
Contributions are welcome! Fork this repository and submit pull requests for any improvements or bug fixes.