<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio | Natthakorn</title>

<link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Prompt',sans-serif;
}

body{
    background:linear-gradient(135deg,#0f172a,#1e3a8a,#4f46e5);
    color:white;
    overflow-x:hidden;
}

body::before{
    content:"";
    position:fixed;
    width:600px;
    height:600px;
    background:#60a5fa55;
    border-radius:50%;
    top:-250px;
    right:-150px;
    filter:blur(120px);
}

body::after{
    content:"";
    position:fixed;
    width:500px;
    height:500px;
    background:#8b5cf655;
    border-radius:50%;
    bottom:-220px;
    left:-120px;
    filter:blur(120px);
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

header{
    padding:90px 0;
    text-align:center;
}

.profile{
    width:180px;
    height:180px;
    border-radius:50%;
    border:6px solid white;
    object-fit:cover;
    box-shadow:0 0 35px rgba(255,255,255,.3);
    transition:.4s;
}

.profile:hover{
    transform:scale(1.05) rotate(2deg);
}

h1{
    font-size:3rem;
    margin-top:25px;
}

.subtitle{
    color:#cbd5e1;
    margin-top:10px;
    font-size:1.1rem;
}

section{
    margin:60px 0;
}

.card{
    background:rgba(255,255,255,.08);
    backdrop-filter:blur(12px);
    border-radius:20px;
    padding:30px;
    box-shadow:0 10px 40px rgba(0,0,0,.25);
    transition:.35s;
}

.card:hover{
    transform:translateY(-8px);
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
    gap:25px;
}

h2{
    color:#93c5fd;
    margin-bottom:20px;
}

.info{
    line-height:2;
}

.skill{
    background:#2563eb;
    padding:10px 18px;
    border-radius:30px;
    display:inline-block;
    margin:8px;
    transition:.3s;
}

.skill:hover{
    background:#7c3aed;
    transform:scale(1.05);
}

footer{
    text-align:center;
    padding:50px;
    color:#dbeafe;
}

.btn{
    display:inline-block;
    margin-top:25px;
    padding:14px 35px;
    background:linear-gradient(45deg,#3b82f6,#7c3aed);
    color:white;
    text-decoration:none;
    border-radius:40px;
    font-weight:bold;
    transition:.35s;
}

.btn:hover{
    transform:translateY(-5px);
    box-shadow:0 10px 25px rgba(0,0,0,.35);
}

@media(max-width:700px){
h1{
font-size:2.2rem;
}
}
</style>

</head>
<body>

<div class="container">

<header>

<img class="profile" src="https://via.placeholder.com/180" alt="Profile">

<h1>ณัฐกรณ์ พรศิวาพัฒน์</h1>

<p class="subtitle">
Portfolio | Mathematics Education
</p>

<a href="#" class="btn">Download Portfolio</a>

</header>

<section class="grid">

<div class="card">
<h2>👤 ข้อมูลส่วนตัว</h2>

<div class="info">
ชื่อ : ณัฐกรณ์ พรศิวาพัฒน์<br>
อายุ : 17 ปี<br>
ส่วนสูง : 183 ซม.<br>
น้ำหนัก : 62 กก.<br>
จังหวัด : สมุทรสาคร
</div>

</div>

<div class="card">
<h2>🎓 การศึกษา</h2>

<div class="info">
โรงเรียนกระทุ่มแบน (วิเศษสมุทรคุณ)<br>
GPAX : <b>3.65</b><br>
สาขาที่สมัคร<br>
ครุศาสตร์ สาขาคณิตศาสตร์
</div>

</div>

</section>

<section class="card">

<h2>✨ About Me</h2>

<p style="line-height:2;">
ผมมีความสนใจด้านคณิตศาสตร์มาตั้งแต่เด็ก
ชอบการคิดวิเคราะห์ การแก้ปัญหา และมีความตั้งใจที่จะเป็นครูคณิตศาสตร์ที่สามารถสร้างแรงบันดาลใจให้กับนักเรียน
พร้อมพัฒนาตนเองอย่างต่อเนื่องทั้งด้านความรู้และทักษะการสอน
</p>

</section>

<section class="card">

<h2>💻 Skills</h2>

<span class="skill">Mathematics</span>
<span class="skill">Teaching</span>
<span class="skill">Problem Solving</span>
<span class="skill">HTML</span>
<span class="skill">CSS</span>
<span class="skill">Canva</span>
<span class="skill">Microsoft Office</span>

</section>

<section class="card">

<h2>🏆 Goals</h2>

<p style="line-height:2;">
ศึกษาต่อคณะครุศาสตร์ สาขาคณิตศาสตร์
เพื่อพัฒนาความรู้ด้านการสอน
และเป็นครูที่ช่วยให้นักเรียนเข้าใจคณิตศาสตร์ได้ง่าย สนุก และสามารถนำไปใช้ในชีวิตจริง
</p>

</section>

<footer>

© 2026 Portfolio | Designed with HTML & CSS ❤️

</footer>

</div>

</body>
</html>
