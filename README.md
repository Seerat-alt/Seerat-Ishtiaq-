<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Seerat Ishtiaq | Digital Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Seerat Ishtiaq</h1>
    <nav>
      <a href="#about">About Me</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>
      Hi, I'm Seerat Ishtiaq, a second-semester BS English student with a passion for literature, storytelling, and creative writing. I enjoy exploring different cultures through books and aim to become a professional writer someday. I'm skilled in communication, content creation, and public speaking. I believe in using language to inspire and connect with people.
    </p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <ul>
      <li>Creative Writing Collection (coming soon)</li>
      <li>Blog on Culture & Language (coming soon)</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form id="contactForm">
      <label for="name">Your Name:</label>
      <input type="text" id="name" required />
      <label for="email">Your Email:</label>
      <input type="email" id="email" required />
      <label for="message">Message:</label>
      <textarea id="message" required></textarea>
      <button type="submit">Send</button>
    </form>
    <p id="formResponse"></p>
  </section>

  <footer>
    <p>© 2025 Seerat Ishtiaq | Follow me on 
      <a href="#" target="_blank">LinkedIn</a> | 
      <a href="#" target="_blank">Instagram</a>
    </p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
