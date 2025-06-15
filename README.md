<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Naif Khan | Data Scientist Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: #f9f9f9;
      color: #333;
      line-height: 1.6;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      background-color: #111;
      color: #fff;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #aaa;
    }

    .section {
      padding: 3rem 1rem;
      max-width: 1000px;
      margin: 0 auto;
    }

    .section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      color: #222;
    }

    .skills, .projects, .contact {
      margin-bottom: 2rem;
    }

    .skills ul {
      list-style: none;
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }

    .skills li {
      background: #ddd;
      padding: 0.5rem 1rem;
      border-radius: 5px;
      font-weight: 600;
    }

    .project {
      background: #fff;
      padding: 1.5rem;
      border: 1px solid #eee;
      border-radius: 10px;
      margin-bottom: 1.5rem;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.05);
    }

    .project h3 {
      margin-bottom: 0.5rem;
    }

    .contact form {
      display: flex;
      flex-direction: column;
      gap: 1rem;
    }

    .contact input, .contact textarea {
      padding: 0.8rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }

    .contact button {
      background: #111;
      color: #fff;
      border: none;
      padding: 0.8rem;
      border-radius: 5px;
      cursor: pointer;
    }

    footer {
      background: #222;
      color: #aaa;
      text-align: center;
      padding: 1rem;
      margin-top: auto;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }

      .section h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>

<body>
  <header>
    <h1>Naif Khan</h1>
    <p>Aspiring Data Scientist | Python • SQL • Machine Learning</p>
  </header>

  <section class="section skills">
    <h2>Skills</h2>
    <ul>
      <li>Python</li>
      <li>Pandas</li>
      <li>NumPy</li>
      <li>Scikit-learn</li>
      <li>SQL</li>
      <li>Data Visualization</li>
      <li>Power BI</li>
      <li>Linux</li>
      <li>Git & GitHub</li>
    </ul>
  </section>

  <section class="section projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Customer Segmentation</h3>
      <p>Applied K-Means clustering on mall customer data to segment users based on spending habits and annual income.</p>
    </div>
    <div class="project">
      <h3>House Price Prediction</h3>
      <p>Used regression models to predict housing prices using scikit-learn, with feature engineering and model evaluation.</p>
    </div>
    <div class="project">
      <h3>EDA on COVID-19 Data</h3>
      <p>Exploratory Data Analysis using pandas, seaborn, and matplotlib to extract insights from global COVID-19 cases.</p>
    </div>
  </section>

  <section class="section contact">
    <h2>Contact</h2>
    <form action="mailto:beingnaif@gmail.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    &copy; 2025 Naif Khan | Built with 💡 and ☕
  </footer>
</body>

</html>
