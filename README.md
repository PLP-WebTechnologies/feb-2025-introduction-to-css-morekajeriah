<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Intro to CSS</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <header id="main-header">
    <h1>Welcome to My CSS Page</h1>
    <p class="intro">Learning CSS is fun and creative!</p>
  </header>

  <section>
    <img src="https://via.placeholder.com/300" alt="Sample" class="styled-image" />
    <p>This image is styled using CSS. Look at the border, spacing, and how it's centered!</p>
  </section>

  <footer>
    <p>&copy; 2025 My CSS Journey</p>
  </footer>

</body>
</html>
/* Element selector */
body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #f5f7fa;
  color: #333;
  margin: 0;
  padding: 0;
}

/* ID selector */
#main-header {
  background-color: #4a90e2;
  color: white;
  text-align: center;
  padding: 20px;
  border-bottom: 5px solid #357ABD;
}

/* Class selector */
.intro {
  font-size: 1.2em;
  margin: 10px 0;
}

/* Image styling */
.styled-image {
  display: block;
  margin: 20px auto;
  padding: 10px;
  border: 3px solid #ccc;
  border-radius: 10px;
  width: 300px;
}

/* Footer styling */
footer {
  text-align: center;
  padding: 15px;
  background-color: #e0e0e0;
  margin-top: 40px;
}
