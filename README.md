# Análise de Churn  

Vou realizar uma análise de Churn de um banco da região sul do Brasil. Serão buscadas possíveis tendências, desvios, padrões de comportamento e outros insights que favoreçam ao negócio, tanto na tomada de medidas para redução dos cancelamentos quanto
no aumento da receita. Depois, será criado um modelo com o objetivo de prever o churn de clientes com base nos dados disponíveis. O projeto será conduzido seguindo o framework Crisp-DM. 

## Crisp-DM
O Crisp-DM é uma metodologia para projetos de mineração e análise de dados. O projeto terá a seguinte estrutura: 
* Compreensão do negócio
* Compreensão dos dados
* Preparação dos dados
* Modelagem
* Avaliação
* Implantação

## Tecnologias  
- Python (pandas, seaborn, statistics)  
- Jupyter Notebooks
- Git e Github

## Sumário
1. config
2. data
3. notebooks
4. src

### 1. config
Pasta destinada às configurações necessárias na utilização do modelo que será desenvolvido. Enquanto o modelo não estiver pronto, haverá um arquivo "config.txt" na pasta, para manter sua existência no repositório.
### 2. data
Pasta destinada aos principais arquivos de dados do projeto, desde os dados originais "raw data", até outras bases de dados criadas no processo de limpeza e tratamento ou previsões do modelo.
### 3. notebooks
Pasta destinada aos notebooks (Jupyter) com a característica de cada um dos processos, da análise do negócio, até a previsão do churn com a utilização do modelo.
### 4. src
Pasta destinada a códigos python que auxiliarão na criação do código do modelo de predição. Enquanto o modelo não estiver em produção, haverá apenas o arquivo "src.txt" na pasta, para manter sua existência no repositório.

## Compreensão do Negócio
Existem dois problemas de negócio neste projeto:
1. Por que os clientes cancelaram com nosso banco?
2. Como podemos prever os próximos clientes que poderão cancelar?

#### Por que os clientes cancelaram com nosso banco?
Essa será a primeira entrega realizada pelo projeto, onde saberei dizer as principais causas (ou combinação de causas/contextos) que levaram os clientes a cancelarem seus serviços, tornando-se parte da estatística de Churn. Nessa etapa será entregue uma Análise Descritiva (O que aconteceu?) e Diagnóstica (Por que aconteceu?), esclarendo as principais dúvidas do negócio a respeito do primeiro problema de negócio, fornecendo ao negócio, o conhecimento sobre as principais causas que levaram essa situação a ocorrer, e desta forma, planos de negócios poderão ser desenvolvidos a fim de evitar a repetição dessas situações.

#### Como podemos prever os próximos clientes que poderão cancelar?
A etapa anterior descreveu as possíveis causas que levaram os clientes a cancelar com o banco, porém, não há nenhuma predição ou dado estatístico a respeito do futuro. A segunda etapa trata da estatística do futuro, onde será criado um modelo de machine learning para a predição do Churn, assim, o banco poderá agir de forma proativa, buscando prever o desdobramentos das ações que podem ser tomadas, as estatísticas a favor ou contra o negócio, além de fornecer uma visão sobre os futuros cancelamentos. Com essa ferramenta entregue, ações concretas poderão ser tomadas, diminuindo o percentual de Churn de clientes e evitando a perda de receita da companhia.

## Compreensão dos dados
O objetivo principal desta etapa é obter uma compreensão profunda dos dados antes de aplicar modelos de machine learning ou realizar análises mais complexas.
A compreensão dos dados foi ralizada com método EDA (Exploratory Data Analysis), ou Análise Exploratória de Dados, uma etapa crucial na ciência de dados. Investiguei as principais características do conjunto de dados, com técnicas visuais e estatísticas para identificar padrões, tendências, valores atípicos e relacionamentos. 

Nessa primeira etapa, pude identificar diversos problemas como duplicidades, inconsistências, incompletudes e inconformidades nos dados. Na resolução desses problemas, utilizei conceitos (como conceitos gaussianos) aplicados  à estatística aplicada à dados.

## Preparação dos dados

## Modelagem

## Avaliação

## Implementação

# Andamento do projeto
A análise exploratória foi finalizada, a limpeza e tratamento dos dados está em fase final, e assim que essa fase for finalizada, o modelo de predição será construído.
