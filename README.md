<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Welcome to My Homepage</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      padding: 0.5rem;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1rem;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    main {
      padding: 2rem;
    }
    section {
      margin-bottom: 2rem;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
      position: fixed;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Homepage</h1>
    <p>Your simple, clean start on the web</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <main>
    <section id="about">
      <h2>About</h2>
      <p>This is a basic homepage template created with HTML and a bit of CSS styling.</p>
    </section>

    <section id="services">
      <h2>Services</h2>
      <p>Here you can list the services you offer, such as web design, writing, or anything else.</p>
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: example@example.com</p>
      <p>Phone: (123) 456-7890</p>
    </section>
  </main>

  <footer>
    &copy; 2025 Your Name. All rights reserved.
  </footer>

</body>
</html>
