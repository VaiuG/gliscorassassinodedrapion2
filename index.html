const readline = require('readline');
const rl = readline.createInterface({
    input: process.stdin,
    output: process.stdout
});
function pedeNumero(pergunta) {
  return new Promise((resolve) => {
  function solicitar() {
  rl.question(pergunta, (resposta) => {
  const valor = Number(resposta.replace(',', '.'));

if (!isNaN(valor) && valor > 0) {
resolve(valor);
                } else {
console.log("Digite um número válido e maior que zero!");
solicitar();
}
});
}
     solicitar();
});
}

function calRenda(saldo, taxa, meses) {
    let total = saldo;

    for (let i = 1; i <= meses; i++) {
        const rendimento = total * (taxa / 100);
        total += rendimento;
        console.log(`No ${i}º mês a aplicação rendeu R$ ${rendimento.toFixed(2).replace('.', ',')} e o total aplicado passou a ser R$ ${total.toFixed(2).replace('.', ',')}`);
    }
    console.log(`O saldo final da aplicação será de R$ ${total.toFixed(2).replace('.', ',')}`);
}

async function inicio() {
    const saldo = await pedeNumero("Informe o saldo inicial: ");
    const taxa = await pedeNumero("Informe a taxa (%): ");
    const meses = Math.floor(await pedeNumero("Informe os meses: "));

    calRenda(saldo, taxa, meses);
    rl.close();
}

inicio();
