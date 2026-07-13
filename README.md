# Painéis D'Impacto — Site

Site institucional one-page. Site estático puro (HTML + JS), sem build step.

## Estrutura
```
index.html          página principal
support.js          runtime (carrega React/Babel via CDN em tempo de execução)
assets/              logo e imagem do hero
```

## Deploy no Vercel
1. Suba esta pasta para um repositório no GitHub.
2. Em vercel.com → **Add New Project** → importe o repositório.
3. Framework Preset: **Other** (site estático). Build Command: vazio. Output Directory: `.` (raiz).
4. Deploy — pronto, sem configuração extra.

## Deploy no GitHub Pages (alternativa)
Settings → Pages → Source: branch `main`, pasta `/ (root)`.

## Domínio / contato
WhatsApp: (11) 98269-3709 — editar em `index.html` caso o número mude.
