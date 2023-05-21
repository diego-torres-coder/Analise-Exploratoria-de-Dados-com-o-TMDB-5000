# Análise Exploratória de Dados com o Dataset do TMDB 5000

Este projeto apresenta uma análise exploratória dos dados do [MovieLens](https://grouplens.org/datasets/movielens/) usando o *dataset* recomendado para educação e desenvolvimento, o qual possui 100 mil avaliações de 9 mil filmes, feitas por 600 usuários. 

O objetivo era explorar a distribuição das notas de cada filme usando tabelas de frequência, medidas de tendência central — moda, média e mediana — e visualizações com histogramas e box-plots.

Além disso, fiz uma análise exploratória dos dados do [TMDB 5000](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv) a fim de comparar as quantidades de filmes produzidos em uma determinada língua. Essas comparações foram feitas através da construção de tabelas de frequência e gráficos de barras.

Por fim, fiz uma análise da distribuição das notas dos cinco primeiros filmes do dataset para descobrir quais os mais amados e os mais odiados.

## Créditos

Este relatório foi construído com base no conteúdo do curso [Data Science: analise e visualização de dados](https://cursos.alura.com.br/course/data-science-primeiros-passos) da Escola de Data Science da Alura.

Fiz algumas modificações com a finalidade de enriquecer não somente os relatórios, mas também meu aprendizado.

## Como Reproduzir este Projeto

Navegue para a pasta em que deseja clonar este projeto. Em seguida, digite o comando a seguir:

```bash
git clone https://github.com/diego-torres-coder/Analise-Exploratoria-de-Dados-com-o-TMDB-5000.git
```
Navegue para a pasta recém-criada:

```bash
cd Analise-Exploratoria-de-Dados-com-o-TMDB-5000/
```

Crie um **ambiente conda** para o projeto:

```bash
conda create -n tmdb python=3.11
```

Ative o ambiente virtual com o seguinte comando:

```bash
conda activate tmdb
```

Instale as dependências do projeto:

```bash
conda install numpy openpyxl pandas matplotlib seaborn jupyterlab
```

Execute o Jupyter Lab:

```bash
jupyter-lab
```
Por fim, execute todas as células do notebook.



