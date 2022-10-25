<h1 align="center"> RocketPay </h1>

<p align="center">
Explorer lab 01: Evento exclusivo e gratuito, promovido pela Rocketseat para ensino de tecnologias WEB.
</p>

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

<p align="center">
  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=49AA26&labelColor=000000">
</p>

<br>

<p align="center">
  <img alt="rocketpay" src=".github/project.png" width="100%">
</p>

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- HTML e CSS
- JavaScript e JSON
- [Node e NPM](https://nodejs.org/)
- [Vite](https://vitejs.dev/)
- [iMask](https://imask.js.org)

## 💻 Projeto

O Rocketpay é uma pequena aplicação que simula o formulário de preenchimento de cartão de crédito, implementando máscara de dados(IMask) para entradas de datas e números aos cortões de crédito, usando expressões regulares(regex) para validar o tipo de cartão que será adicionado e atualizar elementos HTML via DOM. 

Apliquei mais dois cartões, o do american express e o union pay para praticar o que foi passado.

**Exemplos:**

- Quando o número do cartão começa com 4, automaticamente ele vai para o visa e com suas cores.
- Quando começa com 3 e o próximo número for maior que 47, ele vai para o american express e com as suas cores.
- Quando começa com 5 e o próximo número for maior que 1 até 5, ele vai para o mastercard e com as suas cores.
- Quando começa com 62, ele vai para o union pay e com as suas cores.
- Se não for nenhum desses, ele fica com o valor padrão.

## 🔖 Layout

Você pode visualizar o layout do projeto através [DESSE LINK](https://www.figma.com/file/gpqavL469k0pPUGOmAQEM9/Explorer-Lab-%2301/duplicate). É necessário ter conta no [Figma](https://figma.com) para acessá-lo.

## :memo: Licença

Esse projeto está sob a licença MIT.

---
