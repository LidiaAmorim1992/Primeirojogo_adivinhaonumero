<meta charset="UTF-8">

<script>

    function pulaLinha() {

        document.write("<br>");
        document.write("<br>");
}

    function mostra(frase) {

        document.write(frase);
        pulaLinha();
}

var numeroPensado = Math.round(Math.random() *10);

var chute = parseInt(prompt("Digite o seu chute!"));

if(chute == numeroPensado) {

	mostra("Você acertou!");
}

else {

	mostra("Você errou! o número pensado foi " + numeroPensado);
}

</script>
