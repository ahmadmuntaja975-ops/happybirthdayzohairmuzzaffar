<!DOCTYPE html>
<html>
<head>
<title>Happy Birthday Zohair</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body{
margin:0;
font-family:sans-serif;
text-align:center;
background:black;
color:white;
overflow:hidden;
}

canvas{
position:fixed;
top:0;
left:0;
z-index:-1;
}

.container{
margin-top:80px;
padding:20px;
}

h1{
font-size:35px;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{text-shadow:0 0 10px #fff;}
to{text-shadow:0 0 25px #00ffff;}
}

img{
width:150px;
border-radius:15px;
margin:10px;
transition:0.4s;
}

img:hover{
transform:scale(1.1);
}

button{
padding:12px 25px;
border:none;
border-radius:30px;
background:cyan;
cursor:pointer;
font-size:18px;
margin-top:20px;
}

#msg{
display:none;
margin-top:30px;
font-size:18px;
}

.repeat{
font-size:24px;
font-weight:bold;
margin-top:20px;
color:yellow;
animation:blink 1s infinite;
}

@keyframes blink{
50%{opacity:0.3;}
}
</style>
</head>

<body>

<div class="container">

<h1>🎉 Happy Birthday Zohair Muzzaffar 🎉</h1>

<!-- Yahan apni image link lagana -->
<img src="PASTE_IMAGE_LINK_HERE">

<br>

<button onclick="showMsg()">Open Your Surprise 🎁</button>

<div id="msg">
<p>
May Allah bless you with success, health,
and unlimited happiness.

Tum sirf dost nahi, bhai ho.

Har baat pe kehne wale...

</p>

<div class="repeat">
Thek Hy 😎 Thek Hy 😎 Thek Hy 😎
</div>

<p>
Stay blessed. Stay strong.

With Best Wishes ❤️  
By Ahmad Muntaja
</p>
</div>

<audio id="music" loop>
<source src="https://www2.cs.uic.edu/~i101/SoundFiles/HappyBirthday.wav">
</audio>

</div>

<script>
function showMsg(){
document.getElementById("msg").style.display="block";
document.getElementById("music").play();
}
</script>

</body>
</html>
