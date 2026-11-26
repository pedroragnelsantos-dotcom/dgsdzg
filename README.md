# Semáforo da Comunicação

Página web educativa desenvolvida em **HTML5** e **CSS3** que apresenta boas e más práticas de comunicação em interfaces web, organizadas nas três cores do semáforo.

## Estrutura do Projeto (15 Cards)

- **🟢 VERDE – Boas práticas (5 cards):** Linguagem direta, botões autoexplicativos, mensagens de erro úteis, ícones com texto e hierarquia visual clara.
- **🟡 AMARELO – Cuidado (5 cards):** Siglas e termos técnicos, notificações frequentes, textos longos em bloco, formulários extensos e tempo limite de ação.
- **🔴 VERMELHO – Evitar (5 cards):** Informação apenas por cor, baixo contraste, janelas pop-up invasivas, links genéricos e animações piscantes.

## Práticas de Acessibilidade Implementadas

1. **HTML5 Semântico:** Uso adequado das tags `<header>`, `<nav>`, `<main>`, `<section>`, `<article>` e `<footer>`.
2. **Identificação Redundante (Cor + Símbolo + Texto):** Nenhum card ou categoria depende exclusivamente da cor para transmitir significado.
3. **Contraste Adequado:** Combinações de cores planejadas para leitura confortável e nítida.
4. **Navegação por Teclado e Foco Visível:** Inclusão de link de salto (*Skip Link*) e contorno de foco bem definido (`:focus-visible`).
5. **Suporte a Leitores de Tela (ARIA):** Uso de `aria-label`, `aria-labelledby` e `aria-hidden="true"` para ícones decorativos.
6. **Layout Responsivo e Espaçado:** Adaptação automática para computadores, tablets e celulares usando `CSS Grid`, `Flexbox` e `@media`, sem animações bruscas.

## Como publicar no GitHub Pages

1. Crie um repositório público no GitHub chamado `semaforo-comunicacao`.
2. Envie os arquivos `index.html`, `style.css` e `README.md` para a raiz do repositório.
3. Acesse **Settings → Pages**, selecione a branch `main` e a pasta `/ (root)` e clique em **Save**.
