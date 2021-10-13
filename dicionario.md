# A

## Álgebra Linear

A álgebra linear é um ramo da matemática, mas a verdade é que a álgebra linear é a matemática dos dados. Matrizes e vetores são a linguagem dos dados.

A álgebra linear trata de combinações lineares. Isto é, usando aritmética em colunas de números chamadas vetores e arranjos de números chamados matrizes, para criar novas colunas e arranjos de números. Álgebra linear é o estudo de linhas e planos, espaços vetoriais e mapeamentos necessários para transformações lineares. [1](https://machinelearningmastery.com/gentle-introduction-linear-algebra/).

Álgebra linear é o estudo de conjuntos lineares de equações e suas propriedades de transformação. A álgebra linear permite a análise de rotações no espaço, ajuste de mínimos quadrados , solução de equações diferenciais acopladas, determinação de um círculo passando por três pontos dados, assim como muitos outros problemas em matemática, física e engenharia. [2](https://mathworld.wolfram.com/LinearAlgebra.html).

## Algoritmos

São conjuntos de passos finitos e organizados que, quando executados, realizam uma tarefa. [1](https://www.youtube.com/watch?v=8mei6uVttho), [2](https://www.khanacademy.org/computing/computer-science/algorithms/intro-to-algorithms/v/what-are-algorithms).

## Análise Exploratória de Dados

É uma tradição estatística que provê ferramentas conceituais e computacionais para descobrir padrões para o desenvolvimento e refinamento de hipóteses. 1.(Behrens, 1997)

## Análise Não-Supervisionada

É a capacidade do sistema em aprender padrões com dados de entrada, mesmo não sendo fornecido um retorno evidente. Tem como tarefa mais recorrente, o reconhecimento de grupos com os dados de entrada potencialmente úteis. 1.(Russel e Norvig, 2013).

## Análise Supervisionada

O objetivo é alcançado através da aprendizagem dos dados de entrada e seus respectivos resultados fornecidos por um supervisor. Em linhas gerais, o sistema observa a amostra de dados em pares de entrada e saída e aprende uma função que faz a rota entre estes pares. 1.(Alpaydin, 2010).

## Aprendizado por Reforço

O aprendizado por reforço é uma área do aprendizado de máquina que lida com a maneira como os agentes de software devem executar ações em um ambiente de modo a maximizar alguma noção de recompensa cumulativa [1](https://en.wikipedia.org/wiki/Reinforcement_learning). É estudado em estatística, psicologia, neurociência e ciência da computação que está diretamente ligado a aprendizado de máquina e inteligência artificial. É um método de programação de agentes que devem aprender a se comportar em um ambiente dinâmico através de interações de “tentativa e erro”, conhecidas também como premiações e punições, sem a necessidade de especificar como uma tarefa deve ser realizada. A abordagem que é utilizada nesse trabalho é feita usando técnicas de estatísticas e métodos de programação dinâmica, buscando estimar qual a vantagem em se tomar determinadas ações em diferentes estados do ambiente dado um objetivo. [2](https://www.maxwell.vrac.puc-rio.br/19637/19637_4.PDF), [3](https://en.wikipedia.org/wiki/Reinforcement_learning).

## Árvore de Decisão (_Decision Tree_)
Uma árvore de decisão é uma técnica de aprendizado de máquina que é representada por uma árvore que recebe como entrada um vetor de características e retorna uma decisão baseada nesses valores. A decisão  fornecida pelo algoritmo é obtido através da execução de uma sequência de testes. Cada nó interno na árvore corresponde a um teste do valor de um dos atributos do vetor de entrada, e os ramos do nó são rotulados com os valores possíveis do atributo. Cada nó da folha na árvore especifica um valor a ser retornado pela Árvore, ou seja, a decisão final (Russel e Norvig, 2013).

Na imagem abaixo temos o exemplo da representação de uma ávore de decisão para decidir se um cliente deve aguardar por uma mesa no restaurante.

![decision_tree](https://image.ibb.co/cMaWgz/Screenshot_from_2018_10_06_01_10_53.png)

Abaixo temos algumas possíveis entradas para a árvore de decisão, representada acima, e seus respectivos resultados.

![decision_tree_inputs_outputs](https://image.ibb.co/koz2oe/Screenshot_from_2018_10_06_01_15_57.png)

## AUC (Area Under the Curve)

O índice AUC é um valor único que agrega os limiares da curva [ROC](#roc-receiver-operating-characteristics), definindo a área abaixo da curva.[1](https://medium.com/@eam.avelar/o-que-%C3%A9-auc-e-roc-nos-modelos-de-machine-learning-2e2c4112033d)

- Um valor próximo de 1 quer dizer que as distribuições de verdadeiros positivos e verdadeiros negativos quase não se sobrepõe, e o modelo consegue separar bem entre as duas classes;
- Um valor próximo de 0.5 quer dizer que as distribuições de verdadeiros positivos e verdadeiros negativos se sobrepõe quase totalmente e que o modelo não consegue diferenciar entre as classes;
- Um valor próximo de 0 quer dizer que as distribuições de verdadeiros positivos e verdadeiros negativos estão totalmente inversas e que o modelo prediz instâncias negativas como positivas e vice-versa.

# B

## Banco de Dados Não-Relacional

Comumente conhecido como NoSQL (Not Only SQL - Não Somente SQL, tradução literal) é um termo genérico para banco de dados não-relacionais, por exemplo, Document Store (MongoDB), Graph Databases (Neo4j), etc. Uma lista desses softwares pode ser encontrada [neste site](http://nosql-database.org/). Recomenda-se mais estudos em: 1. [NoSQL databases overview](https://www.thoughtworks.com/insights/blog/nosql-databases-overview) e 2. [Gessert et. al. 2016](https://pdfs.semanticscholar.org/af76/dfc90a8feaf91d5cb8057228897978c0eb77.pdf)

## Banco de Dados Relacional

O conceito de bancos de dados relacionais está na forma em que eles são implementados, que estabelece uma relação lógica entre os dados, para que a repetição de dados (redundância) seja a menor possível, economizando espaço em disco e aumentando a velocidade de consulta dos dados.

Um banco de dados relacional possui como entidade central tabelas, onde as colunas armazenam os tipos de dados e as linhas um caso específico de dados, sendo chamada de tupla ou registro. Também é importante o conceito de chave, que identifica unicamente um registro.

O modelo relacional tem sua origem em 1970 quando um matemático da IBM chamado Edgar Frank Codd publicou um artigo onde foi definido formalmente o modelo relacional. Em 1985 o mesmo matemático publicou um artigo com as 13 regras que caracterizam um modelo de dados relacional.
[1](https://www.portaleducacao.com.br/conteudo/artigos/informatica/bancos-de-dados-relacionais/46246)

## Bias

Ver [Viés](https://github.com/PizzaDeDados/datascience-pizza/blob/master/dicionario.md#vi%C3%A9s-bias).

## Big Data
É um termo que descreve o grande volume de dados - estruturados e não estruturados - que sobrecarrega as empresas diariamente. Pode ser usado para obter insights que levam a decisões melhores e ações estratégicas de negócio. Normalmente tem a definição separada em 3 V's:

  - Volume: A quantidade de dado importa. Com big data você deve que processar grandes quantidades de dados para obter resultados concretos, o tamanho exato varia de empresa para empresa, podendo ser terabytes ou zetabytes.
  
  - Velocidade: Todos os dados devem ser transmitidos em grandes velocidades e tratados em um tempo baixo. Normalmente a velocidade está diretamente ligada a memória e escrita em disco.
  
  - Variedade: Os dados são gerados em inúmeros formatos, desde dados estruturados (bancos de dados normais) a não estruturados (textos, e-mails, som, vídeo, fotos, tweets e etc...)

Também são considerados dois V's adicionais:
  - Veracidade: É a garantia da qualidade do dado, ou seja, garantir que as informações sejam verdadeiras para a análise.
  
  - Valor: Tudo o que for feito com o big data tem que gerar um valor no final, não adianta ler uma quantidade massiva de dados sem gerar algum valor no fim. [1](https://www.oracle.com/big-data/guide/what-is-big-data.html) [2](https://www.bbva.com/en/five-vs-big-data/) [3](https://canaltech.com.br/big-data/Big-Data-os-cinco-Vs-que-todo-mundo-deveria-saber/)

## Box plot
Um gráfico que tem a finalidade de mostrar a distribuição de dados numéricos através de quartis. A caixa ( que justifica o nome box) mostra o Intervalo Interquartil (IC). A linha que passa por dentro da caixa indica a mediana, enquanto a superior indica o primeiro quartil (Q1) e a inferior mostra o 3o quartil (Q3). Acima da caixa, é mostrado o limite superior, calculado por 1,5 * Q3, e o limite inferior, cuja fórmula é 1,5 * Q1. [1](https://en.wikipedia.org/wiki/Box_plot)

O box plot ainda traz os valores que estão acima do limite superior ou abaixo do limite inferior (os outliers), geralmente exibidos como pontos em formato de astericos.

A maior vantagem em relação ao histograma é que este gráfico ocupa menos espaço e pode ser útil para comparar a distribuição de vários conjuntos de dados. [1](https://en.wikipedia.org/wiki/Box_plot)

![boxplot](http://www.portalaction.com.br/sites/default/files/resize/EstatisticaBasica/figuras/boxplot1-700x354.png "Box plot")

# C

## Classificação (Aprendizado de Máquina)

É o tipo de tarefa de aprendizado de máquina em que as entradas são mapeadas em saídas baseadas nos pares examplos de entrada-saída. O desafio enfrentado pelo algoritmo classificador é ajustar uma função que possa separar os exemplos de entrada de forma a maximizar a quantidade de saídas corretas [Supervised learning](https://en.wikipedia.org/wiki/Supervised_learning). Uma abstração seria ter como entrada um conjunto de informações a respeito do tecido da mama extraídos da mamografia. A saída neste caso poderia ser tecido normal, tumor maligno ou tumor benigno (podem existir mais categorias). O algoritmo de classificação deve inferir a cerca dos dados de forma a reconhecer o padrão de dados de entrada de forma a determinar a saída que mais se aproxime do parão identificado.

## Clustering

Ver [Clusterização](https://github.com/PizzaDeDados/datascience-pizza/blob/master/dicionario.md#clusteriza%C3%A7%C3%A3o-clustering).

## Clusterização (_Clustering_)

É a classificação não supervisionada de padrões (observações, itens de dados ou classes) em grupos (clusters). Intuitivamente, itens dentro de um cluster válido são mais similares uns aos outros do que itens de outros clusters (Jain et. al, 1999).

## Coeficiente

É o fator multiplicativo de um termo em uma expressão, sendo geralmente um número, e que não se confunde com as variáveis da expressão.[1](https://pt.wikipedia.org/wiki/Coeficiente)

## Coeficiente de Determinação

O coeficiente de determinação (R2) é uma estimativa da qualidade de um modelo de regressão. Usualmente R2 é interpretado como o quanto da variância de uma variável independente pode ser capturada (dado o modelo) a partir das variáveis dependentes [1](http://stattrek.com/statistics/dictionary.aspx?definition=coefficient_of_determination). Para modelos lineares, R2 é usualmente definido como sendo o quadrado do coeficiente de correlação da amostra, sendo, neste caso, uma medida de o quanto a variável independente pode ser explicada a partir de uma combinação linear das variáveis dependentes [2](https://en.wikipedia.org/wiki/Coefficient_of_determination).

## Conda

É um gerenciador de pacotes, dependências e ambientes para qualquer idioma - Python, R, Ruby, Lua, Scala, Java, JavaScript, C / C ++, FORTRAN. [ref](https://conda.io/docs/)

## Conda-Forge

É uma organização no github contendo repositórios de receitas conda. Graças a alguns incríveis provedores de integração contínua (AppVeyor, CircleCI e TravisCI), cada repositório, também conhecido como feedstock, constrói automaticamente sua própria receita de forma limpa e repetitiva no Windows, Linux e OSX. [1](https://conda-forge.org/)

## Correlação

Correlação é a medida estatística que descreve a associação entre variáveis randômicas. Frequentemente,  correlação é o primeiro passo para entender relacionamentos e consequentemente construir melhores modelos estatísticos. [1](https://www.datascience.com/blog/introduction-to-correlation-learn-data-science-tutorials)
Para interpretar o coeficiente é preciso saber que 1 significa que a correlação entre as variáveis é perfeita positiva e -1 significa que é perfeita negativa. Se o coeficiente for igual a 0 significa que as variáveis não dependem uma da outra.[1](https://www.significados.com.br/correlacao/)

## Covariância

Em probabilidade, a covariância de duas variáveis X e Y é uma medida da variabilidade conjunta destas variáveis aleatórias. Se as variáveis tem covariância positiva tendem a mostrar um comportamento semelhante, ou seja, os menores (maiores) valores da variável X corresponde aos menores (maiores) da variável Y . Se a covariância é negativa então as variáveis tendem a mostrar um comportamento oposto, ou seja, os menores (maiores) valores da variável X corresponde aos maiores (menores) da variável Y.
Assim, podemos ver que o sinal da covariância mostra a tendência na relação linear entre as variáveis. [1](http://www.portalaction.com.br/probabilidades/42-covariancia-e-coeficiente-de-correlacao).

## Cross-validation

Ver [Validação Cruzada](https://github.com/PizzaDeDados/datascience-pizza/blob/master/dicionario.md#valida%C3%A7%C3%A3o-cruzada-cross-validation).

## Curva de Gauss

A Curva de Gauss, também conhecida como curva de sino, é a representação de uma [distribuição normal](#distribuição-normal), sendo a distribuição mais referenciada quando se fala em distribuições normais. Por isso, muitas vezes existe a confusão entre qual a diferença entre a gaussiana e a [normal](#curva-normal).[1](https://www.quora.com/What-is-the-difference-between-Gaussian-and-normal-distribution#:~:text=A%20gaussian%20and%20normal%20distribution%20is%20the%20same%20in%20statistics%20theory.&text=The%20normal%20distribution%20contains%20the,and%20corresponding%20the%20PDF%20values.)

Em termos simples, a gaussiana não sofre padronização Z e pode ser denotada pela equação abaixo:

![Equação da curva de densidade de uma gaussiana](https://wikimedia.org/api/rest_v1/media/math/render/svg/362834b765239b64cf7719a3a3a04e172c883e3d)

## Curva Normal

A Curva Normal Padrão é o caso mais simples de uma [distribuição normal](#distribuição-normal) e também pode ser vista na literatura com o nome de curva normal centrada e reduzida. Ela é o caso específico onde a variável aleatória (X) é transformada em uma variável padronizada (Z) que segue a distribuição com valores de média (mu) = 0 e desvio padrão (sigma) = 1.[1](http://leg.ufpr.br/~shimakur/CE701/node36.html)

Mais detalhes sobre as funções de densidade, distribuição e característica podem ser vistas [aqui](https://pt.wikipedia.org/wiki/Distribui%C3%A7%C3%A3o_normal#Distribui%C3%A7%C3%A3o_normal_padr%C3%A3o).

# D

## Data Storytelling

O processo de tradução de dados em termos leigos para influenciar uma decisão ou ação de negócios. [1](http://farolbi.com.br/data-storytelling-conte-uma-historia-com-os-dados/)
Para que o Data Storytelling seja bem-sucedido, a pessoa deve ter boas habilidades em comunicação, para que seja possível a transferência de informações sobre o que foi feito, como foi feito e por quê foi feito, apresentando motivos bem estruturados e se possível, figuras ou mapas que demonstrem toda a informação.[1] (https://paulovasconcellos.com.br/o-que-%C3%A9-data-storytelling-ac5a924dcdaf)

## Dataset

São conjuntos de dados tabulados, onde para cada individuo são denotadas diversas características. Cada coluna corresponde a uma varíavel, e cada linha é o conjunto de caracteristicas do individuo. Os valores(itens) dessa tabela são chamados dados. [wiki](https://pt.wikipedia.org/wiki/Conjunto_de_dados)

## Decision Tree
ver [Árvore de Decisão](https://github.com/PizzaDeDados/datascience-pizza/blob/master/dicionario.md#%C3%A1rvore-de-decis%C3%A3o-decision-tree).

## Desvio padrão

É definido como a raiz quadrada positiva da variância (Bussab et al, 2010). Em probabilidade, o desvio padrão ou desvio padrão populacional é uma medida de dispersão em torno da média populacional de uma variável aleatória. Em estatística, desvio padrão amostral indica uma medida de dispersão dos dados em torno de média amostral [1](https://pt.wikipedia.org/wiki/Desvio_padr%C3%A3o).

## Distribuição Normal

A distribuição normal é uma das distribuições de probabilidade mais utilizadas para modelar fenômenos naturais devido ao fato de representar o limite de um grande número de distribuições probabilísticas demonstrado pelo [Teorema do Limite Central](#teorema-do-limite-central).

Em termos simples, a normal emula o comportamento agregado de experiências aleatórias e semelhantes dada uma amostra simples de tamanho grande.[1](https://web.archive.org/web/20170822212659/http://www.fau.usp.br/cursos/graduacao/arq_urbanismo/disciplinas/aut0516/Apostila_2_-_DistribuiCAo_Amostral.pdf) É uma distribuição simétrica em torno da média o que implica que a média, a mediana e a moda são todas coincidentes.[2](http://leg.ufpr.br/~silvia/CE055/node44.html)

Sua curva geral pode ser vista em [Curva de Gauss](#curva-de-gauss), e sua curva padronizada pode ser vista na definição de [Curva Normal](#curva-normal).

## Dropout

Dropout é uma técnica de regularização de redes neurais em que, a cada iteração do treinamento, uma seleção aleatória de neurônios é desligada. A quantidade de neurônios desligados é controlada por um hiper-parâmetro, sendo que, quanto mais neurônios são desligados, mais forte é a regularização. É importante que o dropout seja aplicado apenas durante o treinamento e nunca para fazer predições. (Srivastava, 2014)

# E

## Embeddings

Diga-me com quem andas e eu te direi quem és. Esse provérbio resume bem o conceito por trás dessa abordagem de aprendizado que consiste na representação vetorial da relação entre entidades de um determinado conjunto dentro de um espaço multi-dimensional.

Um dos algoritmos mais famosos a aplicar esse conceito é o word2vec [1](https://en.wikipedia.org/wiki/Word2vec) que é capaz de abstrair, através desses vetores de relações, propriedades semânticas e sintáticas das palavras. Isto pode ser exemplificado através da operação Rei - Homem + Mulher = Rainha, que demonstra que o vetor que representa o conceito de feminino pode ser adicionado a uma palavra masculina para obter sua contraparte feminina como resultado.

## Engenharia de Features

Refere-se ao processo de seleção e transformação de variáveis envolvidos na criação de modelos preditivos usando machine learning ou modelagem estatística. O processo envolve a combinação de análise de dados, prática/experiência e julgamento. Pode às vezes se referir ao pré-processamento, mas esse termo pode ter um significado mais generalista. [1](https://www.displayr.com/what-is-feature-engineering/)

## Ensemble Learning

Método de aprendizado que consiste em utilizar a predição de vários algoritmos de Aprendizado de Máquina e combinar seus resultados de modo à obter uma predição melhorada. Um exemplo conhecido é o Random Forest, que utiliza diversas Decision Trees para fazer sua predição. [1](https://en.wikipedia.org/wiki/Ensemble_learning)

## Entropia Cruzada

Método usado para calcular a diferença entre duas distribuições probabilísticas e por isso é muito usado em problemas de classificação, pois se quer alcançar uma aproximação da distribuição das classes do referido problema, é dado por: ![ce1](https://latex.codecogs.com/svg.latex?H%28p%2C%20q%29%20%3D%20-%20%5Csum_%7Bx%7D%5E%7B%20%7D%20p%28x%29%20%5Clog%20%28q%28x%29%29),
onde ![ce2](https://latex.codecogs.com/svg.latex?p(x)) é a probabilidade do exemplo ser da classe _x_ (1 na classe correspondente e 0 nas restantes) e ![ec2](https://latex.codecogs.com/svg.latex?q(x)) é a probabilidade obtida. Faz-se o somatório do produto para cada classe _x_ e no final teremos o erro entre a distribuição esperada e a obtida. [1](https://ml-cheatsheet.readthedocs.io/en/latest/loss_functions.html) [2](https://en.wikipedia.org/wiki/Cross-entropy_method)

## Erro quadrático médio

O erro quadrático médio ou desvio quadrático médio é uma medida do erro cometido ao estimar um observável [MSE](https://en.wikipedia.org/wiki/Mean_squared_error). Sejam ![eq1](http://www.sciweavers.org/tex2img.php?eq=%28x_i%2C%20%5Chat%7Bx%7D_i%29&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0) o i-ésimo valor observado e o i-ésimo valor estimado, respectivamente, em um conjunto de N observações,
isto é, i = 1, 2, ..., N. O erro quadrático médio desse experimento é dado por ![eq2](http://www.sciweavers.org/tex2img.php?eq=%5Cfrac%7B1%7D%7BN%7D%20%5Csum_%7Bi%3D1%7D%5E%7BN%7D%20%28%5Chat%7Bx%7D_i%20-%20x_i%29%5E2&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0).

# F

# G

# H

## Hadoop

O Apache Hadoop é uma coleção de utilitários de software de código aberto que facilitam o uso de uma rede de vários computadores para resolver problemas envolvendo grandes quantidades de dados e cálculos. Ele fornece uma estrutura de software para armazenamento distribuído e processamento de big data usando o modelo de programação MapReduce. [1](https://en.wikipedia.org/wiki/Apache_Hadoop)

## Hipótese

Trata-se de supostas respostas para um problema em questão. É importante que as proposições possam ser testadas de maneira empírica, a fim de determinar sua validade.
[1](http://www2.anhembi.br/html/ead01/metodologia_pesq_cientifica_80/lu06/lo2/index.htm)

## Hipótese nula

Hipótese inicial a ser testada, que é colocada em teste de hipótese. Normalmente baseada em análises anteriores ou conhecimentos especializados em geral indica uma igualdade a ser contestada.
[1](https://support.minitab.com/pt-br/minitab/18/help-and-how-to/statistics/basic-statistics/supporting-topics/basics/null-and-alternative-hypotheses/)
[2](http://www.lee.dante.br/pesquisa/amostragem/glossario.html#hip-nul)

## Histograma

Um gráfico composto por retângulos justapostos em que a base de cada um deles corresponde ao intervalo de classe e a sua área à respectiva frequência. Um histograma é utilizado para representar a distribuição de frequências de variáveis *contínuas*. Os valores observáveis da variável são divididos em classes (faixas de valores) e, então, conta-se a frequência de ocorrência dos valores em cada classe. O histograma é o gráfico que relaciona as classes no eixo X e valores proporcionais à frequência no eixo Y.

![histograma](https://upload.wikimedia.org/wikipedia/commons/d/dd/Histograma_wiki1.png "Histograma da coleta de HDL de um grupo de 18 pacientes. Seis classes definidas em intervalos de 5 mg/dL.")

# I

## Intervalo de Confiança

Diferentes amostras podem ser retiradas de uma mesma população, e amostras diferentes podem resultar em estimativas diferentes. Isto é, um estimador é uma variável aleatória, podendo assumir valores diferentes para cada amostra. Então, ao invés de estimar o parâmetro de interesse por um único valor, é muito mais informativo estimá-lo por um intervalo de valores que considere a variação presente na amostra e que contenha o seu verdadeiro valor com determinada confiança.[1](http://leg.ufpr.br/~silvia/CE055/node56.html)

# J

## Julia (Linguagem)

Julia é uma linguagem de propósito geral desenhada para alta-performance com características como a tipagem dinâmica, polimorfismo, e Entrada e saída asíncronos de forma nativa, permitindo computação paralela e distribuída. Uma das principais características da linguagem é a utilização de multimétodos como um paradigma. [1](https://julialang.org/)

## Jupyter

O [Project Jupyter](http://jupyter.org/) é um projeto de código aberto, sem fins lucrativos, nascido do [Projeto IPython](https://ipython.org/) em 2014, que evoluiu para dar suporte à ciência de dados interativa e computação científica em todas as linguagens de programação. Jupyter é, e sempre será, 100% de software de código aberto, livre para todos usarem e liberados sob os termos liberais da [licença BSD modificada](https://opensource.org/licenses/BSD-3-Clause).

# K

## K-means

É um algoritmo de agrupamento (clustering) que utiliza distância euclidiana para dividir/organizar/separar os N valores de uma amostra em K subconjuntos. K é definido previamente e o algoritmo faz o trabalho de calcular a distribuição da amostra nos subconjuntos mais próximos. Os pontos de onde mede-se a distância euclidiana, que são os centros dos subconjuntos (K0,K1,K2,Kn) são definidos aleatoriamente na primeira iteração e a cada iteração posterior são movimentados afim de distribuir a amostra em subconjuntos de tamanhos iguais.
![k-means](https://upload.wikimedia.org/wikipedia/commons/e/ea/K-means_convergence.gif)

## Keras

Keras é uma API de redes neurais de alto nível, escrita em Python e capaz de rodar em cima de TensorFlow, Microsoft Cognitive Toolkit(CNTK), R, Theano, ou PlaidML. Foi desenvolvida com o foco em possibilitar rápida experimentação. De acordo com sua documentação, é uma biblioteca de deep learning para quem precisa de algo fácil e rápido, que suporta tanto redes neurais convolucionais quanto redes neurais recorrentes (como também combinações das duas) e funciona perfeitamente em CPU e GPU. [1](https://keras.io/) [2](https://pt.wikipedia.org/wiki/Keras)

# L

# M

## Matriz

Matriz é uma estrutura de dados utilizada para armazenar dados em mais de uma dimensão. Por exemplo, com duas dimensões, temos linhas e colunas acessadas com dois índices.
É possível criar matrizes de n dimensões, que serão acessadas com n índices. Dados dois números naturais m e n não-nulos, denomina-se matriz m por n (indica-se m x n) toda tabela formada por (m • n) elementos dispostos em m linhas e n colunas. As matrizes são indicadas por letras maiúsculas do alfabeto latino e representadas utilizando-se parênteses ou colchetes. Um elemento genérico de uma matriz A é simbolizado por `aij`, em que `i` indica a linha e `j` a coluna a que pertence o elemento.

Numa matriz quadrada de ordem 2 destacam-se:
* diagonal principal: `a11` e `a22`;
* diagonal secundária: `a12` e `a21`.

Numa matriz quadrada de ordem 3 destacam-se:
* diagonal principal: `a11`, `a22` e `a33`;
* diagonal secundária: `a13`, `a22` e `a31`.

Em suma, para matrizes quadradas de ordem `n`:
* diagonal principal: elementos `aij`, com `i = j`;
* diagonal secundária: elementos `aij`, com `i+j = n+1`

Matrizes especiais:

Existem matrizes que apresentam maior utilidade e possuem um nome diferenciado (especial):
* Matriz nula é toda matriz que tem todos os elementos iguais a zero. Representa-se por Om x n.
* Matriz identidade de ordem n ou matriz unidade de ordem n é toda matriz quadrada no qual os elementos de sua diagonal principal são iguais a 1 e os demais, nulos.
* Matriz oposta de A é a matriz que se obtém de A, trocando-se o sinal de cada um de seus elementos. Representa-se por -A.
[1](https://www.resumoescolar.com.br/matematica/matriz-quadrada/) [2](https://en.wikipedia.org/wiki/Matrix_representation)

## Matriz de Confusão

Uma matriz de confusão é uma tabela que te permite visualizar o desempenho de um modelo de classificação por meio de uma comparação dos valores de classificação prevista contra os valores da classificação atual.[1](https://medium.com/data-hackers/entendendo-o-que-%C3%A9-matriz-de-confus%C3%A3o-com-python-114e683ec509) Um exemplo de matrix de confusão de um modelo que classifica grávidas e não-grávidas pode ser visto abaixo:

![Matriz de confusão de um modelo que classifica grávidas e não-grávidas](https://miro.medium.com/max/808/1*DYOERtaPlawq2-LDmFK5EA.png)

Com os valores positivos e negativos preditos, e os valores positivos e negativos reais, é possível tirar métricas de avaliação do modelo como [precisão](#precisão) [2](https://en.wikipedia.org/wiki/Precision_and_recall#Precision), [revocação](revocação) [3](https://en.wikipedia.org/wiki/Precision_and_recall#Recall), especificidade [4](https://en.wikipedia.org/wiki/Sensitivity_and_specificity#Specificity), sensitividade [5](https://en.wikipedia.org/wiki/Sensitivity_and_specificity#Sensitivity), acurácia [6](https://en.wikipedia.org/wiki/Accuracy_and_precision), F-score [7](https://en.wikipedia.org/wiki/F-score), dentre outros.

## Média Móvel

É uma técnica utilizada para analisar dados que cria várias médias de vários intervalos de dados dentro do dataset. A média móvel é calculada da seguinte maneira: dado um tamanho k de subset, o primeiro ponto da média móvel é obtido a partir da média dos k primeiros elementos. Depois, essa "janela" é movida para frente, excluindo o primeiro valor e calculando a média com o próximo dado. Essa é uma técnica amplamente usada para suavizar curvas e descobrir tendências dentro dos dados, muito usada no setor financeiro. [1](https://en.wikipedia.org/wiki/Moving_average)

## Mediana

A mediana de um grupo de itens é o valor do item central quando todos os itens do grupo estão ordenados de forma crescente ou decrescente. Para um grupo com 3 valores, a mediana é o valor de posição 2, quando os valores estão ordenados. Exemplo: No grupo [5, 10, 15], a mediana é o 10. Já em grupos que a quantidade de valores é par, a mediana é a média dos valores centrais. Exemplo: No grupo [5, 10, 15, 20], a mediana é a média entre 10 e 15 (os valores centrais), no caso, 12,5. (Kazmier, Leonard. 2007).

## Modelagem Preditiva

É a prática de extrair informações de uma massa de dados, a fim de determinar padrões e resultados futuros. Utiliza-se de várias técnicas como mineração de dados, modelagem estatística e machine learning para dar suporte na tomada de decisão. [1](https://www.ibm.com/developerworks/br/industry/library/ba-predictive-analytics1/index.html)

## Modelo Discriminativo

Ao contrário da modelagem generativa, que estuda a partir da probabilidade conjunta , a modelagem discriminativa estuda o ou os mapas diretos a dada variável não observada (alvo) de uma etiqueta de classe dependente das variáveis observados (amostras de treino). No campo prático de reconhecimento de objectos, é provável que seja um vetor (isto é, materias-pixels, características extraídas a partir da imagem ou mais). Dentro de uma estrutura probabilística, isto é feito por modelagem da distribuição de probabilidade condicional, que pode ser usado para prever a partir. Observe que ainda há distinção entre o modelo condicional e modelo discriminativo, embora na maioria das vezes, eles são apenas categorizados como modelo discriminativo. 

<p align="center"><strong>P (x, y)P (Y | x)XyX P (Y | x)yX</strong></p>

E são uma classe de modelos usados especialmente em Machine Learning para modelar a dependência de uma variável y com uma variável x. Como esses modelos tentam calcular probabilidades condicionais, isto é, **P (y | x)** são frequentemente utilizados em aprendizagem supervisionada. Exemplos incluem regressão logística, SVMs e Redes Neuronais. [1](https://en.wikipedia.org/wiki/Discriminative_model)

## Modelo Generativo

Pode-se dizer que a modelagem generativa se baseia na probabilidade condicional de uma variável X, dada a probabilidade da variável resposta Y. O modelo pode *gerar* leituras aleatórias e, por isso tem esse nome associado a ele (você pode literalmente gerar dados!). A função da modelagem generativa é entender como os dados surgem e a principal diferença para a modelagem discriminativa é que nela os modelos aprendem o *limite* entre classes e na modelagem generativa, aprendem a distribuição das classes individuais. Os modelos generativos mais famosos são LDA e o Teorema de Bayes. [1](http://www.vision.ime.usp.br/~teo/publications/dissertacao/node36.html) e [2](https://pt.wikipedia.org/wiki/Teorema_de_Bayes)  

# N

## Naive Bayes

O Naive Bayes é um algoritmo classificador probabilístico baseado no [Teorema de Bayes](https://pt.wikipedia.org/wiki/Teorema_de_Bayes). Ele recebe o nome de “naive” (ingênuo) porque desconsidera a correlação entre as variáveis (features). Ou seja, se determinada fruta é rotulada como “Limão”, caso ela também seja descrita como “Verde” e “Redonda”, o algoritmo não vai levar em consideração a correlação entre esses fatores. Isso porque trata cada uma das variáveis de forma independente. é muito utilizado em aprendizado de máquinas. [1](https://www.datageeks.com.br/naive-bayes/) [2](http://www.eletrica.ufpr.br/ufpr2/professor/36/TE808/5-NaiveBayes-AM.pdf) [3](https://pt.wikipedia.org/wiki/Infer%C3%AAncia_bayesiana#Bayes_ing%C3%AAnuo_(BI,_Naive_Bayes))


## NoSQL

Ver [Banco de Dados Não-Relacional](https://github.com/leportella/datascience-pizza/blob/master/dicionario.md#banco-de-dados-n%C3%A3o-relacional).

# O

## Ontologia

Em filosofia, ontologia é a teoria da "natureza do ser ou dos tipos de existências". Para Ciência da Computação, ontologias são um meio para modelar formalmente a estrutura de um sistema, ou seja, as entidades e relações relevantes que emergem da observação, e que são úteis para um determinado propósito (STAAB, Steffen; STUDER, Rudi (Ed.). Handbook on ontologies. Springer Science & Business Media, 2010).

## Outlier

É uma instância em uma base de dados que pode ser apenas um ruído que se deseja eliminar em uma etapa de pré-processamento, ou ainda uma instância que possui um padrão nunca analisado antes, a qual possa representar um comportamento extraordinário e, portanto, passível de estudo e atenção especial. [Campos 2015](http://www.teses.usp.br/teses/disponiveis/55/55134/tde-04082015-084412/pt-br.php)

## Overfitting

É um evento que ocorre quando o modelo se encaixa bem nos dados de treinamento, mas não se generaliza para dados não vistos ou testados. Isto é, não produz boas predições para dados desconhecidos. [Chaoji et. al. 2016](http://www.vldb.org/pvldb/vol9/p1597-chaoji.pdf)


## Oversampling 

É um conjunto de técnicas utilizadas para ajustar a distribuição do conjunto de dados de uma amostragem, é principalmente utilizado quando a amostragem de dados é insuficiente. Consiste da copia de dados dos conjuntos com menos amostras, a fim de que os conjuntos de amostras tenham uma quantidade de dados equivalentes.
Prinipalmente utilizado para amostragem estatistica, aprendizado de máquina e metodologias de pesquisa.[1](https://en.wikipedia.org/wiki/Oversampling), [2](https://pdfs.semanticscholar.org/9908/404807bf6b63e05e5345f02bcb23cc739ebd.pdf)

# P


## Pandas

Pandas é uma biblioteca Python open source, ela fornece ferramentas de análise de dados e estruturas de dados de alta performance e fáceis de usar. É considerada a principal e mais completa biblioteca para estes objetivos, sendo fundamental para Análise de Dados. [1](https://medium.com/data-hackers/uma-introdu%C3%A7%C3%A3o-simples-ao-pandas-1e15eea37fa1)

## Paradoxo de Simpson

O paradoxo de Simpson é um paradoxo da estatística no qual um conjunto de dados completo aponta em uma direção, mas uma análise de subconjuntos aponta na direção contrária. Este tipo de paradoxo é encontrado frequentemente em análises estatísticas de pesquisas tanto em ciências sociais quanto em ciências médicas e é particularmente problemático quando dados de frequência são interpretados como causais. O paradoxo foi nomeado em memória de Edward Simpson (1922), o primeiro estatístico a popularizá-lo.[Vídeo do Minuto da Física falando sobre o tema](https://www.youtube.com/watch?v=FBsVRJVA0ro) [2](https://pt.wikipedia.org/wiki/Paradoxo_de_Simpson) [3](https://proec.ufabc.edu.br/gec/o-que-que-a-ciencia-tem/paradoxo-de-simpson/)

## PCA (_Principal Component Analysis_)

É um procedimento matemático que utiliza uma transformação ortogonal (ortogonalização de vetores) para converter um conjunto de observações de variáveis possivelmente correlacionadas em um conjunto de valores de variáveis linearmente não correlacionadas chamadas de componentes principais [1](https://pt.wikipedia.org/wiki/An%C3%A1lise_de_componentes_principais).

## Perceptron

É um algorítimo para aprendizado de máquina supervisionado para classificadores binários(funções que determinam se os dados pertencem a uma determinada classe ou não). É um tipo de classificador linear, ou seja, algoritmo de classificação que faz suas predições baseado em uma função de predição linear combinando pesos de um vetor de características. [1](https://en.wikipedia.org/wiki/Perceptron)

## Precisão

Uma métrica para modelos de classificação. A precisão identifica a frequência com que um modelo estava correto ao prever a classe positiva. Isso é:
<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?\text{Precisao}&space;=&space;\frac{\text{Verdadeiros&space;Positivos}}&space;{\text{Verdadeiros&space;Positivos}&space;&plus;&space;\text{Falsos&space;Positivos}}">
</p>

[1](https://developers.google.com/machine-learning/glossary/#precision)

## Pytorch


É um ecossistema de ferramentas e bibliotecas de Machine Learning, para uso em Processamento de Linguagem Natural e Visão Computacional. Escrito em Python e de código aberto, é baseado em Torch, um framework escrito em Lua. [1](https://en.wikipedia.org/wiki/PyTorch) 
[2](https://pytorch.org/)


# Q

## Quartil (*Quartile*)

Ao contrário da expectativa, os quartis são 3 pontos que dividem um conjunto em 4 subconjuntos de iguais quantidades. *eg.* um conjunto que contém os números de 1 a 10, os quartis Q1, Q2 e Q3 são, respectivamente: 3, 5.5 e 8. [1](https://en.wikipedia.org/wiki/Quartile)

# R

## Random Forest

Método de aprendizado usado para classificação, regressão e outras aplicações, que se baseia na junção de outros algoritmos conhecidos
(logistic regression, linear regression,etc). Esse modelo é obtido pela construção de árvores de decisão, que conforme vão sendo construídas, decidem
quais algoritmos juntos levam ao melhor modelo. (Hastie et. al. 2008).

## Redes Neurais

São sistemas físicos que podem adquirir, armazenar e utilizar conhecimentos experimentais, que podem alcançar uma boa performance, devido à sua densa interconexão entre os nós da rede. (Lippmann, 1997 apud. Fernandes, 2003)

## Regressão

Tarefas de regressão em aprendizado de máquina são aquelas onde o objetivo é atribuir um valor contínuo a uma amostra. Um modelo de regressão é treinado de maneira supervisionada com pares de entradas e saídas, onde a entrada é um vetor de características (ou atributos) e a saída é um ou mais valores contínuos. O modelo final representa uma função que mapeia o conjunto dos dados de entrada em um conjunto de valores reais possíveis de saída. São exemplos de problemas clássicos de regressão: predição do valor de casas com base em suas características (e.g., tamanho do lote, número de quartos, ano de construção) e a predição da produção em um processo químico com base nos compostos (concentração dos reagentes, temperatura, pressão). [Regressão Linear](#regress%C3%A3o-linear) é um exemplo de técnica amplamente utilizada para criar modelos de regressão onde a relação entre os atributos e a saída é linear. Exemplos de métricas de qualidade comuns em modelos de regressão são [MSE](#erro-quadr%C3%A1tico-m%C3%A9dio) e [Coeficiente de Determinação](#coeficiente-de-determina%C3%A7%C3%A3o). (Bishop, 2006)

## Regressão Linear

Conceitualmente, é uma técnica para analisar dados e encontrar uma formulação matemática linear e explícita que descreva de maneira aproximada o comportamento (a relação) dos dados. Na prática, é encontrar dois coeficientes (linear e angular) que minimizem o erro quadrático entre a função linear resultante e os dados. [1](http://www.mit.edu/~6.s085/notes/lecture3.pdf)

## Regressão Logística

A regressão logística é uma técnica estatística que tem como objetivo produzir, a partir de um conjunto de observações, um modelo que permita a predição de valores tomados por uma variável categórica, frequentemente binária, a partir de uma série de variáveis explicativas contínuas e/ou binárias. Em comparação com as técnicas conhecidas em regressão, em especial a regressão linear, a regressão logística distingue-se essencialmente pelo facto de a variável resposta ser categórica. Esse algoritmo é comumente usado em problemas de classificação. [1](https://pt.wikipedia.org/wiki/Regress%C3%A3o_log%C3%ADstica).

## Regularização

Regularização é uma técnica para reduzir o problema do [overfit](#overfitting) em modelos de aprendizado de máquina. Existem diferentes formas de regularização e dentre as mais comuns estão a regularização L1 e L2, que adicionam um termo de regularização na função de custo a ser otimizada a fim de reduzir a complexidade do modelo final. A regularização L1 penaliza os pesos do modelo somando os valores absolutos de todos os parâmetros, fazendo features irrelevantes tenderem a um peso 0, enquanto a regularização L2 penaliza pela soma dos quadrados dos parâmetros, evitando que alguma feature tenha um peso muito superior às demais. [Dropout](#dropout) é outro exemplo de técnica de regularização utilizado em redes neurais. (Bishop, 2006)

## ReLU

Função não-linear de ativação de neurônios numa rede neural artificial[1](https://en.wikipedia.org/wiki/Rectifier_(neural_networks)). É definida pela função e forma:

![ReLU](https://wikimedia.org/api/rest_v1/media/math/render/svg/1d25c25758581789c97cdf80d52bf82bbfd0f237)
![ReLU-plot](https://upload.wikimedia.org/wikipedia/commons/thumb/6/6c/Rectifier_and_softplus_functions.svg/495px-Rectifier_and_softplus_functions.svg.png)

Surgiu recentemente como uma eficiente substituição para a função Sigmóid[2](https://en.wikipedia.org/wiki/Logistic_function).

## Revocação (*Recall*)

Uma métrica para modelos de classificação que responde à seguinte pergunta: de todos os possíveis rótulos positivos, quantos o modelo identificou corretamente? Isso é:
<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?\text{Revocacao}&space;=&space;\frac{\text{Verdadeiros&space;Positivos}}&space;{\text{Verdadeiros&space;Positivos}&space;&plus;&space;\text{Falsos&space;Negativos}}">
</p>

[1](https://developers.google.com/machine-learning/glossary/#recall)

## ROC (_Receiver Operating Characteristics_)

ROC é uma curva de probabilidade que denota a razão entre a taxa de verdadeiros positivos e a taxa de falsos positivos e mostra quão bom é o modelo na tarefa de distinguir entre duas saídas. O índice [AUC](#auc-area-under-the-curve) é um valor único que agrega todos os limiares da curva ROC, definindo a área abaixo da curva.[1](https://medium.com/@eam.avelar/o-que-%C3%A9-auc-e-roc-nos-modelos-de-machine-learning-2e2c4112033d)

# S

## Scala

Scala é uma linguagem de programação desenvolvida para expressar padrões de programação comuns de forma elegante e com tipagem segura através da integração de características de linguagens orientadas a objetos e funcional. [Referência](https://docs.scala-lang.org/tour/tour-of-scala.html)

## Scikit-learn

A scikit-learn é uma biblioteca de código aberto muito popular para realizar apredizado de máquina e mineração de dados em Python. Ela inclui diversos algoritmos de classificação, regressão e agrupamento, tais como [máquinas de vetores de suporte](#support-vector-machine), [florestas aleatórias](#random-forest), gradient boosting, [k-means](#k-means), DBSCAN e muitos outros. Além disso, a biblioteca também oferece técnicas de pré-processamento, seleção de atributos, seleção de modelos, métricas e outros utilitários. [1](http://scikit-learn.org/) [2](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html) [3](http://scikit-learn.org/stable/faq.html#what-is-the-project-name-a-lot-of-people-get-it-wrong)

## Simpson's Paradox (Paradoxo de Simpson)

Ver [Paradoxo de Simpson](https://github.com/alefjan/datascience-pizza/blob/master/dicionario.md#paradoxo-de-simpson).

## Sistemas de Recomendação

Um sistema de recomendação combina técnicas de Recuperação de Informação e Aprendizagem de Máquina para selecionar itens personalizados com base nos interesses dos usuários e conforme o contexto no qual estão inseridos, é utilizado em diversas áreas como: filmes, músicas, livros, pesquisas, sites de comércios eletrônicos, etc. Através dessas técnicas, é gerado uma filtragem da informação para o usuário e assim retornando uma lista de recomendação, as filtragens mais comuns são:

- **Filtragem colaborativa**: considera a experiência de todos os usuários
- **Filtragem baseada em conteúdo**: Considera a experiência do usuário alvo
- **Filtragem Híbrida**: utiliza-se os dois  tipos para gerar uma recomendação mais personalizada.

Veja mais nesse [link](https://en.wikipedia.org/wiki/Recommender_system).

## SVM (_Support Vector Machine_)

Máquina de vetores de suporte (do inglês SVM: support vector machine) é um método de aprendizado supervisionado que, dado um conjunto de treino X, tenta encontrar um hiperplano no espaço vetorial formado pelos exemplos em X que melhor separa os subconjuntos de exemplos definidos pelas classes nesse conjunto (James et. al. 2017). De forma efetiva, o método tenta encontrar uma margem de separação para os exemplos de acordo com as classes informadas. De posse da margem, é possível predizer a classe de um novo exemplo como sendo aquela do conjunto definido pelas margens encontradas durante o treino em que o novo exemplo está inserido. O método pode ser estendido para permitir margens mais ou menos severas (hard vs. soft margin), projeções não lineares em espaços de dimensão superior (kernel trick), predições probabilísticas entre outras [1](https://en.wikipedia.org/wiki/Support_vector_machine).

# T

## TensorFlow

O TensorFlow™ é uma biblioteca de software de código aberto para computação numérica que usa gráficos de fluxo de dados. Os nodes no gráfico representam operações matemáticas, e as arestas representam as matrizes ou tensores de dados multidimensionais que se comunicam com os nodes. A arquitetura flexível permite que você implante aplicações de computação a uma ou mais CPUs ou GPUs em um computador, servidor ou dispositivo móvel usando uma única API. O TensorFlow foi desenvolvido por pesquisadores e engenheiros da Google Brain Team no departamento de pesquisas de inteligência de máquina do Google com a finalidade de realizar pesquisas sobre redes neurais profundas e aprendizado de máquina. No entanto, devido à característica abrangente do sistema, ele também pode ser aplicado a vários outros domínios. [1](https://www.tensorflow.org)

## Teorema do Limite Central

O teorema do limite central afirma que ao extrairmos uma amostra suficientemente grande de uma população, a distribuição amostral da média aproxima-se de uma distribuição normal, não importando de qual população a amostra foi extraída. Isso permite o cálculo de probabilidades mesmo que a amostra não tenha distribuição normal. Para a maioria das populações, se o tamanho da amostra for maior do que 30, o Teorema do Limite Central pode ser aplicado. (Navidi, 2012)

# U

## Underfitting

É um evento que ocorre quando o seu modelo não representa de maneira eficaz o problema que foi proposto, ou seja, o modelo não se ajusta aos dados. Normalmente é possível identificar o underfitting por uma baixa variância e um alto bias. [1](https://chemicalstatistician.wordpress.com/2014/03/19/machine-learning-lesson-of-the-day-overfitting-and-underfitting/)

## Undersampling 

Equivalente ao Oversampling é um conjunto de técnicas utilizadas para ajustar a distribuição do conjunto de dados de uma amostragem e é principalmente utilizado quando a amostragem de dados é insuficiente porém faz o oposto do que é feito no Oversampling.
Consiste da remoção de dados dos conjuntos com maiores quantidades de amostras, a fim de que os conjuntos de amostras tenham uma quantidade de dados balanceada.
Prinipalmente utilizado para amostragem estatistica e aprendizado de máquina.
[1](https://en.wikipedia.org/wiki/Undersampling), [2](https://pdfs.semanticscholar.org/9908/404807bf6b63e05e5345f02bcb23cc739ebd.pdf)

# V

## Validação cruzada (_Cross-validation_)
Na abordagem básica, chamada método k-fold, o conjunto de treinamento é particionado em k subconjuntos. Dentre esses k subconjuntos teremos:
* 1 subconjunto de validação
* k-1 subconjuntos de treinamento

Quando um valor específico para k é escolhido, por exemplo k = 10, teremos uma Validação cruzada 10-fold. Neste caso o processo de validação será repetido 10 vezes, onde cada uma das 10 subamostras serão usadas como dados de validação [scikit learn cross-validation](http://scikit-learn.org/stable/modules/cross_validation.html).

Abaixo temos uma animação exemplificando as iterações.

![cross_validation](https://imada.sdu.dk/~marco/Teaching/AY2010-2011/DM825/animation.gif)

## Variância

Em termos estatísticos, a variância determina o quão distante cada valor está do valor médio do conjunto. Quanto maior a variância, mais distante o valor está da média. Quanto menor a variância, mais próximo o valor está da média. [1](http://brasilescola.uol.com.br/matematica/medidas-dispersao-variancia-desvio-padrao.htm)

## Variáveis Categóricas

Variáveis que possuem valores não-quantitativos. Os diferentes valores de uma variável categórica são normalmente chamados níveis (*levels*). Se os valores dos níveis forem nomes arbitrários a variável é normal (por exemplo, cor do olho). Porém se existirem ao menos 3 níveis (notas de escola como A, B, C) a variável é ordinal.

## Variáveis Discretas

Variável que possui valor quantitativo, ou seja, que pode ser contado. Em outras palavras, são variáveis com características mensuráveis que podem assumir apenas um número finito ou infinito contável de valores e, assim, somente fazem sentido valores inteiros. Geralmente são o resultado de contagens. Exemplos: número de filhos, número de bactérias por litro de leite. [1](http://leg.ufpr.br/~silvia/CE055/node8.html)


## Vetor

Na computação um vetor (arranjo unidimensional) é uma estrutura de dados que armazena um grupo de elementos, identificados por um índice e tipicamente com elementos do mesmo tipo. [1](https://techterms.com/definition/array),[2](https://en.wikipedia.org/wiki/Array_data_structure)

## Viés (_Bias_)

Também conhecido como erro sistemático, é a distorção sistemática entre a medida de uma variável estatística e o valor real da grandeza a ser estimada. [1](https://pt.wikipedia.org/wiki/Vi%C3%A9s_sistem%C3%A1tico)

# X

# W

# Y

# Z


# Referências

Alpaydin, Ethem. Introduction to Machine Learning. 2.ed. Massachusetts: MIT Press, 2010.

Behrens, J. T.. Principles and procedures of Exploratory Data Analysis. American Psychological Association Inc. 1997. Vol.2, No.2, 131-160

Bishop, Christopher M. Pattern Recognition and Machine Learning. New York, Springer, 2006.

Bussab, Wilton de O., and Pedro A. Morettin. Estatística básica. 8.ed. Página 41. Saraiva, 2010.

CAMPOS, Guilherme Oliveira. Estudo, avaliação e comparação de técnicas de detecção não supervisionada de outliers. 2015. Dissertação (Mestrado em Ciências de Computação e Matemática Computacional) - Instituto de Ciências Matemáticas e de Computação, Universidade de São Paulo, São Carlos, 2015. doi:10.11606/D.55.2015.tde-04082015-084412. Acesso em: 2017-10-03.

Fernandes, Anita Maria da Rocha. Inteligência Artificial: noções gerais. 1.ed. Florianópolis: Visual Books, 2003.

Gessert, W. Wingerath, S. Friedrich, and N. Ritter. Nosql database systems:a survey and decision guidance.
Computer Science - Research and Development,32(3):353–365, Jul 2017

Hastie, Trevor; Tibshirani, Robert; Friedman, Jerome. The Elements of Statistical Learning (2nd ed.). Springer. ISBN 0-387-95284-5, 2008.

Jain, A.K.; Murty, M.N.; Flynn, P.J.; Data Clustering: A review. ACM Computing Surveys, Vol. 31, No. 3, 1999.

Kazmier, Leonard. 2007. Estatística aplicada à administração e economia. Cap. 3.4, pág. 52.

Navidi, William. Probabilidade e Estatística para Ciências Exatas. AMGH. ISBN 978-85-805-5074-0,  2012.

Russell, Stuart J.; Norvig, Peter. Inteligência Artificial. 3.ed. Rio de Janeiro: Elsevier, 2013.

Srivastava N., Hinton G., Krizhevsky A., Sutskever I., and Salakhutdinov R. Dropout: a simple way to prevent neural networks from overfitting. Journal of Machine Learning Research. 15, 1 (January 2014), 1929-1958.

Staab, Steffen, and Rudi Studer, eds. Handbook on ontologies. Springer Science & Business Media, 2010.

Vineet Chaoji, Rajeev Rastogi, and Gourav Roy. 2016. Machine learning in the real world. Proc. VLDB Endow. 9, 13 (September 2016), 1597-1600. DOI: http://dx.doi.org/10.14778/3007263.3007318

Gareth James, Daniela Witten, Trevor Hastie e Robert Tibshirani. 2017. An Introduction to Statistical Learning. Spring. disponível em [link](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf). DOI: 10.1007/978-1-4614-7138-7

Gary M. Weiss, Kate McCarthy, and Bibi Zabar. Cost-Sensitive Learning vs. Sampling: Which is Best for Handling Unbalanced Classes with Unequal Error Costs?. Fordham University. em [link](https://pdfs.semanticscholar.org/9908/404807bf6b63e05e5345f02bcb23cc739ebd.pdf).
