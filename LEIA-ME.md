# SistemaFC PRO — página de download

A página usa a imagem original enviada por você. O botão desenhado nela tem uma área clicável real, proporcional à imagem, que abre:
https://play.google.com/store/apps/details?id=br.com.lojamaster.android.play

## Publicar no GitHub Pages
1. Crie um repositório público (por exemplo, sistemafc-pro-download).
2. Extraia este ZIP e envie seu conteúdo para a raiz do repositório.
3. Mantenha a pasta assets com a imagem dentro dela.
4. Em Settings → Pages, selecione a branch principal e a pasta / (root). Como alternativa, selecione GitHub Actions e configure o modelo Static HTML / HTML estático.
5. Aguarde a publicação e copie o endereço que o GitHub apresentar.

Arquivos:
- index.html
- estilo.css
- assets/sistemafc-pro.jpg
- .nojekyll
- LEIA-ME.md (estas instruções)

O site é estático: sem instalação, compilação, scripts, rastreadores ou fontes externas. O botão funciona com mouse, toque e teclado. A imagem mantém a proporção, sem corte. Em telas estreitas, acompanha a largura; em telas grandes, cabe na altura disponível.

Para trocar o destino, edite apenas o href do link class="download" em index.html. Não substitua o caminho da imagem pelo link do aplicativo.

A publicação no GitHub não foi realizada nesta entrega. Não foram adicionados preços, avaliações, números de downloads ou outras informações além da imagem e do link fornecidos.

O botão tem animação suave de pulsação com brilho, sem movimentar a imagem inteira. A animação é desativada automaticamente quando o visitante utiliza a preferência de redução de movimento.
