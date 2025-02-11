# Titanic - Regressão Linear para Previsão de Idade

Este projeto utiliza a técnica de **Regressão Linear** para prever a idade de passageiros do Titanic, com base em várias características presentes no conjunto de dados, como classe, sexo e número de familiares a bordo. O objetivo é treinar um modelo preditivo para estimar a idade dos passageiros que possuem dados ausentes.

## Objetivo

O principal objetivo deste projeto é realizar a **previsão da idade** dos passageiros do Titanic a partir de características como:

- **Classe do passageiro**
- **Sexo**
- **Número de irmãos e cônjuges a bordo**
- **Número de pais e filhos a bordo**
  
Através da análise exploratória e do tratamento de dados, o modelo de **Regressão Linear** foi treinado para fazer previsões sobre as idades ausentes nos dados.

## Etapas do Projeto

1. **Pré-processamento de Dados**: Carregamento dos dados e transformação das colunas para análise.
2. **Tratamento de Dados Faltantes**: Preenchimento de valores ausentes para atributos como "Idade", utilizando o modelo preditivo.
3. **Criação de Novas Features**: Como a coluna "Título", extraída dos nomes dos passageiros.
4. **Modelo Preditivo**: Aplicação da **Regressão Linear** para prever as idades com base nas variáveis disponíveis.
5. **Avaliação do Modelo**: Análise do desempenho do modelo utilizando métricas como o **Root Mean Squared Error (RMSE)**.
6. **Geração de Resultados**: Criação de um arquivo contendo as idades previstas para os passageiros.

## Como Funciona

O modelo de regressão linear foi treinado utilizando as informações dos passageiros cujas idades estavam disponíveis. Após o treinamento, ele foi usado para prever as idades dos passageiros cujos dados estavam ausentes. As previsões foram geradas e armazenadas em um arquivo para posterior análise.

## Tecnologias Utilizadas

- **Python**: Linguagem utilizada para análise de dados e construção do modelo.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **NumPy**: Biblioteca para operações matemáticas e numéricas.
- **Scikit-learn**: Biblioteca para criação do modelo de regressão linear e avaliação de desempenho.
- **Matplotlib** e **Seaborn**: Bibliotecas para visualização de dados.

## Contribuições

Se você tiver sugestões ou melhorias para o projeto, fique à vontade para abrir uma **issue** ou **pull request**!

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
