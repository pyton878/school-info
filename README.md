<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GVHSS MOOLAMATTOM</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    /* Base Reset */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: #f0f4f8;
      color: #333;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* Header */
    header {
      background-color: #1e3a8a;
      padding: 15px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      color: white;
    }

    .logo-area {
      display: flex;
      align-items: center;
      gap: 10px;
    }

    .logo-area img {
      height: 50px;
      border-radius: 50%;
    }

    nav a {
      margin-left: 20px;
      font-weight: 500;
      color: white;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #ffd700;
    }

    /* Hero */
    .hero {
      background: url('/home/gvhss/web page of school/WhatsApp Image 2025-09-13 at 12.33.50 PM.jpeg') center/cover no-repeat;
      height: 500px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      position: relative;
    }

    .hero::before {
      content: "";
      position: absolute;
      inset: 0;
      background-color: rgba(0, 0, 0, 0.4);
    }

    .hero h1 {
      position: relative;
      font-size: 2.8em;
      animation: fadeIn 2s ease-out;
    }

    /* Sections */
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      text-align: center;
      font-size: 2em;
      margin-bottom: 30px;
      color: #1e3a8a;
    }

    /* Notice Board */
    .notice-board {
      display: grid;
      gap: 20px;
    }

    .notice {
      background: white;
      border-left: 5px solid #1e3a8a;
      padding: 15px 20px;
      box-shadow: 0 2px 8px rgba(0,0,0,0.05);
    }

    /* About Section */
    .about-container {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      align-items: center;
    }

    .about-text {
      flex: 1;
      min-width: 250px;
    }

    .about-img {
      flex: 1;
      min-width: 250px;
    }

    .about-img img {
      width: 100%;
      border-radius: 10px;
    }

    /* Gallery */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
    }

    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    /* Contact */
    .contact p {
      margin-bottom: 10px;
    }

    .contact strong {
      color: #1e3a8a;
    }

    /* Footer */
    footer {
      background-color: #1e3a8a;
      color: white;
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
    }

    /* Animations */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Responsive Nav */
    @media (max-width: 700px) {
      header {
        flex-direction: column;
        align-items: flex-start;
      }

      nav {
        margin-top: 10px;
        width: 100%;
        text-align: center;
      }

      nav a {
        display: inline-block;
        margin: 10px;
      }

      .hero h1 {
        font-size: 2em;
      }
    }
  </style>
</head>
<body>

  <header>
    <div class="logo-area">
      <img src="/home/gvhss/web page of school/WhatsApp Image 2025-09-13 at 12.33.48 PM.jpeg" alt="School Logo">
      <h1>GVHSS MOOLAMATTOM</h1>
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#notices">Notices</a>
      <a href="#about">About</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>Welcome to Our School</h1>
  </section>

  <section id="notices">
    <h2>📢 Notice Board</h2>
    <div class="notice-board">
      <div class="notice"><strong>Sep 10:</strong> Parent-Teacher meeting at 3 PM</div>
      <div class="notice"><strong>Sep 12:</strong> Holiday for Ganesh Chaturthi</div>
      <div class="notice"><strong>Sep 13:</strong> psc exam 12pm - 3pm</div>
    </div>
  </section>

  <section id="about">
    <h2>🏫 About Our School</h2>
    <div class="about-container">
      <div class="about-text">
        <p>We are a committed educational institution, offering quality education since 1998. Our mission is to develop responsible, respectful, and well-rounded individuals who can thrive in a global society.</p>
      </div>
      <div class="about-img">
        <img src="/home/gvhss/web page of school/WhatsApp Image 2025-09-13 at 12.33.35 PM.jpeg" alt="Our School Building">
      </div>
    </div>
  </section>

  <section id="gallery">
    <h2>🖼️ School Gallery</h2>
    <div class="gallery">
      <img src="/home/gvhss/web page of school/WhatsApp Image 2025-09-13 at 12.33.49 PM(1).jpeg" alt="Annual Day Performance">
      <img src="/home/gvhss/web page of school/WhatsApp Image 2025-09-13 at 12.33.49 PM.jpeg" alt="Science Fair Awarding">
      <img src="/home/gvhss/web page of school/WhatsApp Image 2025-09-13 at 12.33.50 PM(1).jpeg" alt="School Star">
      <img src="/home/gvhss/web page of school/entrance.jpeg" alt="Cultural Event">
    </div>
  </section>

  <section id="contact">
    <h2>📞 Contact Us</h2>
    <div class="contact">
      <p><strong>Address:</strong> 123 School Road, YourCity</p>
      <p><strong>Phone:</strong> 04862252007</p>
      <p><strong>Email:</strong> 29012ghs@gmail.com</p>
      <p><a href="https://www.educationboard.gov.in" target="_blank" style="display:inline-block; background:#1e3a8a; color:white; padding:10px 20px; border-radius:5px; text-decoration:none;">facebook</a></p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 GVHSS MOOLAMATTOM. All rights reserved.</p>
  </footer>

</body>
</html>

