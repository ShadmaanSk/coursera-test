<!DOCTYPE html>
<html>
<head>
  <title>My Simple Website</title>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <h1>My Simple Website</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>
  <main>
    <section id="home">
      <h2>Welcome to My Simple Website</h2>
      <p>This website is a demonstration of a simple website layout and structure.</p>
    </section>
    <section id="about">
      <h2>About My Simple Website</h2>
      <p>This website was created as a demonstration of a simple website layout and structure using HTML, CSS, and JavaScript.</p>
    </section>
    <section id="contact">
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name">
        <br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email">
        <br>
        <label for="message">Message:</label>
        <textarea id="message" name="message"></textarea>
        <br>
        <input type="submit" value="Submit">
      </form>
    </section>
  </main>
  <footer>
    <p>Copyright © 2021 My Simple Website</p>
  </footer>
</body>
</html>
