# top
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Top 10 DJs Favoritos</title>
  <style>
    @keyframes fadeUp {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes gradientMove {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    @keyframes pulse {
      0%, 100% { text-shadow: 0 0 10px #ffcc00; }
      50% { text-shadow: 0 0 25px #ffd700; }
    }

    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', sans-serif;
      color: white;
      background: linear-gradient(-45deg, #611212, #0e0116, #133544, #1b2735);
      background-size: 400% 400%;
      animation: gradientMove 12s ease infinite;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .container {
      background: rgba(0, 0, 0, 0.75);
      border-radius: 20px;
      padding: 50px 60px;
      max-width: 900px;
      width: 95%;
      box-shadow: 0 0 30px rgba(255, 255, 255, 0.15);
      backdrop-filter: blur(8px);
    }

    h1 {
      text-align: center;
      font-size: 3.5rem;
      margin-bottom: 50px;
      color: #d193e4;
      animation: pulse 2s infinite;
    }

    ol {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    li {
      display: flex;
      align-items: center;
      background: rgba(255, 255, 255, 0.08);
      margin-bottom: 25px;
      padding: 20px 25px;
      border-radius: 20px;
      gap: 20px;
      transform: translateY(30px);
      opacity: 0;
      animation: fadeUp 0.6s forwards;
      transition: background 0.3s ease;
    }

    li:nth-child(1) { animation-delay: 0.2s; }
    li:nth-child(2) { animation-delay: 0.4s; }
    li:nth-child(3) { animation-delay: 0.6s; }
    li:nth-child(4) { animation-delay: 0.8s; }
    li:nth-child(5) { animation-delay: 1s; }
    li:nth-child(6) { animation-delay: 1.2s; }
    li:nth-child(7) { animation-delay: 1.4s; }
    li:nth-child(8) { animation-delay: 1.6s; }
    li:nth-child(9) { animation-delay: 1.8s; }
    li:nth-child(10) { animation-delay: 2s; }

    li:hover {
      background: rgba(255, 255, 255, 0.15);
    }

    .img-wrapper {
      width: 90px;
      height: 90px;
      overflow: hidden;
      border-radius: 50%;
      flex-shrink: 0;
      border: 3px solid #ffcc00;
      box-shadow: 0 0 12px #ffcc00aa;
    }

    .img-wrapper img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .dj-info {
      display: flex;
      flex-direction: column;
    }

    .dj-name {
      font-size: 1.8rem;
      font-weight: bold;
      color: #fff;
    }

    .dj-music {
      font-size: 1.3rem;
      color: #ccc;
      font-style: italic;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Top 10 DJs Favoritos</h1>
    <ol>
      <li>
        <div class="img-wrapper">
          <img src="https://thisis-images.spotifycdn.com/37i9dQZF1DZ06evO3oZvlT-default.jpg" alt="Chapeleiro">
        </div>
        <div class="dj-info">
          <span class="dj-name">1. Chapeleiro</span>
          <span class="dj-music">Música: Metal</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://statics.otvfoco.com.br/2022/03/Captura-de-Tela-2022-03-08-a%CC%80s-16.43.42.png" alt="Camacho">
        </div>
        <div class="dj-info">
          <span class="dj-name">2. Camacho</span>
          <span class="dj-music">Música: 50's</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://geo-static.traxsource.com/files/artists/426911.jpg" alt="Gonzi">
        </div>
        <div class="dj-info">
          <span class="dj-name">3. Gonzi</span>
          <span class="dj-music">Música: Maruska</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://cdn-images.dzcdn.net/images/artist/bcfa439ec63bbf3fd77b67a67b1ea811/1900x1900-000000-80-0-0.jpg" alt="Mandragora">
        </div>
        <div class="dj-info">
          <span class="dj-name">4. Mandragora</span>
          <span class="dj-music">Música: Faze</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://vegaslive.com.br/wp-content/uploads/2023/02/Design-sem-nome.png" alt="Vegas">
        </div>
        <div class="dj-info">
          <span class="dj-name">5. Vegas</span>
          <span class="dj-music">Música: Imaginarium</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://i.scdn.co/image/ab67616100005174d4517b263eed5eb218006f97" alt="Kova">
        </div>
        <div class="dj-info">
          <span class="dj-name">6. Kova</span>
          <span class="dj-music">Música: Drop It</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://taogroup.com/wp-content/uploads/2022/01/240000_Fisher.jpg" alt="Fisher">
        </div>
        <div class="dj-info">
          <span class="dj-name">7. Fisher</span>
          <span class="dj-music">Música: Losing It</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://i.scdn.co/image/ab6761610000e5ebb657b9854c1fa00cd35e8dcd" alt="ZAPRAVKA">
        </div>
        <div class="dj-info">
          <span class="dj-name">8. ZAPRAVKA</span>
          <span class="dj-music">Música: Per 3 Dose</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://images.suamusica.com.br/Va_JRt_B6YWTk2w7Anfdd4CWL8M=/500x500/filters:format(webp)/46814201/3165415/cd_cover.png" alt="Aura Vórtex">
        </div>
        <div class="dj-info">
          <span class="dj-name">9. Aura Vórtex</span>
          <span class="dj-music">Música: Rampage!</span>
        </div>
      </li>
      <li>
        <div class="img-wrapper">
          <img src="https://media.gazetadopovo.com.br/2019/07/01155405/claudinho-brasil-.jpg" alt="Claudinho Brasil">
        </div>
        <div class="dj-info">
          <span class="dj-name">10. Claudinho Brasil</span>
          <span class="dj-music">Música: Mamma Mia</span>
        </div>
      </li>
    </ol>
  </div>
</body>
