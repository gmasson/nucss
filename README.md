# NuCSS – Framework CSS Semântico e Minimalista

**NuCSS** é uma biblioteca CSS projetada para estilizar elementos HTML5 de forma semântica e elegante, **sem o uso de classes**. Focada na simplicidade, responsividade e acessibilidade, ela redefine o visual padrão de elementos nativos usando apenas seletores diretos e variáveis CSS.

---

## Recursos e Benefícios

- Estilização automática de **todos os elementos HTML5**
- Sem uso de classes ou IDs
- Compatível com formulários, tabelas, mídia, blocos interativos, etc.
- Tema centralizado via `:root` (cores, espaçamentos, fontes, sombras, etc.)
- Tipografia elegante e hierárquica
- Responsividade embutida por padrão
- Acessibilidade básica respeitada

---

## Exemplos de Elementos Suportados

A página `example.html` cobre os seguintes blocos, todos estilizados com NuCSS puro:

- **Artigos e texto enriquecido** (`<article>`, `<blockquote>`, `<mark>`, `<kbd>`, etc.)
- **Formulários completos** (`input`, `textarea`, `select`, `button`, etc.)
- **Tipografia** (`<h1>–<h6>`, `<small>`, `<sup>`, `<sub>`, etc.)
- **Elementos multimídia** (`<img>`, `<video>`, `<audio>`, `<svg>`, `<canvas>`)
- **Tabelas** (`<table>`, `<thead>`, `<tfoot>`, etc.)
- **Componentes interativos** (`<details>`, `<summary>`, `<progress>`, `<meter>`)
- **Blocos HTML5 adicionais** (`<address>`, `<aside>`, `<figure>`, `<time>`, etc.)

---

## Como Usar

### 1. Instalação

Você pode baixar diretamente o `nu.css` ou incluí-lo no seu projeto HTML:

```html
<link rel="stylesheet" href="nu.css">
````

> Não é necessário importar nenhuma outra biblioteca. Tudo funciona com HTML5 puro.

### 2. Estrutura HTML recomendada

Evite `div` desnecessárias. Use tags semânticas sempre que possível:

```html
<header>
  <nav>...</nav>
</header>

<main>
  <article>...</article>
  <section>...</section>
</main>

<footer>...</footer>
```

### 3. Personalização via `:root`

Você pode sobrescrever as variáveis no seu CSS para mudar o tema:

```css
:root {
  --color-primary: #1a1a1a;
  --font-family-base: 'Inter', sans-serif;
  --font-size-base: 1.1rem;
}
```

---

## Layout Responsivo

* O conteúdo é centralizado com largura máxima (`max-width`) de `71.25rem`.
* Navegação e tipografia são ajustadas automaticamente em telas menores.
* Tabelas e mídia são fluidas por padrão (`max-width: 100%`).

---

## Demonstração

Acesse o arquivo `example.html` para visualizar todos os elementos HTML5 estilizados com NuCSS, organizados por seções.

---

## Licença

Este projeto está licenciado sob a Licença MIT]. Você pode usá-lo, modificá-lo e distribuí-lo livremente.
