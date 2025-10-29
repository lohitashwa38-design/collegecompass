<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>College Compass | SJCE Navigation System</title>
  <style>
    body {
      margin: 0;
      font-family: "Poppins", sans-serif;
      background-color: #0d1117;
      color: #e6edf3;
      text-align: center;
    }

    header {
      background-color: #161b22;
      padding: 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    h1 {
      margin: 0;
      color: #58a6ff;
      font-size: 2em;
      letter-spacing: 2px;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: #58a6ff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: 0.3s;
    }

    nav a:hover, nav a.active {
      color: #1f6feb;
      text-decoration: underline;
    }

    .hero {
      padding: 100px 20px;
      background: linear-gradient(180deg, #0d1117, #161b22);
      border-bottom: 1px solid #21262d;
    }

    .hero h2 {
      font-size: 2em;
      color: #58a6ff;
    }

    .hero p {
      max-width: 700px;
      margin: 20px auto;
      line-height: 1.6;
      font-size: 1.1em;
      color: #c9d1d9;
    }

    .btn {
      display: inline-block;
      background: #238636;
      color: white;
      padding: 12px 25px;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      background: #2ea043;
      transform: scale(1.05);
    }

    footer {
      background: #161b22;
      padding: 15px;
      color: #8b949e;
      font-size: 0.9em;
      border-top: 1px solid #21262d;
    }

    .about {
      padding: 60px 20px;
      background-color: #0d1117;
    }

    .about h3 {
      color: #58a6ff;
      font-size: 1.5em;
      margin-bottom: 15px;
    }

    .about p {
      max-width: 800px;
      margin: auto;
      color: #c9d1d9;
      line-height: 1.7;
    }
  </style>
</head>
<body>

  <header>
    <h1>COLLEGE COMPASS</h1>
    <nav>
      <a href="cc.html" class="active">Home</a>
      <a href="navi.html">Navigator</a>
      <a href="contact.html">Queries & Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to College Compass</h2>
    <p>
      <strong>College Compass</strong> is your personal digital navigator for <b>St. Joseph’s College of Engineering</b>, OMR, Chennai.  
      Explore your campus with real-time GPS tracking and get turn-by-turn routes to any location — from labs and lecture halls to hostels and the library.
    </p>
    <a href="navi.html" class="btn">Start Navigating 🚀</a>
  </section>

  <section class="about">
    <h3>Why College Compass?</h3>
    <p>
      Finding your way around a large campus can be confusing — especially for new students or visitors.
      College Compass simplifies this with <strong>live location tracking</strong> and <strong>interactive navigation</strong>
      across all key points on campus including the Auditorium, Labs, Hostel, and Department Blocks.
    </p>
  </section>

  <footer>
    <p>© 2025 College Compass | St. Joseph’s College of Engineering</p>
  </footer>

</body>
</html>
