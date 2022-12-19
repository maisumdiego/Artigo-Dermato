<img width=100% src="https://capsule-render.vercel.app/api?type=rect&color=0:2B32B2,100:1488CC&section=header&height=120&text=Projeto%20de%20análise%20de%20dados&desc=Artigo%20científico%20de%20dermatologia%20hospitalar&animation=fadeIn&fontColor=ffffff&fontSize=30&descSize=15&fontAlignY=45&descAlignY=70"/>

## Navegação
1. [Sobre o projeto](##Sobre-o-projeto)
2. [Ferramentas utilizadas](##Ferramentas-utilizadas)
3. [Conhecendo os dados](##Conhecendo-os-dados)

## Sobre o projeto
### Dermatologia hospitalar, análise do perfil das consultorias dermatológicas
Os dados tratados e analisados neste relatórios são referentes a pesquisa realizada no artigo **"Dermatologia hospitalar: análise do perfil das consultorias hospitalares em hospital terciário no sul do Brasil"**, dos autores MSc Iago Gonçalves Ferreira, MS Camila Saraiva Almeida, MS Lucas Abascal Bulcão, BSCE Diego Gonçalves Ferreira, PhD Renan Rangel Bonamigo, PhD Magda Blessmann Weber.

### Sobre o estudo
"As doenças de pele apresentam elevada prevalência no cenário hospitalar, representando importantes fatores de risco de morbimortalidade e de impacto nos custos hospitalares. Nessa perspectiva, a Dermatologia pode propiciar notáveis contribuições à assistência hospitalar, auxiliando as demais especialidades médicas no manejo clínico adequado das afecções dermatológicas. À vista disso, este estudo teve como objetivo analisar o perfil das requisições e consultorias realizadas pelo serviço de Dermatologia em complexo hospitalar terciário no sul do Brasil."

"[...] o estudo caracteriza-se como descritivo, observacional, e retrospectivo, sendo conduzido por meio de levantamento de dados e revisão de prontuários acerca das consultorias realizadas por serviço de Dermatologia, no período de agosto de 2018 a janeiro de 2020. As variáveis incluídas foram procedência das requisições, dados clínicos e hipótese diagnóstica das solicitações, perfil dos pacientes hospitalizados, diagnósticos dermatológicos finais, exames complementares, condutas terapêuticas e acompanhamento recomendado pelas equipes de consultoria dermatológica."

"Conclusão: Por meio deste estudo, demonstra-se a ampla gama de afecções dermatológicas prevalentes entre pacientes hospitalizados, enfatizando a importância da Dermatologia no diagnóstico e manejo clínico dessas condições, de forma a aperfeiçoar a assistência médica hospitalar. Além disso, destaca-se o benefício educacional, visto que a Dermatologia tem o potencial de contribuir com a formação de estudantes de medicina, médicos residentes de dermatologia e de outras especialidades."

## Ferramentas utilizadas

[![Jupyter Notebook](https://img.shields.io/badge/jupyter-103b91.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/try)
[![Python](https://img.shields.io/badge/python-103b91?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-103b91?style=for-the-badge&logo=microsoft-excel&logoColor=white)](https://www.microsoft.com/pt-br/microsoft-365/excel)

### Bibliotecas
[![Pandas](https://img.shields.io/badge/pandas-545454.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/numpy-545454.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org/)

## Conhecendo os dados
### Variáveis utilizadas na análise
#### 1. Status da consultoria

|Código|Status|
|---|---|
|1|Realizada|
|2|Duplicada|
|3|Suspensa|

##
#### 2. CID (Classificação Internacional de Doenças)
Doenças diagnosticadas nas consultorias.

##
#### 3. Idade
Idade exata do paciente na data de referência em anos.

##
#### 4. Faixa etária
Classificação das idades dos pacientes por faixas de idade.

|Faixa etária|
|---|
|0 - 1|
|2 - 12|
|13 - 18|
|19 - 25|
|26 - 35|
|36 - 45|
|46 - 55|
|56 - 65|
|66 - 85|
|> 85|

##
#### 5. Hospital
Hospitais de onde os dados foram coletados.

|Código|Hospital|
|---|---|
|1|Hospital Santa Clara|
|2|Hospital São Francisco|
|3|Hospital São José|
|4|Pavilhão Pereira Filho|
|5|Hospital Santa Rita|
|6|Hospital da Criança Santo Antônio|
|7|Hospital Dom Vicente Scherer|

##
#### 6. Classe de Hospital
Classificação dos hospitais de acordo com a sua finalidade, realizada pelo próprio artigo.

|Código|Classe|
|---|---|
|1|Hospitais Clínicos Adulto|
|2|Hospital Pediátrico|
|3|Hospital Ginecológico|
