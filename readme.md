#ESTUDO WEB#

  HTML
      
   -Estrutura padrão html-
      
    <!doctype html>

    <html>

      <head>

        <title></title>

        <meta charset="utf-8">

      </head>

      <body>


      </body>

    </html>

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


TAGS USADAS EM FORMATAÇÃO DE TEXTO

    <!doctype html>
  
    <head>
    
      <title>Meu Site</title>
      
      <meta charset="utf-8">
    
    </head>
    
    <body>
    
      Para usar <strong>negrito</strong>
      
      Para usar <em>itálico</em>
      
      Para usar <u>underline</u>
      
      Para usar <strike>errado</strike>
    
    </body>
    
//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
    
TAGS PARA LISTAS NÃO ORDENAS E ORDENADAS

    <!doctype html>
  
    <head>
    
      <title>Meu Estudos WEB</title>
      
      <meta charset="utf-8">
    
    </head>
    
    <body>
    
      <h1>TIPOS DE LISTAS NÃO ORDENADAS</h1>
      <!-- Tipos de Listas: circle, square, disc -->
      <ul type="square">
        
        <li>Notebook</li>
        <li>Rorteador</li>
        
      </ul>
      
      <h1>TIPOS DE LISTAS ORDENADAS</h1>
      <!-- Tipos de Listas: A, 1, a, I, i -->
      <ol type="A">
      
        Para usar os tipos de listas ordenadas apenas trocar entre aspas:
        A = para listagem com o alfabeto maiúsculo
        1 = para listagem com os números
        a = para listagem com o alfabetos em minúscula
        I =  para listagem com os números romanos maiúsculo
        i = para listagem com os números romanos minúsculo
      
      </ol>
    
    </body>

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

-CRIAÇÃO DE HYPER LINKS-

    <!doctype html>
    
    <head>
      
      <title>HYPER LINKS</title>
      <meta charset="utf-8">
      
    </head>
    
    <body>
    
      <a href="-LINK-"></a>
    
    </body>

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

-PARA CRIACAÇÃO DE TABELAS-

    <!doctype html>

      <head>

        <title>TABELAS</title>
        <meta charset="utf-8">
        
      </head>

      <body>

    <!-- CRIA A TABELA, E MUDA O TAMANHO DA BORDA-->
        <table border="2">

    <!-- CRIA A LINHA DA TABELA -->    
          <tr>

    <!-- CRIA A LINHA PARA COLOCAR OS DADOS DENTRO DA CELULA DA TABELA -->      
            <td></td>

    <!-- CRIA A LINHA DE CABEÇALHO DA TABELA -->
            <th></th>

          </tr>

        </table>

      </body

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

-PODEMOS ADCIONAR IMAGENDS NA TABLE E LINKS, ATRAVES DAS TAGS -

    <a href=""></a>

    <<img src="" alt="">


-PODEMOS TAMBÉM DEFINIR WIDTH DE IMAGENDS COM PORCENTAGENS-

//////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////


-PARA DEFINIRMOS O TAMANHO DAS ROWS PODEMOS UTLIZAR OS CODIGOS-

    <!-- Usado para definir a quantidade de linhas que a data vai ocupar -->
    <td rowspan="2">

    <!-- Usado para definir a quantidade de colunas que a data irá ocupar -->
    <td colspan="2">



//////////////////////////////////////////////////////////////////////////////////////////////////////////////

-FORMULÁRIOS-

    <!doctype html>

    <head>

      <title> FORMULÁRIOS </title>
      <meta charset="utf-8">

    </head>

    <body>

      <form>

      <!-- Input pode ser usado para adcionar um tipo de inserção de dado,
      Podendo definir o tipo com (type=""), por exemplo, text, para inserção de texto, e o name serve para dar um nome para o input, para obtenção dos dados do input -->
        <input type="" name=''>

      <!-- EXEMPLOS -->

        <input type="text">

        <!-- No caso dos INPUT com o tipo SUBMIT devemos usar o value para adicionar um nome ao botão -->
        <input type="submit" value="">

        <input type="password">

      </form>

    </body>

-DENTRO DO FORM PODEMOS USAR OUTRAS TAG PARA EXPANDIR A OPÇÃO DE COLETA DE DADOS-

  Exemplo:

    <!doctype html>

    <head>

      <title> FORMULÁRIOS </title>
      <meta charset="utf-8">

    </head>

    <boby>

      <select>

        <option> Podemos usar a tag OPTION </option>
        <option> Para criarmos uma caixa de opções </option>
        <option> Mas e recomendado a usar essa tag com grande quantidade de opções </option>

      </select>

      <h2> MAIS OPÇÕES </h2>

      <!-- A tag TEXTAREA serve para adicionar um campo de texto para escrever grandes quantidades de caracteres -->
      <textarea></textarea>

    </body>

-CARACTERES ESPECIAIS

      non-breaking space                  &nbsp;  &#160;  
    < less than                           &lt;    &#60; 
    > greater than                        &gt;    &#62; 
    & ampersand                           &amp;   &#38; 
    " double quotation mark               &quot;  &#34; 
    ' single quotation mark (apostrophe)  &apos;  &#39; 
    ¢ cent                                &cent;  &#162;  
    £ pound                               &pound; &#163;  
    ¥ yen                                 &yen;   &#165;  
    € euro                                &euro;  &#8364; 
    © copyright                           &copy;  &#169;  
    ® registered trademark                &reg;   &#174;
