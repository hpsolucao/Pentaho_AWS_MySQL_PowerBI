## Pentaho + AWS  + MySQL + PowerBI
Ingestão de Dados com Pentaho para o S3 (2 camadas Raw e Processed) Banco Mysql+Athena, Dashboard PowerBI

O trabalho consiste em simular um ambiente de Data Lake com 2 camadas onde a ultima camada é o espelho do Banco de dados e Resultado final em um Dashboard desenvolvido em PowerBI

*<n>Fonte de Dados CSV:</n><br>
-Lojas.csv<br>
-Produto.csv<br>
-Vendas.csv<br>
-Vendedor.csv<br>

*ELT: <br>
-Camada RawZone (Dados puro igual a origem)<br>
-Camada Processed (Dados igual ao banco com possibilidade de acesso direto sem necessidade de um banco de dados SGBD)<br>

*Banco:<br>
-Mysql (opção por ser free, a modelagem é a mesma pra qualquer outra opção SGBD ou DW etc.)<br>

*Dashboard:<br>
-PowerBI<br>

*Desenho do projeto:<br>
![Desenho do Projeto](Desenho_Projeto.jpg)
<br>
*Desenho do ELT DataLake S3 com Pentaho PDI:<br>
![ELT S3](DataLake_ELT.jpg)

<br>
*Dashboard Resultado final com tendencia de vendas:<br>
![Dashboard](dashboard_vendas.jpg)
