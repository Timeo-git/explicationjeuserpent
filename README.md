<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Le Serpent du Verger - Explication</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      background-color: #121212;
      color: #f5f5f5;
      font-family: 'Segoe UI', Arial, sans-serif;
    }

    body {
      display: flex;
      flex-direction: column;
      align-items: center;
      text-align: center;
      min-height: 100vh;
      padding: 40px 20px;
      box-sizing: border-box;
    }

    h1 {
      font-size: 2.8rem;
      margin-bottom: 1rem;
    }

    .content {
      max-width: 650px;
      text-align: left;
    }

    p {
      font-size: 1.2rem;
      color: #cccccc;
      line-height: 1.6;
    }

    h2 {
      font-size: 1.5rem;
      margin-top: 2rem;
      color: #f5f5f5;
    }

    ul {
      font-size: 1.2rem;
      color: #cccccc;
      line-height: 1.8;
    }

    .btn {
      font-size: 1.2rem;
      padding: 12px 30px;
      margin-top: 2.5rem;
      border-radius: 8px;
      border: 2px solid #f5f5f5;
      background-color: transparent;
      color: #f5f5f5;
      text-decoration: none;
      display: inline-block;
      transition: transform 0.15s ease;
    }

    .btn:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <h1>Le Serpent du Verger</h1>

  <div class="content">
    <p>Le Serpent du Verger est un jeu de serpent classique dans un décor de verger. Le but est simple : diriger le serpent pour qu'il mange les fruits qui apparaissent, sans foncer dans les bords du terrain, dans un obstacle, ou dans sa propre queue.</p>

    <h2>Commandes</h2>
    <ul>
      <li>Flèches directionnelles ou touches WASD pour déplacer le serpent</li>
      <li>Barre d'espace pour mettre le jeu en pause</li>
    </ul>

    <h2>Progression</h2>
    <p>Chaque fruit mangé fait grandir le serpent et augmente le score. Plus le niveau monte, plus des obstacles apparaissent dans le verger, rendant le parcours plus difficile à négocier.</p>

    <h2>Objectif</h2>
    <p>Survivre le plus longtemps possible et battre son meilleur score, affiché en haut de l'écran de jeu.</p>
  </div>

  <a href="https://timeo-git.github.io/jeuxsiteweb/" class="btn">Jouer maintenant</a>
</body>
</html>
