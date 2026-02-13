<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>হালাল সপ | Premium Dates</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family: Arial, sans-serif;
scroll-behavior:smooth;
}

body{
background:#f8f5f0;
}

/* NAVBAR */
nav{
background:#4b2e1e;
padding:15px 20px;
display:flex;
justify-content:space-between;
align-items:center;
}

nav h2{
color:white;
}

nav ul{
list-style:none;
display:flex;
gap:20px;
}

nav ul li a{
color:white;
text-decoration:none;
font-weight:bold;
}

nav ul li a:hover{
color:#ffd700;
}

/* MOBILE MENU */
@media(max-width:768px){
nav{
flex-direction:column;
}
nav ul{
margin-top:10px;
}
}

/* SECTION */
section{
padding:60px 20px;
max-width:1100px;
margin:auto;
}

h1{
margin-bottom:20px;
color:#4b2e1e;
}

/* PRODUCTS GRID */
.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:20px;
}

.card{
background:white;
padding:15px;
border-radius:12px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
border-radius:10px;
}

.price{
font-weight:bold;
margin:10px 0;
color:#4b2e1e;
}

.btn{
display:inline-block;
padding:10px 15px;
margin-top:10px;
background:#25D366;
color:white;
text-decoration:none;
border-radius:6px;
font-size:14px;
}

.messenger{
background:#0084FF;
margin-left:5px;
}

/* CONTACT */
.contact-box{
background:white;
padding:20px;
border-radius:10px;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

/* FOOTER */
footer{
background:#4b2e1e;
color:white;
text-align:center;
padding:15px;
}
</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
<h2>হালাল সপ 🌴</h2>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#products">Product</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<!-- HOME -->
<section id="home">
<h1>স্বাগতম হালাল সপ এ</h1>
<p>আমরা বিশুদ্ধ ও হালাল মানের খেজুর সরবরাহ করি। সেরা মান, সেরা
দাম।</p>
<p>রংপুরের একমাত্র হোম ডেলিভারি সার্ভিস হালাল সপ</p>
</section>

<!-- PRODUCTS -->
<section id="products">
<h1>আমাদের খেজুর</h1>

<div class="products">

<div class="card">
<h3>Ajwa Dates</h3>
<img src="https://i.imgur.com/3ZQ3Z4B.jpg">
<p>মদিনার বিখ্যাত কালো খেজুর। সুন্নাহ খেজুর হিসেবে পরিচিত।</p>
<div class="price">০ টাকা</div>
<a class="btn" href="https://wa.me/8801521552703">WhatsApp Order</a>
<a class="btn messenger" href="https://m.me/dedarbinnur">Messenger</a>
</div>

<div class="card">
<h3>Medjool Dates</h3>
<img src="https://i.imgur.com/9Xn6p3T.jpg">
<p>বড় সাইজ ও অত্যন্ত রসালো প্রিমিয়াম খেজুর।</p>
<div class="price">০ টাকা</div>
<a class="btn" href="https://wa.me/8801521552703">WhatsApp Order</a>
<a class="btn messenger" href="https://m.me/dedarbinnur">Messenger</a>
</div>

<div class="card">
<h3>Safawi Dates</h3>
<img src="https://i.imgur.com/F3nYh7C.jpg">
<p>গাঢ় রঙের জনপ্রিয় ও সুস্বাদু খেজুর।</p>
<div class="price">০ টাকা</div>
<a class="btn" href="https://wa.me/8801521552703">WhatsApp Order</a>
<a class="btn messenger" href="https://m.me/dedarbinnur">Messenger</a>
</div>

</div>
</section>

<!-- CONTACT -->
<section id="contact">
<h1>যোগাযোগ করুন</h1>

<div class="contact-box">
<p>📞 WhatsApp: +8801521552703</p>
<p>💬 Messenger: facebook.com/dedarbinnur</p>
<p>📍 বাংলাদেশ</p>
</div>

</section>

<footer>
© 2026 হালাল সপ | All Rights Reserved
</footer>

</body>
</html>
