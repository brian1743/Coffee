<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cof n Jiro</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Cof n Jiro</h1>
    <p class="tagline">“Brewed with love. Served with care.”</p>
    <button id="theme-toggle">🌙 Dark Mode</button>
  </header>

  <section class="about">
    <h2>Our Story</h2>
    <p>
      The name “Cof n Jiro” reflects the bond between a mother and her son—Cof stands for coffee (mom's comfort), and Jiro is inspired by the child she deeply cares for. Every drink is made with the same warmth, care, and attention a mom gives her child.
    </p>
  </section>

  <section class="gallery">
    <h2>Gallery</h2>
    <div class="photos">
      <img src="https://image.shutterstock.com/image-photo/interior-contemporary-cozy-cafe-several-600w-1309735867.jpg" alt="Cozy café interior">
      <img src="https://quotement.com/wp-content/uploads/2022/06/140-Bond-Between-Mother-And-Child-Quotes-To-Warm-Your-Heart.jpg" alt="Mom and child moment">
      <img src="https://i.ytimg.com/vi/e4QT8eRA0Bw/maxresdefault.jpg" alt="Latte art with heart">
    </div>
  </section>

  <section class="menu">
    <h2>Menu Highlights</h2>
    <ul>
      <li><strong>Mom’s Hug Latte</strong> – Warm cinnamon and vanilla blend</li>
      <li><strong>Jiro’s Joy</strong> – Sweet iced caramel with a chocolate drizzle</li>
      <li><strong>Kalinga Kapeng Barako</strong> – Strong yet comforting, just like a mom</li>
      <li><strong>After-School Choco</strong> – For kids or kids-at-heart</li>
    </ul>
  </section>

  <section class="order-form">
    <h2>Place an Order</h2>
    <form id="orderForm">
      <label for="name">Name:</label>
      <input type="text" id="name" required />

      <label for="drink">Drink:</label>
      <select id="drink" required>
        <option value="">Choose a drink</option>
        <option value="Mom’s Hug Latte">Mom’s Hug Latte</option>
        <option value="Jiro’s Joy">Jiro’s Joy</option>
        <option value="Kalinga Kapeng Barako">Kalinga Kapeng Barako</option>
        <option value="After-School Choco">After-School Choco</option>
      </select>

      <button type="submit">Order Now</button>
    </form>
    <p id="orderMessage"></p>
  </section>

  <footer>
    <p>&copy; 2025 Cof n Jiro. Made with ❤️</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
