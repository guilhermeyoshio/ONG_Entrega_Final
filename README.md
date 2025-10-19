# Projeto ONG Vida Nova - Entrega Final

## 1. Visão Geral do Projeto

Este projeto é um website institucional front-end para a "ONG Vida Nova", focado em educação, cultura e esporte. O site foi desenvolvido como atividade acadêmica final, consolidando conhecimentos em HTML5, CSS3 e JavaScript moderno, com foco em responsividade, acessibilidade (WCAG 2.1) e boas práticas de desenvolvimento e versionamento.

O site foi construído usando uma arquitetura **SPA (Single Page Application)**, onde a navegação entre as páginas (Início, Projetos, Participe) é feita dinamicamente com JavaScript, carregando apenas o conteúdo principal sem recarregar a página inteira.

## 2. Funcionalidades Implementadas

* **Design Responsivo:** O layout se adapta a desktops, tablets e celulares (mobile-first).
* **SPA (Single Page Application):** Navegação assíncrona usando `fetch()` API para carregar conteúdo das páginas dinamicamente.
* **Templates JS:** A página de "Projetos" é renderizada via JavaScript a partir de um objeto de dados.
* **Formulário de Cadastro Interativo:**
    * Validação de campos em tempo real (ao sair do campo) e no envio.
    * Máscaras automáticas para CPF, Telefone e CEP.
* **Acessibilidade (WCAG 2.1 AA):**
    * **Modo Escuro / Alto Contraste:** Um seletor de tema (☀️/🌙) que altera a paleta de cores do site e salva a preferência do usuário no `localStorage`.
    * **Navegação por Teclado:** Todos os elementos interativos são totalmente acessíveis via tecla "Tab".
    * **Semântica HTML:** Uso correto de tags como `<main>`, `<nav>`, `<header>`, `<footer>` e `<fieldset>`.
    * **Contraste de Cores:** Paleta de cores escolhida para atender aos requisitos mínimos de contraste.

## 3. Tecnologias Utilizadas

* **HTML5:** Estruturação semântica.
* **CSS3:**
    * CSS Grid e Flexbox.
    * Variáveis CSS para fácil manutenção e implementação do modo escuro.
    * Arquitetura Modular (arquivos separados).
* **JavaScript (ES6+):**
    * Manipulação do DOM, `fetch()` API, `localStorage`.
* **Git & GitHub:**
    * Estratégia de branching **GitFlow** (`main`, `develop`, `feature/`).
    * **Commits Semânticos** (ex: `feat:`, `fix:`, `docs:`).

## 4. Práticas de Desenvolvimento e Deploy

* **GitFlow:** O fluxo de trabalho foi:
    1.  Código base (Atividade 3) enviado para a `main`.
    2.  Branch `develop` criada a partir da `main`.
    3.  Branch `feature/acessibilidade-modo-escuro` criada a partir da `develop`.
    4.  Implementação do modo escuro na `feature`.
    5.  Pull Request e Merge da `feature` de volta para a `develop`.
* **Otimização de Produção:**
    * (Opcional) Minificação de arquivos CSS e JS.
    * (Opcional) Compressão de imagens.

## 5. Como Executar Localmente

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/guilhermeyoshio/ONG_Entrega_Final.git]
    ```
2.  Navegue até a pasta do projeto:
    ```bash
    cd [ONG_Entrega_Final]
    ```
3.  Abra o arquivo `index.html` no seu navegador de preferência.

---
*Autor: [Guilherme Yoshio Takeuti Takaki]*
*Curso: Análise e Desenvolvimento de Sistemas*