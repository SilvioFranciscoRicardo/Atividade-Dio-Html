<!DOCTYPE html>
<html>
    <head>
        <title>Web Site DIO</title>
    </head>
    <body>
        <h1> Introdução ao HTML</h1>
        <hr>
        <h2>Indice</h2>
        <ul>
            <li> <a href=" #ferramentas ">Ferramentas Ultilizadas Html </a> </li>
            <li> <a href=" #elementos ">Inspetor de Elementos </a> </li>
            <li> <a href=" #estrutura ">Estrutura Basica </a> </li>
            <li> <a href=" #tags ">O que são Tags </a> </li>
            <li> <a href=" #texto ">Textos em Html </a> </li>
            <li> <a href=" #listas ">Listas Ordenadas e Não Ordenadas </a> </li>
            <li> <a href=" #links ">O que são Links </a> </li>
            <li> <a href=" #referencias ">Referencias Html </a> </li>
        </ul>

        <h2 id="ferramentas">Ferramentas Ultilizadas Html</h2>
        <p>A Web está crescendo exponencialmente e ficando cada vez mais complexa. É por isso que desenvolvedores web precisam das ferramentas certas para ajudar com seus trabalhos.</p>
        <p>IDEs (Integrated Development Environment ou Ambiente de Desenvolvimento Integrado) economizam seu tempo de alternar entre diferentes aplicativos e ajudam você manter seu foco no seu código.</p>
        <p>Existem alguns editores de texto mais comuns entre os desenvolvedores, como por exemplo :</p>
        <ul>
            <li><a href="https://code.visualstudio.com/" target="_blank" >Visual Studio Code (VS Code)</a></li>
            <li><a href="https://atom.io/" target="_blank" >Atom</a></li>
            <li><a href="https://www.sublimetext.com/" target="_blank">Sublimetext </a>
            <li><a href="https://aws.amazon.com/pt/cloud9/" target="_blank">Cloud9 </a></li>
            <li><a href="https://netbeans.apache.org/download/index.html" target="_blank">Netbeans </a></li>
        </ul>
        <blockquote><i> Tem alguns requisitos mínimos para usar uma IDE, como:
            1. Uma máquina com dois núcleos de 2 GHz ou mais
            2. 4 GB RAM e 20 GB de HD sobrando (caso você quer usar o Visual Studio, note que ele usa mais de 10 GB de HD).</i></blockquote>

        <h2 id="elementos">Inspetor de Elementos</h2>
        <p>O que é a ferramenta de inspecionar elemento? A ferramenta de inspecionar elemento é um utilitário que permite visualizar o código-fonte subjacente de qualquer página web. Além disso, você pode usá-la para fazer alterações temporárias e ver os resultados em tempo real, deixando o código-fonte original intacto.
        </p>
        <p>Para acessar as ferramentas de desenvolvimento dos browsers basta apertar a tecla <strong>F12</strong><mark>(Pode variar de acordo com o browser e sua versão)</mark>.
        Abra o navegador Google Chrome e insira a <strong> URL</strong> do site que quer alterar. Vamos usar o <u> www.facebook.com.br como exemplo</u>. Posicione o mouse no lugar onde você quer alterar, clique com o botão direito e clique na opção Inspecionar.
        </p>

        <h2 id="estrutura">Estrutura básica HTML</h2>
        <p>O documento HTML sempre inicia com o que chamamos de estrutura básica. Esta estrutura é quase que imutável. Sempre será dessa forma e você sempre, sempre começará seu HTML começando por esse código. Geralmente os editores como o Sublime Text já tem atalhos para iniciar os documentos HTM, com essa estrutura.
        É possível compreender o documento em HTML de uma maneira muito simples, através de uma divisão de blocos das tags essenciais, conforme a a seguinte estrutura:
        </p>
        <ul>
            <li> <abbr title="O doctype não é uma tag HTML"></abbr> Definição do documento (doctype)</li>
            <li>Cabeça (head)</li>
            <li>Corpo (body)</li>
            <li>Doctype - Definindo o documento</li>
        </ul>
        <blockquote> Uma coisa importante: SEMPRE deve existir o doctype, que é este código <strong> DOCTYPE html.</strong>
        </blockquote>
        <p>O doctype não é uma tag HTML, mas uma instrução para o navegador e outros programas que podem ler seu site, que o código encontrado ali é um código HTML. Assim eles sabem o que fazer para mostrar seu site da melhor forma possível. Lembre-se: o doctype é OBRIGATÓRIO e deve ser sempre a PRIMEIRA LINHA do seu documento.
        </p>
        <h5>HEAD</h5>
        <p>Contém informações que não são transpostas visivelmente para o usuário/leitor do documento. São dados implícitos, de uso e controle do documento: vinculação com outros arquivos, aplicação de lógica de programação de scripts e metadados. Na prática, todo o conteúdo do cabeçalho fica delimitado entre a abertura e fechamento tag head.
        </p>
        <h5>BODY</h5>
        <p>Trata-se do documento em si, ou seja, a informação legível para o usuário/leitor do documento. É todo e qualquer texto que se deseja apresentar, assim como toda e qualquer forma de mídia de saída (imagens, sons, miniaplicativos embutidos, conteúdo multimídia, etc). Além disso, toda a apresentação de entrada de dados (formulários) também se aplica neste seção do documento. Na prática, o corpo do documento é delimitado pelo par de tags <body> e </body>.
        </p>

        <h2 id="tags">O que são Tags</h2>
        <p>Tags são o conjunto de caracteres que formam um elemento, ou seja, quando nos referenciamos à Tag "p" estamos falando de paragrafos.

            Existem dois tipos de Tags, as que necessitam de fechamento e as que não necessitam de fechamento.
            
            Para as que necessitam de fechamento, utilizamos o sinal de menor ( < ), seguido do nome do elemento e o sinal de maior ( > ) para abertura. Para fechamento, utilizamos o sinal de menor ( < ), seguido de barra ( / ), nome do elemento e o sinal de maior ( > ).
            </p>
            <p>Atributos são informações que passamos na Tag para que ela se comporte da maneira esperada. Existem atributos globais (que funcionam em todas as Tags) e específicos (que são direcionados para cada Tag, através de especificação).
            </p>

            <h2 id="texto">Texto em HTML</h2>
            <p>Um dos principais objetivos do HTML é dar estrutura de texto e significado, também conhecido como semântica ), para que um navegador possa exibir-lo corretamente. Este artigo explica a forma como HTML pode ser usado para estruturar uma página de texto, adicionar títulos e parágrafos, enfatizar palavras, criar listas e muito mais.
                O texto mais leitura, um livro é composto por títulos e parágrafos, um jornal lendo, um livro da faculdade, etc.A leitura mais conteúdo torna a experiência de fácil e mais agradável.
                A semântica está em todos os lugares — contamos com experiência anterior para nos dizer qual é a função dos objetos do dia a dia.
                </p>

            <h2 id="listas">Listas ordenadas e nao ordenadas</h2>
            <p><strong>Não ordenado</strong>
                Como as listas não ordenadas são usadas para marcar listas de itens para os quais a ordem dos itens não são importantes.
                Toda lista desordenada começa com um <strong>ul</strong> isso envolve todos os itens da lista.
                O passo final da lista cada item da lista em um elemento <strong> li</strong>(elemento).
                </p>
                <p><strong> Ordenada</strong>
                    As listas ordenadas são listas em que a ordem dos itens é importante.
                    A estrutura de marcação é a mesma das listas não ordenadas, exceto que você deve conter os itens da lista em um elemento <strong>ol</strong>, em vez de <strong>ul</strong>.
                    </p>
            <h2 id="links">O que são Link</h2>
            <p>Um link básico é criado para conter o texto (ou outro, Block level links ) que você quer transformar em um link dentro de um elemento <a>, e dando um atributo href, também conhecido como Hypertext Reference , ou target ) que lhe endereço da Web para o qual você deseja que o link aponte.
            </p>

            <h2 id="referencias">Referencias Html</h2>
            <ul>
                <li> https://tableless.github.io/iniciantes/manual/html/oquesemantica.html </li>
                <li>https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML/HTML_text_fundamentals</li>
                <li>https://blog.umbler.com/br/ferramentas-para-desenvolvedores-da-web/?gclid=Cj0KCQiAyMKbBhD1ARIsANs7rEHf-nLw0fliGJWi7u9Ycps3s4x6MCgII7CbY8gPC5_CaM-X6dwo-SkaAjXUEALw_wcB</li>
            </ul>
            
    </body>
</html>
