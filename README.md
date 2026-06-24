
<!DOCTYPE html>
<html lang="pt-br">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Para uma garota mais que especial ❤️</title>

<style>

/* RESET */
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

h1{
    text-align: center;
    margin-bottom: 30px;
    font-size: 40px;
    text-shadow: 0 0 15px rgb(255, 255, 255);
    animation: pulse 1.5s infinite;

}
/* BODY */
body{
    background:#050510;
    font-family:'Courier New', monospace;
    overflow:hidden;
    height:100vh;
}

/* CANVAS MATRIX */
#matrix{
    position:fixed;
    top:0;
    left:0;
    width:100%;
    height:100%;
    z-index:1;
}

/* LOGIN NEON */
#login{
    position:absolute;
    z-index:10;

    top:50%;
    left:50%;

    transform:translate(-50%,-50%);

    width:550px;

    padding:40px;

    border-radius:25px;

    background:rgba(10,10,20,.85);

    backdrop-filter:blur(10px);

    border:2px solid #00aaff;

    box-shadow:
    0 0 15px #00aaff,
    0 0 40px #00aaff;
}

/* FRASE */
.frase{
    text-align:center;
    color:#66ccff;
}

/* INPUT */
input{
    width:100%;
}

/* BOTÃO */
button{
    width:100%;
}

/* CONTAINER DA MENSAGEM */
.container{
    display:none;

    position:absolute;

    z-index:10;

    top:50%;
    left:50%;

    transform:translate(-50%,-50%);

    width:900px;

    background:rgba(255, 255, 255, 0.85);

    padding:40px;

    border-radius:25px;
}

/* TEXTO */
#texto{
    white-space:pre-line;
    color: #00aaff;
}

/* CURSOR */
.cursor{
    animation:blink .7s infinite;
}

@keyframes blink{
    50%{
        opacity:0;
    }
}

/* CORAÇÕES */
.coracao{
    position:fixed;
    top:-50px;
    z-index:2;
}

@keyframes cair{
    from{
        transform:translateY(-100px);
    }

    to{
        transform:translateY(120vh);
    }
}

</style>

</head>
<body>

<canvas id="matrix"></canvas>

<!-- LOGIN -->

<div id="login">

    <h1>SISTEMA PROTEGIDO</h1>

    <p class="frase">
        💙 Para uma garota muito especial 💙
    </p>

    <input
        type="password"
        id="senha"
        placeholder="Digite a senha">

    <button onclick="entrar()">
        Acessar
    </button>

</div>

<!-- MENSAGEM -->

<div class="container">

    <h1>💙 ACESSO AUTORIZADO 💙</h1>

    <div id="texto"></div>

    <span class="cursor">|</span>

    <div class="assinatura">
        Com amor, Gusta 💙
    </div>

</div>

<script>

// SENHA
function entrar(){

    const senha =
    document.getElementById("senha").value;

    if(senha === "2606"){

        document.getElementById("login")
        .style.display = "none";

        document.querySelector(".container")
        .style.display = "block";

        escrever();

    }else{

        alert("Senha incorreta 💙");
    }
}

// MENSAGEM DIGITANDO
const mensagem = `
Inicializando sistema...

Conectando ao coração mais incrível do mundo...💙

Que ninguem te faça duvidar da excelente pessoa que você e do grande coração que você tem 
Se a tua vida depender do meu amor, viverás além da vida, pois eu te amo além do amor,
amo tanto seu sorriso, seus olhinhos brilhantes, sua voz, seu jeitinho, amo tudo em voce,
queria que você pudesse enxergar de fato o tanto que eu te amo, e que tenho dentro de mim
uma eterna e sincera disposição em te fazer tão bem, a ponto de você nem se recordar de existir
algo diferente disso. Te tratar e te fazer sentir como você realmente merece, e que simplesmente 
te ver sorrir e alegrar seus dias mais os seus dias, tudo isso me deixa mais alegre. Saber que você
vive bem me faz viver melhor ainda, saber que posso acrescentar algo em sua vida, e que nunca vou me 
cansar de falar que a amo, porque deixo isso claro todos os dias rsrs, aaaah, se voce pudesse ao menos sentir
que eu sinto, quero sempre buscar ao maximo te transmitir o tanto que posso entregar a ti.
Teu cabelo ao vento parece o universo tentando, em silencio, em ensinar que algumas formas de beleza nao nasceram 
para serem explicadas.
sempre escolherei voce, em cem vidas, em cem mundos e em qualquer versão da realidade, ficaria mil horas olhando 
esses olhinhos tão lindos que você tem
Tudo que eu amo em você:
Seu sorriso ilumina o meu dia.
Você sempre sabe como me fazer rir.
Sua bondade me inspira.
Você me ouve com interesse genuíno.
Você apoia os meus sonhos.
Você tem os olhos mais bonitos.
Seus abraços são os melhores.
Você é incrivelmente atenciosa.
Você desperta o melhor em mim.
Você é minha melhor amiga.
Você me aceita como eu sou.
Seu amor pela aventura.
A forma como você cuida dos outros.
Sua criatividade me surpreende.
Você torna até os momentos comuns especiais.
Seu senso de humor.
A forma como você me olha.
Você é tão paciente.
Você é maior incentivadoa.
Sua inteligência.
Você é confidente.
Você me surpreende das melhores formas.
Você topa tentar coisas novas.
Seu otimismo é contagiante.
Você é incrivelmente dedicada.
Sua lealdade.
Você me faz sentir valorizada.
Sua risada é contagiante.
Você me torna uma pessoa melhor.
Seu espírito aventureira.
Você sempre está lá quando preciso de você.
Sua paixão pela vida.
A forma como você segura minha mão.
Você é um ouvinte incrível.
Sua generosidade.
Você me respeita.
Você é honesta comigo.
Você é minha rocha.
Você me faz sentir querida.
Seus beijos são mágicos.
Você é minha pessoa favorita.
Sua resiliência.
Você é meu cúmplice.
Sua força.
Você me faz sentir vivo.
Sua dedicação ao nosso relacionamento.
Seu coração caloroso.
Você torna cada dia mais brilhante.
Seu senso de estilo.
Você é minha alma gêmea.
Você sempre tem as melhores ideias.
Você é minha inspiração.
Seu altruísmo.
Você me entende.
Você me faz sentir especial.
Sua atitude positiva.
Você é tão carinhosa.
Você é meu conforto.
Seu sorriso é contagiante.
Sua risada me faz feliz.
Sua espontaneidade.
Você sempre arranja tempo pra mim.
Você é minha pessoa favorita para conversar.
Você me faz sentir importante.
Sua lealdade significa o mundo pra mim.
Você é meu apoio constante.
Seu calor humano.
Você me faz sentir compreendido.
Você é minha combinação perfeita.
Sua paciência comigo.
Você me faz rir como ninguém.
Sua natureza amorosa.
Você torna a vida divertida.
Você sempre está lá por mim.
Sua consideração.
Você faz meu coração acelerar.
Você é tudo pra mim.
Seu encorajamento.
Você é minha maior aventura.
Você me faz sentir em casa.
Sua ternura.
Você me faz sorrir.
Sua dedicação a nós.
Você é meu para sempre.
Você torna a vida digna de ser vivida.
Você é meu motivo de sorrir.
Seu amor é minha força.
Você é meu único e verdadeiro amor.


`;

let i = 0;

function escrever(){

    if(i < mensagem.length){

        document.getElementById("texto")
        .innerHTML += mensagem.charAt(i);

        i++;

        setTimeout(escrever,45);
    }
}

// MATRIX
// (cole aqui o código Matrix funcionando)

// CORAÇÕES
function criarCoracao(){

    const heart =
    document.createElement("div");

    heart.classList.add("coracao");

    heart.innerHTML = "💙";

    heart.style.left =
    Math.random()*100+"vw";

    heart.style.animation =
    "cair 6s linear";

    document.body.appendChild(heart);

    setTimeout(()=>{
        heart.remove();
    },6000);
}

setInterval(criarCoracao,300);

</script>

</body>
</html>
