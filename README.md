<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🔥 HASHFFZ | Free Fire Zone</title>
  <style>
    * {margin: 0; padding: 0; box-sizing: border-box; scroll-behavior: smooth;}
    body {font-family: 'Poppins', sans-serif; background: #0e0e0e; color: #fff;}
    a {text-decoration: none;}
    header {background: linear-gradient(135deg, #000000, #ff6a00); padding: 30px 0 20px; text-align: center; box-shadow: 0 0 30px #ffae00;}
    header h1 {font-family: Impact, sans-serif; font-size: 3.2rem; color: #fff; text-shadow: 0 0 20px #ff3c00, 0 0 40px #ffaa00; animation: fireglow 2s infinite alternate;}
    header p {margin-top: 10px; color: #ffaa00; letter-spacing: 1px; font-size: 1rem; text-shadow: 0 0 10px #000;}
    @keyframes fireglow {from { text-shadow: 0 0 10px #ff3c00; } to { text-shadow: 0 0 30px #ffaa00, 0 0 50px #ff5e00; }}
    nav {display: flex; justify-content: center; background: #1b1b1b; padding: 12px 0; flex-wrap: wrap;}
    nav a {color: #ffaa00; margin: 0 15px; font-weight: 600; position: relative; transition: 0.3s;}
    nav a::after {content: ''; height: 2px; width: 0; background: #ff3c00; position: absolute; bottom: -4px; left: 0; transition: 0.3s ease;}
    nav a:hover::after {width: 100%;}
    .hero {background: url('https://staticg.sportskeeda.com/editor/2023/09/47267-16935786987826-1920.jpg') no-repeat center center/cover; height: 80vh; position: relative; display: flex; justify-content: center; align-items: center; text-align: center;}
    .hero::before {content: ''; position: absolute; inset: 0; background: rgba(0, 0, 0, 0.5);}
    .hero h2 {position: relative; font-size: 3rem; color: #fff; animation: glowText 2s ease-in-out infinite alternate; text-shadow: 0 0 10px #ff9900;}
    @keyframes glowText {from { text-shadow: 0 0 5px #ff4a00; } to { text-shadow: 0 0 20px #ffaa00, 0 0 40px #ff3c00; }}
    section {padding: 50px 20px; max-width: 1000px; margin: auto; animation: fadeIn 1s ease;}
    section h2 {font-size: 2.2rem; margin-bottom: 25px; color: #ffaa00; text-align: center; border-bottom: 2px solid #ff3c00; display: inline-block;}
    @keyframes fadeIn {from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); }}
    .card {background: #1e1e1e; margin: 15px 0; padding: 20px; border-left: 5px solid #ff3c00; border-radius: 10px; transition: 0.3s ease; box-shadow: 0 4px 10px rgba(255, 60, 0, 0.2);}
    .card:hover {transform: scale(1.03); box-shadow: 0 0 15px #ff9900;}
    footer {background: #111; text-align: center; padding: 25px; font-size: 0.9em; color: #888; border-top: 1px solid #333;}
    input, button {font-family: 'Poppins', sans-serif; font-size: 1rem;}
  </style>
</head>
<body>
  <audio autoplay hidden><source src="https://assets.mixkit.co/sfx/preview/mixkit-game-success-alert-2039.mp3" type="audio/mp3"></audio>
  <header><h1>🔥 HASHFFZ</h1><p>Free Fire Zone – Drop. Clutch. Dominate.</p></header>
  <nav>
    <a href="#uid-search">Search UID</a>
    <a href="#top">Top Players</a>
    <a href="#tips">Tips</a>
  </nav>
  <div class="hero">
    <h2>Drop In. Survive. Be Legendary.</h2>
  </div>  <section id="uid-search">
    <h2>Search Player UID</h2>
    <div style="text-align: center;">
      <input type="text" id="uidInput" placeholder="Enter UID (e.g. 12345678)" style="padding: 10px; width: 250px; border-radius: 5px; border: none;">
      <button onclick="searchUID()" style="padding: 10px 20px; background: #ff3c00; color: white; border: none; border-radius: 5px; font-weight: bold; margin-left: 10px;">Search</button>
    </div>
    <div id="profileResult" style="margin-top: 30px; display: none;" class="card">
      <h3 id="pname">Name: —</h3>
      <p><strong>Level:</strong> <span id="plevel">—</span></p>
      <p><strong>Rank:</strong> <span id="prank">—</span></p>
      <p><strong>K/D Ratio:</strong> <span id="pkd">—</span></p>
      <img id="pavatar" src="" style="max-width: 120px; margin-top: 10px; border-radius: 10px; display: none;" />
    </div>
  </section>  <section id="top">
    <h2>Top Players</h2>
    <div class="card"><h3>👑 Raistar</h3><p>Speed + Aim + One Taps</p></div>
    <div class="card"><h3>⚔️ Sudip Sarkar</h3><p>Aggressive rusher with beast K/D</p></div>
    <div class="card"><h3>🎯 TG Dada</h3><p>Sniper god + movement king</p></div>
  </section>  <section id="tips">
    <h2>Pro Tips</h2>
    <div class="card"><h3>🧠 One Tap</h3><p>Lower sens + drag headshots</p></div>
    <div class="card"><h3>🏃 Movement</h3><p>Jump, crouch, prone in fights</p></div>
    <div class="card"><h3>🛡️ Gloo Walls</h3><p>Train under pressure = OP reflex</p></div>
  </section>  <footer>© 2025 HASHFFZ | Designed by HASH | #Booyah</footer>  <script>
    const mockProfiles = {
      "12345678": {name: "HASH", level: 70, rank: "Heroic", kd: "4.89", avatar: "https://static.wikia.nocookie.net/freefire/images/1/18/Alok.png"},
      "87654321": {name: "BOOYAHxX", level: 65, rank: "Grandmaster", kd: "6.21", avatar: "https://static.wikia.nocookie.net/freefire/images/9/9b/Chrono.jpg"}
    };

    function searchUID() {
      const uid = document.getElementById("uidInput").value.trim();
      const result = document.getElementById("profileResult");

      if (mockProfiles[uid]) {
        const p = mockProfiles[uid];
        document.getElementById("pname").textContent = "Name: " + p.name;
        document.getElementById("plevel").textContent = p.level;
        document.getElementById("prank").textContent = p.rank;
        document.getElementById("pkd").textContent = p.kd;
        document.getElementById("pavatar").src = p.avatar;
        document.getElementById("pavatar").style.display = "block";
        result.style.display = "block";
      } else {
        result.style.display = "block";
        document.getElementById("pname").textContent = "Name: UID Not Found";
        document.getElementById("plevel").textContent = "—";
        document.getElementById("prank").textContent = "—";
        document.getElementById("pkd").textContent = "—";
        document.getElementById("pavatar").style.display = "none";
      }
    }
  </script></body>
</html> 

