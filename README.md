# cinderela-
<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nosso 1º Mês ❤️</title>

<style>
body{
    margin:0;
    font-family:'Georgia', serif;
    background:linear-gradient(to bottom,#9fd3ff,#eaf7ff);
    color:#fff;
    text-align:center;
}

.container{
    padding:40px 20px;
}

h1{
    font-size:42px;
    color:#ffffff;
    text-shadow:2px 2px 10px #5d9cec;
}

p{
    font-size:20px;
    max-width:700px;
    margin:auto;
    line-height:1.8;
}

.card{
    background:rgba(255,255,255,0.15);
    backdrop-filter:blur(10px);
    border-radius:20px;
    padding:30px;
    margin:30px auto;
    width:85%;
    box-shadow:0 10px 25px rgba(0,0,0,.2);
}

button{
    margin-top:25px;
    padding:15px 35px;
    border:none;
    border-radius:30px;
    background:#ffffff;
    color:#5d9cec;
    font-size:18px;
    cursor:pointer;
    font-weight:bold;
    transition:.3s;
}

button:hover{
    transform:scale(1.05);
}

#surpresa{
    display:none;
    margin-top:25px;
    font-size:22px;
    color:#fff8dc;
}

footer{
    margin-top:50px;
    padding:20px;
    font-size:16px;
    opacity:.9;
}
</style>
</head>

<body>

<div class="container">

<h1>👑 Nossa História de Conto de Fadas 👑</h1>

<div class="card">
<h2>✨ Feliz 1 Mês de Namoro ✨</h2>

<p>
Assim como na história da Cinderela, às vezes a vida guarda
momentos que parecem mágicos. Você apareceu quando eu menos esperava
e, desde então, cada dia ganhou um brilho diferente.
</p>

<p>
Obrigada por cada sorriso, por cada abraço, por todo carinho e por
me fazer sentir tão especial. Que esse seja apenas o primeiro capítulo
da nossa história e que possamos viver muitos outros meses, anos e
momentos inesquecíveis juntos.
</p>

<button onclick="mostrarMensagem()">
Abrir Minha Carta ❤️
</button>

<div id="surpresa">
💙 Meu amor, você é o meu príncipe, meu porto seguro e a pessoa que
transforma dias comuns em momentos mágicos. Feliz 1 mês de namoro!
Eu amo você infinitamente. ✨👑🤍
</div>

</div>

<footer>
💎 "E, a partir daquele dia, descobri que o verdadeiro final feliz era ao seu lado."
</footer>

</div>

<script>
function mostrarMensagem(){
document.getElementById("surpresa").style.display="block";
}
</script>

</body>
</html>
