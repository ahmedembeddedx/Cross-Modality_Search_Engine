<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Multi-Modal Search Engine</title>
</head>

<body style="font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif">
    <header>
        <h1>Multi-Modal Search Engine</h1>
        <p>This project is a Multi-Modal Search Engine developed using CLIP by OpenAI, with Flask API for backend and
            HTML/CSS for the frontend web application.</p>
    </header>

    <section id="introduction">
        <h2>Introduction</h2>
        <p>This project provides a seamless web interface where users can input text queries, and the system retrieves
            relevant images based on the textual description based on CLIP architecture. <a
                href="https://arxiv.org/pdf/2103.00020.pdf">Read the paper.</a></p>
    </section>

    <section id="take-a-look">
        <h2>Take a look</h2>
        <div class="image-grid">
            <img src="https://i.ibb.co/5X0P5kt/Screenshot-2024-04-10-at-11-02-46-PM.jpg" alt="Screenshot 1">
            <img src="https://i.ibb.co/mC0rZZq/Screenshot-2024-04-10-at-11-03-23-PM.jpg" alt="Screenshot 2">
            <img src="https://i.ibb.co/PtTgF57/Screenshot-2024-04-10-at-11-03-51-PM.jpg" alt="Screenshot 3">
            <img src="https://i.ibb.co/yY1cR0q/Screenshot-2024-04-10-at-11-04-14-PM.jpg" alt="Screenshot 4">
            <img src="https://i.ibb.co/hBJYFT4/Screenshot-2024-04-10-at-11-02-35-PM.jpg" alt="Screenshot 5">
        </div>
    </section>

    <section id="demo-video">
        <h2>Demo Video</h2>
        <div class="video-container">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/FbiKR7LwRJ0" frameborder="0"
                allowfullscreen></iframe>
        </div>
        <p>This video demonstrates how to use our project's main feature.</p>
    </section>

    <section id="how-to-use">
        <h2>How to use for your own images?</h2>
        <ul>
            <li>Sample data of 130 images is present in the file.</li>
            <li><a href="https://youtu.be/gJOLHB6QaO0">See the video</a>.</li>
            <li>Place your images in <code>src/minidata</code>.</li>
            <li>Run the notebook <code>src/image-processor</code>.</li>
            <li>Move the data in <code>src/image_embeddings</code> & the data in <code>src/minidata</code> to
                <code>flaskapp/image_embeddings</code> & <code>flaskapp/static</code> respectively (caution: transfer the
                data, not the directories).</li>
        </ul>
    </section>

    <section id="features">
        <h2>Features</h2>
        <ul>
            <li><strong>Multi-Modal Search:</strong> Users can input textual descriptions of images to retrieve relevant
                images.</li>
            <li><strong>Intuitive Web Interface:</strong> The frontend is built using React to provide a user-friendly
                experience.</li>
            <li><strong>Scalable Backend:</strong> Flask API serves as the backend, handling requests and interacting
                with the CLIP model.</li>
        </ul>
    </section>

    <section id="usage">
        <h2>Usage</h2>
        <p>Start the backend server:</p>
        <pre><code>cd flaskapp/
flask run
        </code></pre>
        <p>Access the web application in your browser at <a href="http://127.0.0.1:5000/">http://127.0.0.1:5000/</a>.
        </p>
    </section>

    <section id="stacks">
        <h2>Stacks</h2>
        <ul>
            <li><a href="https://openai.com">OpenAI</a> for developing CLIP.</li>
            <li><a href="https://flask.palletsprojects.com/">Flask</a> for the backend framework.</li>
        </ul>
    </section>

    <section id="future-expectations">
        <h2>Future Expectations</h2>
        <ul>
            <li>Shift the app to ReactJs.</li>
            <li>Use ImageBind by MetaAI.</li>
            <li>More accurate modal evaluation.</li>
            <li>Integrate Audio & Video Functionality.</li>
        </ul>
    </section>

    <footer>
        <p>Clone the repository:</p>
        <pre><code>git clone https://github.com/ahmedembeddedx/Multi-Modal_Search_Engine.git
        </code></pre>
    </footer>
</body>

</html>
