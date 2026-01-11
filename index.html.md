```
<!DOCTYPE html>
<html lang="en">
<
```
```
head>

```
```
<
```
```
meta charset="UTF-8">

```
```
<
```
```
meta name="viewport" content="width=device-width, initial-scale=1.0">

```
```
<title>For Mirabel ❤️</title>

<
```
```
style>

```
```
* {
  margin: 0;
  
```
```
padding: 0;

```
```
  
```
```
box-sizing: border-box;

```
```
  font-family: 'Georgia', serif;
}

body
```
```
 {

```
```
  
```
```
min-height: 100vh;

```
```
  
```
```
background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);

```
```
  
```
```
display: flex;

```
```
  
```
```
align-items: center;

```
```
  
```
```
justify-content: center;

```
```
  color: #fff;
  
```
```
overflow: hidden;

```
```
}

.container
```
```
 {

```
```
  
```
```
max-width: 520px;

```
```
  
```
```
padding: 30px;

```
```
  text-align: center;
  
```
```
z-index: 2;

```
```
  
```
```
animation: fadeIn 2s ease;

```
```
}

h1
```
```
 {

```
```
  
```
```
font-size: 2.3em;

```
```
  
```
```
margin-bottom: 15px;

```
```
}

p {
  font-size: 1.1em;
  
```
```
line-height: 1.7;

```
```
  
```
```
margin-bottom: 25px;

```
```
}

.gallery
```
```
 {

```
```
  display: flex;
  
```
```
gap: 12px;

```
```
  
```
```
justify-content: center;

```
```
  
```
```
margin-bottom: 25px;

```
```
}

.gallery
```
```
 img {

```
```
  
```
```
width: 105px;

```
```
  
```
```
height: 140px;

```
```
  object-fit: cover;
  
```
```
border-radius: 14px;

```
```
  box-shadow: 0 0 18px rgba(255,255,255,0.25);
  
```
```
transition: transform 0.4s ease;

```
```
}

.gallery
```
```
 img:hover {

```
```
  
```
```
transform: scale(1.05);

```
```
}

button
```
```
 {

```
```
  
```
```
padding: 13px 32px;

```
```
  
```
```
border-radius: 30px;

```
```
  
```
```
border: none;

```
```
  
```
```
background: #ff5f7e;

```
```
  color: white;
  
```
```
font-size: 1em;

```
```
  
```
```
cursor: pointer;

```
```
  
```
```
transition: transform 0.3s;

```
```
}

button:hover {
  
```
```
transform: scale(1.1);

```
```
}

.response
```
```
 {

```
```
  
```
```
display: none;

```
```
  margin-top: 25px;
  
```
```
font-size: 1.3em;

```
```
  
```
```
color: #ffb6c1;

```
```
}

.heart {
  position: fixed;
  bottom: -10px;
  
```
```
font-size: 20px;

```
```
  animation: floatUp 6s linear infinite;
  
```
```
opacity: 0.8;

```
```
}

@keyframes
```
```
 floatUp {

```
```
  from { transform: translateY(0); opacity: 1; }
  
```
```
to { transform: translateY(-100vh); opacity: 0; }

```
```
}

@keyframes fadeIn {
  from { opacity: 0; transform: translateY(20px); }
  
```
```
to { opacity: 1; transform: translateY(0); }

```
```
}
</style>
</head>

<body>

<
```
```
audio id="music" loop>

```
```
  <
```
```
source src="love-my-baby.mp3" type="audio/mpeg">

```
```
</audio>

<div class="container">
  <
```
```
h1>Mirabel ❤️</h1>

```
```

  <
```
```
p>

```
```
    From the moment you walked into my life, something shifted.
    Your smile, your presence, the way you carry yourself —
    it all feels like peace to me.
    <
```
```
br><br>

```
```
    I don’t want to rush life.  
    I just know I want to experience it with you.
  </p>

  <
```
```
div class="gallery">

```
```
    <
```
```
img src="mirabel1.jpg">

```
```
    <img src="mirabel2.jpg">
    <
```
```
img src="mirabel3.jpg">

```
```
  </
```
```
div>

```
```

  <
```
```
h2>Will you be my girlfriend?</h2>

```
```
  <br>
  <
```
```
button onclick="sayYes()">Yes 💕</button>

```
```

  <
```
```
div class="response" id="response">

```
```
    You just made me the happiest person alive, Mirabel.
    <br><br>
    With love,<br>
    — Sage 💖
  </
```
```
div>

```
```
</div>

<
```
```
script>

```
```
function sayYes() {
  document.getElementById(
```
```
"response").style.display = "block";

```
```
  document.getElementById("music").play();
}

// Floating hearts
setInterval(() => {
  const heart = document.createElement("div");
  heart.className = 
```
```
"heart";

```
```
  heart.innerHTML = 
```
```
"💖";

```
```
  heart.style.left = Math.random() * 
```
```
100 + "vw";

```
```
  heart.style.fontSize = Math.random() * 
```
```
20 + 15 + "px";

```
```
  document.body.appendChild(heart);

  setTimeout(() => heart.remove(), 6000);
}, 
```
```
500);

```
```
</
```
```
script>

```
```

</body>
</
```
```
html>
```
```


```
