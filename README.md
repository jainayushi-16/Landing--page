# Landing--page
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Landing Page</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header>
    <div class="logo">MyWebsite</div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Features</a>
      <a href="#">About</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Welcome to MyWebsite</h1>
    <p>Your solution for modern web design</p>
    <a href="#" class="btn">Get Started</a>
  </section>

  <section class="features">
    <div class="feature">
      <h2>Fast</h2>
      <p>Lightning-fast performance for all users.</p>
    </div>
    <div class="feature">
      <h2>Responsive</h2>
      <p>Looks great on every screen size.</p>
    </div>
    <div class="feature">
      <h2>Customizable</h2>
      <p>Easily tailored to your needs.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 MyWebsite. All rights reserved.</p>
  </footer>

</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', sans-serif;
  line-height: 1.6;
  color: #333;
  background: #f9f9f9;
}

header {
  background: #333;
  color: #fff;
  padding: 20px 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header .logo {
  font-size: 1.5em;
  font-weight: bold;
}

header nav a {
  color: #fff;
  text-decoration: none;
  margin-left: 20px;
  font-weight: 500;
}

.hero {
  text-align: center;
  padding: 100px 20px;
  background: linear-gradient(to right, #4facfe, #00f2fe);
  color: #fff;
}

.hero h1 {
  font-size: 3em;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2em;
  margin-bottom: 30px;
}

.btn {
  padding: 12px 25px;
  background: #fff;
  color: #007bff;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
}

.features {
  display: flex;
  justify-content: space-around;
  padding: 60px 20px;
  background: #fff;
  flex-wrap: wrap;
}

.feature {
  max-width: 300px;
  text-align: center;
  margin: 20px;
}

.feature h2 {
  color: #007bff;
  margin-bottom: 10px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #333;
  color: #fff;
}
