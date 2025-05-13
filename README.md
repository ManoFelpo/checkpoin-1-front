# 🍷 Vinharia Agnello - Projeto de Site

## Sobre o projeto
Este projeto é a criação do site da **Vinharia Agnello**, uma tradicional vinícola de São Paulo que há mais de 15 anos oferece vinhos nacionais e internacionais com atendimento personalizado. O objetivo do site é proporcionar uma experiência online próxima à da loja física, apresentando informações, produtos e um canal de contato para os clientes.

## Estrutura do site
O site é composto pelas seguintes páginas:

- `index.html` – Página inicial com introdução sobre a vinheria e destaque para atendimento especializado.
- `historia.html` – História da Vinharia Agnello, origem e trajetória com tradição.
- `produtos.html` – Galeria de vinhos disponíveis, separados por categorias.
- `contato.html` – Formulário de contato para dúvidas, sugestões e pedidos.
- `dicas.html` – Um guia rápido de harmonização dos vinhos.

O site conta com:
- Menu de navegação funcional em todas as páginas
- Textos informativos e descritivos
- Imagens relacionadas ao mundo dos vinhos
- Um vídeo incorporado sobre vinhos
- Lista e tabela em páginas específicas
- Formulário de contato com campos de nome, e-mail e mensagem
- Estilização completa com CSS

## 🎨 Efeitos Visuais

O projeto aplica diversas **pseudo-classes**, **pseudo-elementos** e **animações CSS** para aprimorar a experiência visual e interativa do site:

### ✅ Pseudo-classes utilizadas:
- `nav li:hover`: aumenta o tamanho dos itens do menu ao passar o mouse (`scale: 1.3`).
- `.botao:hover`: altera a cor de fundo dos botões ao passar o mouse.
- `.formulario:focus`: muda a cor de fundo ao focar em campos do formulário.
- `.linkvideo:visited`: muda a cor de links já visitados.
- `.botao:active`: inicia uma animação personalizada ao clicar no botão.

### ✅ Pseudo-elemento utilizado:
- `p::selection`: estiliza o texto selecionado, mudando a cor da fonte e o fundo.

### ✅ Animação com @keyframes:
```css
@keyframes mensagemEnviada {
  0% {
    background-color: #521417;
    transform: scale(0.9);
  }
  20%, 80% {
    transform: scale(1);
  }
  100% {
    background-color: green;
    transform: scale(0.95);
  }
}
```
Essa animação é aplicada ao botão ao ser clicado, simulando envio de mensagem com efeito visual de "pulso" e troca de cor.

## 👤 Integrantes
- Felipe Santos Nunes

## 🔗 Links
- [📂 Repositório no GitHub](https://github.com/ManoFelpo/vinharia-agnello.git)
- [🌐 Site publicado no GitHub Pages](https://manofelpo.github.io/checkpoin-1-front/)
