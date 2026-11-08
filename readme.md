# Associação de Artesãos de Caxias — Landing Page

Página de apresentação da Associação de Artesãos de Caxias (MA), feita em **HTML, CSS e JavaScript puros** — sem framework, sem build.

Feita para apresentar a associação ao público: quem são, o que produzem e como chegar até eles. É a página que dá rosto ao projeto institucional em Laravel.

🔗 **No ar:** https://sshs3rejo.github.io/artesanato-landing-page/

## Seções

- **Home** — identidade visual e apresentação
- **Sobre** — a associação e seu propósito
- **Produtos / Artesanato** — o que é produzido
- **Contato**

## Detalhes técnicos

- **Navbar responsiva** com botão hambúrguer, controlada por `aria-expanded` — funciona por teclado e leitor de tela, não só no clique
- **Navegação por âncoras** (`#home-section`), sem roteador: é uma página só, e isso basta
- **Identidade própria** — logotipo e wordmark como imagens separadas, para compor o cabeçalho sem depender de fonte externa
- **Zero dependências** — `index.html`, `style.css`, `script.js` e a pasta `img/`

## Rodando

```bash
git clone https://github.com/sshs3rejo/artesanato-landing-page.git
cd artesanato-landing-page
# abra index.html, ou:
python3 -m http.server 8000
```

Publicado no GitHub Pages.

## Estrutura

```
├── index.html
├── style.css
├── script.js
└── img/          logotipo e imagens da associação
```

## Contexto

Landing page do Projeto Integrador Extensionista — UniFacema, em apoio à Associação de Artesãos de Caxias. O sistema administrativo completo (Laravel + PostgreSQL) fica em [Associacao-de-Artesaos-de-Caxias](https://github.com/sshs3rejo/Associacao-de-Artesaos-de-Caxias).

## Licença

MIT
