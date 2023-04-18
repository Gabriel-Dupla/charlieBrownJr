<h1 align="center">Projeto: charlieBrownJr</h1>

<div>
  <p align="center">
    <img alt="Status do projeto com os dizeres: Concluído" src="https://img.shields.io/static/v1?label=Status&message=Concluído &color=green">
  </p>
</div>

## **Sobre**

Desenvolvimento da página **Início** e da página de **Picos** do site da HZC. O projeto foi elaborado ao longo do cursos de [CSS: dispondo elementos com Flexbox e Grid](https://cursos.alura.com.br/course/css-dispondo-elementos-flexbox-grid), realizado na plataforma [Alura](https://www.alura.com.br/) e orientado pelo instrutor Matheus Alberto. O objetivo do projeto foi aprofundar os conhecimentos em HTML e CSS, por meio do uso de tags semânticas, estruturas de HTML mais complexas e novas propriedades como grid.

## **Aprendizagens** 

- Uso da tag `<article>` para criar cartões
- Uso do método toggle para criar um menu lateral oculto
- Incorporar ícones como fontes à página, fazendo uso de pseudo-elementos para mostrar tais ícones ( `::before` `::after` )
- Propriedades do display `grid`:`grid-template-column`, `grid-template-row`, `grid-template-area`, `grid-area`, `grid-column`, `grid-row`, `row-gap`, `column-gap`, `span`, `repeat(valor1, valor2)`
- Uso de propriedades do display `flex`: `justify-content`, `gap`, `align-itens`, entre outras.
- Como fazer os itens aparecerem em um tamanho de display e sumirem em outro por meio do `display:none` e `display:block`
- Uso da técnica de mobile-first

## **Como usar os arquivos?**

- Inicialmente você precisa ter instalado em seu computador um editor de código-fonte, no meu caso eu utilizo o [Visual Studio Code](https://code.visualstudio.com/download). 
- Depois, você pode fazer o download do projeto clicando na opção **Code** e em seguida selecionando **Download Zip**.

<p>Ou</p>

1. Clonar o repositório

```
clone https://github.com/Gabriel-Dupla/charlieBrownJr.git
```
2. Localizar e abrir a pasta *charlieBrownJr*

```
cd charlieBrownJr
```

# Guia de estilos

Toda a estilização que será usada no projeto dentro do figma.

[Link do projeto no figma](https://www.figma.com/file/ibWktwVpnog76rMYOdVhks/Dispondo-elementos-com-flexbox-e-grid?node-id=54%3A2358)

## Fonte

```html
Open Sans:
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@400;600;700&display=swap">
```

## Cores

corpo: `#1D232A`

cabeçalho: `#1D232A`

cabeçalho mobile: `#15191C`

menu lateral: `#15191C`

cartão: `#2C343A`

fonte: `#FFFFFF`

fonte alternativa: `#95999C`

links: `#0480DC`

botão: `#0480DC`

sombras: `0px 4px 4px rgba(0, 0, 0, 0.16)`

## Ícones

Estão dentro do arquivo de fonte `icones.ttf`. Para usar, primeiro importe a fonte no projeto usando `@font-face` e depois utilize os códigos abaixo para exibir o ícone.

```css
@font-face {
    font-family: 'icones';
    src: url(../font/icones.ttf);
}
```

> Cuidado com a localização do arquivo `icones.ttf`

Camisas = `\e900`

Carrinho = `\e901`

Inicio = `\e902`

Integrantes = `\e903`

Menu = `\e904`

Moeda = `\e905`

Notificação = `\e906`

Pico = `\e908`

Picos = `\e909`

Pinturas = `\e90a`

Play = `\e90b`

Relogio = `\e90c`

Seta-baixo = `\e90d`

Videos = `\e90e`

Visualizacao = `\e90f`

## Espaçamentos

Espaço interno botão: `8px`

Espaço entre elementos do botão: `8px`

Espaço entre elementos: `16px/8px`

Espaçamento interno do corpo: `16px`

Espaçamento entre o título do cartão de recentes e seus itens: `24px`

## Tamanhos

Tamanho do dispositivo mobile: `360px`

Tamanho do dispositivo desktop: `1440px`

Largura máxima do conteúdo principal: `1120px`

Largura máxima de um cartão desktop: `256px`

Altura mínima de um cartão: `320px`

## **Tecnologias usadas**

Neste projeto foram usadas as seguintes linguagens:

<p>
 <img align="center" alt="HTML 5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
 <img align="center" alt="CSS 3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
 <img align="center" alt="JavaScript" src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E">
</p>

Para a construção dos códigos que compõem a página foi utilizado o editor de código-fonte abaixo:

<img align="center" alt="VS Code" src="https://img.shields.io/badge/Visual_Studio-5C2D91?style=for-the-badge&logo=visual%20studio&logoColor=white">
