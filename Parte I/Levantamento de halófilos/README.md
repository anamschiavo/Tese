## halophile_bruto.tsv
Arquivo **"halophile_bruto.tsv"** contém os dados do levantamento de halófilos descritos no International Journal of Evolutionary and Systematic Microbiology.

## halophile_pre.R
Arquivo **"halophile_pre.R"** é script que realiza o pré-processamento dos dados, retirando espécies com informações incompletas de faixa ótima e suportada de NaCl, transformações de unidades, etc.
### Input
O input desse script é o arquivo **"halophile_bruto.tsv"**.
### Output
O output são os arquivos **"halo_sup.tsv"**, que contém as informações limpas das espécies com faixa suportada de NaCl completas, e **"halo_opt.tsv"**, que contém as informações limpas das espécies com faixa ótima de NaCl completas.

## halophile_count.R
O arquivo **"halophile_count.R"** é o script que realiza o Método da Contagem (descrito na tese) e cria os gráficos.
### Input
O input desse script são *ambos* os arquivos **"halo_sup.tsv"** e **"halo_opt.tsv"**.
### Output
Vários gráficos diferentes de estatística descritiva desses dados.

## halophile_mean.R
O arquivo **"halophile_count.R"** é o script que realiza o Método da Média (descrito na tese) e cria os gráficos.
### Input
O input desse script são *ambos* os arquivos **"halo_sup.tsv"** e **"halo_opt.tsv"**.
### Output
Vários gráficos diferentes de estatística descritiva desses dados.
