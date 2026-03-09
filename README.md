<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>11 APOSTLES</title>

<style>

/* cores */
:root{
--blue:#4f6df5;
--black:#000;
--white:#fff;
}

/* fundo */
body{
margin:0;
background:var(--black);
color:var(--white);
font-family:Arial, Helvetica, sans-serif;
text-align:center;
}

/* header */
header{
padding:30px;
font-weight:bold;
letter-spacing:4px;
}

/* logo */
.logo{
margin-top:120px;
}

.logo img{
max-width:420px;
width:90%;
}

/* título */
h1{
font-size:48px;
margin-top:20px;
letter-spacing:6px;
}

/* botão */
.btn{
display:inline-block;
margin-top:40px;
background:var(--blue);
padding:15px 40px;
color:white;
text-decoration:none;
font-weight:bold;
border-radius:6px;
transition:.3s;
}

.btn:hover{
transform:scale(1.05);
}

/* faixa animada */
.apostle-bar{
position:fixed;
bottom:0;
left:0;
width:100%;
background:var(--blue);
overflow:hidden;
white-space:nowrap;
}

.apostle-bar span{
display:inline-block;
padding-left:100%;
font-weight:bold;
font-size:22px;
color:white;
animation:scroll 15s linear infinite;
}

@keyframes scroll{
0%{transform:translateX(0);}
100%{transform:translateX(-100%);}
}

</style>
</head>

<body>

<header>
11 APOSTLES
</header>

<div class="logo">
<img src="logo.png">
<h1>11 APOSTLES</h1>

<p>UMA MARCA PARA OS VALENTES</p>

<a class="btn" href="#">
TORNE-SE UM APÓSTOLO
</a>
</div>

<div class="apostle-bar">
<span>
✦ TORNE-SE UM APÓSTOLO ✦ TORNE-SE UM APÓSTOLO ✦ TORNE-SE UM APÓSTOLO ✦ TORNE-SE UM APÓSTOLO
</span>
</div>

</body>
</html>