<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>prelovedyouu.id – Gitar, Skincare, Baju Lucu</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: system-ui, -apple-system, "Segoe UI", sans-serif;
      background: #fff8f3;
      color: #49352f;
      line-height: 1.6;
    }

    header {
      position: sticky;
      top: 0;
      z-index: 100;
      background: rgba(255, 248, 243, 0.95);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid #ead8cf;
      padding: 15px 6%;
    }

    .navbar {
      max-width: 1200px;
      margin: auto;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 24px;
      font-weight: 700;
      color: #b86b77;
    }

    nav {
      display: flex;
      gap: 25px;
    }

    nav a {
      text-decoration: none;
      color: #49352f;
      font-weight: 600;
      transition: 0.2s;
    }

    nav a:hover {
      color: #b86b77;
    }

    section {
      max-width: 1200px;
      margin: auto;
      padding: 80px 6%;
    }

    .hero {
      min-height: 90vh;
      display: flex;
      align-items: center;
      justify-content: space-between;
      gap: 50px;
    }

    .hero-text {
      flex: 1;
    }

    .hero-text h1 {
      font-size: clamp(40px, 6vw, 72px);
      line-height: 1.05;
      color: #a95e6b;
      margin-bottom: 20px;
    }

    .hero-text p {
      font-size: 18px;
      max-width: 550px;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 13px 24px;
      border-radius: 30px;
      background: #b86b77;
      color: white;
      text-decoration: none;
      font-weight: 700;
      transition: 0.2s;
    }

    .btn:hover {
      transform: translateY(-2px);
      opacity: 0.9;
    }

    .hero-card {
      flex: 1;
      min-height: 350px;
      border-radius: 30px;
      background: #f1dcd2;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 100px;
    }

    .section-title {
      text-align: center;
      margin-bottom: 40px;
    }

    .section-title h2 {
      color: #a95e6b;
      font-size: 38px;
      margin-bottom: 10px;
    }

    .catalog {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
      gap: 25px;
    }

    .product {
      background: white;
      border: 1px solid #ead8cf;
      border-radius: 22px;
      overflow: hidden;
      transition: 0.25s;
    }

    .product:hover {
      transform: translateY(-6px);
      box-shadow: 0 15px 35px rgba(100, 60, 50, 0.12);
    }

    .product-image {
      height: 220px;
      background: #f5e6df;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 80px;
    }

    .product-info {
      padding: 20px;
    }

    .product-info h3 {
      margin-bottom: 8px;
      color: #593e38;
    }

    .price {
      color: #b86b77;
      font-size: 20px;
      font-weight: 700;
      margin: 12px 0;
    }

    .product-info a {
      display: block;
      text-align: center;
      background: #b86b77;
      color: white;
      text-decoration: none;
      padding: 10px;
      border-radius: 12px;
      font-weight: 600;
    }

    .contact-box {
      background: #f1dcd2;
      border-radius: 30px;
      padding: 45px;
      text-align: center;
    }

    .contact-box h2 {
      color: #a95e6b;
      margin-bottom: 15px;
    }

    .contact-box p {
      margin-bottom: 10px;
    }

    .wa {
      margin-top: 20px;
      display: inline-block;
      background: #6c9f72;
      color: white;
      padding: 13px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 700;
    }

    .profile {
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: #49352f;
      color: white;
    }

    @media (max-width: 700px) {
      nav {
        gap: 12px;
        font-size: 14px;
      }

      .hero {
        flex-direction: column;
        text-align: center;
        padding-top: 50px;
      }

      .hero-card {
        width: 100%;
      }

      section {
        padding: 60px 5%;
      }
    }
  </style>
</head>

<body>

  <!-- NAVBAR -->
  <header>
    <div class="navbar">
      <div class="logo">prelovedyouu.id</div>

      <nav>
        <a href="#beranda">Beranda</a>
        <a href="#katalog">Katalog</a>
        <a href="#kontak">Kontak</a>
        <a href="#profil">Profil</a>
      </nav>
    </div>
  </header>


  <!-- BERANDA -->
  <section id="beranda" class="hero">

    <div class="hero-text">
      <h1>Barang Lucu,<br>Harga Bersahabat ♡</h1>

      <p>
        Selamat datang di prelovedyouu.id!
        Temukan berbagai barang preloved pilihan,
        mulai dari gitar, skincare, sampai baju lucu.
      </p>

      <a href="#katalog" class="btn">
        Lihat Katalog
      </a>
    </div>

    <div class="hero-card">
      🎸 🧴 👗
    </div>

  </section>


  <!-- KATALOG -->
  <section id="katalog">

    <div class="section-title">
      <h2>Katalog</h2>
      <p>Pilihan barang preloved yang tersedia</p>
    </div>

    <div class="catalog">

      <!-- GITAR -->
      <div class="product">

        <div class="product-image">
          🎸
        </div>

        <div class="product-info">
          <h3>Gitar Akustik</h3>

          <p>
            Gitar preloved dengan kondisi masih bagus
            dan cocok untuk pemula.
          </p>

          <div class="price">
            Rp350.000
          </div>

          <a
            href="https://wa.me/6282171580100?text=Halo%20Admin,%20saya%20tertarik%20dengan%20Gitar%20Akustik"
            target="_blank">
            Tanya Barang
          </a>
        </div>

      </div>


      <!-- SKINCARE -->
      <div class="product">

        <div class="product-image">
          🧴
        </div>

        <div class="product-info">
          <h3>Skincare</h3>

          <p>
            Produk skincare preloved pilihan
            dengan kondisi sesuai keterangan.
          </p>

          <div class="price">
            Rp50.000
          </div>

          <a
            href="https://wa.me/6282171580100?text=Halo%20Admin,%20saya%20tertarik%20dengan%20produk%20Skincare"
            target="_blank">
            Tanya Barang
          </a>
        </div>

      </div>


      <!-- BAJU -->
      <div class="product">

        <div class="product-image">
          👗
        </div>

        <div class="product-info">
          <h3>Baju Lucu</h3>

          <p>
            Baju preloved dengan model cute
            dan masih layak digunakan.
          </p>

          <div class="price">
            Rp75.000
          </div>

          <a
            href="https://wa.me/6282171580100?text=Halo%20Admin,%20saya%20tertarik%20dengan%20Baju%20Lucu"
            target="_blank">
            Tanya Barang
          </a>
        </div>

      </div>

    </div>

  </section>


  <!-- KONTAK -->
  <section id="kontak">

    <div class="contact-box">

      <h2>Hubungi Kami ♡</h2>

      <p>
        Admin: <strong>Agintha Annisa</strong>
      </p>

      <p>
        WhatsApp: <strong>0821-7158-0100</strong>
      </p>

      <a
        class="wa"
        href="https://wa.me/6282171580100"
        target="_blank">
        Chat WhatsApp
      </a>

    </div>

  </section>


  <!-- PROFIL -->
  <section id="profil">

    <div class="section-title">
      <h2>Profil Usaha</h2>
    </div>

    <div class="profile">

      <p>
        <strong>prelovedyouu.id</strong> merupakan toko
        yang menyediakan berbagai barang preloved
        dengan pilihan yang menarik dan harga
        yang bersahabat.
      </p>

      <br>

      <p>
        Kami menyediakan berbagai macam barang,
        seperti gitar, skincare, pakaian, dan
        barang lucu lainnya.
      </p>

    </div>

  </section>


  <!-- FOOTER -->
  <footer>
    <p>
      © 2026 prelovedyouu.id
    </p>

    <p>
      Made with ♡
    </p>
  </footer>


  <script>

    // Smooth scroll untuk navigasi
    document.querySelectorAll('a[href^="#"]').forEach(link => {

      link.addEventListener("click", function(e) {

        const target = document.querySelector(
          this.getAttribute("href")
        );

        if (target) {
          e.preventDefault();

          target.scrollIntoView({
            behavior: "smooth"
          });
        }

      });

    });

  </script>

</body>
</html>
