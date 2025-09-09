!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Charity: Water Landing Page</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #333;
      line-height: 1.6;
      background-color: #78a8ba;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }


    header {
      background: #78a8ba;
      color: #fff;
      padding: 80px 20px 40px;
      position: relative;
    }


    .nav-bar-container {
      background-color: #1b3061;
      padding: 15px 20px;
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 3px solid #fff;
    }


    .logo {
      max-width: 180px;
      height: auto;
      background: #fff;
      padding: 5px;
      border-radius: 5px;
    }


    .nav-links {
      display: flex;
      gap: 10px;
      align-items: center;
    }


    .dropdown {
      position: relative;
    }


    .dropbtn {
      background-color: #1b3061;
      color: #fff;
      padding: 8px 15px;
      font-size: 14px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
    }


    .dropbtn:hover {
      background-color: #fff;
      color: #333;
    }


    .dropdown-content {
      display: none;
      position: absolute;
      background-color: #78a8ba;
      min-width: 200px;
      padding: 10px;
      border-radius: 8px;
      box-shadow: 0 8px 16px rgba(0,0,0,0.2);
      top: 40px;
      right: 0;
      z-index: 1;
    }


    .dropdown-content p, .dropdown-content a {
      margin: 0;
      font-size: 14px;
      color: #fff;
      text-decoration: none;
      display: block;
      padding: 5px 0;
    }


    .dropdown-content a:hover {
      text-decoration: underline;
    }


    .dropdown:hover .dropdown-content {
      display: block;
    }


    header h1 {
      font-size: 2.5em;
      margin-top: 40px;
      margin-bottom: 10px;
      color: #fff;
      text-align: center;
    }


    header p {
      font-size: 1.1em;
      margin-bottom: 10px;
      color: #d9d9de;
      font-style: italic;
      text-align: center;
    }


    .cta-container {
      text-align: center;
      margin-top: 10px;
    }


    header a.cta-btn {
      background: #1b3061;
      color: #fff;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      border: 2px solid #fff;
      transition: background 0.3s, color 0.3s;
      display: inline-block;
    }


    header a.cta-btn:hover {
      background: #fff;
      color: #333;
    }


    .impact-section {
      background-color: #78a8ba;
      text-align: center;
      padding: 40px 20px;
      flex: 1;
    }


    .impact-section h2 {
      color: #fff;
      margin-bottom: 15px;
    }


    .impact-section p {
      color: #d9d9de;
      font-size: 1em;
      margin-bottom: 20px;
    }


    .impact-images {
      display: flex;
      justify-content: center;
      gap: 15px;
      flex-wrap: wrap;
    }


    .impact-images img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.3);
    }


    footer {
      background: #78a8ba;
      color: #fff;
      text-align: center;
      padding: 0;
      margin-top: auto;
    }


    .footer-bar {
      background-color: #1b3061;
      padding: 15px 20px;
      text-align: center;
      border-top: 3px solid #fff;
      width: 100%;
    }


    @media (max-width: 768px) {
      .nav-bar-container {
        flex-direction: column;
        align-items: center;
      }


      .nav-links {
        flex-direction: column;
        width: 100%;
        align-items: center;
      }


      .dropbtn {
        width: 100%;
        text-align: center;
      }
    }
  </style>
</head>
<body>


  <header>
    <div class="nav-bar-container">
      <img src="photo.png" alt="Charity Water Logo" class="logo">
      <div class="nav-links">
        <div class="dropdown">
          <button class="dropbtn">About Us</button>
          <div class="dropdown-content">
            <p>charity: water is a nonprofit organization on a mission to bring clean and safe drinking water to every person on the planet. Founded in 2006, we believe clean water changes everything — improving health, boosting education, and unlocking economic opportunity.</p>
          </div>
        </div>
        <div class="dropdown">
          <button class="dropbtn">Features</button>
          <div class="dropdown-content">
            <p>Brought Clean Water: They’ve helped bring clean water to millions worldwide.</p>
            <p>100% Model: All public donations go directly to clean water projects.</p>
          </div>
        </div>
        <div class="dropdown">
          <button class="dropbtn">Get Started</button>
          <div class="dropdown-content">
            <p>With just $5–$10, your voice and your campus community can create lasting change by bringing clean water, health, and opportunity to millions worldwide.</p>
            <a href="#">Join the Ripple Effect</a>
          </div>
        </div>
      </div>
    </div>
    <h1>Be the Generation That Ends the Water Crisis</h1>
    <p><em>With just $5–$10, your voice and your campus community can create lasting change by bringing clean water, health, and opportunity to millions worldwide.</em></p>
    <div class="cta-container">
      <a href="#" class="cta-btn">Join the Ripple Effect</a>
    </div>
  </header>


  <section class="impact-section">
    <h2>Impact & Results</h2>
    <p>Your fundraising and donations make real change possible. Together, we’re bringing clean water, health, and opportunity to communities worldwide.</p>
    <div class="impact-images">
      <img src="child drinking.jpg" alt="Child drinking clean water">
      <img src="Fauct with Water.jpg" alt="Filling water container">
    </div>
  </section>


  <footer>
    <p>&copy; 2025 charity: water. All Rights Reserved.</p>
    <div class="footer-bar"></div>
  </footer>


</body>
</html>



