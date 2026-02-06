<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Adeoye's Portfolio</title>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <!-- Font Awesome for social icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>
    :root {
      --primary: #0078d7;
    }

    /* 🔹 Animated gradient background */
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      color: #333;
      background: linear-gradient(-45deg, #0078d7, #00c6ff, #ff6f61, #6a11cb);
      background-size: 400% 400%;
      animation: gradientBG 15s ease infinite;
      transition: background 0.5s, color 0.5s;
      position: relative;
      overflow: hidden;
    }

    body.dark-mode {
      background: linear-gradient(-45deg, #121212, #1e1e1e, #333333, #000000);
      background-size: 400% 400%;
      animation: gradientBG 20s ease infinite;
      color: #f4f4f4;
    }

    @keyframes gradientBG {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    /* 🔹 Floating shapes */
    .background-animation {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      z-index: -1;
      overflow: hidden;
    }

    .background-animation::before,
    .background-animation::after {
      content: '';
      position: absolute;
      width: 200px; height: 200px;
      background: rgba(255, 255, 255, 0.15);
      border-radius: 50%;
      animation: float 20s infinite;
    }

    .background-animation::after {
      left: 50%;
      background: rgba(0, 120, 215, 0.2);
      animation-duration: 25s;
    }

    @keyframes float {
      0% { transform: translateY(0) translateX(0); }
      50% { transform: translate
