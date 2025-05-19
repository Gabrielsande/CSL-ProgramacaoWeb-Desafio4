# 💡 Controle de Luz – Simulador de Interruptor

Este projeto simula um interruptor digital que liga e desliga uma lâmpada virtual em um ambiente realista, utilizando apenas HTML, CSS e JavaScript. Ele foi desenvolvido como parte do curso técnico em informática com o objetivo de praticar DOM, eventos e manipulação de classes.

## 🎯 Objetivos do Projeto

- Criar um botão (interruptor) que altera o estado da luz
- Alternar entre imagens de lâmpada acesa e apagada
- Trabalhar com `classList.toggle()` para manipular classes no DOM
- Adicionar interatividade e estilo visual realista

## ✅ Requisitos atendidos

- ✅ Imagem de lâmpada acesa e apagada
- ✅ Botão que altera o estado da luz
- ✅ Efeito visual de ligar/desligar a luz (com plano de fundo que escurece)
- ✅ Contador de vezes que a luz foi acesa
- ✅ Botão “Ver Contagem” com resultado exibido diretamente na página
- ✅ Efeito visual (fade-in/fade-out) na lâmpada

## ✨ Melhorias implementadas

- 💠 Efeito de transição na troca da imagem
- 🛏️ Cenário de fundo escurece com a lâmpada
- 🔢 Contador visível das vezes que a luz foi acesa
- 🎨 Estilização do interruptor e do botão com efeitos visuais
- 📦 Estrutura organizada para facilitar futuras melhorias

## 🖼️ Imagens

### Imagem de Fundo:

![Imagem de Fundo](imagens/plano-de-fundo-para-chamadas-de-zoom-com-estante)

### Luz acesa:

![Luz acessa](imagens/lampadaLigada.png)


### Luz apagada:

![Luz apagada](imagens/lampadaDesligada.png)


## 🛠️ Como modificar a imagem usada

As imagens da lâmpada são definidas no JavaScript. Para trocar por outras imagens, basta substituir os arquivos `lampadaLigada.png` e `lampadaDesligada.png` na pasta do projeto. Certifique-se de manter o mesmo nome ou atualizar no código JS:

```js
lampada.src = ligado ? 'lampadaLigada.png' : 'lampadaDesligada.png';
