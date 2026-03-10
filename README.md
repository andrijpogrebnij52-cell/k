<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Мій сайт</title>

<style>
body{
    margin:0;
    font-family:Arial, sans-serif;
    background:#0f172a;
    color:white;
}

header{
    background:#1e293b;
    padding:20px;
    text-align:center;
}

nav a{
    color:#38bdf8;
    margin:0 15px;
    text-decoration:none;
    font-weight:bold;
}

.hero{
    padding:100px 20px;
    text-align:center;
}

.hero h1{
    font-size:48px;
}

button{
    padding:12px 25px;
    font-size:16px;
    border:none;
    border-radius:8px;
    background:#38bdf8;
    cursor:pointer;
}

section{
    padding:60px 20px;
    max-width:900px;
    margin:auto;
}

footer{
    background:#1e293b;
    text-align:center;
    padding:20px;
    margin-top:40px;
}
</style>

</head>
<body>

<header>
<h2>Мій перший сайт</h2>
<nav>
<a href="#about">Про мене</a>
<a href="#projects">Проєкти</a>
<a href="#contact">Контакт</a>
</nav>
</header>

<div class="hero">
<h1>Привіт 👋</h1>
<p>Це сайт, розміщений через GitHub Pages</p>
<button onclick="hello()">Натисни мене</button>
</div>

<section id="about">
<h2>Про мене</h2>
<p>Тут буде інформація про вас.</p>
</section>

<section id="projects">
<h2>Проєкти</h2>
<p>Опишіть свої проєкти або портфоліо.</p>
</section>

<section id="contact">
<h2>Контакт</h2>
<p>Email: example@email.com</p>
</section>

<footer>
<p>© 2026 Мій сайт</p>
</footer>

<script>
function hello(){
    alert("Дякую що відвідав мій сайт!");
}
</script>

</body>
</html>
