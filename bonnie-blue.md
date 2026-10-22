<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Daniel & Jonny – Celebrating Love 🏳️‍🌈</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Lato:wght@300;400;700&display=swap');

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --red:    #e40303;
      --orange: #ff8c00;
      --yellow: #ffed00;
      --green:  #008026;
      --blue:   #004dff;
      --violet: #750787;
    }

    body {
      font-family: 'Lato', sans-serif;
      background: #0d0d0d;
      color: #f5f0ea;
      min-height: 100vh;
      overflow-x: hidden;
    }

    /* Rainbow stripe header */
    .rainbow-bar {
      height: 8px;
      background: linear-gradient(
        to right,
        var(--red)    0% 16.6%,
        var(--orange) 16.6% 33.2%,
        var(--yellow) 33.2% 49.8%,
        var(--green)  49.8% 66.4%,
        var(--blue)   66.4% 83%,
        var(--violet) 83% 100%
      );
    }

    .hero {
      text-align: center;
      padding: 5rem 1.5rem 4rem;
      position: relative;
      background: radial-gradient(ellipse at top, #1a0a2e 0%, #0d0d0d 70%);
    }

    .rings {
      font-size: 3rem;
      margin-bottom: 1.5rem;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50%       { transform: translateY(-10px); }
    }

    @media (prefers-reduced-motion: reduce) {
      .rings { animation: none; }
    }

    .celebrating {
      font-family: 'Lato', sans-serif;
      font-weight: 300;
      font-size: 0.9rem;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: #aaa;
      margin-bottom: 1rem;
    }

    h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2.2rem, 6vw, 4rem);
      font-weight: 700;
      line-height: 1.2;
      background: linear-gradient(
        135deg,
        var(--red), var(--orange), var(--yellow),
        var(--green), var(--blue), var(--violet)
      );
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      margin-bottom: 0.75rem;
    }

    .ampersand {
      font-style: italic;
      font-weight: 400;
    }

    .tagline {
      font-size: 1.2rem;
      color: #ccc;
      margin-bottom: 0.5rem;
    }

    .pride-flag {
      font-size: 1.5rem;
      letter-spacing: 0.2rem;
      margin-top: 1.5rem;
    }

    /* Cards section */
    .cards {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1.5rem;
      padding: 3rem 1.5rem;
      max-width: 900px;
      margin: 0 auto;
    }

    .card {
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(255,255,255,0.1);
      border-radius: 1.25rem;
      padding: 2rem 1.75rem;
      flex: 1 1 260px;
      max-width: 280px;
      text-align: center;
      transition: transform 0.2s, border-color 0.2s;
    }

    .card:hover { transform: translateY(-4px); border-color: rgba(255,255,255,0.25); }

    .card-icon { font-size: 2.5rem; margin-bottom: 0.75rem; }
    .card h2 {
      font-family: 'Playfair Display', serif;
      font-size: 1.3rem;
      margin-bottom: 0.5rem;
      color: #fff;
    }
    .card p { font-size: 0.9rem; color: #aaa; line-height: 1.6; }

    /* Quote banner */
    .quote {
      text-align: center;
      padding: 3rem 1.5rem;
      background: linear-gradient(135deg, rgba(229,3,3,0.08), rgba(117,7,135,0.12));
      border-top: 1px solid rgba(255,255,255,0.06);
      border-bottom: 1px solid rgba(255,255,255,0.06);
    }

    .quote blockquote {
      font-family: 'Playfair Display', serif;
      font-style: italic;
      font-size: clamp(1.2rem, 3vw, 1.8rem);
      color: #f0e8ff;
      max-width: 700px;
      margin: 0 auto;
      line-height: 1.6;
    }

    .quote cite {
      display: block;
      margin-top: 1rem;
      font-family: 'Lato', sans-serif;
      font-style: normal;
      font-size: 0.85rem;
      letter-spacing: 0.1em;
      color: #888;
      text-transform: uppercase;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 2.5rem 1.5rem;
      font-size: 0.85rem;
      color: #555;
    }

    footer .hearts { font-size: 1.1rem; margin-bottom: 0.4rem; }
  </style>
</head>
<body>

  <div class="rainbow-bar"></div>

  <section class="hero">
    <div class="rings">💍 ✨ 💍</div>
    <p class="celebrating">Celebrating the Marriage of</p>
    <h1>Daniel <span class="ampersand">&</span> Jonny</h1>
    <p class="tagline">Love wins. Always. 🏳️‍🌈</p>
    <div class="pride-flag">🏳️‍🌈 🤍 🏳️‍🌈</div>
  </section>

  <div class="cards">
    <div class="card">
      <div class="card-icon">💒</div>
      <h2>The Couple</h2>
      <p>Daniel "Jew" Kagan and Jonny "Horny" Yox — two people who found each other and never looked back.</p>
    </div>
    <div class="card">
      <div class="card-icon">🥂</div>
      <h2>Cheers to You</h2>
      <p>May your life together be as colorful, joyful, and unapologetically yourselves as this very day.</p>
    </div>
    <div class="card">
      <div class="card-icon">🎉</div>
      <h2>From Your Friends</h2>
      <p>With every bit of love we have — congratulations. We are so happy for both of you.</p>
    </div>
  </div>

  <div class="quote">
    <blockquote>
      "The best thing to hold onto in life is each other."
      <cite>— Audrey Hepburn</cite>
    </blockquote>
  </div>

  <footer>
    <div class="hearts">❤️🧡💛💚💙💜</div>
    <p>With love from your friends &nbsp;·&nbsp; Forever and always</p>
  </footer>

  <div class="rainbow-bar"></div>

</body>
</html>
