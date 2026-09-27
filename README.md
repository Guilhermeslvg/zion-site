# Site da agência Zion

No ar em: https://guilhermeslvg.github.io/zion-site/

## Como editar

Tudo fica em um arquivo só: `index.html`. As imagens ficam na pasta `img/`.

1. Abra o `index.html` aqui no GitHub e clique no lápis (Editar).
2. Procure a seção que quer mudar. Cada uma tem um comentário no começo: `<!-- ABERTURA -->`, `<!-- SERVIÇOS -->`, `<!-- MODELOS -->`, `<!-- SOBRE -->`, `<!-- CONTATO -->`.
3. Troque o texto entre as tags. Não precisa mexer no `<style>` nem no `<script>`.
4. Clique em "Commit changes". Em uns dois minutos o site atualiza sozinho.

## Coisas que aparecem em mais de um lugar

- **WhatsApp:** todos os links `https://wa.me/55...` e a linha `const ZAP = ...` dentro do `<script>`. Troque o número em todos.
- **Instagram:** os links `https://instagram.com/agenczion`.
- **Cores da marca:** no começo do `<style>`, dentro de `:root`.


## Modelos (carrossel)

Para adicionar um modelo, copie um bloco `<article class="carta">` dentro da seção `<!-- MODELOS -->` e troque o nome e a frase. O contador atualiza sozinho.
