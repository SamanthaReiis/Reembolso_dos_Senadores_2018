# Análise de Dados de Reembolso de Senadores no ano 2018

 ##### Análise de reembolso de diversas despesas de senadores em 2018 com a biblioteca Pandas do Python
 
 #### Os Dados são provinientes do site : [Dados Camara](https://dadosabertos.camara.leg.br) 
  - O formato do arquivo é csv
  - O arquivo é uma tabela com 10 colunas do tipo: Ano, Mês, Senador, tipo de despesa ,Valor_Reembolsado e etc. 
      E possui 24492 linhas.
#### O objetivo da análise foi saber quais e quantos senadores fizeram o seu devido reembolso.

#### Resultados Obtidos
 - O valor total de reembolso foi de R$: 25604701.33
 - O Senador com maior número solicitação de reembolso foi EDUARDO LOPES com 864 pedidos.
 - O Senador com menor número de solicitação de reembolso foi ZÉ SANTANA com 8 pedidos.
 - O maior valor de reembolso foi  para a Senadora ROSE DE FREITAS no valor de R$ 103900.00 com  despesa de 
    divulgação da atividade parlamentar
 - O menor valor de reembolso foi com despesa de passagens aéreas, aquáticas e terrestres nacionais  no valor de R$ 0.01,
    com isto faz entender que não houve reembolso ou ainda não havia sido realizado. Nesta categoria aparece com os mesmos 
    valores e tipo de despesas os Senadores DÁRIO BERGER e JORGE VIANA.
 - A quantidade de reembolsos por tipo de despesa
 
 
 | Tipo de Despesa                                                  | Quantidade de Reembolso |
|------------------------------------------------------------------|-------------------------|
| Locomoção,Hospedagem,Alimentação,Comb. e Lubrif.                 |          10147          |
| Passagens Aéreas, Aquát. e Terrestres Nacionais                  |          5820           |
|         Aluguel de imóveis para escritório político, ...         |          5042           |
| Aquisição de material de consumo para uso no escritório político |          1761           |
| Contratação de consultorias, assessorias,  pesquisas ...         |          928            |
| Divulgação da atividade parlamentar                              |          750            |
| Serviços de segurança privada                                    |          44             |


- Valor de reembolso por tipo de despesa

| Tipo de Despesa                                                  | Valor de Reembolso |
|------------------------------------------------------------------|--------------------|
| Locomoção,Hospedagem,Alimentação,Comb. e Lubrif.                 | 5620092.84         |
| Passagens Aéreas, Aquát. e Terrestres Nacionais                  | 6335284.94         |
|         Aluguel de imóveis para escritório político, ...         | 6335284.94         |
| Aquisição de material de consumo para uso no escritório político | 900312.04          |
| Contratação de consultorias, assessorias,  pesquisas ...         | 4966449.41         |
| Divulgação da atividade parlamentar                              | 2568910.24         |
| Serviços de segurança privada                                    | 172213.61          |


 #### AVISOS IMPORTANTES
 
 1. A análise foi bem básica, usando as principais funções da biblioteca pandas.
 2. Encontrou algum erro? Me ajude a melhorar!
 3. Está com dúvidas sobre a documentação ou os dados? Entre em contato.
 4. Ao decorrer do meu aprendizado as análise será revisada e melhorada.
