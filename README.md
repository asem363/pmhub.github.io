<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PMHub KZ - Learn Project Management</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Inter', sans-serif;
    }
    html {
      scroll-behavior: smooth;
    }
    body {
      background-color: #ffffff;
      color: #1f3c88;
      line-height: 1.6;
    }
    header {
      background-color: #1f3c88;
      color: #ffffff;
      padding: 20px 40px;
      text-align: center;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      z-index: 1000;
    }
    header img {
      max-height: 50px;
      margin-bottom: 10px;
      display: block;
      margin-left: auto;
      margin-right: auto;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #ffffff;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      padding: 120px 20px 60px; /* Учитываем высоту фиксированной шапки */
      text-align: center;
      background-color: #e6ecff;
    }
    section {
      padding: 80px 20px 40px; /* Отступ сверху из-за фиксированного хедера */
      max-width: 900px;
      margin: auto;
    }
    .features {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 20px;
    }
    .feature {
      background-color: #f0f4ff;
      border-left: 4px solid #1f3c88;
      padding: 20px;
      border-radius: 8px;
    }
    .screenshots {
      overflow-x: auto;
      white-space: nowrap;
      padding: 20px 0;
    }
    .screenshots img {
      max-height: 400px;
      margin-right: 15px;
      border-radius: 8px;
      display: inline-block;
    }
    .pricing {
      background-color: #f8f9ff;
      padding: 40px 20px;
      text-align: center;
      border-top: 4px solid #1f3c88;
      border-bottom: 4px solid #1f3c88;
    }
    footer {
      background-color: #1f3c88;
      color: #ffffff;
      text-align: center;
      padding: 20px;
    }
    .pricing h2,
    .section h2 {
      margin-bottom: 20px;
    }
    .pricing p,
    .section p {
      font-size: 1.2em;
    }
  </style>
</head>
<body>

  <header>
    <img src="5192769092300435085.jpg" alt="PMHub KZ Logo">
    <h1>PMHub KZ</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#features">Features</a>
      <a href="#screenshots">Screenshots</a>
      <a href="#pricing">Pricing</a>
      <a href="#contact">Contact</a>
      <a href="#contact">FAQ</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Learn Project Management Anytime, Anywhere</h1>
    <p>PMHub KZ is a mobile-first platform that helps students and SMEs in Kazakhstan master project management through localized content and real cases.</p>
  </section>

  <section class="section" id="about">
    <h2>About the Project</h2>
    <p>Our goal is to make project management accessible and practical for everyone, especially in the SME sector of Kazakhstan. PMHub KZ combines mobile learning, real-world scenarios, and community support to help users gain real project management experience.</p>
  </section>

  <section class="section" id="features">
    <h2>Features</h2>
    <div class="features">
        <div class="feature">
            <h3>📱 Mobile Learning</h3>
            <p>Study on-the-go with our mobile app, complete tasks, and earn certification-ready skills.</p>
        </div>
        <div class="feature">
            <h3>🤖 Telegram Chatbot</h3>
            <p>Use our bot for daily PM tips, updates, resources, and micro-lessons right inside Telegram.</p>
        </div>
        <div class="feature">
            <h3>🌐 Community</h3>
            <p>Join like-minded learners and mentors to grow your network and exchange knowledge.</p>
        </div>
        <div class="feature">
            <h3>📂 Templates & Tools</h3>
            <p>Access practical project templates, checklists, and toolkits designed for SMEs in Kazakhstan.</p>
        </div>
        <div class="feature">
            <h3>🌍 Project Management News & Events</h3>
            <p>Stay up-to-date with the latest news, global events, and conferences in project management, both worldwide and within Kazakhstan.</p>
            <div class="news-events">
                <!-- Dynamic data or widget can be used here -->
                <ul>
                    <li><a href="#">PM Global Summit 2025: Join industry leaders worldwide</a></li>
                    <li><a href="#">Project Management Week Kazakhstan: Upcoming workshops in Almaty</a></li>
                    <li><a href="#">New PM Trends: What to Expect in 2025</a></li>
                    <li><a href="#">International PM Conference: Call for speakers</a></li>
                </ul>
            </div>
        </div>
    </div>
</section>

  <section class="section" id="screenshots">
    <h2>App Screenshots</h2>
    <div class="screenshots">
      <img src="Снимок экрана 2025-04-29 220711.png" alt="Screenshot 1">
      <img src="Снимок экрана 2025-04-29 220812.png" alt="Screenshot 2">
      <img src="Снимок экрана 2025-04-29 220902.png" alt="Screenshot 3">
      <img src="Снимок экрана 2025-04-29 220926.png" alt="Screenshot 4">
      <img src="Снимок экрана 2025-04-29 221005.png" alt="Screenshot 5">
    </div>
  </section>


  <section class="pricing" id="pricing">
    <h2>Pricing</h2>
    <p>Monthly Plan: <strong>5,000 KZT</strong></p>
    <p>Yearly Plan: <strong>45,000 KZT</strong></p>
  </section>

<section class="section" id="contact">
  <h2>Contact Us</h2>
  <p>Have questions or want to partner with us?</p>
  <p>Email: <a href="mailto:pmhubkz@gmail.com">pmhubkz@gmail.com</a></p>
  <p>
    Telegram:
    <a href="https://t.me/PMHubKZ_bot" style="display: inline-flex; align-items: center;">
      <img src="Telegram_logo.svg.png" alt="Telegram Logo" style="height: 20px; margin-right: 8px;">
      @PMHubKZ_bot
    </a>
  </p>
</section>

<section class="section" id="faq">
  <h2>FAQ</h2>
  <ul>
    <li><strong>What is PMHub KZ?</strong><p>PMHub KZ is a mobile learning platform for mastering project management in SMEs.</p></li>
    <li><strong>How do I get started?</strong><p>Simply download the app and start learning with our free content or sign up for the premium plan.</p></li>
    <li><strong>Is there a certification?</strong><p>Yes, we offer certification upon completion of key learning modules.</p></li>
  </ul>
</section>

<section class="section" id="download">
  <h2>Download the App</h2>
  <p>Get PMHub KZ on your device:</p>
  <div style="display: flex; gap: 20px; justify-content: center; margin-top: 20px;">
    <a href="#"><img src="эпл.png" alt="App Store" style="height: 60px;"></a>
    <a href="#"><img src="гугл плэй.png" alt="Google Play" style="height: 60px;"></a>
  </div>
</section>

  <footer>
    <p>&copy; 2025 PMHub KZ. All rights reserved.</p>
  </footer>

</body>
</html>



