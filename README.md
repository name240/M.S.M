
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
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
	  https://github.com/name240/M.S.M/blob/1e6dc9b297556dc750c2d15c01972976d78ec2f1/School%20Logo.jpg

    <div class="school-name">THE RADIANCE SCHOOL SYSTEM</div>
    <div class="tagline">Glow the minds with knowledge</div>
  </div>

  <section id="about">
    <h2><u> M.S.M </u><br>
	   
	About</u></br></h2>
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

  <footer>
    &copy; 2025 The Radiance School System.
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

