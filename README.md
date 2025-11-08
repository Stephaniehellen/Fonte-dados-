# Fonte-dados
Fontes de informação e bancos de dados. 

**1-ATIVIDADE MAPA MENTAL**
<img width="1280" height="853" alt="image" src="https://github.com/user-attachments/assets/3edb1c0c-be66-43a6-8cbc-e46bba8a5162" />



**APRESENTAÇÃO DADOS-EM GRUPO**
[Trabalho-de-Fontes-e-Dados (2) (1).pdf](https://github.com/user-attachments/files/23427224/Trabalho-de-Fontes-e-Dados.2.1.pdf)



**2-DADOS DE MUNICIPIOS** 
[Atividade (VTI).xlsx](https://github.com/user-attachments/files/23427284/Atividade.VTI.xlsx)
Foi usado a seguintes formulas para a 5 perguntas: 
Qual foi o Valor Total da Transformação Industrial (VTI), em mil reais corrigidos para 2022, do município de São Paulo no ano de 2022? 
Formula:=SOMASES(Tabela1[[#Tudo];[VTI-(MilReais)]];Tabela1[[#Tudo];[municipio]];"São Paulo";Tabela1[[#Tudo];[Ano]];2022)

Qual foi a remuneração média dos trabalhadores da produção em Campinas, ajustada para valores de 2022?
=MÉDIASES(Tabela1[[#Tudo];[Remuneracao_trabalhadores_da_producao_(MilReais)]];Tabela1[[#Tudo];[municipio]];"Campinas";Tabela1[[#Tudo];[Ano]];2022)

Qual é a produtividade média dos trabalhadores da produção em São José dos Campos, considerando o VTI por trabalhador em mil R$ de 2022?
=MÉDIASES(Tabela1[[#Tudo];[Trabalhadores_da_producao]];Tabela1[[#Tudo];[municipio]];"São José dos Campos";Tabela1[[#Tudo];[Ano]];2022)

Qual é o VTI acumulado (em mil R$ de 2022) de São José dos Campos, somando em 2005?
=SOMASES(Tabela1[VTI(MilR$2022)];Tabela1[municipio];"São José dos Campos";Tabela1[Ano];2005)

Qual é a produtividade média dos trabalhadores da produção em São José dos Campos, considerando o VTI por trabalhador em mil R$ de 2004?
=MÉDIASES(Tabela1[[#Tudo];[Trabalhadores_da_producao]];Tabela1[[#Tudo];[municipio]];"São José dos Campos";Tabela1[[#Tudo];[Ano]];2004)

<img width="1826" height="539" alt="Captura de tela 2025-11-07 210742" src="https://github.com/user-attachments/assets/90bf3c54-d6c9-4237-a487-c274226fb32c" />
<img width="1850" height="570" alt="Captura de tela 2025-11-07 211002" src="https://github.com/user-attachments/assets/60fa408f-fa3f-4e5e-9e45-06cf3935786b" />

[Atividade (VTI).xlsx](https://github.com/user-attachments/files/23427400/Atividade.VTI.xlsx) 


