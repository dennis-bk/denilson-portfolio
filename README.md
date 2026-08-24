# Portfolio Pessoal — Denilson Santos de Lima 🌐

**Portfólio responsivo publicado no GitHub Pages** — single-file HTML com CSS embutido, zero dependências build.

---

## 🌍 Live

**[dennis-bk.github.io/denilson-portfolio](https://dennis-bk.github.io/denilson-portfolio/)**

---

## 📄 Conteúdo

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Portfolio completo (HTML + CSS + JS inline) |
| `curriculo.pdf` | Currículo em PDF (ATS-friendly) |
| `portfolio-homelab-profissional.pdf` | Portfolio estendido com projetos de infraestrutura |
| `n8n-workflow-g1-bahia.json` | Workflow n8n de exemplo (integração G1 Bahia) |

---

## 🎨 Features

- **Design responsivo** (mobile-first, breakpoints 640/768/1024/1280)
- **Tema escuro/claro** com persistência em `localStorage`
- **Animações CSS** (fade-in, slide-up, hover effects)
- **SEO otimizado** (meta tags, Open Graph, Twitter Cards, JSON-LD)
- **Acessibilidade** (ARIA labels, foco visível, semântica HTML5)
- **Performance** — single request, fonts via preconnect, CSS crítico inline

---

## 🛠️ Stack

- **HTML5** semântico
- **CSS3** (Custom Properties, Grid, Flexbox, Container Queries)
- **Vanilla JS** (theme toggle, smooth scroll, intersection observer)
- **Font Awesome 6** (CDN)
- **Inter Font** (Google Fonts, preconnect)

---

## 🚀 Deploy

Automático via **GitHub Pages** (branch `main`, pasta `/root`):

```yaml
# .github/workflows/pages.yml (opcional)
name: Deploy to GitHub Pages
on:
  push:
    branches: [main]
jobs:
  deploy:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: actions/configure-pages@v4
      - uses: actions/upload-pages-artifact@v3
        with:
          path: .
      - uses: actions/deploy-pages@v4
```

---

## 📱 Seções

1. **Hero** — Nome, título, localização, CTA (LinkedIn, GitHub, Email, Currículo)
2. **Sobre** — Resumo profissional + 8+ anos experiência
3. **Habilidades** — Cloud, Redes, Automação, Monitoramento, SO, Metodologias
4. **Experiência** — Timeline (DXC, Login, Solutis, Freelancer)
5. **Projetos** — Cards com links GitHub (Homelab, KAMBA Quest, Portal, Bots)
6. **Certificações** — AZ-900 (em andamento), ITIL, etc.
7. **Contato** — Formulário mailto + links sociais

---

## 📄 Licença

MIT — conteúdo pessoal, código livre para inspiração.

---

**Autor:** Denilson Santos de Lima — [GitHub](https://github.com/dennis-bk) · [LinkedIn](https://linkedin.com/in/denilsonsantosdelima)