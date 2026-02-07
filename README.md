<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Adeoye's Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    :root {
      --primary: #0078d7;
    }
background.mp4
    /* 🔹 Video background */
    .video-background {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      overflow: hidden;
      z-index: -1;
    }
    .video-background video {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    /* 🔹 Overlay for readability */
    .overlay {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0,0,0,0.4); /* dark tint */
      z-index: -1;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      color: #fff;
      text-align: center;
    }

    h1 {
      margin-top: 100px;
      font-size: 3rem;
    }

    section {
      padding: 80px 20px;
    }

    .project-card {
      background: rgba(255,255,255,0.1);
      padding: 20px;
      margin: 10px;
      border-radius: 10px;
      display: inline-block;
      color: #fff;
      transition: transform 0.3s ease;
    }
    .project-card:hover {
      transform: scale(1.05);
    }

    .social-icons a {
      margin: 0 10px;
      font-size: 1.5rem;
      color: var(--primary);
    }
  </style>
</head>
<body>
  <!-- 🔹 Video background -->
  <div class="video-background">
    <video autoplay muted loop>
      <!-- Replace with your chosen architecture video -->
      <source src="background.mp4" type="video/mp4">
    </video>
  </div>
  <div class="overlay"></div>

  <h1>Adeoye's Portfolio</h1>
  <p>Welcome to my portfolio site!</p>

  <section id="projects">
    <h2>Projects</h2>
    <div class="project-card">Modern Residential Concept</div>
    <div class="project-card">Futuristic Office Space</div>
    <div class="project-card">Eco-Friendly Pavilion</div>
  </section>

  <section id="about">
    <h2>About REFUGE</h2>
    <p>I'm Adeoye Refuge – a visionary</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>Email: adeoye@example.com</p>
    <div class="social-icons">
      <a href="#"><i class="fab fa-twitter"></i></a>
      <a href="#"><i class="fab fa-github"></i></a>
      <a href="#"><i class="fab fa-linkedin"></i></a>
    </div>
  </section>
</body>
</html>
