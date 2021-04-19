### A histótia da Internet 

Um vídeo para ajudar:
https://youtu.be/TNQsmPf24go

em 1993, Tim Berners-Lee foi o criado do protocolo `http://` e a linguagem de marcação `HTML`

### Representação de Dados

0 1 === bit
01000001 === 8bits == 1byte
1024 bytes === 1 KB
1024 KB === 1 MB
1024 MB === 1 GB
1024 GB === 1 TB
1024 TB === 1 PB
1024 PB === 1 EB

MB === MEGABYTES === ARMAZENAMENTO 
Mb === MEGABITS === TRANSMISSÃO

Na internet, todo site está em um servidor, que é identificado pelo número IP

Existe o IP local, e o IP publico 
uma das maneiras de descubrirmos o IP publico, é acessar o site https://www.iplocation.net/
para mudar o IP publico, é necessário somente desligar e ligar o modem.

Assim como um número de celular. Não decoramos todos os números de nossos amigos, colocamos um nome, e
para encontrar o número, procuramos na agenda de contaots para facilitar o contato do amigo
na internet, existem algo parecido, chamado `DNS`.

DOMÍNIO 
    - Nome único 
    - Pago anualmente
    - Vários TLDs

HOSPEDAGEM 
    - Espaço para armazenar arquivos
    - Pago mensalmente
    - Espaço, memória, recursos

### A diferença entre HTML, CSS

HTML (HYPER TEXT MARKUP LANGUAGE)
CSS (CASCADING STYLE SHEETS)

HTML é focada em contéudo, como textos, imagens, vídeos, tabelas, etc.
CSS é focado em design, como cores, sombras, tamanhos, posicionamento, etc.
JS é focada em interação, como menus, animações, popups, validações

https://emojipedia.org/
emojis para se colocar na aplicação, sempre iniciando com `&#x` + código

### Formatos de arquivos de imagem
os mais usados para web é `JPEG`, `PNG`
JPEG, ou JPG é uma imagem compacta
PBG é uma imagem com fundo transparente, com uma qualidade melhor.

No google, existem um campo chamado de `ferramentas`, usada muito para encontrar imagens se total acesso de modificar, ou comercializar imagens, há um filtro na busca, sempre se atentar a isso para não ter problema com direitos autorais, existe também dentro de `ferramentas`, o tamanho, para encontrar imagens pequenas, médias ou grandes.

### Colocando um Favicon (ícone da aba de titulo do site)
Uma dica importante é não pegar uma com muitos detalhes. Caso não tenha idéia de ícones, o site https://iconarchive.com/ pode ajudar, baixando com a extensão `ICO`.
Já para criar um ícone, o site https://favicon.cc pode ajuda
Já o site https://favicon.io permiti converter um texto, um emoji, imagem e formato de ícone (ICO)
no head do html, é recomendado colocar como nome padrão chamado `favicon`

### Semântica na HTML5
Com o avançado das tecnologias, muitas coisas se tornam obsoletas, ou seja, em breve vai ser parado de usar, por isso, é super importante se atualizar com respeito as tags, o que é semântica, o que é fomra.
No HTML5 é usado somente semântica, que é significado, formas é considerar em CSS, incluindo estilos.
Para ver se alguma tag está obsoleta, sempre veja no site oficial https://dev.w3.org/html5/pf-summary/obsolete.html

### Atalho no VScode
`Ctrl + shift + p -> emmet: Wrap with Abbreviation -> nome da tag `
Usado para facilitar tags dentro de um texto, como a utilização de um <strong>, ou um p dentro de outra tag.




### Tags importantes

<h1></h1> === Título nivel1
<h2></h2> === Título nivel2
<h3></h3> === Título nivel3
<h4></h4> === Título nivel4
<h5></h5> === Título nivel5
<h6></h6> === Título nivel6
<p></p> === parágrafo
<hr> === linha horizontal (horizontal row)
<br> === quebra de linha
&lt; === mostra o símbolo < (LESS THAN)
&gt; === mostra o símbolo > (GREATER THAN)
<!----> === comentários
lorem === um texto pronto para utilizar na tag <p>
<strong></strong> === Negrito / destaque
<em></em> === Itálico / Enfâse
<mark></mark> === marcar texto
<small></small> === texto pequeno
<sup></sup> === texto ou número na parte superior do texto (ex: 53 = 125)
<sub></sub> === texto ou número na parte inferior do texto (ex: H2O)
<code></code> === mostrar em formato de código-fonte
<pre></pre> === utilizado em mostrar muitas linhas no formato código-fonte
<q></q> === aspas ("")
<blockquote></blockquote> === espaçamento pra frente, como se fosse um parágrafo, inclusive, há um parâmetro dentro da tag chamado `cite="informações"`, que é basicamente na hora de buscar vai ser encontrado com a referência do site que você colocar.
<abbr title=""></abbr> === informações completas de uma abreviação
<bdo></bdo> === com o parãmetro `dir="ltr"` texto normal, e `dir="rtl"` texto invertido
<li></li> === linhas (obs, a partir do HTML, o fechamento da tag é opcioanl)
<ol></ol> === ordenação das listas, existem 3 tipos de parâmetros, o `type="1"` que é uma lista de números, o `type="a"`, que é uma lista de letras, e o `type="i"`, que é uma lista de algoritmos romanos.
<ul></ul> === lista não ordenadas, existem 3 tipos de parâmetros, o `type="disc"` que é bolinhas, o padrão, o `type="square"` que é quadradinhos, e o `type="circle"` que é bolinhas abertas.
<dt></dt> === como se fosse um tema de uma lista
<dd><dd> === contéudo do dt
<a></a> === link para entrar uma outra pagina, para funcionar é necessário utilizar o parâmetro `href="<url>"`, dessa forma, você entra na página, porém,  isso vai sobrepor sua página anterior, para resolver, pode-se utilizar mais um parâmetro que é o `target="_blank"`, que vai abrir um outra aba, não fechando a sua principal.
Outro ponto importante é colocar a parâmetro `rel="external`, para indicar ao navegador que o link é externo, link internos não é necessário utilizar o parâmetro `target="_blank"`.
Outro parâmetro padrão é o `target="_self"`, que é a pra prória aba.
Outro parãmetro utilizado é o `download="<nomedoarquivo>"` junto com o `type="nomedotipodoarquivo"`, para descobrir o type, o site https://www.iana.org/assignments/media-types ajuda a encontrar examente o tipo.