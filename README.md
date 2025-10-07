# Fundo Mágico

Uma aplicação web pequena e prática que gera "fundos mágicos" (backgrounds visuais) a partir de uma descrição em texto. Foi feita como projeto de aprendizado — o código é simples, claro e pensado para quem está começando, mas já com boas práticas básicas.

Aqui eu tento explicar o que o projeto faz, como ele funciona (inclusive a parte do webhook no n8n).

---

## O que faz

- O usuário escreve uma descrição (ex.: "céu estrelado em tons roxos com nuvens suaves").
- O front-end envia essa descrição para um webhook (n8n) que processa a requisição e devolve um JSON com dois campos principais: `code` (HTML do preview) e `style` (CSS adicional).
- O front-end mostra o preview ao vivo, exibe o HTML/CSS retornados e injeta o CSS dinamicamente na página.

É uma ferramenta de prototipagem visual: serve para experimentar ideias de backgrounds sem precisar escrever tudo na mão.

---

## Tecnologias

- HTML5
- CSS3
- JavaScript (vanilla)
- n8n (workflow / webhook de processamento)


4. Abra um pull request descrevendo o que foi alterado.

Se for a primeira contribuição, um README claro como este ajuda bastante — obrigado!
