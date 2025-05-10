<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>PMHub KZ</title>
  <style>
    /* === Preloader === */
    #preloader {
      background: #ffffff;
      bottom: 0;
      height: 100vh;
      left: 0;
      position: fixed;
      right: 0;
      top: 0;
      width: 100vw;
      z-index: 10000;
      display: flex;
      align-items: center;
      justify-content: center;
    }
{
    .loader {
      border: 6px solid #f3f3f3;
      border-top: 6px solid #007bff;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      animation: spin 1s linear infinite;
    }
}
    @keyframes spin {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }
{
    /* === Telegram Icon === */
    .telegram-icon {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: white;
      border-radius: 50%;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      padding: 10px;
      z-index: 1000;
    }
}
    .telegram-icon img {
      height: 40px;
      width: 40px;
    }
{
    .telegram-button {
      display: inline-block;
      background-color: #0088cc;
      color: white;
      padding: 12px 20px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      margin-top: 20px;
    }
}
    .telegram-button:hover {
      background-color: #0077b6;
    }
{
    /* === Download Section === */
    .download-buttons {
      text-align: center;
      margin-top: 40px;
    }
}
    .download-buttons img {
      height: 60px;
      margin: 0 10px;
      opacity: 0.6;
    }
{
    .download-buttons p {
      color: gray;
      font-size: 0.9em;
    }
}
    /* === Features Hover Effect === */
    .feature {
      transition: transform 0.3s, box-shadow 0.3s;
      cursor: pointer;
      padding: 20px;
      border: 1px solid #ccc;
      border-radius: 12px;
      background: #f9f9f9;
      margin: 10px;
    }
{
    .feature:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.1);
      background-color: #dde5ff;
    }
}
    /* === Contact Form === */
    #feedback {
      padding: 40px;
      text-align: center;
    }
{
    #feedback form {
      max-width: 500px;
      margin: auto;
      display: flex;
      flex-direction: column;
    }
{
    #feedback input,
    #feedback textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 6px;
      margin-bottom: 10px;
    }
}
    #feedback button {
      background-color: #007bff;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
    }
{
    #feedback button:hover {
      background-color: #0056b3;
    }
}
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
{
    .section {
      padding: 60px 20px;
    }
}
    h2 {
      text-align: center;
    }
  </style>
</head>

<body>
  <!-- Preloader -->
  <div id="preloader">
    <div class="loader"></div>
  </div>

  <!-- Telegram Chat Icon -->
  <a href="https://t.me/PMHubKZ_bot" class="telegram-icon" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram Chat">
  </a>

  <!-- Features Section -->
  <section class="section" id="features">
    <h2>Features</h2>
    <div style="display: flex; flex-wrap: wrap; justify-content: center;">
      <div class="feature">🎯 Task Planning</div>
      <div class="feature">📊 Analytics Dashboard</div>
      <div class="feature">🎓 Microlearning Modules</div>
      <div class="feature">👥 Team Collaboration</div>
    </div>
  </section>

  <!-- Telegram Contact Section -->
  <section class="section" id="contact">
    <h2>Contact Us</h2>
    <p>Have questions? Reach out anytime:</p>
    <a href="https://t.me/PMHubKZ_bot" class="telegram-button" target="_blank">Message us on Telegram</a>
  </section>

  <!-- Feedback Form -->
  <section class="section" id="feedback">
    <h2>Send Us a Message</h2>
    <form action="mailto:youremail@example.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your name" required>
      <input type="email" name="email" placeholder="Your email" required>
      <textarea name="message" rows="5" placeholder="Your message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <!-- Download Section -->
  <section class="section" id="download">
    <h2>Download the App</h2>
    <p style="text-align:center;">Coming soon to your favorite app store</p>
    <div class="download-buttons">
      <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Available_on_the_App_Store_%28black%29_SVG.svg" alt="App Store">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/78/Google_Play_Store_badge_EN.svg" alt="Google Play">
      <p>App launching soon on iOS and Android</p>
    </div>
  </section>

  <!-- Preloader Script -->
  <script>
    window.addEventListener("load", function () {
      const preloader = document.getElementById("preloader");
      preloader.style.display = "none";
    });
  </script>
</body>
</html>


