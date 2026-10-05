# Tarefa 13 — Distribuições em Ciências dos Alimentos

## Integrantes

* \[Gustavo Gabriel da Silva Rodrigues Bruno Nº USP: 11373741]
* \[Henrique de Angelo Silva Nº USP: 178960221]
* \[Luciana Gouveia dos Santos Nº USP: 15472401]

## Arquivos

* `tarefa13\\\\\\\_Python\\\\\\\_Ciencias\\\\\\\_dos\\\\\\\_Alimentos.ipynb`: notebook com pesquisa teórica, fórmulas, gráficos de parâmetros, probabilidades e áreas sombreadas.
* A base Wine Quality é baixada automaticamente da UCI quando o notebook é executado; se isso falhar, consulte as instruções abaixo.

## Base de dados

UCI Machine Learning Repository — Wine Quality: https://archive.ics.uci.edu/dataset/186/wine+quality  
Pacote ZIP: https://archive.ics.uci.edu/static/public/186/wine+quality.zip  
Acesso/consulta registrado no trabalho: 04/10/2026.

Cada linha representa uma amostra de vinho com características físico-químicas e avaliação de qualidade. O notebook usa a variável `alcohol` dos arquivos de vinho tinto e branco. Confirme os termos de licença da fonte antes de redistribuir os dados.

## Como executar

1. Instale Python 3.10 ou superior.
2. Instale as dependências: `pip install pandas numpy matplotlib scipy jupyter`.
3. Abra o notebook com Jupyter Notebook ou JupyterLab.
4. Execute todas as células em ordem. É necessária conexão com a internet para baixar os dados automaticamente.
5. Se o download falhar, baixe o ZIP no link acima, extraia `winequality-red.csv` e `winequality-white.csv` para a mesma pasta do notebook e execute novamente.

## Referências teóricas

* SciPy — Normal: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.norm.html
* SciPy — t de Student: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.t.html
* SciPy — qui-quadrado: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.chi2.html
* SciPy — F de Fisher: https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.f.html
* NIST/SEMATECH e-Handbook: https://www.itl.nist.gov/div898/handbook/

**Antes de entregar:** substitua os campos de integrantes, execute todas as células, confira os gráficos e resultados, e publique o repositório no GitHub com acesso público.

