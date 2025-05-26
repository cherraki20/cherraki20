<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ismail's Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: linear-gradient(120deg, #0f0c29, #302b63, #24243e);
      color: white;
      padding: 30px;
    }

    header {
      text-align: center;
      margin-bottom: 60px;
    }

    header h1 {
      font-size: 3em;
      color: #00ffd5;
      text-shadow: 0 0 10px #00ffd5, 0 0 20px #00ffd5;
    }

    header p {
      font-size: 1.2em;
      color: #ccc;
    }

    section {
      margin-bottom: 80px;
    }

    h2 {
      font-size: 2em;
      border-left: 5px solid #00ffd5;
      padding-left: 15px;
      margin-bottom: 30px;
    }

    .card {
      background: rgba(255, 255, 255, 0.05);
      border: 1px solid rgba(255, 255, 255, 0.1);
      border-radius: 20px;
      padding: 20px;
      margin-bottom: 20px;
      backdrop-filter: blur(8px);
      box-shadow: 0 0 15px rgba(0, 255, 213, 0.2);
    }

    .skills span {
      background-color: #00ffd5;
      color: #000;
      padding: 8px 15px;
      margin: 5px;
      border-radius: 20px;
      display: inline-block;
      font-weight: 500;
      box-shadow: 0 0 10px #00ffd5;
    }

    .contact a {
      color: #00ffd5;
      text-decoration: none;
      font-size: 1.2em;
      display: block;
      margin-bottom: 10px;
    }

    footer {
      text-align: center;
      color: #888;
      margin-top: 50px;
      font-size: 0.9em;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ismail Cherraki</h1>
    <p>Future Frontend Developer 🚀 | Passionate about clean design & code</p>
  </header>

  <section>
    <h2>👨‍💻 About Me</h2>
    <div class="card">
      <p>Hello! I'm Ismail, a self-taught web developer passionate about beautiful and responsive design. I started my journey learning HTML & CSS, and now I'm aiming to explore more tech fields in the future.</p>
    </div>
  </section>

  <section>
    <h2>💡 Skills</h2>
    <div class="card skills">
      <span>HTML5</span>
      <span>CSS3</span>
      <span>Responsive Design</span>
      <span>UI/UX Basics</span>
      <span>Git</span>
    </div>
  </section>

  <section>
    <h2>📁 Projects</h2>
    <div class="card">
      <h3>Personal Portfolio</h3>
      <p>A creative and unique portfolio made with just HTML & CSS, with animations and stunning layout.</p>
    </div>
    <div class="card">
      <h3>Landing Page Clone</h3>
      <p>A responsive landing page inspired by modern SaaS websites.</p>
    </div>
  </section>

  <section>
    <h2>📬 Contact</h2>
    <div class="card contact">
      <a href="https://www.linkedin.com/in/ismail-cherraki-438213307/" target="_blank">LinkedIn</a>
      <a href="mailto:yourmail@example.com">yourmail@example.com</a>
    </div>
  </section>

  <footer>
    © 2025 Ismail Cherraki. All rights reserved.
  </footer>
</body>
</html>
