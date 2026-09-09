# SELVA crossfitbox Landing Page (Pure HTML/CSS)

![HTML5 Validado](https://img.shields.io/badge/HTML5-W3C_Validado-brightgreen?style=for-the-badge&logo=html5)
![CSS3 Validado](https://img.shields.io/badge/CSS3-W3C_Validado-brightgreen?style=for-the-badge&logo=css3)
![No JS](https://img.shields.io/badge/JavaScript-Zero%20Dependencies-brightgreen?style=for-the-badge)

Landing page responsiva desenvolvida para um box de CrossFit. O foco arquitetural do projeto foi construir a interface inteiramente sem dependência de JavaScript, utilizando técnicas avançadas de CSS para manipulação de estado e interatividade.

[Acesse a aplicação em produção aqui](https://jonathan3703226.github.io/SELVA-crossfitbox-pure-html-css/)

## Arquitetura e Interatividade (No-JS)

Comportamentos que tradicionalmente dependem de manipulação do DOM via JavaScript foram resolvidos exclusivamente com CSS, utilizando a técnica de Checkbox Hack (pseudo-classe `:checked`). As implementações incluem:

* **Dark/Light Mode:** Inversão global do tema baseada em Custom Properties (variáveis CSS).
* **Carrossel de Imagens:** Controle de navegação horizontal com inputs ocultos.
* **Sistema de Abas (Tabs):** Alternância de exibição entre a listagem de avaliações e o formulário de submissão.
* **Menu Responsivo:** Toggle do menu de navegação para dispositivos móveis.

## Stack Tecnológico

* **HTML5:** Foco em estruturação semântica.
* **CSS3:** Flexbox, Grid Layout, Custom Properties, Media Queries e Transições 3D.
* **Assets:** Google Fonts e FontAwesome.

## 🛠️ Qualidade do Código e Semântica

Para garantir as melhores práticas de desenvolvimento web e semântica estrutural, o código deste projeto foi integralmente testado e aprovado utilizando as ferramentas oficiais:

- **HTML5:** Validado via [W3C Markup Validation Service](https://validator.w3.org/) (Zero erros e avisos, com correta hierarquia de headings e tags semânticas como `<article>`, `<header>` e `<nav>`).
- **CSS3:** Validado via [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/).

## Estrutura do Projeto

* **Hero Section:** Banner inicial de conversão.
* **Modalidades:** Listagem de serviços e horários via Grid.
* **Habitat:** Seção institucional com background em vídeo e sobreposição opaca.
* **Planos:** Cards comparativos de precificação.
* **O Líder:** Flip card com transição de perspectiva 3D (Hover/Tap).

## Execução Local

Por ser uma aplicação estática e não possuir dependências, o projeto não exige processo de build.

1. Clone o repositório: 
`git clone https://github.com/jonathan3703226/selva-crossfit-landing-page.git`
2. Abra o arquivo `index.html` em qualquer navegador.