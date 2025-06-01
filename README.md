# Dbatu-pyq
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Himmat F. Pawara | B.Pharm Student</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background: #f4f8fb;
      color: #333;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }
    header h1 {
      margin: 0;
    }
    nav a {
      color: white;
      margin-left: 1rem;
      text-decoration: none;
      font-weight: 500;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    #profile-pic {
      max-width: 200px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }
    .contact a {
      display: inline-block;
      margin: 0.5rem 0;
      color: #2c3e50;
      text-decoration: none;
    }
    .contact a:hover {
      text-decoration: underline;
    }
    form input, form textarea {
      width: 100%;
      padding: 0.75rem;
      margin: 0.5rem 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      padding: 0.75rem 1.5rem;
      background: #2c3e50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      background: #2c3e50;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
    @media (max-width: 600px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Himmat F. Pawara</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" style="text-align:center;">
    <img id="profile-pic" src="https://via.placeholder.com/200x200.png?text=Profile" alt="Himmat F. Pawara">
    <h2>Bachelor of Pharmacy Student</h2>
    <p>Welcome to my personal website! I'm passionate about sharing DBATU previous year question papers and academic support for fellow students.</p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a student pursuing a B.Pharm degree. I created this website to help DBATU students easily access previous year question papers and helpful content for better exam preparation. I enjoy learning HTML and using tech to support education.</p>
    <p><strong>Skills:</strong> HTML</p>
  </section>

  <section id="projects">
    <h2>My Project</h2>
    <h3>DBATU PYQ + Helping</h3>
    <p>A collection of DBATU university previous year question papers and guides for pharmacy students.</p>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact">
      <p>Email: <a href="mailto:himmatpawara283@gmail.com">himmatpawara283@gmail.com</a></p>
      <p>Instagram: <a href="https://instagram.com/himmat_pawara_0708" target="_blank">@himmat_pawara_0708</a></p>
    </div>
    <form onsubmit="alert('Thank you for your message!'); return false;">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Himmat F. Pawara. All rights reserved.</p>
  </footer>

</body>
</html>
