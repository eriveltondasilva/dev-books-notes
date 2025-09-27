# 📚 Dev Books Notes

Repositório para organizar destaques, reflexões e rascunhos de artigos a partir de livros de desenvolvimento de software

---

## Estrutura

```markdown
books/
├── <book>/
│ ├── README.md
│ ├── highlights/
│ │ └── 01-introdução.md
│ ├── thoughts/
│ │ └── 01-introdução.md
│ └── drafts/
│   └── artigo-01.md
BACKLOG.md
README.md
LICENSE
```

---

## Como usar

1. **Leitura** → adicionar citações em `highlights/`.
2. **Reflexão** → registrar ideias em `thoughts/`.
3. **Artigo** → escrever rascunhos em `drafts/`.

---

## Exemplo de Nota com Metadados

`books/<book>/<highlights|thoughts>/01-introdução.md`

```markdown
---
chapter: 01
title: "título do capítulo"
book: "título do livro"
date: 2025-09-27
---

# {Highlights|Thoughts} - Capítulo 01

- Enim mollit mollit consectetur aliquip labore magna.
- Consequat consequat ullamco sit eiusmod ullamco dolore et.
- Eu culpa consectetur enim consectetur excepteur veniam laborum commodo commodo deserunt consectetur Lorem sint voluptate.
```

---

## Exemplo de Artigo em Rascunho

`books/<book>/drafts/artigo-01.md`

```markdown
---

title: "O que é Código Limpo?"
source: "Clean Code - Capítulo 01"
status: draft
tags: ["código limpo", "artigo", "boas práticas"]
---

# O que é Código Limpo?

Reprehenderit anim culpa in eiusmod id do ex laborum consequat est id. Incididunt consequat velit nisi labore est Lorem dolor aliqua. Nisi nostrud deserunt laborum fugiat sint duis elit Lorem ut. Eiusmod cillum ad officia ad enim labore in et nulla incididunt laborum tempor quis. Anim sint quis culpa id aute magna deserunt cupidatat. Velit magna deserunt veniam et sunt minim.
```
