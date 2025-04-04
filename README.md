<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Introduction</title>
  <!-- Linking external CSS file -->
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header id="main-header">
    <h1>Welcome to CSS Styling!</h1>
  </header>
  
  <section class="content">
    <p>This page demonstrates basic CSS styling using different selectors, colors, typography, and spacing. .</p>
    <!-- Image styled with a specific class -->
    <img src="https://via.placeholder.com/150" alt="Placeholder Image" class="styled-image">
  </section>
  
  <footer>
    <p>KOYOTITO</p>
  </footer>
</body>
</html>





/* Element Selector: Apply global styles */
body {
  font-family: 'Arial', sans-serif; /* Different font */
  background-color: #f0f8ff;
  margin: 0;
  padding: 0;
}

/* ID Selector: Style the header */
#main-header {
  background-color: #4682b4;
  color: #fff;
  padding: 20px;
  text-align: center;
}

/* Class Selector: Style the content area */
.content {
  margin: 20px;
  padding: 20px;
  border: 2px solid #4682b4; /* Border */
  border-radius: 5px;
}

/* Image Styling using Class Selector */
.styled-image {
  display: block;
  margin: 20px auto; /* Center the image with margin */
  border: 5px solid #4682b4; /* Border for the image */
  border-radius: 10px;
  padding: 5px; /* Padding inside the border */
}

/* Footer styling using an element selector */
footer {
  background-color: #4682b4;
  color: #fff;
  text-align: center;
  padding: 10px;
}
