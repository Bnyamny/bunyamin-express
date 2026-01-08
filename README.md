<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<title>Bünyamin Express | Kurye Hizmetleri</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
:root{
  --orange:#ff7a00;
  --dark:#222;
}

*{box-sizing:border-box}

body{
  margin:0;
  font-family:Arial, Helvetica, sans-serif;
  background:#f4f4f4;
  color:#333;
  line-height:1.6;
}

/* HEADER */
header{
  background:var(--orange);
  color:#fff;
  padding:20px;
}

.header-inner{
  max-width:1100px;
  margin:auto;
  display:flex;
  align-items:center;
  gap:15px;
}

/* LOGO */
.logo{
  width:55px;
  height:55px;
  background:#fff;
  border-radius:12px;
  display:flex;
  align-items:center;
  justify-content:center;
  color:var(--orange);
  font-weight:bold;
  font-size:22px;
}

.header-text h1{
  margin:0;
  font-size:26px;
}
.header-text p{
  margin:4px 0 0;
  font-size:15px;
}

/* LAYOUT */
.container{
  max-width:1100px;
  margin:auto;
  padding:20px;
}

.section{
  background:#fff;
  padding:20px;
  margin-bottom:20px;
  border-radius:10px;
}

.section h2{
  margin-top:0;
  color:var(--orange);
}

/* SERVICES */
.services{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:15px;
}
.service{
  background:#fafafa;
  padding:15px;
  border-radius:8px;
  border-left:5px solid var(--orange);
}

/* MAP */
.map iframe{
  width:100%;
  height:300px;
  border:0;
  border-radius:8px;
}

/* WHATSAPP */
.whatsapp{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#25d366;
  color:#fff;
  padding:14px 18px;
  border-radius:50px;
  text-decoration:none;
  font-weight:bold;
  box-shadow:0 4px 10px rgba(0,0,0,.3);
}

/* FOOTER */
footer{
  background:var(--dark);
  color:#ccc;
  text-align:center;
  padding:15px;
  font-size:14px;
}

/* MOBILE */
@media(max-width:600px){
  .header-inner{
    flex-direction:column;
    text-align:center;
  }
  .header-text h1{
    font-size:22px;
  }
}
</style>
</head>

<body>

<header>
  <div class="header-inner">
    <div class="logo">BX</div>
    <div class="header-text">
      <h1>Bünyamin Express</h1>
      <p>Hızlı • Güvenilir • Zamanında Kurye</p>
    </div>
  </div>
</header>

<div class="container">

  <div class="section">
    <h2>Hakkımızda</h2>
    <p>
      Bünyamin Express olarak şehir içi hızlı kurye ve express teslimat
      hizmetleri sunuyoruz. Evrak, paket ve acil gönderileriniz
      güvenle ve zamanında teslim edilir.
    </p>
  </div>

  <div class="section">
    <h2>Hizmetlerimiz</h2>
    <div class="services">
      <div class="service">🚀 Express Kurye</div>
      <div class="service">📄 Evrak Teslimatı</div>
      <div class="service">📦 Paket Taşıma</div>
      <div class="service">🏪 İşletmelere Özel Kurye</div>
      <div class="service">⏱️ Acil Teslimat</div>
    </div>
  </div>

  <div class="section">
    <h2>İletişim</h2>
    <p><strong>WhatsApp:</strong> 0530 265 03 55</p>
    <p>7/24 hızlı dönüş</p>
  </div>

  <div class="section map">
    <h2>Konumumuz</h2>
    <!-- ÖRNEK HARİTA: İstersen adresine göre değiştiririm -->
    <iframe 
      src="https://www.google.com/maps?q=İstanbul&output=embed">
    </iframe>
  </div>

</div>

<a class="whatsapp" href="https://wa.me/905302650355" target="_blank">
WhatsApp’tan Yaz
</a>

<footer>
© 2026 Bünyamin Express • Tüm Hakları Saklıdır
</footer>

</body>
</html>
