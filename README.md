# honey-beddings-website
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Honey Beddings and More</title>

<link rel="stylesheet" href="style.css">
</head>

<body>

<header>
<h1>Honey Beddings & More</h1>
<p>Luxury Comfort For Your Dream Space</p>

<nav>
<a href="#products">Products</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>


<section class="hero">

<div>
<h2>Sleep In Luxury</h2>

<p>
Premium bedsheets, duvets and mattress toppers
crafted for comfort and elegance.
</p>

<a class="btn" href="https://wa.me/2348055313933">
Order Now
</a>

</div>

</section>



<section id="products">

<h2>Our Luxury Collection</h2>


<div class="cards">


<div class="card">
<h3>Luxury Bedsheets</h3>
<p>4/6 - ₦8,000</p>
<p>6/6 - ₦10,000</p>
<p>6/7 - ₦13,000</p>
<p>7/7 - ₦15,000</p>
</div>


<div class="card">

<h3>Duvet Collection</h3>

<p>
Medium Thickness
</p>

<p>4/6 - ₦25,000</p>
<p>6/6 - ₦30,000</p>
<p>7/7 - ₦40,000</p>

</div>



<div class="card">

<h3>Mattress Toppers</h3>

<p>
Premium comfort topper
</p>

<p>
Starting from ₦50,000
</p>

</div>


</div>

</section>



<section id="about">

<h2>Why Choose Honey?</h2>

<p>
We provide affordable luxury bedding with nationwide delivery,
quality materials and beautiful packaging.
</p>

</section>



<section class="delivery">

<h2>Nationwide Delivery</h2>

<p>
Lagos • Abuja • Port Harcourt • Across Nigeria
</p>

</section>



<section id="contact">

<h2>Contact Us</h2>

<p>
WhatsApp: +234 805 531 3933
</p>


<a class="btn" 
href="https://wa.me/2348055313933">

Chat With Us

</a>


</section>



<footer>

<p>
© 2026 Honey Beddings and More
</p>

</footer>


<script src="script.js"></script>

</body>
</html>
*{
box-sizing:border-box;
font-family:Georgia, serif;
}


body{

margin:0;
background:#fffaf0;
color:#333;

}


header{

background:#111;
color:#d4af37;
padding:30px;
text-align:center;

}


nav a{

color:white;
margin:15px;
text-decoration:none;

}



.hero{

height:80vh;

background:
linear-gradient(
rgba(0,0,0,.5),
rgba(0,0,0,.5)
),
url("https://images.unsplash.com/photo-1505693416388-ac5ce068fe85");

background-size:cover;
background-position:center;

display:flex;
align-items:center;
justify-content:center;

text-align:center;

color:white;

}


.hero h2{

font-size:50px;

}


.btn{

background:#d4af37;
color:#111;

padding:15px 30px;

border-radius:30px;

text-decoration:none;

display:inline-block;

margin-top:20px;

font-weight:bold;

}



section{

padding:50px 10%;

text-align:center;

}



.cards{

display:flex;

gap:25px;

justify-content:center;

flex-wrap:wrap;

}



.card{

background:white;

padding:30px;

width:280px;

border-radius:15px;

box-shadow:0 5px 20px #ddd;

}



.card h3{

color:#d4af37;

}



.delivery{

background:#111;

color:white;

}



footer{

background:#000;

color:white;

padding:20px;

text-align:center;

}



@media(max-width:700px){

.hero h2{

font-size:35px;

}


}
console.log("Honey Beddings Website Loaded");