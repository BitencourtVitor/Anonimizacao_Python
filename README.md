# Linhas & Agulhas

###### Aqui, você terá acesso a:

- Arquivo .ipynb criado para anonimizar os dados;
- Arquivo .pbix para caso queira interagir;
- Base de dados já depois do tratamento;
- Print do Dashboard feito em Power BI

## Introdução
Após trabalhar em uma indústria vidreira e desenvolver um estudo de Análise de Dados para as vendas no ano de 2021, foi obtida uma base com dados anônimos acerca da empresa. Afim de desenvolver uma análise que pudesse aproveitar dos dados, foi feita uma anonimização utilizando programação em linguagem Python.

## Conclusão
Observando as vendas por Rota, foi possível constatar uma disparidade: a maior rota vende cerca de 5 vezes mais que a menor. Caso pense-se em uma expansão nas vendas, pode-se considerar fortalecer pontos fracos.

Houve uma queda na média do valor vendido pela empresa no mês de dezembro, o que pode ser justificado pela chegada do período do fim de ano, onde o mercado se posiciona menos no atacado (ou indústria) e mais no varejo.

## Pontos a melhorar 
A análise possui limitadores, sabe-se quanto vendeu mas não se sabe nenhuma informação sobre a saúde financeira dos clientes enquanto ativos, por exemplo.

Usar ferramentas diferentes para coleta e tratamento seria algo dispensável caso houvesse proficiência em uma única ferramenta.

A utilização de cidades fictícias na anonimização impossibilitou a realização de uma observação geográfica, um dos principais fatores a serem observados caso pense-se em expansão das vendas em determinada região.

## Passo a passo
- OBJETIVO: Realizar um estudo sobre as vendas feitas no ano de 2021 afim de identificar padrões, insights, pontos fortes e fracos e traçar, a partir disso, possíveis estratégias para o ano seguinte.

- EXTRAÇÃO: O banco de dados da empresa é baseado na linguagem SQL.
A partir disso, foram feitas consultas (queries) com o nome do cliente, metragem comprada, valor comprado, cidade do cadastro, roteiro de entrega e o período (mês) em referência. Os resultados das consultas foram salvos em arquivos no formato .csv
- TRANSFORMAÇÃO: O arquivo .csv foi manuseado no Power Query para fazer as devidas correções, desde correção de ortografia até formatação dos valores para evitar discrepância.
- ANONIMIZAÇÃO: Após instalar a biblioteca Faker dentro do Anaconda Prompt, foi desenvolvido o [código para anonimização dos dados](https://github.com/BitencourtVitor/Anonimizacao_Python/blob/main/C%C3%B3digo%20para%20Anonimizar.ipynb).
- LOAD: O dashboard foi criado no Figma tomando cuidado com paleta de cores, distribuição dos elementos visuais, etc.

![Aqui um print do dashboard](https://github.com/BitencourtVitor/Anonimizacao_Python/blob/main/print%20dashboard%20L%26A.png)
