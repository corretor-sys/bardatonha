# Bar da Tonha

## Publicar no GitHub Pages

1. Extraia o ZIP. No GitHub, crie um repositório público e abra **Add file → Upload files**. Envie o conteúdo extraído para a raiz da branch `main`, mantendo as pastas. O arquivo `index.html` deve aparecer ao lado de `assets` e `cardapio`.
2. Salve em **Commit changes**. Abra **Settings → Pages**, selecione **Deploy from a branch**, escolha **main** e **/ (root)** e clique em **Save**.
3. Quando a publicação terminar, use **Visit site** para conferir a página inicial, o cardápio e o vídeo.

## Conectar seu domínio

Em **Settings → Pages → Custom domain**, digite o endereço que você registrou e clique em **Save**. O GitHub cria o arquivo CNAME. Depois, abra a área de DNS no provedor do domínio.

- Para um endereço com **www**, crie um registro `CNAME` de nome `www` apontando para `SEU-USUARIO.github.io`. Substitua SEU-USUARIO pelo nome da conta ou organização no GitHub.
- Para o domínio **sem www**, configure quatro registros `A` na raiz (normalmente `@`), um para cada IP do GitHub Pages no guia abaixo.
- Quando o GitHub confirmar o DNS e liberar o certificado, marque **Enforce HTTPS**.

[Guia oficial do GitHub com a tabela de DNS](https://docs.github.com/pt/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site)

## Editar o site

A página inicial está em `index.html` e o cardápio completo em `cardapio/index.html`. Os arquivos CSS controlam o visual. Os arquivos JavaScript contêm o conteúdo e as interações. As imagens, o logotipo e o vídeo estão em `assets/`. O projeto usa HTML, CSS e JavaScript e pode ser publicado diretamente.
