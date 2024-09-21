# Diamantina

## UVC_escolhidos.tsv
Arquivo com contagem de colônia dos micro-organismos isolados de Diamantina em diversas fluências (no arquivo chamada de *dose*) de radiação Ultravioleta C (de onda curta).

## UV-escolhidos.R
Esse é o scrip que pega informações de contagem de colônia, calcula sobrevivência de cada replicata, calcula a média entre as replicatas, cria os gráficos de sobrevivência em monolog. Também realiza o ajuste da reparametrização de Brain-Cousens considerando hormesis para o cálculo de LD10 e LD1 (dose letal com 10% de população sobrevivente e 1% de sobrevivência respectivamente).

### Input
O input desse script é o arquivo **"UVC_escolhidos.tsv"**.
### Output
Esse script tem como output diversos gráficos de sobrevivência x fluência assim como o fit do modelo para cada isolado. Além disso, cria-se o arquivo **"ld10_tab.tsv"** que é uma tabela com os valores de LD10 de cada isolado.

# Validação de método
Nesse trabalho foi realizada a irradiação em meio sólido. Como a literatura utiliza principalmente irradiação em líquido, foram realizados experimentos com a bactéria radiotolerante *Deinococcus radiodurans* para validar os dados obtidos.

## deira.tsv
Esse arquivo contém os dados brutos de contagem de colônia da *D. radiodurans* em diversas fluências (no arquivo chamada de *dose*) em meio líquido e meio sólido.

## deira_methods.R
Script que analiza os dados presentes em **"deira.tsv"**, realizando cálculo de sobrevivência, média entre as replicatas com propagação de erro. O modelo Brain-Cousens é utilizado novamente para cálculo de LD10 e LD1 para cada método.
### Input
O input desse script é o arquivo **"deira.tsv"**.
### Output
Gráfico com as duas curvas de sobrevivência
