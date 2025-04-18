<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Phat Vo - Logistics & SCM</title>
  <style>
    :root {
      --primary-color: #00b4d8;
      --bg-color: rgba(10, 10, 10, 0.6);
      --text-color: #f1f1f1;
      --secondary-text: #ccc;
    }

    body, html {
      margin: 0;
      padding: 0;
      height: 100%;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: url('https://images.unsplash.com/photo-1590066411268-0c17b8fcf8a0?auto=format&fit=crop&w=1740&q=80') no-repeat center center/cover;
      position: relative;
    }

    .overlay {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: var(--bg-color);
      z-index: 0;
    }

    .content {
      position: relative;
      z-index: 1;
      height: 100%;
      color: var(--text-color);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 2rem;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 0.5rem;
      color: var(--primary-color);
    }

    h2 {
      font-size: 1.4rem;
      color: var(--secondary-text);
      margin-bottom: 1.5rem;
    }

    p {
      max-width: 600px;
      font-size: 1rem;
      line-height: 1.6;
      margin-bottom: 2rem;
    }

    .skills h3 {
      color: var(--primary-color);
      margin-bottom: 0.5rem;
    }

    ul {
      list-style: none;
      padding: 0;
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      justify-content: center;
    }

    li {
      background-color: rgba(255, 255, 255, 0.05);
      padding: 0.5rem 1rem;
      border-radius: 8px;
      color: #ddd;
      font-size: 0.95rem;
    }

    .contact {
      margin-top: 2rem;
      font-size: 0.9rem;
    }

    .contact a {
      color: var(--primary-color);
      text-decoration: none;
    }

    footer {
      margin-top: 3rem;
      font-size: 0.8rem;
      color: #888;
    }

    @media (max-width: 600px) {
      h1 { font-size: 2rem; }
      h2 { font-size: 1rem; }
      ul { flex-direction: column; gap: 0.5rem; }
    }
  </style>
</head>
<body>
  <div class="overlay"></div>
  <div class="content">
    <h1>Phat Vo</h1>
    <h2>Logistics & Supply Chain Management</h2>
    <p>
      I'm a student with a passion for smart logistics, global trade, and efficient supply chains.
      I'm exploring how automation and AI can transform global commerce.
    </p>

    <div class="skills">
      <h3>Key Skills:</h3>
      <ul>
        <li>Supply Chain Planning</li>
        <li>Warehouse Management</li>
        <li>AI & Automation</li>
        <li>Data Analysis</li>
        <li>Process Optimization</li>
      </ul>
    </div>

    <div class="contact">
      📧 Email: <a href="mailto:phatvonguyen2005@gmail.com">phatvonguyen2005@gmail.com</a><br />
      💻 GitHub: <a href="https://github.com/opp987150" target="_blank">opp987150</a>
    </div>

    <footer>
      © 2025 Phat Vo
    </footer>
  </div>
</body>
</html>
