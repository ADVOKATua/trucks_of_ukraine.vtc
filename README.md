<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<title>Trucks of Ukraine VTC</title>

<style>
body{
margin:0;
font-family:Arial;
background:#0b1f4d;
color:white;
}

/* ШАПКА */
header{
display:flex;
justify-content:space-between;
align-items:center;
padding:15px;
background:#08142e;
border-bottom:2px solid #ffd700;
}

.logo{
color:#ffd700;
font-weight:bold;
font-size:20px;
}

/* ГОЛОВНИЙ БАНЕР */
.hero{
text-align:center;
padding:80px;
background:url("https://images.unsplash.com/photo-1601584115197-04ecc0da31d7?auto=format&fit=crop&w=1400&q=60");
background-size:cover;
background-position:center;
position:relative;
}

.hero::before{
content:"";
position:absolute;
top:0;left:0;
width:100%;height:100%;
background:rgba(0,0,0,0.6);
}

.hero h1,.hero p,.hero a{
position:relative;
}

.hero h1{
font-size:45px;
color:#ffd700;
}

.btn{
display:inline-block;
padding:12px 20px;
margin:10px;
background:#ffd700;
color:black;
text-decoration:none;
border-radius:8px;
font-weight:bold;
}

/* СЕКЦІЇ */
.section{
padding:30px;
}

/* КАРТКИ */
.card{
background:#102a6b;
padding:15px;
margin:10px;
border:1px solid #ffd700;
border-radius:10px;
}

/* ФОРМА */
input{
width:100%;
padding:10px;
margin:5px 0;
border-radius:5px;
border:none;
}

button{
width:100%;
padding:12px;
background:#ffd700;
border:none;
font-weight:bold;
cursor:pointer;
}

/* КАРТИНКИ АВТОПАРК */
.fleet img{
width:200px;
border-radius:10px;
margin:10px;
border:2px solid #ffd700;
}
</style>

</head>

<body>

<header>
<div class="logo">🚛 Trucks of Ukraine</div>

<div>
<a href="https://discord.gg/NkCCHJed" style="color:#ffd700;margin-right:10px;">Discord</a>
<a href="#" style="color:#ffd700;">TikTok</a>
</div>
</header>

<!-- HERO -->
<div class="hero">
<h1>TRUCKS OF UKRAINE</h1>
<p>Українська VTC у Euro Truck Simulator 2</p>

<a class="btn" href="#apply">🚛 Вступити</a>
<a class="btn" href="#fleet">🚚 Автопарк</a>
</div>

<!-- ЗАЯВКА -->
<div class="section" id="apply">

<h2>📩 Заявка на вступ</h2>

<div class="card">

<input placeholder="Ім'я">
<input placeholder="Discord">
<input placeholder="TruckersMP нік">
<input placeholder="TMP ID">
<input placeholder="Steam ID">
<input placeholder="Вік">

<button onclick="alert('Заявка відправлена (поки без Discord, підключимо далі)')">
Відправити заявку
</button>

</div>

</div>

<!-- АВТОПАРК -->
<div class="section" id="fleet">

<h2>🚚 Автопарк компанії</h2>

<div class="fleet">

<img src="https://truckersmp.com/storage/images/vehicles/scania_s.jpg">
<img src="https://truckersmp.com/storage/images/vehicles/volvo_fh5.jpg">
<img src="https://truckersmp.com/storage/images/vehicles/man_tgx.jpg">
<img src="https://truckersmp.com/storage/images/vehicles/daf_xg.jpg">

</div>

</div>

<!-- ІНФО -->
<div class="section">

<div class="card">
<h2>🛈 Про компанію</h2>
<p>Trucks of Ukraine — українська VTC спільнота для ETS2</p>
</div>

<div class="card">
<h2>📘 Правила</h2>
<p>Повага, дисципліна, конвої, командна гра</p>
</div>

<div class="card">
<h2>⭐ Ролі</h2>
<p>Стажер → Водій → Досвідчений → Старший → Майстер</p>
</div>

</div>

</body>
</html>
