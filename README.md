# webmotors

Carro usado versus carro desejado 
<br>
Qual compensa mais para seu bolso?
<br>
 Consulte <a href=https://www.webmotors.com.br/>aqui</a> caso tenha duvidas nas especificações dos veículos.
  <br>
<script>
var login = prompt("Digite o seu email ");
if(login == "carshenriquearaujo@gmail.com" || "wagnerassis@gmail.com" || "paulovieira@gmail.com"){
} else {
alert("acesso negado")
}
    var senha = parseInt(prompt("digite sua senha "));
if(senha == "tutu" || "theo" || "jasmine" ) {
    alert("Acesso liberado!");
} else {
    alert("Acesso negado!");
}
alert(" SOMENTE NÚMEROS SÃO PERMITIDOS ");
function pulaLinha(){
document.write("<br>");
}
function mostra(frase) {
document.write(frase);
pulaLinha();
  }
function calculaKmPorLitro(distancia,tanque){
return distancia/tanque;
  }     
let nomeCarroUsado = prompt("informe o nome do seu veículo ");
let carroUsado= calculaKmPorLitro(parseInt((prompt("informe a distancia percorrida do seu carro atual"))),parseInt(prompt("tamanho em litros do tanque do seu carro atual ")));
let nomeCarroNovo = prompt("informe o nome do carro desejado ");
    let carroNovo = calculaKmPorLitro(parseInt((prompt("informa a distancia percorrida do seu carro desejado "))),parseInt(prompt("tamanho em litros do tanque do seu carro desejado ")));
mostra("O "+ nomeCarroUsado + " faz " + carroUsado + " litros por km ");
mostra("O " + nomeCarroNovo + " faz " + carroNovo + " litros por km ");
if(carroUsado > carroNovo) {
    mostra(" O " + nomeCarroUsado + " consome menos combustível do que o " + nomeCarroNovo);
}
if(carroUsado < carroNovo) {
    mostra("O " + nomeCarroNovo + " consome menos combustível do o " + nomeCarroUsado);
}
if(carroUsado == carroNovo) {
    mostra(" Os dois irão consumir a mesma quantidade de combustível ");
}
</script>