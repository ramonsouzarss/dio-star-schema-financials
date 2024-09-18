# DIO Bootcamp Sysvision - Data Analytics com Power BI

Modelagem de Dados a partir do sample Financials do Power BI. Foi modelado um Star Schema utilizando Agrupamento de colunas, referências a partir da tabela principal e foi criada uma tabela e colunas por meio de DAX:

- D_Calendario = CALENDÁRIO(DATA(2020, 1, 1), DATA(2023, 12, 31))

Novas colunas para a tabela D_Calendario:

- Ano = YEAR([Date])
- Mês = MONTH([Date])
- Dia = DAY([Data])
