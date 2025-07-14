<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🔥 HASHFFZ | Free Fire Zone</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background: #0e0e0e;
      color: #fff;
    }

    a {
      text-decoration: none;
    }

    header {
      background: linear-gradient(135deg, #000000, #ff6a00);
      padding: 30px 0 20px;
      text-align: center;
      box-shadow: 0 0 30px #ffae00;
    }

    header h1 {
      font-family: Impact, sans-serif;
      font-size: 3.2rem;
      color: #fff;
      text-shadow: 0 0 20px #ff3c00, 0 0 40px #ffaa00;
      animation: fireglow 2s infinite alternate;
    }

    header p {
      margin-top: 10px;
      color: #ffaa00;
      letter-spacing: 1px;
      font-size: 1rem;
      text-shadow: 0 0 10px #000;
    }

    @keyframes fireglow {
      from { text-shadow: 0 0 10px #ff3c00; }
      to { text-shadow: 0 0 30px #ffaa00, 0 0 50px #ff5e00; }
    }

    nav {
      display: flex;
      justify-content: center;
      background: #1b1b1b;
      padding: 12px 0;
      flex-wrap: wrap;
    }

    nav a {
      color: #ffaa00;
      margin: 0 15px;
      font-weight: 600;
      position: relative;
      transition: 0.3s;
    }

    nav a::after {
      content: '';
      height: 2px;
      width: 0;
      background: #ff3c00;
      position: absolute;
      bottom: -4px;
      left: 0;
      transition: 0.3s ease;
    }

    nav a:hover::after {
      width: 100%;
    }

    .hero {
      background: url('https://staticg.sportskeeda.com/editor/2023/09/47267-16935786987826-1920.jpg') no-repeat center center/cover;
      height: 80vh;
      position: relative;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
    }

    .hero::before {
      content: '';
      position: absolute;
      inset: 0;
      background: rgba(0, 0, 0, 0.5);
    }

    .hero h2 {
      position: relative;
      font-size: 3rem;
      color: #fff;
      animation: glowText 2s ease-in-out infinite alternate;
      text-shadow: 0 0 10px #ff9900;
    }

    @keyframes glowText {
      from { text-shadow: 0 0 5px #ff4a00; }
      to { text-shadow: 0 0 20px #ffaa00, 0 0 40px #ff3c00; }
    }

    section {
      padding: 50px 20px;
      max-width: 1000px;
      margin: auto;
      animation: fadeIn 1s ease;
    }

    section h2 {
      font-size: 2.2rem;
      margin-bottom: 25px;
      color: #ffaa00;
      text-align: center;
      border-bottom: 2px solid #ff3c00;
      display: inline-block;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    .card {
      background: #1e1e1e;
      margin: 15px 0;
      padding: 20px;
      border-left: 5px solid #ff3c00;
      border-radius: 10px;
      transition: 0.3s ease;
      box-shadow: 0 4px 10px rgba(255, 60, 0, 0.2);
    }

    .card:hover {
      transform: scale(1.03);
      box-shadow: 0 0 15px #ff9900;
    }

    footer {
      background: #111;
      text-align: center;
      padding: 25px;
      font-size: 0.9em;
      color: #888;
      border-top: 1px solid #333;
    }

    #popupOverlay {
      position: fixed;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background: rgba(0, 0, 0, 0.8);
      display: flex;
      justify-content: center;
      align-items: center;
      z-index: 1000;
    }

    #popupBox {
      background: #1e1e1e;
      padding: 30px;
      border-radius: 10px;
      text-align: center;
      max-width: 90%;
      box-shadow: 0 0 30px #ff5e00;
    }

    #popupBox h2 {
      color: #ffaa00;
      margin-bottom: 15px;
    }

    #popupBox p {
      font-size: 1rem;
      color: #fff;
      margin-bottom: 20px;
    }

    #popupBox button {
      background: #ff3c00;
      color: #fff;
      padding: 10px 25px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 0 10px #ffaa00;
    }

    @media (max-width: 768px) {
      header h1 {
        font-size: 2rem;
      }

      .hero h2 {
        font-size: 1.8rem;
      }

      nav {
        flex-direction: column;
      }

      nav a {
        margin: 8px 0;
      }
    }
  </style>
</head>
<body>

  <!-- 🔊 Intro Sound -->
  <audio autoplay hidden>
    <source src="https://assets.mixkit.co/sfx/preview/mixkit-game-success-alert-2039.mp3" type="audio/mp3">
  </audio>

  <!-- ⚠️ Startup Warning -->
  <div id="popupOverlay">
    <div id="popupBox">
      <h2>⚠️ Free Fire India Warning</h2>
      <p>Free Fire India is set in a virtual world and does not represent real life.<br>
      Please play responsibly and take frequent breaks.</p>
      <button onclick="closePopup()">OK</button>
    </div>
  </div>

  <!-- Header -->
  <header>
    <h1>🔥 HASHFFZ</h1>
    <p>Free Fire Zone – Drop. Clutch. Dominate.</p>
  </header>

  <!-- Navbar -->
  <nav>
    <a href="#top">Top Players</a>
    <a href="#tips">Tips</a>
    <a href="#tutorials">Tutorials</a>
    <a href="#updates">News</a>
  </nav>

  <!-- Hero Section -->
  <div class="hero">
    <h2>Drop In. Survive. Be Legendary.</h2>
  </div>

  <!-- Top Players -->
  <section id="top">
    <h2>Top Players</h2>
    <div class="card">
      <h3>👑 Raistar</h3>
      <p>Famous for speed, aim, and one-taps. One of India's most feared players.</p>
    </div>
    <div class="card">
      <h3>⚔️ Sudip Sarkar</h3>
      <p>Aggressive rusher with deadly instincts. A K/D beast in rank.</p>
    </div>
    <div class="card">
      <h3>🎯 TG Dada</h3>
      <p>Sniper god and movement king. Always ready to clutch a squad wipe.</p>
    </div>
  </section>

  <!-- Pro Tips -->
  <section id="tips">
    <h2>Pro Tips</h2>
    <div class="card">
      <h3>🧠 One Tap Mastery</h3>
      <p>Use drag-headshot technique + lower sensitivity = BOOYAH every time.</p>
    </div>
    <div class="card">
      <h3>🏃 Movement is Everything</h3>
      <p>Jump, crouch, prone — mix it up in every fight to confuse your enemies.</p>
    </div>
    <div class="card">
      <h3>🛡️ Gloo Wall Instant Deploy</h3>
      <p>Train yourself in Training Island to drop gloo walls like a pro under pressure.</p>
    </div>
  </section>

  <!-- 📺 Tutorial Videos -->
  <section id="tutorials">
    <h2>Tutorial Videos</h2>

    <div class="card">
      <h3>🔥 One Tap Headshot Tutorial</h3>
      <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:10px;">
        <iframe src="https://www.youtube.com/embed/J1Y2uycd1yA" 
          title="One Tap Headshot Free Fire" 
          style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allowfullscreen></iframe>
      </div>
    </div>

    <div class="card">
      <h3>🎯 Movement + Gloo Wall Tricks</h3>
      <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:10px;">
        <iframe src="https://www.youtube.com/embed/6B61C1Zt6Yk" 
          title="Gloo Wall Tricks" 
          style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allowfullscreen></iframe>
      </div>
    </div>

    <div class="card">
      <h3>👑 Rank Push Guide (Updated)</h3>
      <div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;border-radius:10px;">
        <iframe src="https://www.youtube.com/embed/5qM0K7azNYA" 
          title="Rank Push Free Fire" 
          style="position:absolute;top:0;left:0;width:100%;height:100%;border:0;" allowfullscreen></iframe>
      </div>
    </div>
  </section>

  <!-- Latest News -->
  <section id="updates">
    <h2>Latest News</h2>
    <div class="card">
      <h3>🚨 New Character: Kairos</h3>
      <p>Skill-based elite fighter coming in July update. Unlockable with rank tokens!</p>
    </div>
    <div class="card">
      <h3>🔥 Gold Royale Overhaul</h3>
      <p>New bundles, fire skins and FFIC-themed gear added. Spin before it ends!</p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 HASHFFZ | Designed with 🔥 by HASH | #Booyah
  </footer>

  <!-- Popup Script -->
  <script>
    function closePopup() {
      document.getElementById("popupOverlay").style.display = "none";
    }
  </script>

</body>
</html>
