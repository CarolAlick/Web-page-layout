<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Complex HTML Example</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    margin: 0;
    padding: 0;
  }
  header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
  }
  nav {
    background-color: #444;
    color: #fff;
    padding: 10px 0;
    text-align: center;
  }
  nav a {
    color: #fff;
    text-decoration: none;
    padding: 0 10px;
  }
  section {
    padding: 20px;
    margin: 20px 0;
    background-color: #fff;
  }
  footer {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
    position: fixed;
    bottom: 0;
    width: 100%;
  }
</style>
</head>
<body>

<header>
  <h1>Welcome to My Website</h1>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#">About</a>
  <a href="#">Services</a>
  <a href="#">Contact</a>
</nav>

<section>
  <h2>About Us</h2>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed aliquam justo nec urna molestie, ut malesuada lectus tincidunt. Proin non ligula eu leo gravida egestas. Nulla facilisi. Sed eleifend, lacus sed viverra scelerisque, justo magna feugiat arcu, vel semper ligula turpis eu purus.</p>
</section>

<section>
  <h2>Our Services</h2>
  <ul>
    <li>Web Design</li>
    <li>Graphic Design</li>
    <li>SEO Optimization</li>
    <li>Content Writing</li>
  </ul>
</section>

<section>
  <h2>Contact Us</h2>
  <form>
    <label for="name">Name:</label><br>
    <input type="text" id="name" name="name"><br>
    <label for="email">Email:</label><br>
    <input type="email" id="email" name="email"><br>
    <label for="message">Message:</label><br>
    <textarea id="message" name="message" rows="4"></textarea><br>
    <input type="submit" value="Submit">
  </form>
</section>

<footer>
  <p>&copy; 2024 My Website. All Rights Reserved.</p>
</footer>

</body>
</html>
