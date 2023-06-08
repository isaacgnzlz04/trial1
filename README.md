```
<!DOCTYPE html>
<html>
<head>
	<title>Cake Shop</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>Cake Shop</h1>
		<nav>
			<ul>
				<li><a href="#about">About</a></li>
				<li><a href="#products">Products</a></li>
				<li><a href="#contact">Contact</a></li>
			</ul>
		</nav>
	</header>
	<main>
		<section id="about">
			<h2>About Us</h2>
			<p>We are a cake shop that specializes in creating delicious and beautiful cakes for all occasions. Our cakes are made with the finest ingredients and are sure to impress your guests.</p>
		</section>
		<section id="products">
			<h2>Our Products</h2>
			<ul>
				<li>
					<img src="cake1.jpg" alt="Cake 1">
					<h3>Chocolate Cake</h3>
					<p>A rich and decadent chocolate cake that is perfect for any occasion.</p>
					<p>$25</p>
				</li>
				<li>
					<img src="cake2.jpg" alt="Cake 2">
					<h3>Vanilla Cake</h3>
					<p>A classic vanilla cake that is sure to please everyone.</p>
					<p>$20</p>
				</li>
				<li>
					<img src="cake3.jpg" alt="Cake 3">
					<h3>Strawberry Cake</h3>
					<p>A light and refreshing strawberry cake that is perfect for summer.</p>
					<p>$30</p>
				</li>
			</ul>
		</section>
		<section id="contact">
			<h2>Contact Us</h2>
			<form action="submit.php" method="post">
				<label for="name">Name:</label>
				<input type="text" id="name" name="name" required>
				<label for="email">Email:</label>
