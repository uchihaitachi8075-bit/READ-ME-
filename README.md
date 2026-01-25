<!DOCTYPE html>
<html lang="hi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Kisan Seva | Product</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, Helvetica, sans-serif;
}

body{
  background:#f4fff4;
}

/* Header */
header{
  background:#2e7d32;
  color:#fff;
  padding:20px;
  text-align:center;
}

nav a{
  color:#fff;
  margin:0 12px;
  text-decoration:none;
  font-weight:bold;
}

/* Product Section */
section{
  padding:40px 20px;
  max-width:1100px;
  margin:auto;
}

.card{
  background:#fff;
  padding:30px;
  border-radius:15px;
  box-shadow:0 8px 20px rgba(0,0,0,0.15);
}

/* Image Section */
.product-img{
  width:100%;
  max-width:420px;
  display:block;
  margin:20px auto;
  border-radius:15px;
  box-shadow:0 6px 15px rgba(0,0,0,0.25);
}

/* Text */
.card h3{
  text-align:center;
  color:#2e7d32;
  margin-bottom:10px;
}

.card p{
  line-height:1.7;
  margin-top:15px;
}

/* WhatsApp Button */
.whatsapp{
  display:inline-block;
  background:#25D366;
  color:#fff;
  padding:14px 24px;
  border-radius:40px;
  text-decoration:none;
  margin-top:25px;
  font-size:16px;
  font-weight:bold;
}

.whatsapp:hover{
  background:#1ebd5a;
}

/* Footer */
footer{
  background:#1b5e20;
  color:#fff;
  text-align:center;
  padding:18px;
  margin-top:40px;
}
</style>
</head>

<body>

<header>
  <h2>हमारा उत्पाद</h2>
  <nav>
    <a href="index.html">Home</a>
    <a href="product.html">Product</a>
    <a href="contact.html">Contact</a>
  </nav>
</header>

<section>
  <div class="card">

    <h3>वर्मी कम्पोस्ट (केंचुआ खाद)</h3>

    <!-- PRODUCT IMAGE -->
    <img 
      src="images/vermicompost.jpg" 
      alt="Vermi Compost Product Image"
      class="product-img"
    >

    <p>
      ✔ ऑर्गेनिक कार्बन: 20–25% <br>
      ✔ नाइट्रोजन: 1.5–2.0% <br>
      ✔ फास्फोरस: 0.5–1.5% <br>
      ✔ पोटैशियम: 0.5–1.0% <br><br>

      ✔ मिट्टी की उर्वरता बढ़ाता है <br>
      ✔ फसल की गुणवत्ता और पैदावार बढ़ाता है <br>
      ✔ पौधों की जड़ों को मजबूत बनाता है <br>
      ✔ 100% जैविक और सुरक्षित
    </p>

    <center>
      <a 
        class="whatsapp" 
        href="https://wa.me/919340065949?text=नमस्ते,%20मुझे%20वर्मी%20कम्पोस्ट%20की%20कीमत%20और%20जानकारी%20चाहिए" 
        target="_blank">
        WhatsApp से Order करें
      </a>
    </center>

  </div>
</section>

<footer>
  © 2026 Kisan Seva
</footer>

</body>
</html>