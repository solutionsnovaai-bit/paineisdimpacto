# Painéis D'Impacto — Site

Site institucional one-page. Site estático puro (HTML + JS), sem build step.

## Estrutura
```
index.html          página principal (inclui favicons + Open Graph)
support.js          runtime (carrega React/Babel via CDN em tempo de execução)
favicon.ico         favicon raiz (navegadores/Google buscam em /favicon.ico)
assets/             imagens do site, favicons e og-image
```

## Deploy no Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Em vercel.com → **Add New Project** → importe o repositório.
3. Framework Preset: **Other** (site estático). Build Command: vazio. Output Directory: `.` (raiz).
4. Deploy — pronto, sem configuração extra.

## Domínio próprio (quando ativar)
Trocar as URLs `https://paineisdimpacto.vercel.app/` das meta tags Open Graph
no `<head>` do `index.html` pelo domínio final.

## Contato
WhatsApp: (11) 98269-3709 — editar em `index.html` caso o número mude.

---
Site por Nova AI Solutions
