<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>To-Do Application Setup Guide</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 2rem;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    h1, h2 {
      color: #2c3e50;
    }
    pre {
      background: #ecf0f1;
      padding: 1rem;
      border-left: 4px solid #3498db;
      overflow-x: auto;
    }
    .stage {
      background: #ffffff;
      border: 1px solid #ddd;
      border-left: 5px solid #3498db;
      margin-bottom: 2rem;
      padding: 1rem 1.5rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    .stage h2 {
      margin-top: 0;
    }
    code {
      background: #e1e1e1;
      padding: 0.2rem 0.4rem;
      border-radius: 3px;
    }
  </style>
</head>
<body>

  <h1>📝 To-Do Application</h1>
  <p>A simple and efficient To-Do application to manage your daily tasks.</p>

  <div class="stage">
    <h2>📦 Stage 1: Clone the Repository</h2>
    <pre><code>git clone https://github.com/your-username/todo-app.git
cd todo-app</code></pre>
  </div>

  <div class="stage">
    <h2>📥 Stage 2: Install Dependencies</h2>
    <p>Ensure Node.js and npm are installed.</p>
    <pre><code>npm install</code></pre>
  </div>

  <div class="stage">
    <h2>🖥️ Stage 3: Start the Server</h2>
    <p>Navigate to the server folder and run the backend:</p>
    <pre><code>cd server
node server.js</code></pre>
    <p>Backend runs on <code>http://localhost:5000</code></p>
  </div>

  <div class="stage">
    <h2>💻 Stage 4: Start the Client</h2>
    <p>In another terminal, from the root directory:</p>
    <pre><code>npm run dev</code></pre>
    <p>This will start the frontend and connect it to the backend.</p>
  </div>

  <div class="stage">
    <h2>📁 Project Structure</h2>
    <pre><code>todo-app/
├── client/       # Frontend React code
├── server/       # Backend Node.js/Express code
├── package.json
└── README.html</code></pre>
  </div>

  <div class="stage">
    <h2>✨ Features</h2>
    <ul>
      <li>Add, edit, and delete tasks</li>
      <li>Mark tasks as completed</li>
      <li>Live syncing between frontend and backend</li>
      <li>Minimal, user-friendly UI</li>
    </ul>
  </div>

  <div class="stage">
    <h2>🤝 Contributing</h2>
    <p>Open an issue or pull request for any suggestions or improvements!</p>
  </div>

  <div class="stage">
    <h2>📃 License</h2>
    <p>This project is licensed under the <strong>MIT License</strong>.</p>
  </div>

</body>
</html>
