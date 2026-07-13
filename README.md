# moweb-social-assets

Imagens públicas das peças de redes sociais da Mowebstudio, servidas por GitHub Pages.

## Por que este repositório existe

A API de publicação do Instagram **não aceita upload de bytes**: a Meta busca cada imagem por
URL pública HTTPS. As imagens precisam estar no ar antes de publicar o post.

Este repo é separado do site de propósito: asset de rede social não pertence a um repositório
de conteúdo.

## Estrutura

```
carrossel/<tema>/slide-01.jpg ... slide-NN.jpg
```

A numeração é a narrativa do carrossel. Não renomeie.

## Requisitos da Meta (não os quebre)

- **JPEG apenas.** PNG é rejeitado na criação do container.
- **Proporção entre 4:5 e 1.91:1.** Os slides são 1080x1350 (exatamente 4:5, o limite).
- Máximo de 8 MB por imagem, largura máxima de 1440px, espaço de cor sRGB.
- Carrossel: no máximo 10 imagens.

## URL base

`https://moabe-br-2019.github.io/moweb-social-assets/`
