<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Joyeux Anniversaire Soupou nene 🎉</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #ff7eb9, #ff758c);
      color: white;
      text-align: center;
    }
    section {
      padding: 60px 20px;
      max-width: 800px;
      margin: auto;
    }
    h1, h2 {
      margin-bottom: 20px;
    }
    p {
      font-size: 18px;
      line-height: 1.6;
    }
    .card {
      background: rgba(255, 255, 255, 0.15);
      padding: 30px;
      border-radius: 15px;
      margin-top: 30px;
    }
    button {
      margin-top: 30px;
      padding: 15px 30px;
      font-size: 18px;
      border: none;
      border-radius: 30px;
      background: #ffcc70;
      cursor: pointer;
    }
    button:hover {
      background: #ffd98e;
    }
    #bisous, #secret {
      margin-top: 30px;
      font-size: 22px;
    }
    footer {
      margin-top: 50px;
      font-size: 14px;
      opacity: 0.8;
    }
  </style>
</head>
<body>

  <!-- Écran d'accueil -->
  <section>
    <h1>🎉 Joyeux 19 ans Soupou nene 🎉</h1>
    <p>19 ans et déjà légendaire ! Prépare-toi à sourire et à te sentir spécial 😄</p>
  </section>

  <!-- Section drôle -->
  <section class="card">
    <h2>Un peu de fun 😎</h2>
    <p>À 19 ans, tu es officiellement un pro du chill, expert en rire contagieux et champion du monde des blagues nulles… et je valide 💪😂</p>
  </section>

  <!-- Section émotionnelle -->
  <section class="card">
    <h2>Un petit moment sérieux 💙</h2>
    <p>Souleymane, mon beau, je tiens énormément à toi.  
    Fidèle, drôle, attentionné… tu rends chaque jour meilleur juste en étant toi-même.</p>
  </section>

  <!-- Section 19 bisous -->
  <section class="card">
    <h2>19 bisous pour tes 19 ans 💋</h2>
    <button onclick="showBisous()">Clique pour recevoir tes bisous 🎁</button>
    <div id="bisous"></div>
  </section>

  <!-- Surprise finale -->
  <section class="card">
    <button onclick="showSecret()">Clique pour la surprise finale ✨</button>
    <div id="secret">
      <p>
        Souleymane, mon beau, je te souhaite tout le bonheur du monde 💙<br>
        Je suis tellement fière de toi : tu es devenu mature, réfléchi et responsable.<br>
        Je t’admire vraiment pour tout ce que tu es et tout ce que tu fais.<br>
        Tu es très important à mes yeux, et je suis heureuse de t’avoir dans ma vie.<br>
        Joyeux 19 ans, mon ami légendaire 🎂✨
      </p>
    </div>
  </section>

  <footer>
    Fait avec le cœur pour Soupou nene 💖
  </footer>

  <script>
    // Bisous automatiques
    const bisousDiv = document.getElementById("bisous");
    let countBisous = 0;
    const maxBisous = 19;

    function showBisous() {
      bisousDiv.innerHTML = ""; // Réinitialise au cas où
      countBisous = 0;
      const interval = setInterval(() => {
        if(countBisous < maxBisous) {
          bisousDiv.innerHTML += "💋";
          countBisous++;
        } else {
          clearInterval(interval);
        }
      }, 200); // 200 ms entre chaque bisou
    }

    // Surprise finale
    function showSecret() {
      document.getElementById("secret").style.display = "block";
    }
  </script>

</body>
</html>
