📖 README – Estrutura Básica de um Site em HTML e CSS
🔹 Estrutura Padrão

Um site geralmente é dividido nas seguintes partes:

<header> – Cabeçalho

Localizado no topo da página.

Contém logotipo, título, menu de navegação, barra de pesquisa.

<nav> – Navegação

Pode ficar dentro do header ou separado.

É o menu com links para outras seções ou páginas.

<main> – Conteúdo principal

Contém as informações mais importantes do site.

Pode incluir:

<section> → agrupa conteúdos relacionados (ex: "Sobre nós", "Serviços").

<article> → usado para posts, artigos ou conteúdos independentes.

<aside> → conteúdo complementar, geralmente lateral (ex: links extras, propaganda).

<footer> – Rodapé

Fica no fim da página.

Contém créditos, direitos autorais, contatos, redes sociais e links úteis.





┌───────────────────────────────────┐
│              HEADER               │
│   Logo | Menu de Navegação        │
└───────────────────────────────────┘
                │
                ▼
┌───────────────────────────────────┐
│               MAIN                │
│   ┌───────────────┐  ┌──────────┐ │
│   │   SECTION     │  │  ASIDE   │ │
│   │ (Conteúdo)    │  │ Lateral  │ │
│   └───────────────┘  └──────────┘ │
│                                   │
│   ┌───────────────┐               │
│   │   ARTICLE     │               │
│   │ (Post/Texto)  │               │
│   └───────────────┘               │
└───────────────────────────────────┘
                │
                ▼
┌───────────────────────────────────┐
│              FOOTER               │
│  © 2025 - Direitos reservados     │






<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Exemplo de Estrutura</title>
</head>
<body>
  <header>
    <h1>Logo do Site</h1>
    <nav>
      <a href="#">Início</a>
      <a href="#">Sobre</a>
      <a href="#">Contato</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Sobre Nós</h2>
      <p>Informações da empresa.</p>
    </section>

    <aside>
      <h3>Links Rápidos</h3>
      <p>Conteúdo lateral.</p>
    </aside>

    <article>
      <h2>Última Notícia</h2>
      <p>Texto do artigo ou post.</p>
    </article>
  </main>

  <footer>
    <p>© 2025 - Criado por Matheus</p>
  </footer>
</body>
</html>





└───────────────────────────────────┘
