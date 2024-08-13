# IBM HR Analytics Employee Attrition and Performance

Este conjunto de dados é bem conhecido no mundo de People Analytics.
Quando a IBM cria um conjunto de dados que permite praticar modelagem de atrito, você deve prestar atenção.

## Descrição do Conjunto de Dados

O conjunto de dados possui 1470 linhas e 35 colunas.

Descubra os fatores que levam à rotatividade de funcionários e explore questões importantes, como:

- "Mostre-me uma análise da distância de casa por função no trabalho e rotatividade."
- "Compare a renda média mensal por nível de educação e rotatividade."

Este é um conjunto de dados fictício criado por cientistas de dados da IBM.


### Variáveis

**Education (Educação)**
- 1: 'Below College' (Abaixo de Faculdade)
- 2: 'College' (Faculdade)
- 3: 'Bachelor' (Bacharelado)
- 4: 'Master' (Mestrado)
- 5: 'Doctor' (Doutorado)

**EnvironmentSatisfaction (Satisfação com o Ambiente)**
- 1: 'Low' (Baixa)
- 2: 'Medium' (Média)
- 3: 'High' (Alta)
- 4: 'Very High' (Muito Alta)

**JobInvolvement (Envolvimento no Trabalho)**
- 1: 'Low' (Baixo)
- 2: 'Medium' (Médio)
- 3: 'High' (Alto)
- 4: 'Very High' (Muito Alto)

**JobSatisfaction (Satisfação no Trabalho)**
- 1: 'Low' (Baixa)
- 2: 'Medium' (Média)
- 3: 'High' (Alta)
- 4: 'Very High' (Muito Alta)

**PerformanceRating (Avaliação de Desempenho)**
- 1: 'Low' (Baixa)
- 2: 'Good' (Boa)
- 3: 'Excellent' (Excelente)
- 4: 'Outstanding' (Excepcional)

**RelationshipSatisfaction (Satisfação no Relacionamento)**
- 1: 'Low' (Baixa)
- 2: 'Medium' (Média)
- 3: 'High' (Alta)
- 4: 'Very High' (Muito Alta)

**WorkLifeBalance (Equilíbrio entre Vida Profissional e Pessoal)**
- 1: 'Bad' (Ruim)
- 2: 'Good' (Bom)
- 3: 'Better' (Melhor)
- 4: 'Best' (Melhor de Todos)


Essas variáveis fornecem uma visão geral bastante completa que inclui os dados de um sistema de informações de RH médio, combinados com uma pesquisa completa de engajamento. Portanto, o conjunto de dados é excelente para prever a rotatividade ou simplesmente encontrar diferenças entre o grupo que permaneceu e o que saiu.

## Desafio

Este conjunto de dados abre várias possibilidades de análise. Uma das mais interessantes pode ser encontrar preditores usando árvores de decisão ou regressão logística. **Nota:** Confira a apresentação de Pasha Robert sobre [por que você não deve usar regressão logística para prever a rotatividade](https://pt.slideshare.net/slideshow/1345-keynote-roberts/76038388) antes de seguir essa abordagem!

Alternativamente, você pode usar testes mais simples, como ANOVA de uma via ou testes qui-quadrado, para encontrar diferenças entre os grupos que saíram e os que permaneceram, em fatores como satisfação no trabalho e se eles tinham ou não opções de ações.

## Download

Originalmente, o conjunto de dados foi publicado no site da IBM, mas foi removido desde então. No entanto, ele ainda está disponível no [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset). Observe que, no arquivo original da IBM, havia uma segunda planilha chamada "Data Definitions". No Kaggle, essas definições de dados foram incluídas na descrição do arquivo.


Fonte: [7 HR Data Sets for People Analytics](https://www.aihr.com/blog/hr-data-sets-people-analytics)
