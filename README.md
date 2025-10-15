<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jane Doe - CV</title>
  <style>
    body {
      font-family: "Roboto", sans-serif;
      background-color: #f1f1f1;
      margin: 0;
      padding: 0;
    }

    .container {
      max-width: 1400px;
      margin: 20px auto;
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .left {
      flex: 1;
      min-width: 320px;
      max-width: 350px;
      background-color: #fff;
      border-radius: 6px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      overflow: hidden;
    }

    .left img {
      width: 100%;
      display: block;
    }

    .left .profile {
      padding: 20px;
    }

    .left h2 {
      margin: 10px 0;
      font-size: 24px;
    }

    .left p {
      color: #757575;
      margin: 5px 0;
    }

    hr {
      border: none;
      border-top: 1px solid #eee;
      margin: 15px 0;
    }

    .section h3 {
      color: #009688;
      font-size: 18px;
      margin-bottom: 10px;
    }

    .bar-container {
      width: 100%;
      background-color: #f1f1f1;
      border-radius: 20px;
      height: 15px;
      margin-bottom: 10px;
    }

    .bar {
      height: 15px;
      border-radius: 20px;
      background-color: #009688;
    }

    .bar.ps { width: 90%; }
    .bar.photo { width: 80%; }
    .bar.illus { width: 75%; }
    .bar.media { width: 50%; }

    .bar.eng { width: 100%; }
    .bar.span { width: 55%; }
    .bar.ger { width: 25%; }

    .right {
      flex: 2;
      min-width: 500px;
      display: flex;
      flex-direction: column;
      gap: 20px;
    }

    .card {
      background-color: #fff;
      border-radius: 6px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
      padding: 20px;
    }

    .card h2 {
      color: #009688;
      font-size: 24px;
      margin-bottom: 15px;
      display: flex;
      align-items: center;
    }

    .job, .edu {
      margin-bottom: 20px;
    }

    .job h3, .edu h3 {
      margin: 0;
      font-size: 18px;
      color: #333;
    }

    .date {
      color: #009688;
      font-weight: bold;
      margin-top: 5px;
    }

    .current {
      background-color: #009688;
      color: #fff;
      padding: 2px 6px;
      border-radius: 4px;
      font-size: 12px;
      margin-left: 5px;
    }

    .footer {
      text-align: center;
      background-color: #009688;
      color: white;
      padding: 20px;
      margin-top: 20px;
    }

    .footer a {
      color: white;
      margin: 0 8px;
      text-decoration: none;
    }

    .footer a:hover {
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
        align-items: center;
      }
      .right {
        width: 95%;
      }
    }
  </style>
</head>
<body>

<div class="container">
  <div class="left">
    <img src="https://www.w3schools.com/w3images/avatar_hat.jpg" alt="Avatar">
    <div class="profile">
      <h2>Jane Doe</h2>
      <p class="icon"> Designer</p>
      <p class="icon"> London, UK</p>
      <p class="icon">ex@mail.com</p>
      <p class="icon">1224435534</p>

      <hr>

      <div class="section">
        <h3>Skills</h3>
        <p>Adobe Photoshop</p>
        <div class="bar-container"><div class="bar ps"></div></div>
        <p>Photography</p>
        <div class="bar-container"><div class="bar photo"></div></div>
        <p>Illustrator</p>
        <div class="bar-container"><div class="bar illus"></div></div>
        <p>Media</p>
        <div class="bar-container"><div class="bar media"></div></div>
      </div>

      <hr>

      <div class="section">
        <h3>Languages</h3>
        <p>English</p>
        <div class="bar-container"><div class="bar eng"></div></div>
        <p>Spanish</p>
        <div class="bar-container"><div class="bar span"></div></div>
        <p>German</p>
        <div class="bar-container"><div class="bar ger"></div></div>
      </div>
    </div>
  </div>

  <div class="right">
    <div class="card work">
      <h2>Work Experience</h2>

      <div class="job">
        <h3>Front End Developer / w3schools.com</h3>
        <p class="date">Jan 2015 - <span class="current">Current</span></p>
        <p>Lorem ipsum dolor sit amet. Praesentium magnam consectetur vel in deserunt aspernatur est reprehenderit sunt hic. Nulla tempora soluta et odio, unde doloremque repellendus iure, iste.</p>
      </div>

      <div class="job">
        <h3>Web Developer / something.com</h3>
        <p class="date">Mar 2012 - Dec 2014</p>
        <p>Consectetur adipisicing elit. Praesentium magnam consectetur vel in deserunt aspernatur est reprehenderit sunt hic.</p>
      </div>

      <div class="job">
        <h3>Graphic Designer / designsomething.com</h3>
        <p class="date">Jun 2010 - Mar 2012</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
      </div>
    </div>

    <div class="card education">
      <h2>Education</h2>

      <div class="edu">
        <h3>W3Schools.com</h3>
        <p class="date">Forever</p>
        <p>Web Development! All I need to know in one place</p>
      </div>

      <div class="edu">
        <h3>London Business School</h3>
        <p class="date">2013 - 2015</p>
        <p>Master Degree</p>
      </div>

      <div class="edu">
        <h3>School of Coding</h3>
        <p class="date">2010 - 2013</p>
        <p>Bachelor Degree</p>
      </div>
    </div>
  </div>
</div>

<div class="footer">
  <p>Find me on social media:</p>
  <p>
    <a href="#">Facebook</a> |
    <a href="#">Instagram</a> |
    <a href="#">Twitter</a> |
    <a href="#">LinkedIn</a>
  </p>
  <p>Powered by <a href="#" style="color:white; text-decoration:underline;">HTML & CSS</a></p>
</div>

</body>
</html># Task4
