
<!DOCTYPE html>
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


* {
    margin: 0;
    padding: 0;
  }
   
  body {
    background-color: #eff1f2;
    font-family: sans-serif;
  }
   
  .content {
    grid-area: content;
  }
   
  .sidebar {
    grid-area: sidebar;
    background: linear-gradient(
      to right,
      rgba(200, 107, 142, 1),
      rgba(218, 105, 250, 1),
      rgba(110, 125, 253, 1)
    );
    justify-content: center;
  }
   
  .footer {
    grid-area: footer;
    background: white;
  }
   
  .container {
    font-size: 1.5em;
    width: 100%;
    height: 100;
    height: 100vh;
    display: grid;
    grid-template-areas: 'sidebar' 'content' 'footer';
    grid-template-columns: 1fr;
    grid-template-rows: 130px 800px 250px;
  }
   
  .content,
  .sidebar,
  .footer {
    padding: 1em;
  }
   
  nav ul {
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
    text-align: center;
  }
   
  nav li {
    list-style: none;
    padding: 1em 0;
  }
   
  nav li a {
    color: white;
    font-weight: 700;
    opacity: 0.6;
    text-decoration: none;
    transition: 0.3s;
  }
   
  nav li a:hover {
    opacity: 1;
  }
   
  .hero {
    max-width: 90 px;
    margin: 0 auto;
    text-align: center;
  }
   
  .hero img {
    width: 200px;
  }
   
  .hero h1 {
    font-size: 2em;
    font-weight: 300;
    color: #373046;
  }
   
  .hero p {
    font-weight: 300;
    line-height: 1.3em;
    color: #98abad;
  }
   
  .action-btn {
    display: inline-block;
    text-decoration: none;
    color: white;
    font-weight: 700;
    background: #567bfb;
    padding: 0.5em 2em;
    border-radius: 60px;
    margin: 1em 0;
    transition: 0.3s;
  }
   
  footer ul {
    max-width: 640px;
    margin: 2em auto;
    padding: 0;
    text-align: center;
    display: flex;
    flex-direction: row;
  }
   
  footer ul li {
    list-style: none;
    align-self: flex-end;
  }
   
  footer ul li a {
    text-decoration: none;
    color: #c1c6ce;
  }
   
  footer ul li img {
    width: 30%;
  }
   
  footer p {
    font-size: 0.8em;
  }
   
  @media (min-width: 1040px) {
    .container {
      grid-template-areas: 'sidebar content' 'sidebar footer';
      grid-template-rows: 1fr auto;
      grid-template-columns: 300px 1f;
    }
   
    nav ul {
      display: flex;
      justify-content: space-between;
      flex-direction: column;
    }
   
    .sidebar {
      background: linear-gradient(
        rgba(200, 107, 142, 1),
        rgba(218, 105, 250, 1),
        rgba(110, 125, 253, 1)
      );
      padding-top: 10em;
    }
   
    .hero {
      text-align: left;
      margin: 7em 0;
    }
   
    .hero img {
      width: 200px;
      float: right;
    }
   
    .hero h1 {
      font-size: 3em;
    }
   
    .hero p {
      width: 60%;
    }
   
    footer ul {
      max-width: 900px;
      margin: 0 auto;
      padding: 1em 0;
    }
   
    footer ul li a img {
      width: 20%;
    }
  }
