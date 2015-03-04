::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::centerplate:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

Centerplate é uma framework CSS que criei pra facilitar minha vida quando o assunto é hotsite e landing page. Centralize o conteúdo e faça qualquer div do código preencher a tela inteira horizontalmente sem barra de rolagem. Abra o arquivo de exemplo e você vai entender!

1) USO
- Crie pelo menos uma div que você deseja que seja horizontalmente infinita. Dê a altura que você precisa e coloque a largura em 100%.
<div style="height:200px; width:100%;"></div>

- Aproveite esta div e dê a cor ou imagem de fundo que você quer que ela tenha.
<div style="height:200px; width:100%; background-color:"#F0F;"></div>

- Crie uma nova div dentro desta, com as classes "centerit" e "h-ext". Esta é a div onde o seu conteúdo ficará.
<div style="height:200px; width:100%; background-color:"#F0F;">
<div id="conteudo" class="centerit h-ext">
<p>Conteúdo</p>
</div>
</div>

- Faça isso com todas as divs que você quiser que sejam assim.

2) CLASSES

Não tem segredo. São apenas duas:
"centerit": é como se fosse um wrapper, bota o conteúdo no meio da tela.
"h-ext": estica a div infinitamente.

3) TERMOS DE USO

Fique à vontade!

4) CONTATOS E CONSIDERAÇÕES

Se precisar de ajuda, me procure aqui no GH ou no Twitter, onde sou o @gordotank.

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
