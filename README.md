# Plataforma Web: Corrente Solidária

![Linguagem](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=for-the-badge)
![Acessibilidade](https://img.shields.io/badge/Accessibility-WCAG%202.1%20AA-007bff?style=for-the-badge)
![Licença](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

Projeto de plataforma web responsiva para a ONG fictícia "Corrente Solidária", desenvolvido para demonstrar habilidades em desenvolvimento front-end, desde a estruturação semântica até a implantação de uma Single Page Application (SPA) otimizada.

> **Nota:** Este projeto é um portfólio acadêmico que simula o desenvolvimento profissional através de quatro entregas incrementais.

---

## Sobre o Projeto

O objetivo foi construir uma presença digital completa para uma ONG, com foco em profissionalismo, performance e acessibilidade.

A arquitetura do projeto é uma **Single Page Application (SPA)** construída com JavaScript puro ("vanilla JS"), que gerencia o carregamento de "templates" HTML de forma dinâmica, sem recarregar a página, utilizando a Fetch API para roteamento do lado do cliente.

## Funcionalidades Principais

* **Arquitetura SPA:** Roteamento dinâmico do lado do cliente. A navegação entre "Início", "Projetos" e "Cadastro" é instantânea e não recarrega a página.
* **Design System Customizado:** O CSS é construído sobre um sistema de design coeso (variáveis CSS) para cores, tipografia hierárquica e espaçamento modular.
* **Layout Responsivo Avançado:** Utiliza um grid de 12 colunas customizado, construído com CSS Grid e Flexbox, garantindo adaptabilidade *mobile-first*.
* **Validação de Formulário Avançada:** Implementa verificação de consistência de dados em JavaScript (antes do envio) e utiliza a biblioteca `IMask.js` para aplicar máscaras de entrada (CPF, CEP, Telefone) em tempo real.
* **Acessibilidade (WCAG 2.1 Nível AA):**
    * Suporte completo para navegação por teclado.
    * Atributos WAI-ARIA para leitores de tela (especialmente no menu de navegação).
    * Contraste de cores validado.
* **Modo Escuro / Claro:** Um seletor de tema acessível que salva a preferência do usuário no `localStorage`.
* **Otimização para Produção:** Todos os arquivos (HTML, CSS, JS) são minificados e as imagens são comprimidas para performance máxima.

---

## Tecnologias Utilizadas

* **HTML5 Semântico:** Estrutura base do projeto.
* **CSS3:** Para estilização, utilizando Flexbox, Grid e Variáveis CSS.
* **JavaScript (ES6+):** Para toda a lógica da SPA, incluindo:
    * Manipulação do DOM
    * Fetch API (para carregamento de templates)
    * Event Listeners
    * LocalStorage (para o Modo Escuro)
* **IMask.js:** Biblioteca externa para máscaras de formulário.
* **Git & GitHub:** Para controle de versão, seguindo a estratégia GitFlow (branches `main`, `develop`, `feature`).

---

## Processo de Desenvolvimento (As 4 Entregas)

Este projeto foi construído de forma incremental, simulando um ambiente de desenvolvimento ágil:

1.  **Entrega I: Fundamentos HTML**
    * Criação da estrutura semântica (`.html`), formulários complexos e estrutura de pastas.

2.  **Entrega II: CSS Avançado e Responsividade**
    * Implementação do Design System (Variáveis CSS).
    * Criação do grid de 12 colunas, Flexbox e componentes (cards, botões).
    * Criação do menu hambúrguer e dropdowns.

3.  **Entrega III: JavaScript e Interatividade (SPA)**
    * Transformação do site estático em uma Single Page Application (SPA).
    * Implementação do roteador com `fetch()` e `window.location.hash`.
    * Implementação do sistema de verificação de consistência de formulários com JS.

4.  **Entrega IV: Acessibilidade e Produção**
    * Implementação da estratégia GitFlow (`main`, `develop`, `feature`).
    * Conformidade com WCAG 2.1 (ARIA, navegação por teclado).
    * Implementação do Modo Escuro acessível.
    * Otimização de imagens e minificação de arquivos para produção.

---

## 👨‍💻 Autor

Desenvolvido por **Augusto Lonardi** como parte do curso de Desenvolvimento Front End.
