# profil
<!DOCTYPE html>
<html>
<head>
  <title>My portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="container">
     <div class="logo-section"
      <a href="#" class="logo">
      <img src="https://images.unsplash.com/photo-1688064124627-7023483359eb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=580&q=80" alt="Logo" class="logo-image">
    </a>
    <div class="logo-text">
      <h1>Amadeo Dino</h1>
    </div>
  </div>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#portfolio">Portfolio</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <div class="container">
      <h2>Hi, I'm dino</h2>
      <p>I'm a web developer and vidio editor with a passion for creating beautiful and functional websites. With several years of experience in the industry, I specialize in front-end development and enjoy turning ideas into reality.</p>
      <a href="#contact" class="btn">Contact Me</a>
    </div>
  </section>
<img
src="foto lu"
alt="logo-image"
  <section id="portfolio">
    <div class="container">
      <h2>Portfolio</h2>
      <div class="portfolio-items">
        <div class="portfolio-item">
          <img src="https://images.unsplash.com/photo-1688066318209-30c02c0bcdf8?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1032&q=80" alt="Project 1">
          <h3>Project 1</h3>
        </div>
        <div class="portfolio-item">
          <img src="https://images.unsplash.com/photo-1688064124627-7023483359eb?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=580&q=80" alt="Project 2">
          <h3>Project 2</h3>
        </div>
        <div class="portfolio-item">
          <img src="https://images.unsplash.com/photo-1688066052469-3cf7061f022d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=410&q=80" alt="Project 3">
          <h3>Project 3</h3>
        </div>
      </div>
    </div>
  </section>

  <section id="contact">
    <div class="container">
      <h2>Contact Me</h2>
      <form>
        <div class="form-group">
          <label for="name"></label>
          <input type="text" id="name" name="name" placeholder="Enter your name" required>
        </div>

        <div class="form-group">
          <label for="email"></label>
          <input type="email" id="email" name="email" placeholder="Enter your email" required>
        </div>

        <div class="form-group">
          <label for="message"></label>
          <textarea id="message" name="message" placeholder="Enter your message" required></textarea>
        </div>

        <input type="submit" value="Send Message" class="btn">
      </form>
    </div>
  </section>

  <footer>
    <p>&copy; 2023 Amadeo Dino. All rights reserved.</p>
  </footer>
</body>
</html>
