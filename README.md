# Blog Estático

> Projeto 4 do roadmap: blog com múltiplas páginas HTML conectadas por links, simulando um blog real de estudos.

## Demo ao vivo

**[https://possi-dev.github.io/estudos-04-blog-estatico/](https://possi-dev.github.io/estudos-04-blog-estatico/)**

## Como este projeto foi feito

**Transparência:** Este código foi gerado pela IA **opencode**. Meu papel foi:

- Entender como múltiplas páginas HTML se conectam via links (`<a href="posts/semana-01.html">`)
- Estudar a navegação entre páginas (cada `.html` é uma página independente)
- Entender como o CSS é compartilhado entre todas as páginas (um único `style.css`)
- Ver como blocos de código são exibidos com `<pre><code>` no HTML

Não escrevi o código do zero — ele foi gerado pela IA e eu estudei o resultado.

## O que este projeto ensina

| Conceito | Onde está no código |
|----------|---------------------|
| Múltiplas páginas | `index.html` + 3 arquivos em `posts/` |
| Navegação entre páginas | Links `<a href="posts/semana-01.html">` e voltar |
| CSS compartilhado | Um `style.css` serve todas as páginas |
| Syntax highlight | Tags `<pre><code>` exibem blocos de código formatados |
| Navegação contextual | "Próximo post" e "Post anterior" no rodapé de cada post |

## Estrutura dos arquivos

```
04-blog-estatico/
├── index.html                    # Página inicial lista os 3 posts
├── style.css                     # Estilos compartilhados por todas as páginas
├── posts/
│   ├── semana-01-html.html       # Post sobre HTML
│   ├── semana-02-css.html        # Post sobre CSS
│   └── semana-03-javascript.html # Post sobre JavaScript
├── README.md
├── LICENSE
└── .gitignore
```

## Posts incluídos

1. **Semana 01 - HTML:** estrutura semântica, tags essenciais
2. **Semana 02 - CSS:** Flexbox, responsividade com media queries
3. **Semana 03 - JavaScript:** DOM, eventos, arrays, localStorage

## Como visualizar

**Online:** Clique no link de demo acima.

**Local:** Abra o `index.html` no navegador e navegue entre os posts pelos links.

## Próximos passos de aprendizado

- [ ] Escrever um 4º post com minhas próprias anotações
- [ ] Adicionar uma imagem em um dos posts
- [ ] Tentar criar uma nova página do zero imitando a estrutura

## Licença

MIT — veja [LICENSE](LICENSE).
