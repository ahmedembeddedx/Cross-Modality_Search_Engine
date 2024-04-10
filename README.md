# Multi-Modal Search Engine

This project is a Multi-Modal Search Engine developed using CLIP by OpenAI, with Flask API for backend and HTML/CSS for the frontend web application.

## Introduction

This project provides a seamless web interface where users can input text queries, and the system retrieves relevant images based on the textual description based on CLIP Architecture.

## Take a look
<a href="https://ibb.co/mbx781N"><img src="https://i.ibb.co/6rd5BVX/Screenshot-2024-04-10-at-11-02-35-PM.png" alt="Screenshot-2024-04-10-at-11-02-35-PM" border="0"></a>
<a href="https://ibb.co/MSwmjRD"><img src="https://i.ibb.co/2hVTLj7/Screenshot-2024-04-10-at-11-02-46-PM.png" alt="Screenshot-2024-04-10-at-11-02-46-PM" border="0"></a>
<a href="https://ibb.co/PG41n3N"><img src="https://i.ibb.co/3mWSqG7/Screenshot-2024-04-10-at-11-03-23-PM.png" alt="Screenshot-2024-04-10-at-11-03-23-PM" border="0"></a>
<a href="https://ibb.co/ynYHHQK"><img src="https://i.ibb.co/LzJVVZB/Screenshot-2024-04-10-at-11-03-51-PM.png" alt="Screenshot-2024-04-10-at-11-03-51-PM" border="0"></a>
<a href="https://ibb.co/W38kLK5"><img src="https://i.ibb.co/xs91N5L/Screenshot-2024-04-10-at-11-04-14-PM.png" alt="Screenshot-2024-04-10-at-11-04-14-PM" border="0"></a>

[![Watch the YouTube video](https://img.youtube.com/vi/FbiKR7LwRJ0/0.jpg)](https://youtu.be/FbiKR7LwRJ0)

## How to use
- sample data of 130 images is present in the file
(or)
- follow these steps to deal with your own images
- place your images in ```src/minidata```
- run the notebook ```src/image-processor```
- move the data in ```src/image_embeddings``` & the data in ```src/minidata``` to ```flaskapp/image_embeddings``` & ```flaskapp/static``` respectively (caution: transfer the data, not the directories)

## Features

- **Multi-Modal Search:** Users can input textual descriptions of images to retrieve relevant images.
- **Intuitive Web Interface:** The frontend is built using React to provide a user-friendly experience.
- **Scalable Backend:** Flask API serves as the backend, handling requests and interacting with the CLIP model.





Clone the repository:

   ```bash
   git clone https://github.com/ahmedembeddedx/Multi-Modal_Search_Engine.git
   ```


## Usage

Start the backend server:

   ```bash
   cd flaskapp/
   flask run
   ```

Access the web application in your browser at `http://127.0.0.1:5000/`.

## Stacks
- [OpenAI](https://openai.com) for developing CLIP.
- [Flask](https://flask.palletsprojects.com/) for the backend framework.


## Future Expectences
- Shift the app to react js
- Use ImageBind by MetaAI
- More accurate modal evaluation
