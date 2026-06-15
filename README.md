<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Zahra ❤️</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Segoe UI',sans-serif;
}

body{
background:linear-gradient(135deg,#ff7eb3,#ffb6d9,#ffd6ec);
overflow-x:hidden;
text-align:center;
min-height:100vh;
color:white;
}

.hero{
padding:60px 20px;
}

h1{
font-size:3rem;
animation:pulse 2s infinite;
}

.subtitle{
font-size:1.3rem;
margin-top:10px;
}

.friendship{
margin-top:15px;
font-size:1.1rem;
}

.btn{
margin-top:25px;
padding:15px 35px;
border:none;
border-radius:50px;
background:white;
color:#ff4d94;
font-size:18px;
font-weight:bold;
cursor:pointer;
}

.card{
display:none;
background:white;
color:#ff4d94;
max-width:800px;
margin:30px auto;
padding:30px;
border-radius:25px;
box-shadow:0 0 25px rgba(0,0,0,.2);
}

.cake{
font-size:100px;
margin:20px 0;
animation:bounce 1.5s infinite;
}

.heart{
position:fixed;
font-size:25px;
animation:float 8s linear infinite;
pointer-events:none;
}

@keyframes float{
0%{
transform:translateY(100vh);
opacity:1;
}
100%{
transform:translateY(-120vh);
opacity:0;
}
}

@keyframes pulse{
50%{
transform:scale(1.08);
}
}

@keyframes bounce{
50%{
transform:translateY(-10px);
}
}

footer{
margin:40px;
font-size:18px;
}
</style>
</head>

<body>

<div class="hero">

<h1>🎂 Happy Birthday 🎂</h1>

<h2>Zahra Majideen ❤️</h2>

<p class="subtitle">15 June ✨</p>

<p class="friendship">
💕 Celebrating 6 Beautiful Years Of Friendship 💕
</p>

<div class="cake">🎂</div>

<button class="btn" onclick="showLetter()">
Open Your Surprise 🎁
</button>

<div class="card" id="letter">

<h2>💌 A Special Letter For Zahra 💌</h2>

<br>

<p>
My Dearest Zahra ❤️
<br><br>

Today is not just your birthday,
it is a celebration of the wonderful person you are.
For the last 6 years, you have been one of the most precious parts of my life.
<br><br>

Thank you for every laugh,
every memory,
every late-night conversation,
and every moment of support.
<br><br>

You are more than a best friend.
You are family. 💕
<br><br>

May Allah bless you with happiness,
success,
good health,
barakah,
and endless smiles.
<br><br>

May every dream in your heart come true
and may your future be brighter than ever. ✨
<br><br>

Happy Birthday to the most amazing friend.
I am lucky to have you in my life. 🎂❤️
<br><br>

Forever grateful for our friendship.
</p>

<br>

<h3>
With Lots Of Love ❤️
</h3>

<h2>
Fatima Hafeez
</h2>

</div>

<footer>
🎉 Happy Birthday Zahra 🎉
</footer>

</div>

<script>

function showLetter(){
document.getElementById("letter").style.display="block";
window.scrollTo({
top:document.body.scrollHeight,
behavior:"smooth"
});
}

setInterval(()=>{

let heart=document.createElement("div");

heart.className="heart";

heart.innerHTML=["💖","💕","💗","💞"][Math.floor(Math.random()*4)];

heart.style.left=Math.random()*100+"vw";

heart.style.fontSize=(20+Math.random()*30)+"px";

document.body.appendChild(heart);

setTimeout(()=>{
heart.remove();
},8000);

},250);

</script>

</body>
</html>
