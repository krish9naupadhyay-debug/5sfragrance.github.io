<!DOCTYPE html>
<html>
<head>
<title>5S Fragrance</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{margin:0;font-family:Arial;background:black;color:white;text-align:center;}
header{padding:40px;background:#111;}
h1{color:gold;font-size:40px;margin:0;}
.products{display:flex;flex-wrap:wrap;justify-content:center;padding:20px;}
.card{background:#111;border:1px solid gold;border-radius:10px;width:280px;margin:15px;padding:15px;}
.card img{width:100%;border-radius:10px;}
.price{color:gold;font-size:18px;margin:10px 0;}
button{background:gold;border:none;padding:10px 15px;font-weight:bold;cursor:pointer;border-radius:5px;}
footer{padding:20px;background:#111;margin-top:30px;}
</style>
</head>
<body>

<header>
<h1>5S Fragrance</h1>
<p>Luxury In Every Drop</p>
</header>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/300x300" alt="Perfume">
<h2>Oud Royal</h2>
<p>Long Lasting 12 Hours</p>
<p class="price">₹999</p>
<button onclick="payNow(999,'Oud Royal')">Pay & Order</button>
</div>

</div>

<footer>
© 2026 5S Fragrance | All Rights Reserved
</footer>

<script>
function payNow(amount, product){
window.location.href="upi://pay?pa=ku289771-1@oksbi&pn=5SFragrance&am="+amount+"&cu=INR";
setTimeout(function(){
window.location.href="https://wa.me/919536335887?text=I have paid ₹"+amount+" for "+product+". My Name: , Address: , Pincode: ";
},3000);
}
</script>

</body>
</html>
