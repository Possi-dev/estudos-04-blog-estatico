# Blog Estático — Múltiplas Páginas HTML

> Projeto 4: blog simples com 4 páginas HTML conectadas por links, CSS compartilhado e navegação contextual entre posts.

**Anterior:** [03 — Todo List](https://github.com/Possi-dev/estudos-03-todo-list) | **Próximo:** [05 — API de Tarefas](https://github.com/Possi-dev/estudos-05-api-de-tarefas)

---

## Demo

**[https://possi-dev.github.io/estudos-04-blog-estatico/](https://possi-dev.github.io/estudos-04-blog-estatico/)**

---

## O que este projeto ensina

| Conceito | Onde está no código |
|----------|---------------------|
| Múltiplas páginas | `index.html` + 3 arquivos em `posts/` |
| Navegação entre páginas | Links `<a href="posts/semana-01.html">` |
| CSS compartilhado | Um `style.css` serve todas as páginas |
| Blocos de código | Tags `<pre><code>` para snippets formatados |
| Navegação contextual | "Post anterior" / "Próximo post" / "Voltar ao blog" |

---

## Estrutura

```
04-blog-estatico/
├── index.html                    # Homepage lista os 3 posts
├── style.css                     # Estilos compartilhados (83 linhas)
├── posts/
│   ├── semana-01-html.html       # Post: HTML semântico
│   ├── semana-02-css.html        # Post: Flexbox, media queries
│   └── semana-03-javascript.html # Post: DOM, eventos, arrays, localStorage
├── README.md
├── LICENSE
└── .gitignore
```

---

## Posts incluídos

1. **Semana 01 — HTML:** estrutura semântica, tags essenciais, links internos
2. **Semana 02 — CSS:** Flexbox, responsividade com media queries
3. **Semana 03 — JavaScript:** DOM, eventos, arrays, localStorage

---

## Como foi feito

**Transparência:** Código gerado pela IA **opencode**. Estudei como múltiplos HTMLs se conectam via `<a href>`, como um único CSS serve todas as páginas, e como a navegação contextual ("próximo/anterior") é só mais links com paths relativos.

---

## Próximos passos de estudo

- [ ] Escrever um 4º post com anotações próprias
- [ ] Adicionar imagem em um post
- [ ] Criar nova página do zero seguindo a estrutura

---

## Licença

MIT — veja [LICENSE](LICENSE).