# Tutorial Pentaho

## Introdução
Este tutorial tem como objetivo demonstrar a utilização do Pentaho Data Integration para realizar a extração, transformação e carregamento de dados (ETL) de forma combinada para uma futura construção de um DataWarehouse. Acompanha também uma série de ferramentas utilizadas para auxiliar na criação de uma melhor análise possível, dado o exemplo das próximas seções.
É importante frisar que os passos abaixo foram realizados no Windows 10.

## Instalação
Primeiro de tudo, vamos à instalação de cada componente que utilizaremos.

#### JDK
> O único pré-requisito é ter um runtime Java (máquina virtual java ) instalada ou uma JDK (Kit de Desenvolvimento Java) instalado em sua máquina que pode ser obtida através do [link](https://www.oracle.com/technetwork/pt/java/javase/downloads/jdk8-downloads-2133151.html)
<img src="_tutorial/3.jpg">

> Após a instalação, podemos seguir as outras instalações...

#### Pentaho Data Integration
> Realize o download como indicado na imagem, através do [link indicado](https://sourceforge.net/projects/pentaho/files/Data%20Integration/)
<img src="_tutorial/1.jpg">

> Ao final do download, a pasta "pdi-ce-8.3.0.0-371" aparecerá no caminho escolhido para armazenar o download. Por padrão, fica em "Downloads".

> Ao entrar na pasta, vá em data-integration

> Para abrir o programa, clique no arquivo Spoon.bat, como indicado na figura abaixo
<img src="_tutorial/2.jpg">

## Onde obter nossas informações
> Bem, temos quase tudo o que precisamos para trabalhar, vamos aos dados que usaremos de exemplo:

> Em [www.dados.gov.br](http://www.dados.gov.br/dataset/microdados-do-censo-da-educacao-superior) podemos extrair alguns dados úteis para uma introdução à ferramenta

> Nele, temos a reunião de  informações sobre as instituições de ensino superior, seus cursos de graduação presencial ou a distância, cursos seqüenciais, vagas oferecidas, inscrições, matrículas, ingressantes e concluintes, além de informações sobre docentes, nas diferentes formas de organização acadêmica e categoria administrativa.
<img src="_tutorial/4.jpg">

> Cabe destacar nesse ponto a importância de uma ferramenta BI como o Pentaho para ETL: 
- a quantidade de informações geradas são muito grandes, 
- de ambientes diferentes, 
- períodos diferentes e 
- podem ser com padrões diferentes, 
- ou formatos diferentes. 
Por exemplo, possuímos dados de 1995 a 2014 que podem abordar todas estas questões apresentadas entre si.

>Por se tratar de um tutorial inicial, vamos abordar somente os arquivos .csv

> Portanto, vamos fazer o download do Microdados Censo da Educação Superior 2013 e 2014 para integrar estes dados e gerar o dado final
<img src="_tutorial/5.jpg">

> Ao clicar em "Explorar -> Ir para recurso" o download será realizado automaticamente. Lembre de fazer esse procedimento para os microdados de 2013 e 2014.
