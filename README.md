<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Archprodesign142 | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Segoe UI", sans-serif;
    }

    body {
      height: 100vh;
      overflow-x: hidden;
      color: #fff;
    }

    /* Video Background */
    video {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -2;
    }

    /* Dark overlay */
    .overlay {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.35);
      z-index: -1;
    }

    /* Navigation */
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
    }

    nav h2 {
      letter-spacing: 2px;
      font-weight: 600;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 30px;
    }

    nav ul li {
      cursor: pointer;
      opacity: 0.8;
    }

    nav ul li:hover {
      opacity: 1;
    }

    /* Hero Section */
    .hero {
      height: 80vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero h1 {
      font-size: 3rem;
      letter-spacing: 3px;
      animation: fadeIn 2s ease;
    }

    .hero p {
      margin-top: 15px;
      font-size: 1.1rem;
      opacity: 0.85;
      max-width: 600px;
    }

    .btn {
      margin-top: 30px;
      padding: 12px 30px;
      border: 1px solid #fff;
      background: transparent;
      color: #fff;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #fff;
      color: #000;
    }

    /* Sections */
    section {
      padding: 80px 60px;
      background: #0e0e0e;
    }

    section h2 {
      margin-bottom: 20px;
      letter-spacing: 2px;
    }

    section p {
      max-width: 800px;
      opacity: 0.85;
      line-height: 1.6;
    }

    /* Footer */
    footer {
      padding: 30px;
      text-align: center;
      background: #000;
      opacity: 0.8;
    }

    /* Animations */
    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Mobile */
    @media (max-width: 768px) {
      nav {
        padding: 20px;
      }

      .hero h1 {
        font-size: 2rem;
      }

      section {
        padding: 60px 20px;
      }
    }
  </style>
</head>

<body>

  <!-- Video Background -->
  <video autoplay muted loop playsinline id="big-video">
    <source src="background.mp4" type="video/mp4">
  </video>
  <div class="overlay"></div>
  <!--END VIDEO BACKGROUND -->
  <!-- Navigation -->
  <nav>
    <h2>ARCHPRO</h2>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Projects</li>
      <li>Contact</li>
    </ul>
  </nav>

  <!-- Hero -->
  <div class="hero">
    <h1>ARCHPRODESIGN142</h1>
    <p>
      Architectural Technology | Design Innovation | Sustainable Concepts
    </p>
    <button class="btn">View Projects</button>
  </div>

  <!-- About -->
  <section>
    <h2>About Me</h2>
    <p>
      I am an architectural technology enthusiast focused on modern design,
      spatial planning, and innovative construction solutions. My work blends
      creativity with technical precision to deliver elegant and functional
      spaces.
    </p>
  </section>

  <!-- Projects -->
  <section>
    <h2>Projects</h2>
    <p>
      Residential designs • Concept models • Technical drawings • 3D
      visualization • Sustainable building ideas.
    </p>
  </section>

  <!-- Footer -->
  <footer>
    © 2026 Archprodesign142 • All Rights Reserved
  </footer>

</body>
</html>
