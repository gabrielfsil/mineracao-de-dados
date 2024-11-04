# DCC127 - Mineração de Dados - 2023.3

A base de dados contém características de Instituições de Ensino Superior - IES. 

A ausência de valores pode aparecer como "S/D" ou outros valores inválidos.

O atributo "Situacao" representa a situação ("Ativa" ou "Extinta") da instituição de ensino quando a base de dados foi gerada.

O atributo "Cursos" indica a quantidade de cursos informada pela IES no Censo da Educação Superior.

Deseja-se entender as características de instituições que estão ativas e extintas.

## Pré-processamento

O objetivo desta etapa é descrever o conjunto de dados apresentado e adequá-lo para as próximas etapas do processo de mineração.

[Link da Apresentação](/assets/pdfs/preprocessamento.pdf)

![Matriz de Correlação](/assets/images/correlacao.png)

## Regras de Associação

Deseja-se neste trabalho que sejam elaboradas e analisadas regras de associação que possuam a situação das instituições (ativa ou extinta) como sucessor.
Além disso, deve-se analisar as principais diferenças encontradas em termos de antecessores para essas regras.

[Link da Apresentação](/assets/pdfs/regras-de-associacao.pdf)

![Regras de Associação](/assets/images/regras-de-associacao.png)

## Agrupamento

Vamos continuar aqui a analisar a base de dados contendo dados de instituições de ensino já adotada nos trabalhos anteriores.
Neste caso, vamos gerar e analisar agrupamentos destas instituições.

[Link da Apresentação](/assets/pdfs/agrupamento.pdf)

![Agrupamentos](/assets/images/clusters.png)

## Classificação - 01

Vamos continuar aqui a analisar a base de dados contendo dados de instituições de ensino já adotada nos trabalhos anteriores.
Neste caso, vamos gerar e analisar modelos de classificação para essas instituições.

[Link da Apresentação](/assets/pdfs/classificacao-01.pdf)

![Árvore de Decisão](/assets/images/arvore.png)


## Classificação - 02

Vamos continuar aqui o trabalho anterior de classificação e tratar o desbalanceamento dos dados

[Link da Apresentação](/assets/pdfs/classificacao-02.pdf)

![Oversampling](/assets/images/oversampling.png)
