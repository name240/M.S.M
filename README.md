
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>M.S.M Firecore Logo</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    html, body {
      height: 100%;
      width: 100%;
      display: flex;
      align-items: center;
      justify-content: center;
      background: linear-gradient(135deg, #1b1b1b, #000000);
      font-family: 'Segoe UI', sans-serif;
    }

    .logo-container {
      position: relative;
      width: 340px;
      height: 200px;
      background: rgba(255, 255, 255, 0.05);
      border-radius: 16px;
      backdrop-filter: blur(12px);
      box-shadow:
        0 0 20px rgba(255, 0, 0, 0.2),
        0 0 60px rgba(255, 0, 0, 0.3),
        inset 0 0 10px rgba(255, 255, 255, 0.1);
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
      cursor: pointer;
      transition: 0.3s ease-in-out;
    }

    .logo-container:hover {
      transform: scale(1.05);
      box-shadow:
        0 0 25px rgba(255, 0, 0, 0.4),
        0 0 80px rgba(255, 0, 0, 0.5),
        inset 0 0 15px rgba(255, 255, 255, 0.15);
    }

    .logo-text {
      font-size: 42px;
      font-weight: bold;
      letter-spacing: 12px;
      color: white;
      z-index: 2;
      text-shadow:
        0 0 8px #ff0000,
        0 0 15px #ff1a1a,
        0 0 30px #ff3333;
      animation: pulseGlow 3s infinite ease-in-out;
    }

    .glow-frame {
      position: absolute;
      top: -2px;
      left: -2px;
      right: -2px;
      bottom: -2px;
      border-radius: 18px;
      background: linear-gradient(120deg, rgba(255,0,0,0.6), transparent, rgba(255,0,0,0.6));
      z-index: 1;
      animation: borderFlow 6s linear infinite;
      opacity: 0.3;
    }

    .reflection {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 50%;
      background: linear-gradient(to bottom, rgba(255,255,255,0.08), transparent);
      border-top-left-radius: 16px;
      border-top-right-radius: 16px;
      pointer-events: none;
    }

    @keyframes pulseGlow {
      0%, 100% {
        text-shadow:
          0 0 8px #ff0000,
          0 0 15px #ff1a1a,
          0 0 30px #ff3333;
      }
      50% {
        text-shadow:
          0 0 12px #ff1a1a,
          0 0 25px #ff3333,
          0 0 40px #ff4d4d;
      }
    }

    @keyframes borderFlow {
      0% { transform: rotate(0deg); }
      100% { transform: rotate(360deg); }
    }

    /* Responsive */
    @media (max-width: 400px) {
      .logo-container {
        width: 90%;
        height: 180px;
      }

      .logo-text {
        font-size: 32px;
        letter-spacing: 8px;
      }
    }
  </style>
</head>
<body>

 <center> <div class="logo-container" onclick="restartEffect()">
    <div class="glow-frame"></div>
    <div class="reflection"></div>
    <div class="logo-text">M.S.M</div>
  </div></center>

  <script>
    function restartEffect() {
      const logo = document.querySelector('.logo-text');
      logo.style.animation = 'none';
      void logo.offsetWidth;
      logo.style.animation = 'pulseGlow 3s infinite ease-in-out';
    }
  </script>

</body>
</html>

<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width,text-align:device , initial-scale=device"/>
  <title>The Radiance School System</title>
  <style>
    /* Basic Reset */
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      scroll-behavior: smooth;
      font-family: 'Segoe UI', sans-serif;
    }

    body {
      background: linear-gradient(to right, #fefcea, #f1da36);
      min-height: 100vh;
      color: #333;
    }

    header {
      background: #002c6b;
      color: #fff;
      padding: 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    }

    nav {
      display: flex;
      justify-content: center;
      background: #0056b3;
      padding: 10px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    .container {
      text-align: center;
      padding: 40px 20px;
    }

    .container img {
      width: 300px;
      max-width: 90%;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }

    .school-name {
      margin-top: 20px;
      font-size: 32px;
      font-weight: bold;
      color: #002c6b;
      text-shadow: 1px 1px 2px #999;
    }

    .tagline {
      font-size: 18px;
      color: #666;
      margin-top: 10px;
    }

    section {
      padding: 60px 20px;
    }

    section h2 {
      color: #002c6b;
      margin-bottom: 20px;
    }
section h1 {
      color: #002c6b;
      margin-bottom: 20px;
	  }
    footer {
      background: #002c6b;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to The Radiance School System</h1>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div id="home" class="container">
	    <img src="https://raw.githubusercontent.com/name240/M.S.M/1e6dc9b297556dc750c2d15c01972976d78ec2f1/School%20Logo.jpg" alt="School Logo" />

    <div class="school-name">THE RADIANCE SCHOOL SYSTEM</div>
    <div class="tagline">Glow the minds with knowledge</div>
  </div>

  <section id="about">
    <h2>About</h2>
    <p>
      The Radiance School System is dedicated to empowering students through knowledge,
      creativity, and moral values. We provide a nurturing environment that encourages
      learning and personal growth for every student.
    </p>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p>Email: info@theradianceschool.edu.pk</p>
    <p>Phone: +92-300-0000000</p>
  </section>
  <section id="created By:">
  <h1>Created By:</h1>
  <p>M.Saim Majoka</p>
  </section>
  <footer>
    &copy; @2025 The Radiance School System.
  </footer>

  <script>
    // Smooth scroll for nav links
    document.querySelectorAll('nav a').forEach(link => {
      link.addEventListener('click', e => {
        e.preventDefault();
        const target = document.querySelector(link.getAttribute('href'));
        if (target) {
          target.scrollIntoView({ behavior: 'smooth' });
        }
      });
    });
  </script>

</body>
</html>

