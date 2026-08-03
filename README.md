#  ifood_chalenge
Esse repositório contém o código desenvolvido em python para o desafio do iFood, que usa uma base de dados do Starbucks. O desafio, em si, envolvem muito mais a mdoelagem dos dados do que o usuod de machine learning.
# Estrutura
## diretório data:
  * Contém o subdiretório raw, com os arquivos csv originais do problema;
  * Contém o subdiretório processed, com os arquivos pré-processados e prontos para a modelagem
## diretírio notebooks
  * contém o notebook de preprocesamento( data_processing.ipynb), o de modelagem( mdeling.ipynb) , o de testes e exploração inicial( teste.ipynb). Também contém os arquivos de readme.md, a apresentacao ppt, e o arquivo de requirements
# Objetivo
Depois de fazer a limpeza e o pré-procesamento, utilizei um regressor logístico simples, sem tunning para resolver o desafio. O ifood deu apenas 5 dias para resolução do problema ( na verdade, 4 , se considerar que só recebi esse desafio na segunda-feira à noite). Gastei mais de 20 horas de trabalho, mesmo com o aceleradorda IA(Claude IA ) para solucionar. O desafio foi totalmente desbalanceado e, obviamente, não atingi os 'altos padrões' deles, mas serviu de aprendizado.
O desafio utilizou o Databricks community edition ( obrigado , Databricks) , o spark ( Obrigado, novamente, Databricks) , as bibliotecas pandas , numpy, sci-kitlearn( obrigado , comunidade python ) e os arquivos da Starbucks, tirados da Udacity( obrigado , Udacity ).
Novamente, devido à falta de tempo e o caráter apertado do desafio, não deu para configurar o ambiente da maneira que gostaria, criando arquivos de configuração, passando parâmetros no notebook e fazendo um trabalho melhor com o spark. Foi 'sugestão' do iFood usar o databricks, o git como repositório, o que adicionou ainda mais a entrega. 
