# Kidswhocode<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>KidsWhoCode | St Francis Adult College</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #003366;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #00509e;
      overflow: hidden;
    }
    nav a {
      float: left;
      display: block;
      color: white;
      text-align: center;
      padding: 14px 16px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #003366;
    }
    section {
      padding: 20px;
    }
    .course {
      background-color: white;
      padding: 15px;
      margin-bottom: 10px;
      border-left: 5px solid #00509e;
    }
    form {
      background: white;
      padding: 20px;
      margin-top: 20px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    input, textarea, select {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      margin-bottom: 20px;
    }
    button {
      padding: 10px 20px;
      background-color: #00509e;
      color: white;
      border: none;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>KidsWhoCode Program</h1>
  <p>Hosted at St Francis Adult College, Gugulethu</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#courses">Courses</a>
  <a href="#register">Register</a>
  <a href="#resources">Resources</a>
  <a href="#faq">FAQ</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h2>About Us</h2>
  <p>KidsWhoCode is an initiative by passionate educators and developers from Gugulethu, led by Thulani Matyeni and team. We teach real coding skills (HTML, CSS, JavaScript, Python) to adults and youth at St Francis Adult College. Our goal is to build the future tech leaders of Africa through coding education and practical application.</p>
</section>

<section id="courses">
  <h2>Courses We Offer</h2>
  <div class="course">
    <h3>HTML & CSS Basics</h3>
    <p>Learn how websites are structured and styled using HTML and CSS.</p>
  </div>
  <div class="course">
    <h3>JavaScript Fundamentals</h3>
    <p>Bring interactivity to your websites using JavaScript — events, forms, and logic.</p>
  </div>
  <div class="course">
    <h3>Python Programming</h3>
    <p>Build scripts, automation tools, and even basic apps using Python.</p>
  </div>
</section>

<section id="register">
  <h2>Student Registration</h2>
  <form onsubmit="event.preventDefault(); alert('Registration Submitted. Thank you!');">
    <label for="fullname">Full Name:</label>
    <input type="text" id="fullname" required>

    <label for="email">Email Address:</label>
    <input type="email" id="email" required>

    <label for="age">Age:</label>
    <input type="number" id="age" required>

    <label for="course">Select Course:</label>
    <select id="course">
      <option>HTML & CSS Basics</option>
      <option>JavaScript Fundamentals</option>
      <option>Python Programming</option>
    </select>

    <label for="message">Why do you want to learn coding?</label>
    <textarea id="message"></textarea>

    <button type="submit">Submit Registration</button>
  </form>
</section>

<section id="resources">
  <h2>Student Resources</h2>
  <ul>
    <li><a href="https://www.freecodecamp.org/" target="_blank">FreeCodeCamp</a></li>
    <li><a href="https://www.codecademy.com/" target="_blank">Codecademy</a></li>
    <li><a href="https://developer.mozilla.org/en-US/" target="_blank">MDN Web Docs</a></li>
    <li><a href="https://dash.generalassemb.ly/" target="_blank">General Assembly Dash</a></li>
    <li><a href="https://www.w3schools.com/" target="_blank">W3Schools</a></li>
  </ul>
</section>

<section id="faq">
  <h2>Frequently Asked Questions</h2>
  <h3>Do I need a laptop?</h3>
  <p>Having a laptop helps, but the school has a few computers available during class sessions.</p>
  <h3>Can I learn even if I’ve never coded before?</h3>
  <p>Yes! We start from the very basics and guide you step by step.</p>
  <h3>How long are the courses?</h3>
  <p>Each course runs for approximately 10 weeks with 2 sessions per week.</p>
</section>

<section id="contact">
  <h2>Contact Us</h2>
  <p>📍 St Francis Adult College, Gugulethu, Cape Town</p>
  <p>📞 WhatsApp: 072 XXX XXXX</p>
  <p>📧 Email: kidswhocode@syug.org.za</p>
</section>

<footer>
  <p>&copy; 2025 KidsWhoCode | SYUG Movement | Built with ❤️ in Gugulethu</p>
</footer>

</body>
</html>

