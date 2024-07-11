# Projeto LH_CD_JULIANOGUEIRA

Este repositório contém o projeto desenvolvido para o Desafio Cientista de Dados da Indicium, envolvendo análise e modelagem de dados de filmes do IMDb, para orientar qual tipo de filme deve ser o próximo a ser desenvolvido por um estúdio de Hollywood chamado PProductions.

## Estrutura de Arquivos

- relatorio_imdb.ipynb: Notebook Jupyter contendo a análise exploratória e o código de modelagem.
- modelo_imdb_linear_regression.pkl: Arquivo pickle contendo o modelo de regressão linear treinado.
- desafio_indicium_imdb.csv: Conjunto de dados contendo informações sobre filmes.
- requirements.txt: Arquivo de requisitos contendo os pacotes Python necessários para reproduzir o ambiente do projeto.

## Instalação e Execução do Projeto

Para executar este projeto, siga os passos abaixo:

1. Clone o repositório:
   git clone https://github.com/seu-usuario/LH_CD_JULIANOGUEIRA.git
   
   cd LH_CD_JULIANOGUEIRA

3. Instale os pacotes necessários utilizando o pip:
   ```bash
   pip install -r requirements.txt

4. Baixe o modelo spaCy em inglês:
   ```bash
   python -m spacy download en_core_web_sm

5. Execute o notebook Jupyter para visualizar as análises e a modelagem:
   ```bash
   jupyter notebook relatorio_imdb.ipynb

6. Para executar o modelo de regressão linear, utilize o código disponível no notebook ou carregue o arquivo modelo_imdb_linear_regression.pkl.
