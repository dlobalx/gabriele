# Site Psicóloga Gabriele Taboni

## Como abrir o site
Clique duas vezes no arquivo `index.html` — ele abre direto no navegador.

## Como adicionar as fotos

Coloque as fotos dentro da pasta `fotos/` e edite o `index.html`:

### Foto 1 — Hero (foto principal, tela toda)
Substitua o bloco `<div class="hero-img-placeholder">...</div>` por:
```html
<img src="fotos/foto-principal.jpg" alt="Psicóloga Gabriele Taboni">
```
Tamanho ideal: **900 × 1200 px** (proporção 3:4, retrato)

### Foto 2 — Sobre Mim
Substitua o bloco `<div class="sobre-photo-slot">...</div>` por:
```html
<img src="fotos/foto-sobre.jpg" alt="Gabriele Taboni" style="width:320px;height:420px;border-radius:20px;object-fit:cover;object-position:top;">
```
Tamanho ideal: **640 × 840 px**

### Foto 3 — Consultório / Abordagem
Substitua o bloco dentro de `<div class="abord-img-slot">` por:
```html
<img src="fotos/consultorio.jpg" alt="Consultório Gabriele Taboni">
```
Tamanho ideal: **700 × 760 px**

## Estrutura de arquivos
```
site gabriele/
├── index.html       ← arquivo principal do site
├── fotos/           ← coloque as fotos aqui
│   ├── foto-principal.jpg
│   ├── foto-sobre.jpg
│   └── consultorio.jpg
└── README.md        ← este arquivo
```

## Para hospedar o site
Envie a pasta inteira (com as fotos) para serviços como:
- **Hostinger** (hostinger.com.br)
- **GitHub Pages** (gratuito)
- **Vercel** (gratuito)
