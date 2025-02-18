<h1>O que é HTML?</h1>

<p>A Linguagem de Marcação de Hipertexto (HTML) é uma linguagem de computador que compõe a maior parte das páginas da internet e dos aplicativos online. Um hipertexto é um texto usado para fazer referência a outros textos, enquanto uma linguagem de marcação é composta por uma série de marcações que dizem para os servidores da web qual é o estilo e a estrutura de um documento.
O HTML não é considerado uma linguagem de programação, já que ele não pode criar funcionalidades dinâmicas. Ao invés disso, com o HTML, os usuários podem criar e estruturar seções, parágrafos e links usando elementos, tags e atributos.
Confira abaixo alguns dos usos mais comuns para o HTML:</p>

* Desenvolvimento web. Os desenvolvedores usam códigos HTML para projetar como um navegador vai exibir os elementos das páginas, como textos, hiperlinks e arquivos de mídia.
* Navegação na internet. Os usuários podem navegar facilmente e inserir links entre páginas e sites relacionados, já que o HTML é amplamente usado para incorporar hiperlinks.
* Documentação. O HTML torna possível a organização e a formatação de documentos, de maneira similar ao Microsoft Word.

<p>Também vale notar que o HTML agora é considerado um padrão oficial da internet. O World Wide Web Consortium (W3C) mantêm e desenvolve especificações do HTML, além de providenciar atualizações regulares.
Um site médio inclui diversas páginas HTML diferentes. Por exemplo, ele pode trazer uma página inicial, uma página “sobre” e uma página de contato. Cada uma delas possui um arquivo HTML separado.
Documentos HTML são arquivos que terminam com uma extensão .html ou .htm. Um navegador lê o arquivo HTML e renderiza o seu conteúdo para que os usuários da internet possam vê-lo.
Todas as páginas HTML possuem uma série de elementos, que consistem num conjunto de tags e atributos. Os elementos HTML são os tijolos de construção de uma página da internet. Uma tag diz para o navegador onde um elemento começa e termina, enquanto um atributo descreve as características de um elemento.
As três principais partes de um elemento são:</p>

* Tag de abertura – usada para dizer onde um elemento começa a ter efeito. A tag é cercada de colchetes angulares para abertura e fechamento. Por exemplo, use a tag de abertura <p> para criar um parágrafo.
* Conteúdo – essa é a parte que os usuários verão.
* Tag de fechamento – igual à tag de abertura, mas com uma barra antes do nome do elemento. Por exemplo, </p> para encerrar um parágrafo.

<p>A combinação dessas três partes vai criar um elemento HTML.
<br>< p >É assim que você adiciona um parágrafo no HTML.< /p >.
<br>OBS: os espaços estão ai por conflitos na formatação!
</p>

<p>Outra parte crucial de um elemento HTML é o seu atributo, que possui duas seções — um nome e um valor de atributo. O nome identifica a informação adicional que um usuário deseja acrescentar, enquanto o valor de atributo fornece mais especificações.
Por exemplo, um elemento de estilo que adiciona a cor roxa e uma fonte da família verdana ficará assim:
<br>< p style ="color:purple;font-family:verdana">É assim que você adiciona um parágrafo no HTML.< /p>
<br>OBS: os espaços estão ai por conflitos na formatação!
</p>

<p>Outro atributo é a classe HTML, que é mais importante para desenvolvimento e programação. Essa classe de atributo adiciona informações de estilo que podem funcionar em elementos diferentes com o mesmo valor de classe.
Por exemplo, vamos usar o mesmo estilo para um cabeçalho < h1> e para um parágrafo < p>. O estilo inclui cor de fundo, borda, margem e preenchimento — tudo dentro da classe .important. Para termos o mesmo estilo no < h1> e no < p>, adicione class=”important” depois de cada tag de abertura:
</p>

<br><p>< html>
<br>< head>
<br>< style>
<br>.important {
  <br>background-color: blue;
  <br>color: white;
  <br>border: 2px solid black;
  <br>margin: 2px;
  <br>padding: 2px;
}
<br></ style>
<br></ head>
<br>< body>
<br>< h1 class="important">Isto é um cabeçalho</ p>
<br>< p class="important">Isto é um parágrafo.</ p>
<br></ body>
<br></ html>
<br><br>OBS: os espaços estão ai por conflitos na formatação!
</p>

<p>A maioria dos elementos possui uma tag de abertura e de fechamento, mas alguns não precisam fechar a tag para funcionar. Esse é o caso dos elementos vazios. Eles não usam uma tag de fechamento pois não têm conteúdo:
<br>< img src="/" alt="Imagem">
<br>OBS: os espaços estão ai por conflitos na formatação!
</p>

<p>Essa tag de imagem possui dois atributos — um atributo src (que é um caminho de imagem) e um atributo alt (que é o texto de descrição). Contudo, ele não tem conteúdo nem uma tag de fechamento.
Finalmente, cada documento HTML deve começar com uma declaração <!DOCTYPE> para informar ao navegador qual é o tipo de documento. Com o HTML5, a declaração doctype HTML pública será:
<br>< !DOCTYPE html>
</p>

<h1>A História do HTML</h1>

<p>O HTML foi inventado por Tim Berners-Lee, um físico do centro de pesquisas CERN, na Suíça. Ele surgiu com a ideia de um sistema de hipertexto na internet.
Hipertexto significa um texto que possui referências (links) para outros textos que podem ser acessados imediatamente. Ele publicou a primeira versão do HTML em 1991, consistindo em 18 tags. Desde então, cada versão do HTML vem com novas tags e atributos (modificadores de tags).
Devido a rápida ascensão e popularidade, o HTML é agora considerado um padrão oficial da web.
O maior upgrade da linguagem foi o lançamento do HTML5 em 2014. Diversas novas tags semânticas foram adicionadas que revelam o significado do seu próprio conteúdo, como  < article>, < header>, e < footer>.
</p>

<h2>Tags e Elementos HTML mais Utilizados</h2>

<p>Atualmente, existem 142 tags HTML disponíveis, que permitem a criação de diversos elementos. Mesmo que os navegadores modernos não suportem algumas dessas tags, você ainda vai se beneficiar de aprender sobre os diferentes elementos disponíveis.
Esta seção vai discutir as tags HTML mais usadas e dois elementos principais: os elementos bloco e os elementos em linha (inline).
</p>
<h2>Elementos Bloco</h2>

<p>Os elementos bloco ocupam a largura completa de uma página. Eles sempre iniciam uma nova linha no documento. Por exemplo, um elemento cabeçalho estará numa linha diferente de um elemento parágrafo.
Toda página HTML usa essas três tags:</p>

* A tag < html> é o elemento raiz que define todo o documento HTML.
* A tag < head> contém metadados sobre o título e a codificação de caracteres da página.
* A tag < body> inclui todo o conteúdo que aparece na página.

<p><br>< html>
 <br>< head>
   <br>< !-- META INFORMAÇÕES --> 
 <br>< /head>
 <br>< body>
   <br>< !-- CONTEÚDO DA PÁGINA -->
 <br> < /body>
<br> < /html> </p>

<p>Outras tags de bloco populares são:</p>

* Tags de Cabeçalho – elas variam entre < h1> e < h6>, onde h1 tem um tamanho maior, que vai diminuindo até chegar no h6.
* Tags de parágrafo – são abertas usando a tag < p>.
* Tags de lista – possuem diferentes variações. Use a tag < ol> para uma lista ordenada, e a tag < ul> para uma lista sem ordem definida. Então, envolva cada item da lista com a tag < li>.

<h2>Elementos em Linha</h2
<p>Um elemento em linha (ou inline) formatam o conteúdo interno de elementos de bloco. Isso inclui a adição de links ou de linhas com ênfase. Os elementos inline são normalmente usados para formatar texto sem quebrar o fluxo do conteúdo.
Por exemplo, uma tag < strong> faz o elemento ser renderizado em negrito, enquanto a tag < em> faz ele aparecer em itálico. Os hiperlinks também são elementos em linha que usam uma tag < a> e um atributo href para indicar o destino do link:
<br>< a href="https://example.com/">Click me! < /a> </p>

