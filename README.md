
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfoilo</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700&display=swap">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 2rem 0;
    }
    .header-content {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    .header-content h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .profile-picture {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin: 20px auto;
    }
    nav {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
    }
    nav ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
    }
    nav ul li {
      display: inline-block;
      margin: 0 20px;
    }
    nav ul li a {
      text-decoration: none;
      color: #fff;
    }
    .section-content {
      background-color: #fff;
      padding: 2rem;
      margin: 2rem auto;
      max-width: 800px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .download-button {
      background-color: #333;
      color: #fff;
      padding: 0.5rem 1rem;
      text-decoration: none;
      border-radius: 20px;
      display: inline-block;
      margin-top: 10px;
    }
    .download-button:hover {
      background-color: #555;
    }
    footer {
      text-align: center;
      padding: 1rem 0;
      background-color: #333;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <div class="header-content">
      <img src="viswa.jpg" alt="Your Profile Picture" class="profile-picture">
      <h1>VISWADHARANI S</h1>
      <p>Web Developer</p>
    </div>
  </header>
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#resume">Resume</a></li>
    </ul>
  </nav>
  <section id="about">
    <div class="section-content">
      <h2>About Me</h2>
      <p>I'm a web development expert who is passionate about creating dynamic and user-friendly websites. I'm driven by the desire to craft high-performance web applications that enhance user experience and provide seamless digital solutions.</p>
    </div>
  </section>
  <section id="education">
    <div class="section-content">
      <h2>Education</h2>
      <p>Baharathiyar University</p>
    </div>
  </section>
  <section id="skills">
    <div class="section-content">
      <h2>Skills</h2>
      <ul>
        <li>Python</li>
        <li>C</li>
        <li>Java</li>
        <li>C++</li>
        <li>JavaScript</li>
      </ul>
    </div>
  </section>
  <section id="projects">
    <div class="section-content">
      <h2>Projects</h2>
      <ul>
        <li><a href="weather server.html">Weather Report</a></li>
        <li><a href="#">Cloud Security IBM</a></li>
        <li><a href="#">Ai Chatbot</a></li>
        <li><a href="Contact.html">Contact Request</a>
          </section>
          <section id="resume">

    

   <div class="section-content">
            <center>
            <h2>Resume</h2>
            <a href="viswa.pdf" target="_blank" class="download-button">Download CV</a>
        </center>
        </div>
        
  </section>

  <footer>
        <p>&copy; 2025 VISWATHARANI.S </p>
    </footer>

   <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^=""]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
   </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfoilo</title>
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700&display=swap">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
  <style>
    body {
      font-family: 'Open Sans', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 2rem 0;
    }
    .header-content {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 20px;
    }
    .header-content h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }
    .profile-picture {
      width: 150px;
      height: 150px;
      border-radius: 50%;
      object-fit: cover;
      margin: 20px auto;
    }
    nav {
      background-color: #333;
      color: #fff;
      text-align: center;
      padding: 1rem 0;
    }
    nav ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
    }
    nav ul li {
      display: inline-block;
      margin: 0 20px;
    }
    nav ul li a {
      text-decoration: none;
      color: #fff;
    }
    .section-content {
      background-color: #fff;
      padding: 2rem;
      margin: 2rem auto;
      max-width: 800px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .download-button {
      background-color: #333;
      color: #fff;
      padding: 0.5rem 1rem;
      text-decoration: none;
      border-radius: 20px;
      display: inline-block;
      margin-top: 10px;
    }
    .download-button:hover {
      background-color: #555;
    }
    footer {
      text-align: center;
      padding: 1rem 0;
      background-color: #333;
      color: #fff;
    }
  </style>
</head>
<body>
  <header>
    <div class="header-content">
      <img src="viswa.jpg" alt="Your Profile Picture" class="profile-picture">
      <h1>VISWADHARANI S</h1>
      <p>Web Developer</p>
    </div>
  </header>
  <nav>
    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#resume">Resume</a></li>
    </ul>
  </nav>
  <section id="about">
    <div class="section-content">
      <h2>About Me</h2>
      <p>I'm a web development expert who is passionate about creating dynamic and user-friendly websites. I'm driven by the desire to craft high-performance web applications that enhance user experience and provide seamless digital solutions.</p>
    </div>
  </section>
  <section id="education">
    <div class="section-content">
      <h2>Education</h2>
      <p>Baharathiyar University</p>
    </div>
  </section>
  <section id="skills">
    <div class="section-content">
      <h2>Skills</h2>
      <ul>
        <li>Python</li>
        <li>C</li>
        <li>Java</li>
        <li>C++</li>
        <li>JavaScript</li>
      </ul>
    </div>
  </section>
  <section id="projects">
    <div class="section-content">
      <h2>Projects</h2>
      <ul>
        <li><a href="weather server.html">Weather Report</a></li>
        <li><a href="#">Cloud Security IBM</a></li>
        <li><a href="#">Ai Chatbot</a></li>
        <li><a href="Contact.html">Contact Request</a>
          </section>
          <section id="resume">

    

   <div class="section-content">
            <center>
            <h2>Resume</h2>
            <a href="viswa.pdf" target="_blank" class="download-button">Download CV</a>
        </center>
        </div>
        
  </section>

   <footer>
        <p>&copy; 2025 VISWATHARANI.S </p>
    </footer>

  <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^=""]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }      });
    });
   </script>
</body>
</html>
