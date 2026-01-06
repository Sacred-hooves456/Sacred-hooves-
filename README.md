# Sacred-hooves-
Sacred hooves is a cow protection website which consist of about mission donation page volunteer page and chatbot and emergency rescue page 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sacred Hooves â€“ Cow Protection</title>


<style>
body{
Â  margin:0;
Â  font-family:Arial, sans-serif;
Â  background:#f4fff0;
Â  line-height:1.6;
}
header{
Â  background:#2e7d32;
Â  color:white;
Â  text-align:center;
Â  padding:25px 10px;
}
nav{
Â  background:#1b5e20;
Â  display:flex;
Â  flex-wrap:wrap;
Â  justify-content:center;
Â  padding:10px;
}
nav a{
Â  color:white;
Â  margin:6px 12px;
Â  text-decoration:none;
Â  font-weight:bold;
}
section{
Â  padding:40px 15px;
Â  max-width:1100px;
Â  margin:auto;
}
h2, h3{
Â  color:#2e7d32;
}
figure{
Â  margin:15px 0;
Â  text-align:center;
}
figure img{
Â  width:100%;
Â  max-width:600px;
Â  border-radius:10px;
}
figcaption{
Â  margin-top:8px;
Â  font-style:italic;
Â  color:#555;
Â  font-size:0.9rem;
}
.gallery{
Â  display:grid;
Â  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
Â  gap:20px;
}
button{
Â  background:#2e7d32;
Â  color:white;
Â  padding:12px 20px;
Â  border:none;
Â  border-radius:5px;
Â  cursor:pointer;
}
footer{
Â  background:#2e7d32;
Â  color:white;
Â  text-align:center;
Â  padding:12px;
}


/* WhatsApp Button */
.whatsapp-btn{
Â  position:fixed;
Â  bottom:20px;
Â  right:20px;
Â  background:#25D366;
Â  color:white;
Â  border-radius:50px;
Â  padding:12px 18px;
Â  display:flex;
Â  align-items:center;
Â  text-decoration:none;
Â  font-weight:bold;
}
.whatsapp-btn img{
Â  width:28px;
Â  margin-right:10px;
}
</style>
</head>


<body>


<header>
Â  <h1>SACRED HOOVES</h1>
Â  <p>Cow Protection & Welfare Initiative</p>
</header>


<nav>
Â  <a href="#home">Home</a>
Â  <a href="#about">About</a>
Â  <a href="#importance">Importance</a>
Â  <a href="#products">Products</a>
Â  <a href="#rescue">Rescue</a>
Â  <a href="#donate">Donate</a>
Â  <a href="#contact">Contact</a>
</nav>


<section id="home">
Â  <h2>Our Mission</h2>
Â  <p>
Â  Â  Sacred Hooves works for the rescue, care, and protection of cows.
Â  </p>
Â  <figure>
Â  Â  <img src="images/cow1.jpg" alt="Sacred Indian Cow">
Â  Â  <figcaption>Rescued Indian cow under care at Sacred Hooves</figcaption>
Â  </figure>
</section>


<section id="about">
Â  <h2>About Sacred Hooves</h2>
Â  <p>
Â  Â  We rescue abandoned, injured, and old cows and provide shelter and medical care.
Â  </p>


Â  <div class="gallery">
Â  Â  <figure>
Â  Â  Â  <img src="images/cow2.jpg">
Â  Â  Â  <figcaption>Cows grazing peacefully at our shelter</figcaption>
Â  Â  </figure>


Â  Â  <figure>
Â  Â  Â  <img src="images/cow3.jpg">
Â  Â  Â  <figcaption>Healthy cows after rehabilitation</figcaption>
Â  Â  </figure>
Â  </div>
</section>


<section id="importance">
Â  <h2>Importance of Cow</h2>
Â  <p>
Â  Â  Cows are essential for agriculture, organic farming, and environmental balance.
Â  </p>
Â  <figure>
Â  Â  <img src="images/farming.jpg">
Â  Â  <figcaption>Cows supporting sustainable farming</figcaption>
Â  </figure>
</section>


<section id="products">
Â  <h2>Cow Products</h2>


Â  <div class="gallery">
Â  Â  <figure>
Â  Â  Â  <img src="images/milk.jpg">
Â  Â  Â  <figcaption>Pure cow milk for nutrition</figcaption>
Â  Â  </figure>


Â  Â  <figure>
Â  Â  Â  <img src="images/ghee.jpg">
Â  Â  Â  <figcaption>Traditional cow ghee prepared naturally</figcaption>
Â  Â  </figure>
Â  </div>


Â  <p>
Â  Â  Cow dung and gomutra are used for organic manure and natural medicine.
Â  </p>
</section>


<section id="rescue">
Â  <h2>Emergency Cow Rescue</h2>
Â  <p>Share your live GPS location for immediate help.</p>


Â  <figure>
Â  Â  <img src="images/rescue1.jpg">
Â  Â  <figcaption>Emergency rescue operation by Sacred Hooves volunteers</figcaption>
Â  </figure>


Â  <button onclick="getLocation()">Share Live Location</button>
Â  <p id="location"></p>
</section>


<section id="donate">
Â  <h2>Support Our Mission</h2>
Â  <p>Your donation helps feed and treat rescued cows.</p>
Â  <p><b>UPI:</b> sacredhooves@upi</p>
</section>


<section id="contact">
Â  <h2>Contact Us</h2>
Â  <p><b>Address:</b> Pattanagere, R R Nagar, Bangalore</p>
Â  <p><b>Phone:</b> 7899574243</p>
Â  <p><b>Email:</b> manushreeg27@gmail.com</p>
</section>


<footer>
Â  Â© 2026 Sacred Hooves â€“ Cow Protection Initiative
</footer>


<a class="whatsapp-btn" href="https://wa.me/917899574243" target="_blank">
Â  <img src="images/whatsapp.png">
Â  WhatsApp
</a>


<script>
function getLocation(){
Â  if(navigator.geolocation){
Â  Â  navigator.geolocation.getCurrentPosition(function(pos){
Â  Â  Â  document.getElementById("location").innerHTML =
Â  Â  Â  Â  "Latitude: " + pos.coords.latitude +
Â  Â  Â  Â  "<br>Longitude: " + pos.coords.longitude +
Â  Â  Â  Â  `<br><a href="https://www.google.com/maps?q=${pos.coords.latitude},${pos.coords.longitude}" target="_blank">
Â  Â  Â  Â  Open in Google Maps</a>`;
Â  Â  });
Â  }
}
</script>


</body>
</html>
