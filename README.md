# Lh_cd_gabb

## Desafio de Ciência de Dados - Previsão de Nota IMDb

Este projeto foi desenvolvido como parte do processo seletivo da Lighthouse. O objetivo é aplicar técnicas de ciência de dados e aprendizado de máquina para analisar um conjunto de dados cinematográficos e construir um modelo preditivo capaz de estimar a nota de avaliação de filmes segundo o IMDb.

---

## Objetivos

- Realizar uma **análise exploratória dos dados (EDA)**, identificando padrões, correlações e insights relevantes sobre os filmes.
- Responder às perguntas analíticas e criativas propostas no desafio:
  - Qual filme você recomendaria para uma pessoa que você não conhece?
  - Quais fatores estão relacionados com alta expectativa de faturamento?
  - É possível inferir o gênero do filme a partir da sinopse (`Overview`)?
  - Como prever a nota do IMDb com base nas variáveis disponíveis?
- Construir um modelo de **regressão** para prever a nota do IMDb utilizando variáveis como:
  - `Meta_score`, `Gross`, `No_of_Votes`, `Runtime`, `Genre`, `Overview`, entre outras.
- Testar o modelo com um exemplo real: **The Shawshank Redemption**.
- Salvar o modelo treinado em formato `.pkl` para uso posterior.

---

## Tecnologias e Bibliotecas Utilizadas

- **Python**
- **Pandas**, **NumPy** – manipulação e análise de dados
- **Scikit-learn** – modelagem preditiva
- **XGBoost** – modelo de alta performance
- **Joblib** – salvamento do modelo
- **Jupyter Notebook** – ambiente de desenvolvimento

---

## Estrutura do Projeto

├── notebook.ipynb # Notebook com EDA, modelagem e respostas ├── modelo_pm.pkl # Modelo treinado salvo em formato .pkl ├── requirements.txt # Lista de pacotes utilizados ├── README.md # Este arquivo


---

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/seurepositorio.git

2. Instale os pacotes necessários:


   - pip install -r requirements.txt

3. Execute o notebook (notebook.ipynb) para visualizar a análise e testar o modelo.


