# Análise de títulos da Netflix

Projeto em desenvolvimento para praticar análise de dados com Python, pandas e Matplotlib.

## Objetivo

Explorar o catálogo de filmes e séries da Netflix, avaliar a qualidade dos dados e preparar uma etapa de limpeza antes de responder perguntas analíticas.

## Estado atual

- carregamento e inspeção inicial da base;
- análise de dimensões, tipos e valores ausentes;
- verificação inicial de registros duplicados;
- exploração da distribuição dos anos de lançamento.

## Próximas etapas

- definir e justificar o tratamento de cada coluna com valores ausentes;
- separar a duração de filmes, em minutos, da duração de séries, em temporadas;
- validar identificadores e títulos duplicados;
- formular perguntas de negócio, criar visualizações e registrar conclusões;
- reiniciar o kernel e executar o notebook completo antes da versão final.

## Dados

A base contém 8.807 títulos e 12 atributos. Ela corresponde ao conjunto [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows), disponibilizado no Kaggle por Shivam Bansal sob licença CC0 (domínio público). Os registros representam um retrato do catálogo, não a oferta atual da Netflix.

## Arquivos

- `analise.ipynb`: análise exploratória em andamento;
- `netflix_titles.csv`: dados utilizados pelo notebook.
- `requirements.txt`: versões das bibliotecas utilizadas.

## Como executar

Instale as dependências:

```bash
python -m pip install -r requirements.txt
```

Depois, abra esta pasta no Jupyter ou no VS Code e execute `analise.ipynb`.
