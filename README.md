<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Website</title>
<style>
       body {
           font-family: Arial, sans-serif;
           margin: 0;
           padding: 0;
           background-color: #f4f4f4;
           text-align: center;
       }
       header {
           background: #333;
           color: white;
           padding: 15px;
           text-align: center;
           font-size: 24px;
       }
       nav {
           display: flex;
           justify-content: center;
           background: #444;
           padding: 10px;
       }
       nav a {
           color: white;
           text-decoration: none;
           padding: 10px 20px;
           margin: 5px;
       }
       nav a:hover {
           background: #555;
       }
       .container {
           padding: 20px;
       }
       .box {
           background: white;
           padding: 20px;
           margin: 20px auto;
           max-width: 600px;
           border-radius: 5px;
           box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
       }
       footer {
           background: #333;
           color: white;
           padding: 10px;
           position: relative;
           bottom: 0;
           width: 100%;
           margin-top: 20px;
       }
</style>
</head>
<body>
<header>
       My Awesome Website
</header>
<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
<div class="container">
<section id="home" class="box">
<h2>Welcome to My Website</h2>
<p>This is a simple HTML website template. You can customize it as needed.</p>
</section>
<section id="about" class="box">
<h2>About Me</h2>
<p>I am a web developer passionate about creating simple and elegant websites.</p>
</section>
<section id="contact" class="box">
<h2>Contact</h2>
<p>Email: <a href="mailto:example@example.com">example@example.com</a></p>
</section>
</div>
<footer>
&copy; 2025 My Website | All Rights Reserved
</footer>
</body>
</html>
