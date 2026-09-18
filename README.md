# Exercício 2 - CSS (INF 321)

Atividades práticas da aula de introdução ao **CSS** da disciplina **INF 321 - Projeto e Desenvolvimento de Sistemas para a Web** (Universidade Federal de Viçosa - UFV).

- **Professor:** Lucas Vegi
- **Aluno:** Rafael Caetité
- **Período:** 2026/2

O trabalho foi desenvolvido utilizando **CSS3** para estilizar as páginas criadas no Exercício 1, atendendo a todos os requisitos solicitados nos slides da aula (Slides 60 a 65).

---

## Links

- **Repositório no GitHub:** https://github.com/rafaelcaetite/ufv-inf321-exercicio2
- **Visualização (GitHub Pages):** https://rafaelcaetite.github.io/ufv-inf321-exercicio2/

---

## Arquivos do Projeto

- `index.html` - Página principal contendo as duas seções estilizadas (Disciplina e Produtos)
- `produtos.html` - Página individual de produtos com os cards e a barra PRODUTOS
- `disciplina.html` - Página individual da disciplina estilizada
- `style.css` - Arquivo com todas as regras de CSS da página
- `img/` - Imagens utilizadas nos produtos e na página

---

## O que foi implementado

### 1. Cards de Produtos (Slide 61)
- Barra superior com fundo escuro e título `PRODUTOS`
- Cards individuais para cada produto com bordas arredondadas e sombra suave:
  - **Notebook:** R$ 5.000 (preço em verde) e botão azul `Comprar`
  - **Celular:** R$ 3.000 (preço em verde) e botão azul `Comprar`
  - **Tablet:** R$ 2.000 (preço em verde) e botão azul `Comprar`
  - Cards adicionais para os periféricos do Exercício 1 (Mouse e Teclado)

### 2. Elementos e Propriedades Estilizadas (Slide 62)
- **Elementos obrigatórios estilizados:**
  - `body`, títulos (`h1`, `h2`, `h3`) e parágrafos (`p`)
  - Links (`a`) e imagens (`img`)
  - Cards de produtos (`.card`)
  - Botões (`button`), formulários (`form`, `input`, `textarea`)
  - Tabelas (`table`, `th`, `td`)
- **Propriedades utilizadas:**
  - `color` e `background-color`
  - `font-size`
  - `padding` e `margin`
  - `border` e `border-radius`
  - `width` e `max-width`
  - `display: flex`

### 3. Layout Responsivo (Slide 63 - Desafio Extra)
- **Desktop (Lado a Lado):** cards posicionados na horizontal com `display: flex` e `flex-direction: row`
- **Celular (Empilhado):** regra de `@media (max-width: 768px)` que altera o layout para `flex-direction: column`, empilhando os cards verticalmente para facilitar a visualização em telas estreitas
