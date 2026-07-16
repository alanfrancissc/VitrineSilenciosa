# Vitrine Silenciosa — página de vendas

Página estática pronta para publicar no GitHub Pages.

## Conteúdo do pacote

- `index.html` — página completa
- `assets/vitrine-silenciosa.jpg` — imagem otimizada da capa

## Link de checkout configurado

https://pay.kiwify.com.br/inZlpZk

## Publicação no GitHub Pages

1. Crie um repositório no GitHub.
2. Envie `index.html` e a pasta `assets` para a raiz do repositório.
3. Abra `Settings` → `Pages`.
4. Em `Build and deployment`, escolha `Deploy from a branch`.
5. Selecione a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde a publicação.

## Personalização opcional

Após publicar, substitua o valor de `og:image` no `<head>` por uma URL absoluta da imagem, por exemplo:

`https://SEU-USUARIO.github.io/SEU-REPOSITORIO/assets/vitrine-silenciosa.jpg`

Isso melhora a prévia ao compartilhar o link em redes sociais.

## Observações

A página não usa bibliotecas JavaScript, construtores externos ou recursos da Hotmart.
O checkout abre diretamente na Kiwify.


## Página de obrigado personalizada

A página foi adicionada em:

`/obrigado/`

Depois que o GitHub Pages publicar o projeto, a URL será semelhante a:

`https://SEU-USUARIO.github.io/SEU-REPOSITORIO/obrigado/`

Na Kiwify:

1. Ative **“Esse produto tem uma página de obrigado personalizada ou upsell”**.
2. No campo **“Cartão ou Pix aprovado”**, cole a URL completa terminando em `/obrigado/`.
3. Salve a configuração.
4. Faça um teste em uma janela anônima após a publicação.

A página orienta o cliente a conferir o e-mail da compra e oferece um botão para:

`https://dashboard.kiwify.com.br/courses`

A página usa `noindex` para não aparecer nos resultados de busca.
