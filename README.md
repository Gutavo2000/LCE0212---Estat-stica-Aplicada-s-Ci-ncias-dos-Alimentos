# Tarefa 11 — Variáveis Aleatórias em Ciências dos Alimentos

## Integrantes

- Gustavo Gabriel da Silva Rodrigues Bruno — Nº USP 11373741
- Henrique de Angelo Silva — Nº USP 17896022
- Luciana Gouveia dos Santos — Nº USP 15472401

## Objetivo

Este trabalho tem como objetivo apresentar e exemplificar conceitos introdutórios de Probabilidade aplicados às Ciências dos Alimentos, com foco no estudo de variáveis aleatórias e nos modelos probabilísticos de Bernoulli, Binomial e Poisson.

Por meio de exemplos contextualizados e simulações desenvolvidas em Python, busca-se demonstrar como esses conceitos podem ser utilizados em situações relacionadas à produção, processamento, controle de qualidade e segurança de alimentos.

## Conteúdos abordados

O notebook está organizado nas seguintes seções:

### 1. Variável aleatória

Apresentação do conceito de variável aleatória como uma função que associa valores numéricos aos possíveis resultados de um experimento aleatório.

Como exemplo aplicado às Ciências dos Alimentos, é considerada a inspeção de um lote de embalagens, em que a variável de interesse corresponde ao número de embalagens defeituosas encontradas.

### 2. Variáveis aleatórias discretas e contínuas

É apresentada a diferença entre variáveis aleatórias discretas e contínuas.

**Exemplos de variáveis discretas:**

- Número de reclamações de consumidores por dia;
- Número de frutas danificadas em uma caixa;
- Número de colônias de bactérias em uma placa de Petri.

**Exemplos de variáveis contínuas:**

- Massa de um produto alimentício;
- Teor de umidade de um alimento;
- Temperatura de armazenamento.

### 3. Modelo de Bernoulli

O modelo de Bernoulli é utilizado para representar experimentos que apresentam apenas dois resultados possíveis.

No exemplo utilizado no trabalho, é considerada a inspeção da selagem de uma única embalagem:

- **Sucesso:** embalagem aprovada;
- **Fracasso:** embalagem reprovada.

Foi considerada uma probabilidade de 98% de aprovação da embalagem.

### 4. Modelo Binomial

O modelo Binomial é utilizado para representar o número de sucessos obtidos em um número fixo de ensaios independentes de Bernoulli.

No trabalho, é considerada uma amostra de 20 embalagens, em que cada embalagem possui probabilidade de 2% de apresentar defeito.

O notebook apresenta:

- Simulação do número de embalagens defeituosas;
- Probabilidade de encontrar exatamente uma embalagem defeituosa;
- Probabilidade de encontrar no máximo duas embalagens defeituosas;
- Representação gráfica da distribuição de probabilidades.

### 5. Modelo de Poisson

O modelo de Poisson é utilizado para representar a contagem de ocorrências de determinado evento em um intervalo de tempo ou espaço.

Como exemplo, é considerado o número de falhas observadas em uma linha de envase durante uma hora.

Foi adotada uma taxa média de:

**λ = 3 falhas por hora**

O notebook apresenta:

- Simulação do número de falhas em uma hora;
- Probabilidade de ocorrerem exatamente duas falhas;
- Probabilidade de ocorrer no máximo uma falha;
- Representação gráfica da distribuição de probabilidades.

### 6. Comparação entre os modelos

Ao final do notebook, é apresentada uma tabela comparativa entre os modelos de Bernoulli, Binomial e Poisson.

A comparação considera:

- Tipo de fenômeno representado;
- Possíveis valores da variável aleatória;
- Situações em que cada modelo pode ser utilizado;
- Exemplos contextualizados em Ciências dos Alimentos.

## Dados utilizados

Os dados utilizados neste trabalho são **simulados** e foram criados exclusivamente para fins didáticos e para exemplificação dos modelos probabilísticos estudados.

A utilização de dados simulados permite definir previamente parâmetros como probabilidade de aprovação, probabilidade de defeito e taxa média de ocorrências, facilitando a demonstração do funcionamento das distribuições de Bernoulli, Binomial e Poisson.

Dessa forma, os valores utilizados não representam dados provenientes de uma indústria, empresa ou estabelecimento específico.

## Arquivo principal

O arquivo principal do trabalho é:

`tarefa11_variaveis_aleatorias_alimentos.ipynb`

O notebook contém explicações em células Markdown, códigos comentados, simulações, cálculos de probabilidade, gráficos e interpretações contextualizadas em Ciências dos Alimentos.

## Bibliotecas utilizadas

O trabalho utiliza as seguintes bibliotecas Python:

- **NumPy** — operações numéricas e geração de dados simulados;
- **Pandas** — organização e apresentação da tabela comparativa;
- **SciPy** — implementação das distribuições de Bernoulli, Binomial e Poisson;
- **Matplotlib** — construção dos gráficos das distribuições de probabilidade.

## Como executar

O notebook pode ser executado utilizando o **Google Colab**, Jupyter Notebook ou outro ambiente compatível com Python.

### Google Colab

1. Acesse o Google Colab;
2. Selecione a opção para abrir um notebook;
3. Faça o upload do arquivo `tarefa11_variaveis_aleatorias_alimentos.ipynb`;
4. Execute as células na ordem apresentada no notebook.

### Execução local

Para executar o notebook localmente, é necessário possuir Python instalado e instalar as bibliotecas utilizadas.

A instalação pode ser realizada com:

```bash
pip install numpy pandas scipy matplotlib jupyter
```

Depois, execute:

```bash
jupyter notebook
```

Abra o arquivo `tarefa11_variaveis_aleatorias_alimentos.ipynb` e execute as células na sequência.

## Organização do repositório

```text
Tarefa-11/
│
├── tarefa11_variaveis_aleatorias_alimentos.ipynb
└── README.md
```

## Referências bibliográficas

MONTGOMERY, Douglas C.; RUNGER, George C. **Estatística Aplicada e Probabilidade para Engenheiros**. Rio de Janeiro: LTC, 2018.

MORETTIN, Pedro Alberto; BUSSAB, Wilton de Oliveira. **Estatística Básica**. São Paulo: Saraiva Educação, 2017.

## Documentações consultadas

- NumPy Documentation: https://numpy.org/doc/
- Pandas Documentation: https://pandas.pydata.org/docs/
- SciPy — Statistical Functions: https://docs.scipy.org/doc/scipy/reference/stats.html
- Matplotlib Documentation: https://matplotlib.org/stable/

## Observação

Este trabalho foi desenvolvido com finalidade acadêmica para aplicação de conceitos introdutórios de Probabilidade no contexto das Ciências dos Alimentos. Todos os exemplos probabilísticos apresentados utilizam situações hipotéticas e dados simulados para fins de aprendizagem.
