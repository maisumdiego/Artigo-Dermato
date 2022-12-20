<img width=100% src="https://capsule-render.vercel.app/api?type=rect&color=0:2B32B2,100:1488CC&section=header&height=120&text=Projeto%20de%20análise%20de%20dados&desc=Artigo%20científico%20de%20dermatologia%20hospitalar&animation=fadeIn&fontColor=ffffff&fontSize=30&descSize=15&fontAlignY=45&descAlignY=70"/>

## Navegação
1. [Sobre o projeto](#sobre-o-projeto)  
 1.1 [Dermatologia hospitalar, análise do perfil das consultorias dermatológicas](#dermatologia-hospitalar-an%C3%A1lise-do-perfil-das-consultorias-dermatol%C3%B3gicas)  
 1.2 [Sobre o estudo](#sobre-o-estudo)
2. [Tecnologias utilizadas](tecnologias-utilizadas)  
 2.1 [Bibliotecas utilizadas](bibliotecas-utilizadas)
3. [Conhecendo os dados](conhecendo-os-dados)  
 3.1 [Variáveis utilizadas na análise](Variáveis-utilizadas-na-análise)
4. [Demonstração das informações obtidas](#demonstração-das-informações-obtidas)  
  4.1 [Os quinze CIDs mais frequentes](#os-quinze-cids-mais-frequentes)  
   4.2 [Os cinco CIDs mais frequentes por classe de hospital](#os-cinco-cids-mais-frequentes-por-classe-de-hospital)  
   4.3 [Frequência de status das consultorias por trimestre](#frequência-de-status-das-consultorias-por-trimestre)  
5. [Relatório completo](#relatório-completo)

## Sobre o projeto
### Dermatologia hospitalar, análise do perfil das consultorias dermatológicas
Os dados tratados e analisados neste relatório são referentes a pesquisa realizada no artigo **"Dermatologia hospitalar: análise do perfil das consultorias hospitalares em hospital terciário no sul do Brasil"**, dos autores MSc Iago Gonçalves Ferreira, MS Camila Saraiva Almeida, MS Lucas Abascal Bulcão, BSCE Diego Gonçalves Ferreira, PhD Renan Rangel Bonamigo, PhD Magda Blessmann Weber.

### Sobre o estudo
"As doenças de pele apresentam elevada prevalência no cenário hospitalar, representando importantes fatores de risco de morbimortalidade e de impacto nos custos hospitalares. Nessa perspectiva, a Dermatologia pode propiciar notáveis contribuições à assistência hospitalar, auxiliando as demais especialidades médicas no manejo clínico adequado das afecções dermatológicas. À vista disso, este estudo teve como objetivo analisar o perfil das requisições e consultorias realizadas pelo serviço de Dermatologia em complexo hospitalar terciário no sul do Brasil."

"[...] o estudo caracteriza-se como descritivo, observacional, e retrospectivo, sendo conduzido por meio de levantamento de dados e revisão de prontuários acerca das consultorias realizadas por serviço de Dermatologia, no período de agosto de 2018 a janeiro de 2020. As variáveis incluídas foram procedência das requisições, dados clínicos e hipótese diagnóstica das solicitações, perfil dos pacientes hospitalizados, diagnósticos dermatológicos finais, exames complementares, condutas terapêuticas e acompanhamento recomendado pelas equipes de consultoria dermatológica."

"Conclusão: Por meio deste estudo, demonstra-se a ampla gama de afecções dermatológicas prevalentes entre pacientes hospitalizados, enfatizando a importância da Dermatologia no diagnóstico e manejo clínico dessas condições, de forma a aperfeiçoar a assistência médica hospitalar. Além disso, destaca-se o benefício educacional, visto que a Dermatologia tem o potencial de contribuir com a formação de estudantes de medicina, médicos residentes de dermatologia e de outras especialidades."

## Tecnologias utilizadas

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

## Demonstração das informações obtidas

### Os quinze CIDs mais frequentes
|N°|CID|Nome|Frequência|(%)|
|:---:|:---:|---|:---:|:---:|
|1|L27|Dermatite devida a substâncias de uso interno|72|9.90|
|2|L30|Outras dermatites|48|6.60|
|3|B00|Infecções pelo vírus do herpes|38|5.23|
|4|L20|Dermatite atópica|34|4.68|
|5|B86|Escabiose (sarna)|28|3.85|
|6|L21|Dermatite seborréica|26|3.58|
|7|B35|Dermatofitose|26|3.58|
|8|L01|Impetigo|25|3.44|
|9|L40|Psoríase|23|3.16|
|10|L24|Dermatites de contato por irritantes|21|2.89|
|11|C44|Outras neoplasias malignas da pele|21|2.89|
|12|B37|Candidiase|19|2.61|
|13|L29|Prurido|15|2.06|
|14|L70|Acne|14|1.93|
|15|L85|Outras formas de espessamento epidérmico|12|1.65|

### Os cinco CIDs mais frequentes por classe de hospital
|N°|Classe Hospital|CID|Frequência|% Relativa|% Geral|
|:---:|:---:|:---:|:---:|:---:|:---:|
|1|Hospitais Clínicos Adulto|L27|37|9.11|5.09|
|2|Hospitais Clínicos Adulto|L30|33|8.13|4.54|
|3|Hospitais Clínicos Adulto|B00|25|6.16|3.44|
|4|Hospitais Clínicos Adulto|B35|20|4.93|2.75|
|5|Hospitais Clínicos Adulto|C44|16|3.94|2.20|
|1|Hospital Pediátrico|L20|32|15.76|4.40|
|2|Hospital Pediátrico|L27|23|11.33|3.16|
|3|Hospital Pediátrico|L01|18|8.87|2.48|
|4|Hospital Pediátrico|B86|17|8.37|2.34|
|5|Hospital Pediátrico|L70|10|4.93|1.38|
|1|Hospital Ginecológico|L27|12|10.17|1.65|
|2|Hospital Ginecológico|L30|9|7.63|1.24|
|3|Hospital Ginecológico|L21|7|5.93|0.96|
|4|Hospital Ginecológico|L24|5|4.24|0.69|
|5|Hospital Ginecológico|C44|5|4.24|0.69|

### Frequência de status das consultorias por trimestre
| Trimestre | Status da consultoria | Frequência |
|:----------------------:|:----------------------:|:-----------:|
| Ago. 2018 - Out. 2018 |                     1 |        104 |
|                       |                     3 |         32 |
|                       |                     2 |         27 |
| Nov. 2018 - Jan. 2019 |                     1 |        101 |
|                       |                     2 |         29 |
|                       |                     3 |         25 |
| Fev. 2019 - Abr. 2019 |                     1 |        107 |
|                       |                     2 |         52 |
|                       |                     3 |         29 |
| Mai. 2019 - Jul. 2019 |                     1 |        110 |
|                       |                     3 |         34 |
|                       |                     2 |         33 |
| Ago. 2019 - Out. 2019 |                     1 |        107 |
|                       |                     2 |         39 |
|                       |                     3 |         19 |
| Nov. 2019 - Jan. 2020 |                     1 |        111 |
|                       |                     2 |         36 |
|                       |                     3 |         24 |

## Relatório completo
O arquivo do relatório completo, com os códigos e todas as tabelas, está disponível neste repositório como "[Relatório de Análise](https://github.com/maisumdiego/Artigo-Dermato/blob/master/Relat%C3%B3rio%20de%20An%C3%A1lise.ipynb)".
