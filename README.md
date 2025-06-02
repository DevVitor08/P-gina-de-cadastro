<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="shortcut icon" href="img/2620777.png" type="image/x-icon">
<title>Página simples</title>
</head>
<body>
<div class="conteiner1">
<h1>LOGIN</h1>
<p class="p1">Informação em baixo do Login</p>
<input type="text" placeholder="Email">
<input type="password" placeholder="Senha">
<p class="p2">Você tem uma conta? se não clica aqui</p>
<a class="linkp2" href="#">Cadastra-se</a>
<button>Entrar</button>
<img class="icon1" src="img/icons8-google-logo-100.png" alt="">
<img class="icon2" src="img/icons8-instagram-100.png" alt="">
<img class="icon3" src="img/icons8-facebook-novo-100.png" alt="">
</div>
<div class="conteiner2">
</div>
<div class="conteiner3">
<img class="fotoPNG" src="img/Screenshot_25 (1).png" alt="">
</div>
<style>
*{
margin: 0;
padding: 0;
}

body{
background-color: rgba(167, 167, 167, 0.384);
display: flex;
justify-content: center;
align-items: center;
height: 100vh;
}

.conteiner1{
background-color: rgb(255, 255, 255);
width: 50%;
height:50vh;
border-radius: 10px 10px 10px 10px;
}

h1{
margin-top: 2vh;
margin-left: 20vh;
font-family: Arial, Helvetica, sans-serif;
}

.p1{
margin-top: 2vh;
margin-left: 14vh;
font-family: Arial, Helvetica, sans-serif;
}

input{
display: flex;
margin-left: 11.2vh;
margin-top: 3vh;
border-radius: 5px 5px 5px 5px;
border: transparent;
padding: 9px;
width: 25vh;
text-align: center;
background-color: rgba(167, 167, 167, 0.37);
}

.p2{
margin-top: 2vh;
margin-left: 6vh;
font-family: Arial, Helvetica, sans-serif;

}

.linkp2{
position: relative;
bottom: 8.3vh;
left: 35.5vh;
text-decoration: none;
font-family: Arial, Helvetica, sans-serif;
color: blueviolet;
}

button{
position: relative;
left: 7.2vh;
bottom: 2vh;
padding: 10px;
width: 15vh;
border-radius: 5px 5px 5px 5px;
border: transparent;
background-image: linear-gradient(145deg, #742ee4, #d01df0);
color: white;
cursor: pointer;
}

.icon1{
width: 8vh;
position: relative;
top: 11vh;
right: 21vh;
cursor: pointer;
}

.icon2{
width: 8vh;
position: relative;
top: 11vh;
right: 13vh;
cursor: pointer;
}

.icon3{
width: 8vh;
position: relative;
top: 11vh;
right: 5vh;
cursor: pointer;
}

.conteiner2{
background-image: linear-gradient(145deg, #742ee4, #d01df0);
position: absolute;
width: 25%;
height:50vh;
right: 48vh;
border-radius: 0 10px 10px 0;
}

.conteiner3{
background-color: rgba(137, 43, 226, 0.37);
border-radius: 10px 10px 10px 10px;
position: absolute;
width: 20%;
height:41vh;
right: 53vh;
}

.fotoPNG{
width: 25vh;
position: absolute;
left: 7vh;
top: 2.3vh;
}
</style>
</body>
</html>
