<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>FillMate — AI Form Autofiller</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background-color: #fff;
      color: #000;
      line-height: 1.6;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 100px 20px 60px;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 20px;
      color: #000;
    }

    h1 span {
      color: #7A3FFF;
    }

    p {
      color: #333;
      max-width: 700px;
      margin: 0 auto 40px;
      font-size: 1.2rem;
    }

    form {
      display: flex;
      justify-content: center;
      gap: 10px;
      flex-wrap: wrap;
    }

    input[type="email"] {
      padding: 15px 20px;
      border: 2px solid #7A3FFF;
      border-radius: 8px;
      font-size: 1rem;
      flex: 1;
      min-width: 250px;
      outline: none;
    }

    button {
      padding: 15px 30px;
      border: none;
      border-radius: 8px;
      background-color: #7A3FFF;
      color: #fff;
      font-size: 1rem;
      font-weight: 600;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    button:hover {
      background-color: #5d2fcc;
    }

    section {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 80px 10%;
      flex-wrap: wrap;
      border-bottom: 1px solid #eee;
    }

    .feature-text {
      flex: 1 1 45%;
      padding: 20px;
    }

    .feature-text h2 {
      color: #000;
      font-size: 2rem;
      margin-bottom: 15px;
    }

    .feature-text span {
      color: #7A3FFF;
      font-weight: 600;
    }

    .feature-text p {
      color: #444;
      font-size: 1.1rem;
    }

    .feature-image {
      flex: 1 1 45%;
      text-align: center;
    }

    .feature-image img {
      width: 100%;
      max-width: 400px;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
    }

    footer {
      text-align: center;
      padding: 40px 20px;
      color: #555;
      font-size: 0.9rem;
    }

    @media (max-width: 900px) {
      section {
        flex-direction: column;
      }
      .feature-image, .feature-text {
        flex: 1 1 100%;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Meet <span>FillMate</span></h1>
    <p>FillMate automatically fills Google Forms and Microsoft Forms using AI. It learns from how <span>you</span> answer forms and becomes smarter every time. Join the waitlist below to get early access.</p>
    <form action="https://formspree.io/f/myzbqyng" method="POST">
      <input type="email" name="email" placeholder="Enter your email" required>
      <button type="submit">Join Waitlist</button>
    </form>
  </header>

  <section>
    <div class="feature-image">
      <img src="img1.jpg" alt="Learning Feature">
    </div>
    <div class="feature-text">
      <h2><span>Smart Learning</span></h2>
      <p>FillMate observes how you fill forms and automatically adapts to your preferences. The more forms you complete, the more accurate it becomes in understanding your style and choices.</p>
    </div>
  </section>

  <section>
    <div class="feature-text">
      <h2><span>AI-Powered Answers</span></h2>
      <p>For open-ended questions, FillMate uses advanced AI to craft responses that sound natural, relevant, and human-like — saving you time and effort on long answers.</p>
    </div>
    <div class="feature-image">
      <img src="img2.jpg" alt="AI Feature">
    </div>
  </section>

  <section>
    <div class="feature-image">
      <img src="img3.jpg" alt="Context Awareness Feature">
    </div>
    <div class="feature-text">
      <h2><span>Context Awareness</span></h2>
      <p>FillMate understands the purpose of each form. Whether it’s a feedback form, an application, or a survey, it tailors responses accordingly for maximum accuracy.</p>
    </div>
  </section>

  <footer>
    © 2025 FillMate. All rights reserved.
  </footer>
</body>
</html>
