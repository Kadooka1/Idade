📊 Classificador de Desempenho

Um projeto simples em HTML, CSS e JavaScript que classifica o desempenho de um aluno com base na nota informada (0 a 10), utilizando estruturas condicionais if, else if e else.

📌 Descrição

O usuário digita uma nota e, ao clicar no botão Analisar, o sistema exibe uma mensagem informando o nível de desempenho:

🌟 Excelente

✅ Bom

⚠️ Regular (Recuperação)

❌ Insuficiente

A cor do texto muda dinamicamente conforme o resultado.

🚀 Tecnologias Utilizadas

HTML5

CSS3

JavaScript (Vanilla JS)

🖥️ Como Usar

Abra o arquivo .html no navegador.

Digite uma nota entre 0 e 10.

Clique no botão Analisar.

Veja o resultado exibido na tela.

🧠 Lógica Utilizada

A classificação funciona com base nas seguintes regras:

Nota	Resultado
≥ 9	Excelente
≥ 7	Bom
≥ 5	Regular
< 5	Insuficiente

A estrutura condicional usada:

if (nota >= 9) { ... }
else if (nota >= 7) { ... }
else if (nota >= 5) { ... }
else { ... }

📂 Estrutura do Projeto
📁 projeto
 └── index.html


Todo o código (HTML, CSS e JS) está em um único arquivo.

🎯 Objetivo Educacional

Este projeto tem como objetivo:

Praticar estruturas condicionais em JavaScript

Trabalhar manipulação do DOM

Alterar estilos dinamicamente via JS

Entender a lógica de fluxo com if/else if/else

🔮 Possíveis Melhorias

Validar se o campo está vazio

Impedir notas menores que 0 ou maiores que 10

Separar CSS e JS em arquivos próprios

Adicionar animações ou feedback visual extra

Transformar em um sistema com múltiplas disciplinas
