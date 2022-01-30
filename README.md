# Calcula-Imc
<meta charset ="UTF-8">

<script>

function pulalinha() {

    document.write("<br>");

    document.write("<br>");
}


function mostra(frase) {

    document.write(frase);
    pulaLinha();
}

function calculaImc(altura, peso) {

    return peso / (altura * altura);

}


var totalImc = imcFlavio(1.71, 73) + imcAmigo(1.72, 68);

document.write("A soma dos icm's é" + totalImc);

function calculaImc(altura, peso) {

    return peso / (altura * altura);
}

var imcFlavio = calculaImc(1.71, 73);
var imcAmigo = calculaImc(1.72, 68);
var totalImc = imcFlavio + imcAmigo;

document.write("A soma dos imc's é " + totalImc);
</script>
