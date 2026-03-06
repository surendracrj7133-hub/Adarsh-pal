<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Surendra Ethical Hacking Learning</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>

body{
margin:0;
font-family:Arial;
background:black;
color:white;
scroll-behavior:smooth;
}

/* HEADER */

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 40px;
background:#111;
position:sticky;
top:0;
}

header h1{
color:#00ffcc;
}

nav a{
margin:0 10px;
text-decoration:none;
color:white;
font-weight:bold;
}

nav a:hover{
color:#00ffcc;
}

/* HERO */

.hero{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:linear-gradient(120deg,#000000,#0f2027,#203a43,#2c5364);
animation:bgmove 10s infinite alternate;
}

@keyframes bgmove{
0%{background-position:left}
100%{background-position:right}
}

.hero h2{
font-size:40px;
color:#00ffcc;
}

.hero button{
padding:12px 25px;
border:none;
background:#00ffcc;
border-radius:20px;
font-size:16px;
cursor:pointer;
}

.hero button:hover{
transform:scale(1.1);
}

/* SECTIONS */

section{
padding:60px 20px;
text-align:center;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
}

.card{
background:#111;
padding:25px;
border-radius:10px;
width:200px;
border:1px solid #00ffcc;
transition:0.3s;
}

.card:hover{
transform:scale(1.1);
box-shadow:0 0 15px #00ffcc;
}

/* LIST */

ul{
list-style:none;
padding:0;
}

ul li{
padding:8px;
}

/* CONTACT */

.contact{
font-size:22px;
color:#00ffcc;
}

/* FOOTER */

footer{
background:#111;
padding:20px;
text-align:center;
margin-top:40px;
}

</style>
</head>

<body>

<header>
<h1>💻 Surendra Hack Lab</h1>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#course">Course</a>
<a href="#tools">Tools</a>
<a href="#contact">Contact</a>
</nav>
</header>


<!-- HOME -->

<section class="hero" id="home">

<h2>Learn Ethical Hacking</h2>

<p>Free learning website for students, friends and teachers</p>

<button onclick="document.getElementById('course').scrollIntoView()">Start Learning</button>

</section>


<!-- ABOUT -->

<section id="about">

<h2>About Me</h2>

<p>

My name is Surendra Pal.  
I am a student who loves coding and cyber security.  

This website is created to help my friends and teachers  
learn the basics of Ethical Hacking and Cyber Security.

</p>

</section>


<!-- COURSE -->

<section id="course">

<h2>Ethical Hacking Course</h2>

<div class="cards">

<div class="card">1️⃣ What is Ethical Hacking</div>

<div class="card">2️⃣ Types of Hackers</div>

<div class="card">3️⃣ Cyber Security Basics</div>

<div class="card">4️⃣ Networking Basics</div>

<div class="card">5️⃣ Kali Linux Intro</div>

<div class="card">6️⃣ Password Security</div>

<div class="card">7️⃣ Social Engineering</div>

<div class="card">8️⃣ Website Security</div>

</div>

</section>


<!-- TOOLS -->

<section id="tools">

<h2>Popular Hacking Tools</h2>

<ul>

<li>Kali Linux</li>
<li>Nmap</li>
<li>Wireshark</li>
<li>Burp Suite</li>
<li>Metasploit</li>

</ul>

</section>


<!-- CONTACT -->

<section id="contact">

<h2>Contact</h2>

<p class="contact">📞 6398931557</p>

</section>


<footer>

<p>© 2026 Surendra Ethical Hacking Learning</p>

</footer>

</body>
</html>
