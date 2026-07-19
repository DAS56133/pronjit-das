DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Das Pronjit - Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f4f8;
      text-align: center;
      margin: 0; padding:0;
    }

    header {
      background-color: #0d6efd;
      color: white;
      padding: 40px 20px;
    }

    header h1 {margin:0; font-size:2.5em;}
    header p {margin-top:10px; font-size:1.2em;}

    .motivation {
      background-color: #e7f1ff;
      padding: 20px; border-radius:10px;
      margin: 30px auto; max-width:700px;
      color:#0d2f6d; line-height:1.6;
    }

    h2 {
      color:#0d6efd;
      border-bottom:2px solid #0d6efd;
      display:inline-block; padding-bottom:5px;
      margin-bottom:15px;
    }

    ul.skills, ul.languages {
      list-style:none; padding:0; display:flex; flex-wrap:wrap; justify-content:center;
    }

    ul.skills li, ul.languages li {
      background:#fff; border:1px solid #0d6efd; color:#0d6efd;
      margin:5px 10px; padding:10px 20px; border-radius:8px;
      font-weight:bold;
    }

    button {
      padding:12px 30px; font-size:18px;
      background-color:#0d6efd; color:white;
      border:none; border-radius:5px; cursor:pointer; transition:0.3s;
      margin-top:20px;
    }

    button:hover {background-color:#084298;}

    #contactInfo {
      margin-top:20px;
      display:none;
      font-size:18px; color:#333;
      background:#e7f1ff; padding:20px; border-radius:10px;
      max-width:400px; margin-left:auto; margin-right:auto;
    }

    #contactInfo a {color:#0d6efd; text-decoration:none;}
    #contactInfo a:hover {text-decoration:underline;}

    footer {
      margin-top:50px; padding:20px;
      background-color:#0d6efd; color:white;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1>Das Pronjit</h1>
    <p>Web Developer & Designer | Based in Paris, France</p>
  </header>

  <!-- About Me -->
  <section class="motivation">
    <h2>About Me</h2>
    <p>Hello! I am a passionate web developer with expertise in HTML, CSS, and JavaScript. 
    I combine technical skills, creativity, and business knowledge to create professional, interactive, and user-friendly websites. 
    I speak multiple languages including Bengali, English, Hindi, Urdu, and French. 
    My goal is to transform ideas into real projects and deliver high-quality solutions.</p>
  </section>

  <!-- Skills -->
  <section>
    <h2>Skills</h2>
    <ul class="skills">
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
      <li>Excel & Data Management</li>
      <li>Photoshop</li>
      <li>Business & Sales Knowledge</li>
    </ul>
  </section>

  <!-- Languages -->
  <section>
    <h2>Languages</h2>
    <ul class="languages">
      <li>Bengali</li>
      <li>English</li>
      <li>Hindi</li>
      <li>Urdu</li>
      <li>French</li>
    </ul>
  </section>

  <!-- Contact -->
  <section>
    <button id="contactBtn">Contact</button>
    <div id="contactInfo">
      <p><strong>Name:</strong> Das Pronjit</p>
      <p><strong>Phone:</strong> <a href="tel:+33758843607">+33 7 58 84 36 07</a></p>
      <p><strong>Email:</strong> <a href="mailto:Pronjitdas98@gmail.com">Pronjitdas98@gmail.com</a></p>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Das Pronjit | Portfolio
  </footer>

  <script>
    const btn = document.getElementById('contactBtn');
    const contactInfo = document.getElementById('contactInfo');

    btn.addEventListener('click', () => {
      contactInfo.style.display = (contactInfo.style.display === "block") ? "none" : "block";
    });
  </script>

</body>
</html>
