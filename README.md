
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The 3-Minute Mental Reset for Overworked Men</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    :root {
      --accent: #ff9966;   /* light orange */
      --accent2: #ff5e62;  /* pinkish sunset */
      --text-dark: #333;
      --text-light: #555;
      --bg-light: #fff9f7;
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: linear-gradient(135deg, var(--accent2), var(--accent));
      background-attachment: fixed;
      color: var(--text-dark);
      overflow-x: hidden;
    }

    /* Smooth fade-in animation */
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* Gradient Motion Effect */
    @keyframes gradientFlow {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background: linear-gradient(-45deg, #ffecd2, #fcb69f, #ff9a9e, #fad0c4);
      background-size: 300% 300%;
      animation: gradientFlow 15s ease infinite;
      z-index: -1;
      opacity: 0.7;
    }

    header, section {
      padding: 60px 20px;
      max-width: 900px;
      margin: 0 auto;
      text-align: center;
      animation: fadeIn 1.2s ease forwards;
    }

    h1 {
      font-size: 2.2rem;
      font-weight: 700;
      color: #2d2d2d;
      margin-bottom: 20px;
    }

    h2 {
      font-size: 1.2rem;
      font-weight: 500;
      color: #3e3e3e;
      margin-bottom: 30px;
    }

    .cta {
      background-color: var(--accent2);
      background: linear-gradient(90deg, var(--accent2), var(--accent));
      color: #fff;
      font-weight: 600;
      padding: 14px 36px;
      border: none;
      border-radius: 50px;
      cursor: pointer;
      font-size: 1rem;
      transition: all 0.3s ease;
      box-shadow: 0 6px 15px rgba(255, 94, 98, 0.3);
    }

    .cta:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(255, 94, 98, 0.4);
    }

    .benefits {
      margin-top: 40px;
      text-align: left;
      background-color: rgba(255, 255, 255, 0.4);
      backdrop-filter: blur(8px);
      border-radius: 12px;
      padding: 30px;
    }

    .benefits ul {
      list-style: none;
      padding: 0;
      margin: 0;
    }

    .benefits li {
      margin: 15px 0;
      position: relative;
      padding-left: 25px;
      color: #333;
    }

    .benefits li::before {
      content: "•";
      position: absolute;
      left: 0;
      color: var(--accent2);
      font-size: 1.5rem;
      line-height: 1;
    }

    .credibility {
      margin: 60px auto;
      background-color: rgba(255, 255, 255, 0.5);
      border-radius: 12px;
      padding: 40px 25px;
      color: #333;
    }

    .badge {
      display: inline-block;
      margin-top: 15px;
      padding: 8px 18px;
      border-radius: 25px;
      border: 1px solid var(--accent2);
      color: var(--accent2);
      font-weight: 600;
      font-size: 0.9rem;
      text-transform: uppercase;
      letter-spacing: 0.05em;
    }

    .form-section {
      background-color: rgba(255, 255, 255, 0.7);
      backdrop-filter: blur(10px);
      border-radius: 15px;
      padding: 60px 25px;
      box-shadow: 0 8px 20px rgba(255, 94, 98, 0.2);
      animation: fadeIn 1.5s ease forwards;
    }

    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      max-width: 400px;
      margin: 0 auto;
    }

    input {
      padding: 14px;
      border-radius: 8px;
      border: 1px solid #ddd;
      font-size: 1rem;
      color: #333;
      background-color: #fff;
      transition: border-color 0.3s;
    }

    input:focus {
      outline: none;
      border-color: var(--accent2);
    }

    .microcopy {
      font-size: 0.85rem;
      color: #555;
      margin-top: 10px;
    }

    footer {
      margin-top: 60px;
      padding: 20px;
      text-align: center;
      font-size: 0.85rem;
      color: #444;
    }

    footer a {
      color: #444;
      text-decoration: none;
      margin: 0 6px;
    }

    @media (max-width: 600px) {
      h1 { font-size: 1.8rem; }
      h2 { font-size: 1rem; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Master the 3-Minute Mental Reset — Regain Focus and Calm in Any Moment</h1>
    <h2>Discover a fast, science-backed mental technique designed for overworked men who want peace without slowing down.</h2>
    <button class="cta" onclick="document.getElementById('lead-form').scrollIntoView({behavior: 'smooth'})">Get My Free Copy</button>
  </header>

  <section class="benefits">
    <ul>
      <li>Reset your mind in 3 minutes or less — no apps, no fluff.</li>
      <li>Backed by behavioral psychology and cognitive reframing.</li>
      <li>Perfect for busy men juggling work, goals, and life.</li>
      <li>Feel calm, clear, and in control — anytime you need it.</li>
    </ul>
  </section>

  <section class="credibility">
    <p>“This reset method is built on proven principles of psychology used by elite performers, entrepreneurs, and leaders to regain clarity and focus instantly.”</p>
    <div class="badge">Backed by Behavioral Science</div>
  </section>

  <section class="form-section" id="lead-form">
    <h2>Get Instant Access to the 3-Minute Mental Reset</h2>
    <form onsubmit="event.preventDefault(); alert('Form submitted! Connect to Firebase or Brevo for automation.');">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <button class="cta" type="submit">Send Me the Reset</button>
      <p class="microcopy">Join 1,000+ men mastering their focus and clarity — and get the free weekly ‘Performance Reset Newsletter.’</p>
    </form>
  </section>

  <footer>
    © 2025 Voice Forward Systems. All rights reserved. |
    <a href="#">Privacy Policy</a> |
    <a href="#">Terms</a>
  </footer>

</body>
</html>
