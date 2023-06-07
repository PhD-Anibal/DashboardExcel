# Dashboard interativo de Clínica de Saúde - Excel

Prof. Ítalo Teotônio

## Apresentação do Problema
A empresa deseja desenvolver um Dashboard em Excel, para analisar os dados presentes em uma base de dados com informações referentes à atendimentos de uma clínica de saúde, nos anos de 2020 e 2021. O gestor que está solicitando este Dashboard não deixa claro os indicadores que gostaria de analisar. Ele simplesmente quer entender melhor as informações da empresa, relacionadas aos atendimentos médicos.

## Observações Importantes, coletadas junto à empresa:
A empresa atende por convênio e de forma particular e é importante entender essas informações de forma comparativa.
Alguns médicos podem solicitar retorno dos seus pacientes e quando isso acontece dentro de um período de 90 dias, estas consultas, denominadas retorno não são cobradas e estão identificadas nas bases de dados.
Os médicos podem solicitar exames aos pacientes. Quando isso ocorre, o exame fica vinculado ao médico, na base de dados da empresa.

## Tabelas da Base de Dados

![tabelas_do_cliente](https://github.com/PhD-Anibal/DashboardExcel/blob/main/img_tabelas.jpg)

Link da tabela em Excel original:
https://github.com/PhD-Anibal/DashboardExcel/blob/main/base_de_dados.xlsx

## Tratamento dos Dados
Com Power Query obtemos a tabela Atendimento:

![tabela_melhorada](https://github.com/PhD-Anibal/DashboardExcel/blob/main/img_atendimentos.jpg)

Esta tabela contem a informação das tabelas do banco de dados e são incluidas colunas para enriquecer os gráficos do Dashboard.

## Apresentação dos Resultados
Menú

![menu_do_dashboard](https://github.com/PhD-Anibal/DashboardExcel/blob/main/img_d_menu.jpg)

Atendimentos

![aba_com_tabela_atendimentos](https://github.com/PhD-Anibal/DashboardExcel/blob/main/img_d_atendimentos.jpg)

Dashboard

![aba_com_dashboard](https://github.com/PhD-Anibal/DashboardExcel/blob/main/img_d_dashboard.jpg)

# Insigths

Foi desenvolvido um dashboard nos seguintes KPI principais: receita e quantidade de atendimentos. A análise prioritária concentrou-se na comparação entre atendimentos por convênio (representado pela cor azul) e atendimentos particulares (representado pela cor verde). Para aprimorar a descrição do projeto, foram incluídos filtros que permitem uma análise mais detalhada, permitindo comparar não apenas por tipo de atendimento, mas também por médico e por ano.

No dashboard, foram utilizados gráficos de barras agrupadas para fornecer uma visão rápida e clara sobre os médicos que tiveram mais atendimentos, bem como a distribuição desses atendimentos entre convênio e particular. Além disso, outro gráfico de barras agrupadas foi implementado para realizar uma comparação semelhante, mas agora com base na especialidade dos médicos.

Além dos insights mencionados anteriormente, também foi criado um gráfico de linhas para comparar os atendimentos, tanto por convênio quanto particulares, em relação aos meses.

Esse gráfico de linhas proporciona uma visão temporal dos atendimentos, permitindo sazonais ou tendências ao longo do tempo. Com essa análise, é possível observar se há variações significativas na quantidade de atendimentos por convênio e particulares em diferentes meses do ano.

A inclusão desse gráfico de linhas adiciona uma perspectiva temporal valiosa ao dashboard, permitindo uma análise mais abrangente do comportamento dos atendimentos ao longo dos meses identificar padrões sazonais ou tendências ao longo do tempo ou eventos específicos que possam influenciar a demanda por atendimentos médicos.

Essas visualizações auxiliam na identificação de padrões e tendências, permitindo uma compreensão mais completa dos dados e facilitando a tomada de decisões informadas. O dashboard oferece uma maneira eficiente de monitorar e explorar os indicadores-chave de desempenho selecionados, fornecendo uma visão geral do projeto de análise de dados.

Link do Dashboard para fazer download e vizualisar no Excel:

https://github.com/PhD-Anibal/DashboardExcel/blob/main/dashboard.xlsx
