<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="desain.css" />
    <title>Web | Portofolio</title>
  </head>
  <body>
    <div class="container">
      <div class="sidebar">
        <nav>
          <ul>
            <li><a href="about.html">About</a></li>
            <li><a href="blog.html">Blog</a></li>
            <li><a href="contact.html">Contact</a></li>
          </ul>
        </nav>
      </div>
      <main class="content">
        <section class="hero">
          <img src="online.png" alt="" />
          <div class="hero-content">
            <h1>BERANDA</h1>
            <br />
            <h2>HALO BANG WELCOMEEE YAHHH</h2>
            <br /><br />
            <p>
              Selamat datang di web training saya disini saya hanya menyoba nyoba saja sambil belajar tipis tipis
              agar dapat saya pahami dengan baik dan benar
            </p>
            <a href="" class="action-btn">Profile Saya</a>
          </div>
        </section>
      </main>
      <div class="footer">
        <footer>
          <ul>
            <li>
              <img src="instagram.png" alt="" /><a><p>Instagram</p></a>
            </li>
            <li>
              <img src="facebook.png" alt="" /><a><p>Facebook</p></a>
            </li>
            <li>
              <img src="twitter.png" alt="" /><a><p>Twitter</p></a>
            </li>
            <li>
              <img src="telegram.png" alt="" /><a><p>Telegram</p></a>
            </li>
          </ul>
        </footer>
      </div>
    </div>
  </body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <section id="about">
        <div class="container">
            <h1>Tentang Saya</h1>
            <p id="about-text">Klik tombol dibawah ini untuk mempelajari lebih lanjut tentang saya</p>
            <button id="toggle-button">Show More</button>
            <div id="more-info" class="hidden">
                <p>Hanya sekedar belajar :I</p>
            </div>
        </div>
    </section>
    <script src="user.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog</title>
    <link rel="stylesheet" href="styles2.css">
</head>
<body>
    <header>
        <h1>My Blog</h1>
        <input type="text" id="search-input" placeholder="Search posts...">
    </header>
    <main>
        <section id="blog-posts">
            <!-- Blog post items will be injected here -->
        </section>
    </main>
    <script src="script.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Social Media Links</title>
    <link rel="stylesheet" href="contact.css">
    <!-- Font Awesome for social media icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <div class="social-links">
        <a href="https://wa.me/qr/E5NAP5M45EZVK1" target="_blank" title="Chat with me on WhatsApp" class="social-link">
            <i class="fab fa-whatsapp"></i>
        </a>
        <a href="https://www.facebook.com/profile.php?id=100041591610151&mibextid=ZbWKwL" target="_blank" title="Follow me on Facebook" class="social-link">
            <i class="fab fa-facebook-f"></i>
        </a>
        <a href="https://www.instagram.com/drkafnii?igsh=MXd2MWFvaXFieHhwZw=" target="_blank" title="Follow me on Instagram" class="social-link">
            <i class="fab fa-instagram"></i>
        </a>
    </div>
</body>
</html>
