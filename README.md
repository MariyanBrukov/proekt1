<!DOCTYPE html>
<html>
<head>
	<title>My Website</title>
	<style>
		/* Style the menu */
		.menu {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: hidden;
			background-color: #333;
		}

		/* Style the links inside the menu */
		.menu li {
			float: left;
		}

		.menu li a {
			display: block;
			color: white;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
		}

		/* Change the link color on hover */
		.menu li a:hover {
			background-color: #111;
		}

		/* Style the logo */
		.logo {
			text-align: center;
			padding: 50px 0;
		}

		/* Style the centered text */
		.centered-text {
			text-align: center;
			padding: 50px 0;
		}
	</style>
</head>
<body>
	<header>
		<ul class="menu">
			<li><a href="">Home</a></li>
			<li><a href="">About Us</a></li>
			<li><a href="">Contact Us</a></li>
		</ul>
		<div class="logo">
			<img src = "bethanylogo.jgp">
		</div>
	</header>
    <article class="article">
        <header>
            <h1>Welcome to Bethany's Pie Shop</h1>
        </header>
        <figure>
            <img src="bethany-fullsize.jpg" alt="Bethany in her pie shop" />
            <figcaption>Bethany in her pie shop</figcaption>
        </figure>
        <h2>Our history</h2>
        <p>For many years, <b>Bethany</b> has been baking the most delicious pies at her home. In 2013, we opened our first store in Brussels (Belgium) in a cosy little street near the Grand Market. People from all over the world fell in love with the soft cakes, heavenly cheese cakes, spicy apple pies...<br><i>The store became a success in no time.</i>
        </p>
        <p>
            In 2015, no less than 100 pies were sold every day and Bethany's Pie Shop moved into a larger building. After receiving many requests, it became clear that our next step was making it possible to order pies from the comfort of your own home and from anywhere in the world. You are now looking at the result of this: our very own webstore, making it possible to order Bethany's delicious pies whenever you feel like it!
        </p>
    </article>
	<main>
		<div>
			<img src="your-image.jpg" alt="Your Image" width="500" height="500">
		</div>
		<div class="centered-text">
			<p>This is some centered text that goes beneath the image.</p>
		</div>
	</main>
</body>
</html>
