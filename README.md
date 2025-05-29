<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ydl Anne Fatima B. Aspili | Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #fff8dc;
      color: #333;
    }

    header, footer {
      background-color: #ffde59;
      color: #000;
      text-align: center;
      padding: 1rem;
    }

    nav {
      background-color: #fff176;
      padding: 0.5rem 1rem;
      position: fixed;
      top: 0;
      width: 100%;
      z-index: 1000;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav a {
      margin: 0 1rem;
      color: #000;
      text-decoration: none;
      font-weight: bold;
    }

    .menu {
      display: flex;
    }

    .hamburger {
      display: none;
      font-size: 1.5rem;
      cursor: pointer;
    }

    .container {
      padding: 6rem 2rem 2rem; /* to make space for fixed nav */
      max-width: 900px;
      margin: auto;
    }

    img {
      max-width: 100%;
      height: auto;
    }

    section {
      margin-bottom: 2rem;
    }

    h2 {
      color: #d4af37;
    }

    @media (max-width: 768px) {
      .menu {
        display: none;
        flex-direction: column;
        width: 100%;
      }

      .menu.active {
        display: flex;
        background-color: #fff176;
        padding: 1rem 0;
      }

      .hamburger {
        display: block;
      }

      nav {
        flex-wrap: wrap;
      }

      nav a {
        margin: 0.5rem 0;
      }
    }
  </style>
  <script>
    function toggleMenu() {
      const menu = document.querySelector('.menu');
      menu.classList.toggle('active');
    }
  </script>
</head>
<body>
  <header>
    <h1>Ydl Anne Fatima B. Aspili</h1>
    <p>I'm a student who loves to learn and explore new ideas. I'm usually fun and always cracking jokes, but I get serious when it comes to academics and schoolwork.</p>
  </header>

  <nav>
    <div class="hamburger" onclick="toggleMenu()">☰</div>
    <div class="menu">
      <a href="#about">About Me</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <main class="container">
    <section id="about">
      <h2>About Me</h2>
      <p>I'm a fun and outgoing student who enjoys making people laugh and creating a positive vibe wherever I go. I love acting—it’s one of my favorite ways to express myself and connect with others. Whether I’m performing on stage or just joking around with friends, acting gives me confidence and helps boost my creativity. While I’m usually playful, I know when to be serious, especially when it comes to academics. I’m responsible, focused, and always put effort into my schoolwork. I work well with others, communicate clearly, and stay organized when working on group projects or tasks. My mix of humor, creativity, and dedication helps me grow as a student and as a person, both inside and outside the classroom.</p>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <h3>Examining the Relationship of Student Leaders’ Leadership Styles and Their Behaviors in the Classroom</h3>
      <p>This research project focused on how different leadership styles—like transformational, servant, and autocratic—affect the behavior of student leaders in classroom settings. We looked at how personality traits such as openness, extraversion, conscientiousness, and neuroticism influence leadership preferences. I contributed to data gathering, analysis, and writing. One of the key findings showed that servant leadership had a positive impact on classroom dynamics and student engagement. This study deepened my understanding of effective leadership and the importance of adapting styles to support a better learning environment.</p>
      <img src="Screenshot 2025-05-29 7.04.26 PM.png" alt="Research Project Screenshot">

      <h3>“CheeSa Ba?” – Banana Cheese Balls</h3>
      <p>This was a hands-on business project I worked on with fellow students, where we developed a unique product: banana cheese balls. Inspired by the abundance of bananas in Ilocos Norte and their popularity in Filipino snacks, we created CheeSa Ba?—a healthier, budget-friendly, and locally loved food item. I was involved in branding, marketing, and planning the sales strategy. Our team focused on sustainability, affordability, and quality. With a marketing budget of ₱50,000 and a set markup of 20%, we aimed for strong growth and real-world learning in entrepreneurship. The project was a great way to apply creativity, teamwork, and business planning skills.</p>
      <img src="1bd9922a-19ce-4738-ae5e-bacfc31ac2f3.jpg" alt="CheeSa Ba Logo">
    </section>

    <section id="contact">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:aspilianne@gmail.com">aspilianne@gmail.com</a></p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Ydl Anne Fatima B. Aspili</p>
  </footer>
</body>
</html>
