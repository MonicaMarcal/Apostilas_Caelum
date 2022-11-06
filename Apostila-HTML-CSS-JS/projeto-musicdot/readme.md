
# OBSERVAÇÕES:
OS arquivos: bootstrap.css é uma configuração padrão não mexemos nela. E o arquivo Bootstrap.js também veio pronto, ele é um arquivo contento o jquery porque precisamos dele para mexer com o bootstrap no javascrip.
De resto os outros arquivos foi implementado conforme o pdf.
##### ##### #####

Existem vários padrões de CSS mas durante o curso vamos usar um chamado BEMCSS. A vantagem de se usar BEMCSS para quem está começando com desenvolvimento HTML e CSS é que ele é um padrão que foca bastante em estrutura e facilita bastante na hora planejar os nomes das classes.

BEM usa um conceito de bloco__elemento--modificador para nomear suas classes, sendo que bloco é o elemento html que representa uma divisão de conteúdo cuja sua existência já tenha um sentido por si só, elemento representa uma parte semântica do bloco e modificador é uma sinalização de comportamento ou estilização.

As divisões entre bloco__elemento--modificador são chamados de: double snake__case e
double kebab--case . Quando queremos uma divisão como o espaço usamos ou kebab-case ou
o camelCase . Kebab-case é o mais comum para HTML e CSS e camelCase é mais comum em
JavaScript.

#######
# Um CSS Para Cada Componente Da Página
Essa abordagem também é bastante utilizada no mercado só que ela é mais utilizada em projetos com o uso de frameworks (React, Angular) e pré processadores de CSS (SASS). Nessa abordagem cada
seção ou componente da página tem um CSS exclusivo.
Vantagens:
Como cada componente tem seu próprio CSS só é necessário importar os componentes que precisamos usar em cada página, evitando importar estilos desnecessários.
Organização e manutenção fica menos complicada porque é mais claro saber exatamente qual arquivo trabalhar.
Desvantagens:
Precisamos importar um arquivo CSS diferente para cada componente que queremos usar que pode gerar linhas de imports gigantescas.

## PROGRESSIVE ENHANCEMENT - P.E
CONDIÇÕES, OPÇÕES, LIMITAÇÕES E RESTRIÇÕES, é como nossa aplicação se comporta, toda a semantica dele deve ser pensada,definir e garantir que o site seja acessível nessas condições definidas.

## DISPLAY FLEX
Vimos algumas maneiras de manipular posicionamento de elementos como
inline/block/inline-block,margin:e text-align display: , mas todas essas maneiras são muito "rígidas" na hora de distribuir elementos na página.Pensando nessa flexibilidade de posicionamento, as pessoas desenvolvedoras criaram um novo tipo de display : o display: flex; .

# BOOTSTRAP
### Uitilizamos Bootstrap na pagina matricula.html
Alguns componentes do Bootstrap possuem interatividade com o usuário através de JavaScript, então além de importar o arquivo CSS precisamos importar também o arquivo de javaScript. Só que
para o JavaScript do Bootstrap funcionar ele precisa de um outro framework chamado JQuery.
https://jquery.com/
A importação desses JavaScripts é feita logo antes do fechamento da tag </body> e o import do
JQuery deve vir antes do arquivo do Bootstrap:
...
<script src="js/jquery.js"></script>
<script src="js/bootstrap.js.js"></script>
</body>
</html>


# JAVASCRIPT
O JavaScript, como o próprio nome sugere, é uma linguagem de scripting. Uma linguagem de scripting é comumente definida como uma linguagem de programação que permite ao programador controlar uma ou mais aplicações de terceiros.
Outra característica comum nas linguagens de scripting é que normalmente elas são linguagens interpretadas, ou seja, não dependem de compilação para serem executadas. Essa característica é
presente no JavaScript: o código é interpretado e executado conforme é lido pelo navegador, linha a linha, assim como o HTML.