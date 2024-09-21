## Arquivos "MS1655_x.tsv"
Os arquivos **"MS1655_1.tsv"**, **"MS1655_2.tsv"** e **"MS1655_3.tsv"** contém os dados brutos de contagem de colônia das curvas de crescimento da *Escherichia coli* MG1655 em diferentes concentrações de NaCl adicionados ao meio de cultura. Cada arquivo corresponde a uma replicata biológica.

## e_coli_ufc.R
Esse arquivo contém o script que processa os dados das curvas de crescimento, realizando a média entre as replicatas e sua propagação de erro. Além disso, esse script utiliza o modelo Baranyi para conseguir valores numéricos para os parâmetros da curva de crescimento (velocidade máxima, lag, capacidade de suporte).
### Input
Os 3 arquivos MS1655_x.tsv
### Output
Gráficos e tabela de velocidade máxima de crescimento em arquivo chamado **"mumax_tab.tsv"**.
