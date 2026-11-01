# Pedido para o Claude Code: novo vídeo ViraWeb (mesmo formato dos anteriores)

## O que fazer
Criar um vídeo novo da ViraWeb no **mesmo formato** de `viraweb-gancho-bola.mp4` e `viraweb-site-sistema-automacao.mp4` (estão neste repositório; use como referência visual e de ritmo).

## Inspiração
Reel: https://www.instagram.com/reel/DeUQCEbDPM7/
Use só a **ideia e a estrutura** (gancho, ritmo, reviravolta). Não copie texto, voz, imagens nem trechos do reel. Todo o texto, a arte e o roteiro devem ser originais e da ViraWeb.

> ATENÇÃO: o Claude que montou este arquivo não conseguiu abrir o reel (o Instagram bloqueia). Antes de começar, abra o link, escreva abaixo em 3 a 5 linhas do que ele trata e como é a estrutura, e então siga.
>
> **Resumo do reel:** (preencher)

## Formato (igual aos outros)
- Vertical 1080x1920, 30 fps, H.264 + AAC, 25 a 50 s.
- Fundo claro, logo ViraWeb pequeno no topo, título grande em Montserrat Bold/ExtraBold.
- Cores: azul `#1757A2`, azul-marinho escuro para texto, amarelo para destaques (etiquetas inclinadas), vermelho só para erro/alerta.
- Cenas em cartões brancos com sombra suave, animações limpas (entrada com fade/slide curto).
- Legenda palavra por palavra na parte de baixo: cada palavra num "chip" (azul com texto branco ou branco com texto escuro), alinhada à fala.
- Gancho forte nos 3 primeiros segundos.
- Final com cartão de chamada: "Me chama no direct pra começar." + botão "Enviar mensagem" + "E comenta aqui: qual é o ramo da sua empresa?" + `viraweb.dev.br`.
- Ferramenta: a mesma usada nos anteriores (Hyperframes: HTML + render para MP4).

## Áudio
- Gerar duas versões: **com narração** (voz natural em português do Brasil) e **sem voz** (só efeitos sonoros/música).
- Efeitos com bom volume e impacto (estouros, batidas, transições). Normalizar sem estourar (pico em torno de -1 dB).

## Entrega
1. `viraweb-<nome>.mp4` (com voz) e `viraweb-<nome>-sem-voz.mp4`.
2. Um `ROTEIRO` curto em texto com a fala de cada cena.
3. Salvar em `~/Downloads` e fazer commit/push na branch `main` de `daltrovitor/videos`.
