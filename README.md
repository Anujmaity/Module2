<!DOCTYPE html>
<html>
<head>
<title>Responsive Page</title>
<link rel="stylesheet" href="css/styles.css">
</head>
<body>
<h1>My Responsive Page</h1>
<section class="chicken">
<h2>Chicken</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas luctus, quam nec semper scelerisque, mauris quam semper eros, nec ultricies lectus quam quis quam.</p>
</section>
<section class="beef">
<h2>Beef</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas luctus, quam nec semper scelerisque, mauris quam semper eros, nec ultricies lectus quam quis quam.</p>
</section>
<section class="sushi">
<h2>Sushi</h2>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas luctus, quam nec semper scelerisque, mauris quam semper eros, nec ultricies lectus quam quis quam.</p>
</section>
</body>
</html>
body {
  font-family: sans-serif;
}

h1 {
  font-size: 2em;
}

h2 {
  font-size: 1.5em;
}

section {
  background-color: #ccc;
  border: 1px solid black;
  margin: 10px;
  padding: 10px;
}

.chicken {
  background-color: #f00;
}

.beef {
  background-color: #00f;
}

.sushi {
  background-color: #0f0;
}

@media (max-width: 767px) {
  section {
    width: 100%;
  }
}

@media (max-width: 480px) {
  section {
    padding: 0;
  }
}
