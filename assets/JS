document.getElementById('btnCalcular').addEventListener('click', function() {
    const inputAno = document.getElementById('ano');
    const resultado = document.getElementById('resultado');

    const anoNascimento = Number(inputAno.value);
    const anoAtual = new Date().getFullYear();

    if (anoNascimento <= 0 || anoNascimento > anoAtual || anoNascimento < 1900) {
        resultado.textContent = 'Por favor, insira um ano válido.';
        resultado.style.color = '#ff6b6b'; // Um vermelho claro para o erro
    } else {
        const idade = anoAtual - anoNascimento;
        resultado.textContent = 'Você tem ' + idade + ' anos.';
        resultado.style.color = '#76ff7a'; // Um verde claro para o sucesso
    }
});
