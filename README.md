# Gabriel Pacheco — Portfolio (site estático)

Portfólio profissional de Gabriel Pacheco — desenvolvedor fullstack sênior
(WordPress, PHP, JavaScript, React/Next.js). Export estático do Next.js, sem
servidor e sem PHP. Conteúdo em PT-BR/EN com alternância no cliente.

- Site: https://gabrielpacheco.com.br
- GitHub: https://github.com/gabrielgpacheco
- LinkedIn: https://linkedin.com/in/gabrielpachecomidias

## Testar localmente

```powershell
npx --yes serve .
```

Abrir `http://localhost:3000/` (não usar duplo-clique no `index.html`).

## Estrutura

```
index.html          single-page (export do Next.js)
404.html            página de erro
_next/              JS/CSS/fontes do build
images/             imagens WebP (projetos e avatares)
manifest.json       metadados PWA
robots.txt          SEO
sitemap.xml         SEO
CNAME               domínio custom (GitHub Pages)
.nojekyll           preserva pastas com "_" (ex.: _next/) no Pages
```

## Deploy

Hospedado no GitHub Pages (branch `main`, raiz); o domínio custom é definido
pelo arquivo `CNAME`.
