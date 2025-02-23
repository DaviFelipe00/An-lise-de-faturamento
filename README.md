# Análise de faturamento empresarial com pandas. 

Primeiro se faz a importação dos dados e sua conversão para poder tratá-los com pandas, isso é feito pela função **read_extensão do arquivo**, nesse caso foi um arquivo excel, logo a função será: **read_excel('Local do arquivo')**.  

![image](https://github.com/DaviFelipe00/Faturamento_com_pandas/blob/main/leitura_do_arquivo.png?raw=true)

Após ler o arquivo, uso a função *group_by* para agrupar apenas as colunas de 'Id_loja' e 'Valor Final' que é o quanto a loja faturou com seus produtos, uso a função *Sum()* para somar o valor final de todo o itens de uma mesma loja baseando-se no id dela. Veja:

![image](https://github.com/DaviFelipe00/Faturamento_com_pandas/blob/main/funcao_de_agrupamento.png?raw=true)
