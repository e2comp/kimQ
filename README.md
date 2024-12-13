<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kim Quiñones Website</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: gray;
      padding: 10px 0;
      text-align: center;
    }
    nav {
      text-align: center;
      margin: 20px 0;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: white;
      font-weight: bold;
      background-color: #333;
      padding: 10px;
      border-radius: 5px;
    }
    section {
      padding: 20px;
      background-color: #fff;
      margin: 20px;
      border-radius: 8px;
    }
    h1, h2 {
      color: #444;
    }
    iframe {
      width: 100%;
      height: 400px;
      border: none;
    }
    audio {
      width: 100%;
      margin-top: 10px;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 10px;
    }
    table, th, td {
      border: 1px solid #ddd;
    }
    th, td {
      padding: 8px;
      text-align: left;
    }
    form input, form select, form textarea {
      width: 100%;
      padding: 8px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }
    form label {
      display: block;
      margin: 10px 0 5px;
    }
  </style>
</head>
<body>

  <header>
    <h1>KIM QUIÑONES</h1>
    <h2>2 - INDIA</h2>
    <h3>(E2 Computer Lab Exercises)</h3>
  </header>

  <nav>
    <a href="#home">Home</a>
    <a href="#article">My Article</a>
    <a href="#blog">My Blog</a>
    <a href="#form">My Form</a>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h2>Home</h2>
    <p>Welcome to my personal webpage!</p>
    <audio controls>
      <source src="videoplayback (7).webm" type="audio/mp3">
      Your browser does not support the audio element.
    </audio>
  </section>

  <!-- My Article Section -->
  <section id="article">
    <h2>MY ARTICLE</h2>
    <iframe src="https://www.youtube.com/embed/-SoAISJrULw" title="US v. Plagiarism Video"></iframe>
    <h3>Plagiarism</h3>
    <p>Plagiarism is the act of using someone else's ideas, words, or work without giving them credit.</p>
    <h4>Examples of plagiarism cases and their consequences</h4>
    <ul>
      <li><strong>Case 1:</strong> Melania Trump's Speech (2016) - Significant similarities to Michelle Obama's speech.</li>
      <li><strong>Case 2:</strong> Joseph Biden (1988) - Accused of plagiarizing speeches.</li>
      <li><strong>Case 3:</strong> Stephen Ambrose (2002) - Historian accused of plagiarizing passages from other authors' works.</li>
    </ul>
    <h4>International Perspectives on Plagiarism Punishment</h4>
    <ul>
      <li><strong>United States:</strong> Plagiarism can lead to fines or imprisonment depending on severity.</li>
      <li><strong>India:</strong> Penalties include imprisonment for 6 months to 3 years under the Copyright Act of 1957.</li>
      <li><strong>United Kingdom:</strong> Penalties include fines or imprisonment under the Copyright, Designs and Patents Act of 1988.</li>
    </ul>
  </section>

  <!-- My Blog Section -->
  <section id="blog">
    <h2>MY BLOG</h2>
    <p>Understanding Malware and Computer Security</p>
    <img src="Messenger_creation_3F55F75A-D9B7-4429-BDA0-DCFB52B53126.jpeg" alt="Security Image" style="width:100%; height:auto;"/>
    <table>
      <tr>
        <th>Term</th>
        <th>Definition</th>
      </tr>
      <tr>
        <td>Malware</td>
        <td>Malicious software created to harm a computer or steal data.</td>
      </tr>
      <tr>
        <td>Computer Virus</td>
        <td>A type of malware that attaches to programs, replicates, and spreads.</td>
      </tr>
      <tr>
        <td>Spam</td>
        <td>Unwanted electronic messages, typically commercial in nature.</td>
      </tr>
      <tr>
        <td>Antivirus</td>
        <td>Software designed to protect devices from malware.</td>
      </tr>
    </table>
  </section>

  <!-- My Form Section -->
  <section id="form">
    <h2>MY FORM</h2>
    <form action="#" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="gender">Gender:</label>
      <input type="radio" id="male" name="gender" value="Male"> Male
      <input type="radio" id="female" name="gender" value="Female"> Female
      <label for="interests">Do you like motorcycles?</label>
      <input type="checkbox" id="motorcycle" name="motorcycle"> Yes, I do!
      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>
      <label for="bike-type">Preferred Bike Type:</label>
      <select id="bike-type" name="bike-type">
        <option value="sport">Sport</option>
        <option value="cruiser">Cruiser</option>
        <option value="dirt">Dirt Bike</option>
      </select>
      <label for="comments">Any comments:</label>
      <textarea id="comments" name="comments"></textarea>
      <input type="submit" value="Submit">
    </form>
  </section>

</body>
</html>
