# 04 — O Blog das Semanas

> **Capitulo 4 da linha do tempo.** Ate aqui, tudo era uma pagina so. Eu queria construir algo com varias paginas conectadas — como a web realmente e. Criei um blog estatico de 4 paginas onde cada post contava o que aprendi nas semanas anteriores.

**Anterior:** [03 — A Lista que nao se Apaga](https://github.com/Possi-dev/estudos-03-todo-list) | **Proximo:** [05 — A Maquina sem Rosto](https://github.com/Possi-dev/estudos-05-api-de-tarefas)

---

## A historia

Tres projetos. Tres paginas unicas. Cada uma isolada no seu proprio `index.html`.

Eu queria mais. Queria ver o que acontecia quando eu tinha **multiplos HTMLs** se conversando. Links entre eles. Navegacao contextual. Um usando o CSS do outro.

*> "Vamos criar um blog,"* disse a IA. *"Um blog de estudos. Cada post documenta uma das semanas que voce acabou de viver."*

A ironia era deliciosa: o blog ia documentar a propria jornada que o blog fazia parte.

Construi 4 paginas:

- **`index.html`** — a homepage, listando os 3 posts como cards clicaveis
- **`posts/semana-01-html.html`** — sobre HTML semantico (o que aprendi no Projeto 01)
- **`posts/semana-02-css.html`** — sobre Flexbox e responsividade (tambem do Projeto 01)
- **`posts/semana-03-javascript.html`** — sobre DOM, eventos e localStorage (Projetos 02 e 03)

Um unico `style.css` servia todas as paginas. Cada post tinha navegacao contextual no rodape: "Post anterior" / "Proximo post" / "Voltar ao blog". Era a primeira vez que eu via a web como ela realmente e — uma teia de paginas conectadas por links.

E algo que parecia simples se revelou profundo: quando cliquei em "Próximo post" pela primeira vez e a pagina mudou suavemente, carregando o proximo conteudo com o mesmo CSS, percebi que tinha construido um **site**. Nao uma pagina. Um site.

---

## Demo ao vivo

**[https://possi-dev.github.io/estudos-04-blog-estatico/](https://possi-dev.github.io/estudos-04-blog-estatico/)**

---

## Como este projeto foi feito

**Transparencia:** Este codigo foi gerado pela IA **opencode**. Meu papel foi:

- Entender como multiplas paginas HTML se conectam via links (`<a href="posts/semana-01.html">`)
- Estudar a navegacao entre paginas (cada `.html` e uma pagina independente)
- Entender como o CSS e compartilhado entre todas as paginas (um unico `style.css`)
- Ver como blocos de codigo sao exibidos com `<pre><code>` no HTML

Nao escrevi o codigo do zero — ele foi gerado pela IA e eu estudei o resultado.

---

## O que este projeto ensina

| Conceito | Onde esta no codigo |
|----------|---------------------|
| Multiplas paginas | `index.html` + 3 arquivos em `posts/` |
| Navegacao entre paginas | Links `<a href="posts/semana-01.html">` e voltar |
| CSS compartilhado | Um `style.css` serve todas as paginas |
| Syntax highlight | Tags `<pre><code>` exibem blocos de codigo formatados |
| Navegacao contextual | "Proximo post" e "Post anterior" no rodape de cada post |

---

## Estrutura dos arquivos

```
04-blog-estatico/
├── index.html                    # Pagina inicial lista os 3 posts
├── style.css                     # Estilos compartilhados por todas as paginas
├── posts/
│   ├── semana-01-html.html       # Post sobre HTML
│   ├── semana-02-css.html        # Post sobre CSS
│   └── semana-03-javascript.html # Post sobre JavaScript
├── README.md
├── LICENSE
└── .gitignore
```

---

## Posts incluidos

1. **Semana 01 - HTML:** estrutura semantica, tags essenciais
2. **Semana 02 - CSS:** Flexbox, responsividade com media queries
3. **Semana 03 - JavaScript:** DOM, eventos, arrays, localStorage

---

## Como visualizar

**Online:** Clique no link de demo acima.

**Local:** Abra o `index.html` no navegador e navegue entre os posts pelos links.

---

## O que aprendi neste capitulo

Aprendi que a web e uma colecao de documentos conectados. Que um unico CSS pode servir infinitas paginas. Que `<pre><code>` e como voce exibe codigo dentro de codigo. Que `href` e a cola que une a internet.

Mas tinha algo me incomodando. Todas as paginas eram estaticas. ESTATICAS. O conteudo nunca mudava a nao ser que eu editasse o HTML. Nao havia dados dinamicos. Nao havia logica no servidor. Nao havia **back-end**.

*> Eu ja sabia fazer o front-end. Mas o que havia atras dele? O que era um servidor? O que era uma API?*

Eu estava prestes a descobrir. Isso me levou ao [Projeto 05](https://github.com/Possi-dev/estudos-05-api-de-tarefas).

---

## Proximos passos de aprendizado

- [ ] Escrever um 4º post com minhas proprias anotacoes
- [ ] Adicionar uma imagem em um dos posts
- [ ] Tentar criar uma nova pagina do zero imitando a estrutura

---

## Licenca

MIT — veja [LICENSE](LICENSE).
