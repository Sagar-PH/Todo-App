<h1 align="center"> Todo Application</h1>
<p align="center">A CRUD Application to manage your todos built with Django and Docker.</p>
<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
</p>

<hr />

<h2>📦 Project Setup</h2>
<p>You can run this <strong>Todo Application</strong> in <strong>two different ways</strong>:</p>
<ul>
  <li><strong>Method 1:</strong> Using Docker</li>
  <li><strong>Method 2:</strong> Running directly on your system</li>
</ul>

<hr />

<h2>🐳 Method 1: Run Using Docker</h2>
<h3>Option A: Use Prebuilt Docker Image (Recommended)</h3>
<p>You can run the application using a prebuilt private Docker image hosted on <strong>GitHub Container Registry (GHCR)</strong>.</p>
<ol><li>Pull the Docker image:</li></ol>
<pre><code>docker pull ghcr.io/sagar-ph/todo-app:latest</code></pre>
<ol start="2"><li>Start the application:</li></ol>
<pre><code>docker run -d ghcr.io/sagar-ph/todo-app:latest</code></pre>
<p>This will pull and run all required services in Docker containers.</p>

<hr />

<h3>🚀 Clone the Repository (For below methods)</h3>
<pre><code>git clone git@github.com:Sagar-PH/Todo-App.git</code></pre>

<hr />

<h3>Option B: Build Docker Image Locally</h3>
<ol>
  <li>Make sure <strong>Docker</strong> is installed on your system.</li>
  <li>Open a terminal in the project directory.</li>
  <li>Build the Docker image: command will build and create a Docker image for the project.</li>
</ol>

<pre><code>docker build -t todo-app .</code></pre>
<ol start="4"><li>Start the application: This will run all required services in Docker containers.</li></ol>
<pre><code>docker run -d todo-app</code></pre>

<hr />

<h2>⚙️ Method 2: Run Directly (Without Docker)</h2>

<h3>Steps</h3>
<ol>
  <li>Open a terminal in the project directory.</li>
  <li>Install project dependencies:</li>
</ol>
<pre><code>pip install -r requirements.txt</code></pre>
<ol start="4"><li>Run the Django application:</li></ol>
<pre><code>python manage.py runserver</code></pre>
<p>🎉 The Todo Application is now running!</p>

<hr />

<p align="center">Made by <strong>Sagar</strong></p>

<hr />

<h2>Demo Screenshot</h2>
<img src="demo/Screenshot.png" width="600">