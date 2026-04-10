<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Bakra Eid</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600;800&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box;}

body{
  font-family:'Poppins',sans-serif;
  background:#020010;
  color:#fff;
  overflow:hidden;
}

/* 🌙 Background Glow */
body::before{
  content:"";
  position:fixed;
  width:300%;
  height:300%;
  background:linear-gradient(45deg,#00ffcc,#0066ff,#00ffcc);
  animation:bg 12s linear infinite;
  opacity:.15;
  z-index:-1;
}
@keyframes bg{
  100%{transform:translate(-50%,-50%)}
}

/* 🌟 Center Box */
.container{
  height:100vh;
  display:flex;
  justify-content:center;
  align-items:center;
  text-align:center;
  padding:20px;
}

.card{
  padding:40px 25px;
  border-radius:25px;
  background:rgba(255,255,255,0.05);
  backdrop-filter:blur(25px);
  box-shadow:0 0 40px rgba(0,255,200,.3);
  max-width:600px;
  width:100%;
}

/* 🐐 Title */
.title{
  font-size:40px;
  font-weight:800;
  background:linear-gradient(90deg,#00ffcc,#00aaff,#00ffcc);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  margin-bottom:10px;
}

/* 🌙 Subtitle */
.subtitle{
  font-size:18px;
  opacity:.8;
  margin-bottom:20px;
}

/* 🕌 Eid Text */
.eid{
  font-size:55px;
  font-weight:800;
  background:linear-gradient(90deg,#fff,#00ffd5,#66aaff,#fff);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
}

/* ✨ Glow line */
.line{
  height:3px;
  width:80px;
  margin:20px auto;
  background:linear-gradient(90deg,#00ffcc,#0066ff);
  border-radius:20px;
}

/* 🐐 Emoji */
.emoji{
  font-size:50px;
  margin-top:15px;
  animation:jump 2s infinite;
}
@keyframes jump{
  50%{transform:translateY(-10px);}
}

/* 💎 Button */
.btn{
  display:inline-block;
  margin-top:25px;
  padding:12px 30px;
  border-radius:30px;
  text-decoration:none;
  color:#fff;
  background:linear-gradient(135deg,#00ffcc,#0066ff);
  box-shadow:0 0 20px rgba(0,255,200,.6);
  transition:.3s;
}

.btn:hover{
  transform:scale(1.1);
  box-shadow:0 0 30px #00ffcc;
}

/* 📱 Mobile */
@media(max-width:768px){
  .eid{font-size:40px;}
  .title{font-size:30px;}
}
</style>
</head>

<body>

<div class="container">
  <div class="card">

    <div class="title">RIZZ LIVE</div>
    <div class="subtitle">Wishes You</div>

    <div class="eid">Happy Bakra Eid</div>

    <div class="line"></div>

    <div class="emoji">🐐🌙✨</div>

    <a href="#" class="btn">Celebrate Now 🎉</a>

  </div>
</div>

</body>
</html>
