# FECHAÊ! — site estático (sem build, sem backend)

Abra `index.html` por um servidor estático (ou direto na hospedagem). Tudo é local: React, fontes e imagens estão na pasta. O progresso fica no `localStorage` do navegador.

## Vercel (mais simples)
1. Vercel → Add New → Project → arraste/importe esta pasta (ou suba num repositório GitHub e importe).
2. Framework Preset: **Other**. Build Command: vazio. Output Directory: `.` (raiz).
3. Deploy. A URL pública aparece ao final.

## GitHub Pages
1. Crie um repositório e envie TODOS os arquivos desta pasta na raiz (inclua `.nojekyll`).
2. Settings → Pages → Source: *Deploy from a branch* → Branch `main` / pasta `/ (root)` → Save.
3. Endereço: `https://SEU-USUARIO.github.io/NOME-DO-REPO/` (os caminhos são relativos, funciona em subpasta).

## Testar localmente
`python3 -m http.server 8080` dentro da pasta → http://localhost:8080
