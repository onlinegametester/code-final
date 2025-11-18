<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>About us</title>

  <style>
    :root {
      --pink-bg: #ff9ecf;
      --blue-box: #7dc9ff;
      --brown-text: #8b5e3c;
      --hover-yellow: #fff7a8;
      --radius: 18px;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: var(--pink-bg);
      font-family: "Poppins", sans-serif;
      color: var(--brown-text);
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }

    header {
      margin-top: 40px;
      font-size: 2rem;
      font-weight: bold;
    }

    /* BLUE BOX */
    .section {
      width: 90%;
      max-width: 950px;
      min-height: 260px;
      background: var(--blue-box);
      border-radius: var(--radius);
      border: 2px solid var(--brown-text);
      margin: 3rem 0;
      padding: 2rem;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      transition: all 0.25s ease;
    }

    .section:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 25px rgba(0,0,0,0.2);
    }

    /* BUTTON */
    .small-btn {
      background: var(--brown-text);
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 10px;
      font-size: 1rem;
      cursor: pointer;
      transition: 0.25s ease;
      margin-top: 1rem;
    }

    .small-btn:hover {
      background: var(--hover-yellow);
      color: var(--brown-text);
      transform: scale(1.05);
      box-shadow: 0 4px 12px rgba(0,0,0,0.18);
    }

    footer {
      margin: 40px 0;
      font-size: 0.9rem;
    }

    @media (max-width: 750px) {
      .section {
        min-height: 200px;
      }
    }
  </style>

</head>
<body>

<header>About US!</header>

<!-- SINGLE BLUE BOX -->
<div class="section">
  <div>
    <p><h1>Welcome to Stitch n’ Stuff! 🧸</h1></p> 
    <p><h2>We are a trio in Transition Year working on</h2></p>
    <p><h2>a small business. We make handmade crochet bears unique to each</p>
    <p>individual by giving them their own distinctive style. 💝” </h2></p>
    <p><h2>If your interested in our work make sure to check our about us in the link below 💖 </h2></p> 
    <p><h6>-</h6></p>
    <p><h6>-</h6></p>
    <p><h1>🧶 Our Bears</h1></p>
    <p><h2>We’re three Transition Year students passionate about creativity, sustainability, and spreading joy through handmade crafts. </h2></p>
    <p><h2>Each bear is 100% handmade with care, love, and attention to detail. </h2></p>
    <p><h2>No two bears are the same — every one has its own personality and style! </h2></p>
    <p><h2>Made using high-quality, soft yarn and eco-friendly stuffing. </h2></p>
    <p><h2>Customisable colours, outfits, and accessories to match your vibe. </h2></p>
    <p><h2>Perfect as gifts for birthdays, holidays, or just because! </h2></p>
    <p><h6>-</h6></p>
    <p><h6>-</h6></p>
    <p><h1>💡 Our Mission </h1></p>
    <p><h2>To bring smiles through handmade, personalised creations. </h2></p>
    <p><h2>To encourage creativity and individuality through design.</h2></p>
    <p><h2>To support sustainable, small-scale crafting. </h2></p>
    <p><h6>-</h6></p>
    <p><h6>-</h6></p>
    <p><h1>💌 How to Order </h1></p>
    <p><h2>DM us on Instagram or message us through our page to design your own bear!</h2></p>
    <p><h2>Choose your theme, colours, and name — and we’ll do the rest. </h2></p>
    <p><h2>Each order comes with a little adoption card and care note. 🐻</h2></p>
    <p><h6>-</h6></p>
    <p><h6>-</h6></p>
    <p><h1>📍 Find Us </h1></p>
    <p><h2>Explore more </p></h2>
    <p><h2>Follow our journey on </p></h2>
    <h2><a href="https://www.instagram.com/stitch.n.stuff_?igsh=eGUzNDJwMWY5eDY0">On Our Instagram!</a></h2>
    <h3>________________________________________________________________________________________</h3>
    <button class="small-btn" onclick="window.location.href='file:///C:/Users/mariu/OneDrive/Ambiente%20de%20Trabalho/sns.html'">Back Home</button>
  </div>
</div>

<footer><h2>© 2025 | About Us</h2></footer>

</body>
</html>
