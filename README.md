# MohanedAdil.github.io
my Data Analytics Portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mohaned Adil | Data Analyst</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #07101f;
      color: #ffffff;
    }

    header {
      background-color: #0d1a2d;
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    header h2 {
      color: #52a8ff;
      margin: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
    }

    .hero {
      padding: 100px 8%;
      text-align: center;
    }

    .hero h1 {
      font-size: 48px;
      margin-bottom: 15px;
    }

    .hero h1 span {
      color: #52a8ff;
    }

    .hero p {
      color: #a7b7cc;
      font-size: 18px;
      line-height: 1.8;
    }

    .button {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background-color: #267fe0;
      color: white;
      text-decoration: none;
      border-radius: 8px;
    }

    @media (max-width: 600px) {
      .hero {
        padding: 70px 6%;
      }

      .hero h1 {
        font-size: 34px;
      }

      header {
        padding: 18px 6%;
      }

      nav a {
        margin-left: 8px;
        font-size: 13px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h2>Mohaned.Data</h2>

    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
    </nav>
  </header>

  <section class="hero" id="about">
    <h1>Hello, I'm <span>Mohaned Adil</span></h1>

    <p>
      Aspiring Data Analyst<br>
      I turn data into insights that support better decisions.
    </p>

    <a href="#projects" class="button">Explore My Projects</a>
  </section>

  <section class="hero" id="skills">
    <h1>My <span>Skills</span></h1>
    <p>Excel | Power BI | SQL | Data Analysis</p>
  </section>

  <section class="hero" id="projects">
    <h1>My <span>Projects</span></h1>
    <p>Sales Analysis | Business Intelligence | Dashboards</p>
  </section>

</body>
</html>
