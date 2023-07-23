## Jogo da Velha em JS
Aqui foi desenvolvido um jogo multiplayer, para dois jogadores, conhecido popularmente como "Jogo da Velha", como requisito de avaliação dissertativa do curso de FULLSTACK. Instruções: O 1° Jogador iniciará jogando com o personagem de sua escolha. Clique nos espaços vazios para posicionar o seu personagem, e confirme qual é esse personagem, o primeiro a completar uma faixa, vence. Boa sorte jogadores e que vença o melhor..

## Layout do Projeto
<img src = "">

## Tecnologias Utilizadas
Front End: HTML5, CSS e JavaScript

## Inspecionando o Código
~~~Html
<!--Html-->
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jogo da Velha</title>
    <link rel="stylesheet" href="css.css">
</head>
<body>
    <h1>Jogo da Velha<img src="img/imgV.png"></h1>
        <br>
        <div class="box">
        <button class="cx1" id="linha1" onclick="clique1()">_</button>
        <button class="cx2" id="linha1" onclick="clique2()">_</button>
        <button class="cx3" id="linha1" onclick="clique3()">_</button>
            <br>
            <button class="cx4" id="linha2" onclick="clique4()">_</button>
            <button class="cx5" id="linha2" onclick="clique5()">_</button>
            <button class="cx6" id="linha2" onclick="clique6()">_</button>
                <br>
                <button class="cx7" id="linha3" onclick="clique7()">_</button>
                <button class="cx8" id="linha3" onclick="clique8()">_</button>
                <button class="cx9" id="linha3" onclick="clique9()">_</button>
                    <br>
                    <h4>Personagens:</h4>
                    <h4>Jogador 01 - BOLA || Jogador 02 - XIS</h4>
                    <button onclick="instrucao()">Instruções do Jogo</button>
                    <button onclick="reset()">Reiniciar Jogo</button><!--reiniciando a página-->

    <script src="js.js"></script>
</body>
</html>
~~~


~~~JavaScript
//JavaScript
function instrucao(){
    alert("INSTRUÇÕES DO JOGO \n O 1° Jogador iniciará jogando com o personagem de sua escolha. \n Clique nos espaços vazios para posicionar o seu personagem, e confirme qual é esse personagem, \n o primeiro a completar uma faixa, vence. \n Boa sorte jogadores e que vença o melhor.. ")
}

function reset(){ //resetando a página
    window.location.reload()
}

function clique1(){ //primeiro quadrado: superior esquerdo
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    if (Jogador == 'x'){
    let cx1 = document.querySelector(".cx1")
    cx1.value
    cx1.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx1 = document.querySelector(".cx1")
        cx1.value
        cx1.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique2(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx2 = document.querySelector(".cx2")
    cx2.value
    cx2.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx2 = document.querySelector(".cx2")
        cx2.value
        cx2.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique3(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx3 = document.querySelector(".cx3")
    cx3.value
    cx3.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx3 = document.querySelector(".cx3")
        cx3.value
        cx3.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique4(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx4 = document.querySelector(".cx4")
    cx4.value
    cx4.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx4 = document.querySelector(".cx4")
        cx4.value
        cx4.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique5(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx5 = document.querySelector(".cx5")
    cx5.value
    cx5.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx5 = document.querySelector(".cx5")
        cx5.value
        cx5.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique6(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx6 = document.querySelector(".cx6")
    cx6.value
    cx6.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx6 = document.querySelector(".cx6")
        cx6.value
        cx6.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique7(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx7 = document.querySelector(".cx7")
    cx7.value
    cx7.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx7 = document.querySelector(".cx7")
        cx7.value
        cx7.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique8(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx8 = document.querySelector(".cx8")
    cx8.value
    cx8.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx8 = document.querySelector(".cx8")
        cx8.value
        cx8.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}

function clique9(){ //segundo quadrado: superior do meio
    let Jogador = prompt("Digite a letra correspondente ao seu personagem: x/o")
    
    if(Jogador == 'x'){
    let cx9 = document.querySelector(".cx9")
    cx9.value
    cx9.innerHTML = "X"}
    else if(Jogador == 'o'){
        let cx9 = document.querySelector(".cx9")
        cx9.value
        cx9.innerHTML = "O"  
    }
    else{
        alert("Erro! Informe um personagem válido: x ou o.")
    }
}
~~~

~~~Css
/*Css*/
body{background: grey;
    color: aliceblue;}

#linha1, #linha2, #linha3{color: aliceblue;
    text-align: center;
    background-color: rgb(231, 224, 224);
    display:inline;
    font-size: 60px;
    width: 90px;}
    
img{border-radius: 50%;
    width: 80px;}

h1{text-align: center;}

.box{margin-left: 500px}    

a{text-decoration: none;
    background-color: aliceblue;
    border-radius: 20px;
    font-size: 20px;
    margin-left: 605px;}

button{border-radius: 15px;}    

button:hover{background-color: rgb(243, 74, 13);}
~~~

## Funcionalidas
° Tratamento de erro ao informar personagem que não existe.

## Propostas Futuras
° 1. Adicionar placar </br>
° 2. Adicionar mensagem de vencedor ao fim de cada rodada </br>
° 3. Adicionar opção de escolha de personagem </br>
° 4. Adicionar temas de cores ao projeto à escolha do usuário  

## Autor

Adalto Carvalho Ribeiro Simão Junior - Jul.23

