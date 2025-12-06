<!DOCTYPE html>

 <center><button id="mais" style="border-radius: 20px; background: #118ead; color: #fff; padding: 100px;">
    Adição
</button></center>

<center><button id="sub" style="margin-top: 20px; border-radius: 20px; background: #03ffd5; color: #000000; padding: 100px;">Subtração</button></center>

<center><button id="vezes" style="margin-top: 25px; border-radius: 20px; background: #118ead; color: #fff; padding: 100PX ;">Multiplicação</button></center>

<center><button id="random" style="margin-top: 20px; border-radius: 20px; background: #03ffd5; color: #000000; padding: 100px;">Número Aleatorio</button></center>


<!--Adição-->
<script>

const botao = document.getElementById("mais");
botao.addEventListener("click", function () {


const num1 = Number(prompt ("Primeiro número da Adição:"));
const num2 = Number(prompt (" Segundo número número:"));


alert (num1 + num2);
    

})

<!--Subtração-->

const botao1 = document.getElementById("sub");
botao1.addEventListener("click", function () {


const num1 = Number(prompt ("Primeiro número da Subtração:"));
const num2 = Number(prompt ("Segundo número da Subtração:"));


alert (  num1 - num2);
    

})


const botao2 = document.getElementById("vezes");
botao2.addEventListener("click", function () {


const num1 = Number(prompt ("Primeiro número:"));
const num2 = Number(prompt (" seg número:"));


alert (num1 * num2);
    

})


const botao3 = document.getElementById("random");

botao3.addEventListener("click", function () {

    const num1 = Math.floor(Math.random() * 100) + 1;
    const num2 = Math.floor(Math.random() * 10) + 1;

    alert(num1);      
    
});


</script>
