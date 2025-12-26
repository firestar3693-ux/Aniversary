# Aniversary
index.html      → Welcome + Teddy
page2.html      → Cute message + Kitty
page3.html      → Heart rain + feelings
page4.html      → Final love page + song
<!DOCTYPE html>
<html>
<head>
<title>For You 💖</title>
<style>
body{
  background:#ffe6f0;
  text-align:center;
  font-family:Comic Sans MS;
}
.teddy{
  font-size:120px;
  animation: bounce 1.5s infinite;
}
@keyframes bounce{
  0%,100%{transform:translateY(0)}
  50%{transform:translateY(-20px)}
}
button{
  padding:15px 30px;
  border:none;
  border-radius:30px;
  background:#ff69b4;
  color:white;
  font-size:20px;
}
</style>
</head>
<body>

<h1>Hey Cutie 🥹💗</h1>
<div class="teddy">🧸</div>
<p>This teddy has a message for you...</p>

<button onclick="location.href='page2.html'">Next 💕</button>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>You Make Me Smile 🐱</title>
<style>
body{
  background:#e6f7ff;
  text-align:center;
  font-family:Comic Sans MS;
}
.kitty{
  font-size:110px;
  animation: wiggle 1s infinite;
}
@keyframes wiggle{
  0%{transform:rotate(0)}
  25%{transform:rotate(5deg)}
  75%{transform:rotate(-5deg)}
}
</style>
</head>
<body>

<h1>You make my heart go 🥺💞</h1>
<div class="kitty">🐱🎀</div>
<p>Every time you smile, my world feels softer 🌸</p>

<button onclick="location.href='page3.html'">More 🩷</button>

</body>
</html>
