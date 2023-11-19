# ispravleniya
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <link rel="stylesheet" href="styleses.css">
        <title>Моя веб страница</title>
    </head>
<body>
<header>
<h1>Лого</h1>
  <nav>
    <ul>
       <li><a href="#">Главная</a></li>
       <li><a href="#">О нас</a></li>
       <li><a href="#">Услуги</a></li>
        <li><a href="#">Контакты</a></li>
</ul>
</nav>
<div class="clear"></div>;
</header>
 <section>
  <h2>Добро пожаловать!<h2>
   <p>Мы рады приветствовать вас на нашей веб-странице. Здесь вы найдете много

полезной информации о нашей компании и услугах, которые мы предлагаем</p>
</section>
 <footer>
  <p>Все права защищены &amp;copy; 2023 Моя компания</p>

</footer>
</body>
 </html>

css

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}


body {
background-color: #f2f2f2;
margin: 0;
font-family: Arial, sans-serif;
color: #333;
}

header {
background-color: #333;
color: #fff;
position:fixed;
top:0;
left:0;
width:100%;
padding:20px 100px;
display:flex;
justify-content: space-between;
align-items: center;
z-index: 99;
}

nav ul {
list-style: none;
padding: 0;
margin: 0;
}

nav ul li {
display: inline;
margin-right: 100px;
}

nav ul li a {
color: #fff;

text-decoration: none;
}

.clear {
clear: both;
}

section {
padding: 220px;
}

footer {
background-color: #333;
color: #fff;
padding: 60px;
text-align: center;
}
