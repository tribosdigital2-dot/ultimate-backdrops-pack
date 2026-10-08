# Ultimate Backdrops Pack – página de vendas

## Como publicar no GitHub Pages
1. Crie um repositório (ex.: `ultimate-backdrops`) e envie **index.html** e a pasta **images/** como estão.
2. Settings → Pages → Branch `main` / pasta `/root` → Save. Em ~1 min o site fica em `https://SEU-USUARIO.github.io/ultimate-backdrops/`.

## O que trocar antes de ir pro ar
- **Link do checkout:** no `index.html`, procure `const CHECKOUT_URL = "#CHECKOUT_LINK";` e cole o link real.
- **Tempo do countdown:** `const SALE_HOURS = 6;` (reinicia por visitante quando zera).

## Vídeo
- `video/before-after.mp4` (1920×1080) e `video/before-after-vertical.mp4` (1080×1920) — a página usa o vertical no celular e o horizontal no computador, tocando sozinho, sem som e em loop.
- As versões `.webm` são reserva para navegadores sem H.264. `poster*.jpg` é a imagem que aparece enquanto o vídeo carrega.
- Também servem para anúncios/Reels (o vertical já está no formato 9:16).

## Imagens
- `images/models/*.webp` – 9 modelos já recortados (noiva, atleta, casal, gestante, moda, formanda, criança, cachorro, gato) usados no "Pick a model. Pick a backdrop."
- `images/packs/b00..b22.jpg` (caixas) e `c00..c22.jpg` (prévia dos fundos) – seção "What’s included" com as 23 coleções
- `images/bg-*.jpg` – 16 fundos gerados no Grok (galeria e provador de modelos)
- `images/ba1..ba8-before/after.jpg` – 8 pares antes/depois gerados no Grok (topo, vídeo e galeria de resultados)
- `images/w-*.jpg` – a mesma foto aplicada nos 8 fundos
- `images/sp*.jpg` – prints de prova social da página original
- `images/thumbs/` – miniaturas
Para trocar uma imagem, substitua o arquivo mantendo o mesmo nome (formato 2:3, ex.: 900×1350).
