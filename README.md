<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Department of Economics</title>
  <style>
    :root {
      --primary: #3399ff;
      --light: #f3f9ff;
      --dark: #003f66;
    }
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: var(--light);
      color: var(--dark);
      line-height: 1.6;
    }
    header {
      background: var(--primary);
      color: white;
      padding: 1rem 2rem;
      text-align: center;
    }
    nav {
      background: white;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 0.5rem 0;
      border-bottom: 1px solid #ddd;
    }
    nav a {
      margin: 0.5rem 1rem;
      text-decoration: none;
      color: var(--dark);
      font-weight: bold;
    }
    .hero {
      background: var(--primary);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    .container {
      max-width: 1000px;
      margin: 2rem auto;
      padding: 1rem;
    }
    .section {
      margin-bottom: 2rem;
    }
    h2 {
      color: var(--primary);
      border-left: 5px solid var(--primary);
      padding-left: 0.5rem;
      margin-bottom: 1rem;
    }
    .calendar, .blog-posts {
      display: grid;
      gap: 1rem;
    }
    .event, .post {
      background: white;
      padding: 1rem;
      border-left: 5px solid var(--primary);
      box-shadow: 0 2px 6px rgba(0,0,0,0.05);
      border-radius: 4px;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background: #e1f1ff;
      font-size: 0.9rem;
    }

    @media(max-width: 600px) {
      nav a {
        margin: 0.5rem;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Department of Economics</h1>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#programs">Programs</a>
  <a href="#faculty">Faculty</a>
  <a href="#calendar">Events</a>
  <a href="#blog">Blog</a>
  <a href="#contact">Contact</a>
</nav>

<div class="hero">
  <h2>Welcome to the Department of Economics</h2>
  <p>Inspiring futures through economics education and research.</p>
</div>

<div class="container">
  <section id="about" class="section">
    <h2>About the Department</h2>
    <p>Our department is committed to academic excellence, research, and equipping students with critical skills for today's economy. We offer BSS and MSS programs and work with passionate faculty and engaged learners.</p>
  </section>

  <section id="programs" class="section">
    <h2>Programs Offered</h2>
    <ul>
      <li><strong>BSS in Economics</strong> – Undergraduate program with applied economics focus</li>
      <li><strong>MSS in Economics</strong> – Postgraduate program with research and advanced theory</li>
    </ul>
  </section>

  <section id="calendar" class="section">
    <h2>Upcoming Events</h2>
    <div class="calendar">
      <div class="event">
        <strong>📅 June 25, 2025:</strong> Orientation Program for First Year
      </div>
      <div class="event">
        <strong>📅 July 10, 2025:</strong> Department Seminar on “Global Inflation Trends”
      </div>
    </div>
  </section>

  <section id="blog" class="section">
    <h2>Department Blog</h2>
    <div class="blog-posts">
      <div class="post">
        <h3>🎓 Convocation 2025 Highlights</h3>
        <p>The department celebrated the success of its graduating batch in a grand event. See photos and speeches...</p>
      </div>
      <div class="post">
        <h3>📊 New Research Publication</h3>
        <p>Faculty member Dr. Rahman publishes paper on “Trade Dynamics in South Asia” in Economic Journal.</p>
      </div>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Email: econ@youruniversity.edu</p>
    <p>Phone: +8801XXXXXXXXX</p>
    <p>Location: Academic Building B, 2nd Floor</p>
  </section>
</div>

<footer>
  &copy; 2025 Department of Economics | Designed with ❤️ in Sky Blue
</footer>

</body>
</html>
