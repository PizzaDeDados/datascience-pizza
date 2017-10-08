# A

**Algoritmos** são conjuntos de passos finitos e organizados que, quando executados, realizam uma tarefa. Mais detalhes em [1](https://www.youtube.com/watch?v=8mei6uVttho), [2](https://www.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/v/what-are-algorithms).

**Análise Exploratria de Dados** é uma tradição estatística que provê ferramentas conceituais e computacionais para descobrir padres para o desenvolvimento e refinamento de hipteses (Behrens, 1997)

**Análise Não-Supervisionada:** é a capacidade do sistema em aprender padrões com dados de entrada, mesmo não sendo fornecido um retorno evidente. Tem como tarefa mais recorrente, o reconhecimento de grupos com os dados de entrada potencialmente úteis. (Russel e Norvig, 2013).

**Análise Supervisionada:** o objetivo é alcançado através da aprendizagem dos dados de entrada e seus respectivos resultados fornecidos por um supervisor. Em linhas gerais, o sistema observa a amostra de dados em pares de entrada e saída e aprende uma função que faz a rota entre estes pares (Alpaydin, 2010).

# B

**Bancos não-relacionais**: Comumente conhecido como NoSQL (Not Only SQL - Não Somente SQL, tradução literal) é um termo genérico para banco de dados não-relacionais, por exemplo, Document Store (MongoDB), Graph Databases (Neo4j), etc. Uma lista desses softwares pode ser encontrada em: http://nosql-database.org/ Recomenda-se mais estudos em: [NoSQL databases overview](https://www.thoughtworks.com/insights/blog/nosql-databases-overview) e [Gessert et. al. 2016](
https://pdfs.semanticscholar.org/af76/dfc90a8feaf91d5cb8057228897978c0eb77.pdf)

**Bancos de Dados Relacional**: O conceito de bancos de dados relacionais está na forma em que eles são implementados, que estabelece uma relação lógica entre os dados, para que a repetição de dados (redundância) seja a menor possível, economizando espaço em disco e aumentando a velocidade de consulta dos dados. 

Um banco de dados relacional possui como entidade central tabelas, onde as colunas armazenam os tipos de dados e as linhas um caso específico de dados, sendo chamada de tupla ou registro. Também é importante o conceito de chave, que identifica unicamente um registro.
O modelo relacional tem sua origem em 1970 quando um matemático da IBM chamado Edgar Frank Codd publicou um artigo onde foi definido formalmente o modelo relacional. Em 1985 o mesmo matemático publicou um artigo com as 13 regras que caracterizam um modelo de dados relacional.
[Portal da Educação - Bancos de Dados Relacionais]
(https://www.portaleducacao.com.br/conteudo/artigos/informatica/bancos-de-dados-relacionais/46246)


# C

**Clustering**: é a classificação não supervisionada de padrões (observações, itens de dados ou classes) em grupos (clusters). Intuitivamente, itens dentro de um cluster válido são mais simiilares uns aos outros do que itens de outros clusters (Jain et. al, 1999).

# D

**Desvio padrão**: É definido como a raiz quadrada positiva da variância (Bussab et al, 2010). Em probabilidade, o desvio padrão ou desvio padrão populacional é uma medida de dispersão em torno da média populacional de uma variável aleatória. Em estatística, desvio padrão amostral indica uma medida de dispersão dos dados em torno de média amostral [Wikipédia](https://pt.wikipedia.org/wiki/Desvio_padr%C3%A3o). 

# E

# F

# G

# H

# I

# J

# K
**K-means clustering**: É um algoritmo de agrupamento (clustering) que utiliza distância euclidiana para dividir/organizar/separar os N valores de uma amostra em K subconjuntos. K é definido previamente e o algoritmo faz o trabalho de calcular a distribuição da amostra nos subconjuntos mais próximos. Os pontos de onde mede-se a distância euclidiana, que são os centros dos subconjuntos (K0,K1,K2,Kn) são definidos aleatoriamente na primeira iteração e a cada iteração posterior são movimentados afim de distribuir a amostra em subconjuntos de tamanhos iguais.
![k-means](https://upload.wikimedia.org/wikipedia/commons/e/ea/K-means_convergence.gif)
 

# L

# M

**Matriz**: Dados dois números naturais m e n não-nulos, de­nomina-se matriz m por n (indica-se m x n) toda tabela formada por (m • n) elementos dispostos em m linhas e n colunas. As matrizes são indicadas por letras maiúsculas do alfabeto latino e representadas utilizando-se parênteses ou colchetes. Um elemento genérico de uma matriz A é simboliza­do por a.., em que i indica a linha e j a coluna a que pertence o elemento.

Numa matriz quadrada destacam-se
	•   diagonal principal: au e a22.
	•   diagonal secundária: a12 e a21.

Nesta matriz quadrada de ordem 3, tem-se
	•    diagonal principal: an, a22 e a33;
	•    diagonal secundária: a,3, a22 e a31.

Matrizes especiais
Existem matrizes que apresentam maior utilidade e possuem um nome diferenciado (especial).
	•    Matriz nula é toda matriz que tem todos os ele­mentos iguais a zero. Representa-se por Om x n.
	•    Matriz identidade de ordem n ou matriz uni­dade de ordem n é toda matriz quadrada no qual os elementos de sua diagonal principal são iguais a l e os demais, nulos.
	•    Matriz oposta de A é a matriz que se obtém de A, trocando-se o sinal de cada um de seus elementos. Representa-se por -A.
[https://www.resumoescolar.com.br/matematica/matriz-quadrada/]

# N

# O

**Outlier**: É uma instância em uma base de dados que pode ser apenas um ruído que se deseja eliminar em uma etapa de pré-processamento, ou ainda uma instância que possui um padrão nunca analisado antes, a qual possa representar um comportamento extraordinário e, portanto, passível de estudo e atenção especial. [Campos 2015](http://www.teses.usp.br/teses/disponiveis/55/55134/tde-04082015-084412/pt-br.php)

**Overfitting**: é um evento que ocorre quando o modelo se encaixa bem nos dados de treinamento, mas não se generaliza para dados não vistos ou testados. Isto é, não produz boas predições para dados desconhecidos. [Chaoji et. al. 2016](http://www.vldb.org/pvldb/vol9/p1597-chaoji.pdf)

# P

# R
**Regressão Linear**: conceitualmente, é uma técnica para analisar dados e encontrar uma formulação matemática linear e explícita que descreva de maneira aproximada o comportamento (a relação) dos dados. Na prática, é encontrar dois coeficientes (linear e angular) que minimizem o erro quadrático entre a a função linear resultante e os dados. [Referência](http://www.mit.edu/~6.s085/notes/lecture3.pdf)

**Random Forest**: método de aprendizado usado para classificação, regressão e outras aplicações, que se baseia na junção de outros algorítimos conhecidos
(logistic regression, linear regression,etc). Esse modelo é obtido pela construção de árvores de decisão, que conforme vão sendo construídas, decidem
quais algorítimos juntos levam ao melhor modelo. (Hastie et. al. 2008).

# S

# T

# U

**Underfitting**: é um evento que ocorre quando o seu modelo não representa de maneira eficaz o problema que foi proposto, ou seja, o modelo não se ajusta aos dados. Normalmente é possível identificar o underfitting por uma baixa variância e um alto bias. [Referência](https://chemicalstatistician.wordpress.com/2014/03/19/machine-learning-lesson-of-the-day-overfitting-and-underfitting/)

# V

**Variáveis Categóricas**: variáveis que possuem valores não-quantitativos. Os diferentes valores de uma variável categórica são normalmente chamados níveis (*levels*). Se os valores dos níveis forem nomes arbitrários a varivel é normal (por exemplo, cor do olho). Porém se existirem ao menos 3 níveis (notas de escola como A, B, C) a variável é ordinal.

**Vetor**: Na computação um vetor (arranjo unidimensional) é uma estrutura de dados que armazena um grupo de elementos, identificados por um índice e tipicamente com elementos do mesmo tipo.[1](https://techterms.com/definition/array),[2](https://en.wikipedia.org/wiki/Array_data_structure)

**Variáveis Discretas**: variável que possui valor quantitativo, ou seja, que pode ser contado. Em outras palavras, são variáveis com características mensuráveis que podem assumir apenas um número finito ou infinito contável de valores e, assim, somente fazem sentido valores inteiros. Geralmente são o resultado de contagens. Exemplos: número de filhos, número de bactérias por litro de leite. [http://leg.ufpr.br/~silvia/CE055/node8.html]

# X

# W

# Y

# Z


# Referências

Behrens, J. T.. Principles and procedures of Exploratory Data Analysis. American Psychological Association Inc. 1997. Vol.2, No.2, 131-160

CAMPOS, Guilherme Oliveira. Estudo, avaliação e comparação de técnicas de detecção não supervisionada de outliers. 2015. Dissertação (Mestrado em Ciências de Computação e Matemática Computacional) - Instituto de Ciências Matemáticas e de Computação, Universidade de São Paulo, São Carlos, 2015. doi:10.11606/D.55.2015.tde-04082015-084412. Acesso em: 2017-10-03.

Gessert, W. Wingerath, S. Friedrich, and N. Ritter. Nosql database systems:a survey and decision guidance.
Computer Science - Research and Development,32(3):353–365, Jul 2017

Jain, A.K.; Murty, M.N.; Flynn, P.J.; Data Clustering: A review. ACM Computing Surveys, Vol. 31, No. 3, 1999.

Vineet Chaoji, Rajeev Rastogi, and Gourav Roy. 2016. Machine learning in the real world. Proc. VLDB Endow. 9, 13 (September 2016), 1597-1600. DOI: http://dx.doi.org/10.14778/3007263.3007318

Alpaydin, Ethem. Introduction to Machine Learning. 2.ed. Massachusetts: MIT Press, 2010.

Russell, Stuart J.; Norvig, Peter. Inteligência Artificial. 3.ed. Rio de Janeiro: Elsevier, 2013.

Hastie, Trevor; Tibshirani, Robert; Friedman, Jerome. The Elements of Statistical Learning (2nd ed.). Springer. ISBN 0-387-95284-5, 2008.

Bussab, Wilton de O., and Pedro A. Morettin. Estatística básica. 8.ed. Página 41. Saraiva, 2010.

https://www.portaleducacao.com.br/conteudo/artigos/informatica/bancos-de-dados-relacionais/46246

http://leg.ufpr.br/~silvia/CE055/node8.html

https://www.resumoescolar.com.br/matematica/matriz-quadrada/