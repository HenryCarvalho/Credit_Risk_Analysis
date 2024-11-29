# Análise de Risco de Crédito

## Descrição do Projeto
Este projeto tem como objetivo a análise de risco de crédito de clientes de um banco. A partir de um conjunto de dados contendo informações financeiras e comportamentais de clientes, o objetivo é prever a probabilidade de inadimplência de um cliente, ajudando instituições financeiras a tomar decisões informadas sobre concessão de crédito.

## Estrutura do Projeto
Este repositório contém um Jupyter Notebook com a implementação do modelo preditivo de risco de crédito. O processo envolve as seguintes etapas:

1. **Importação de bibliotecas**: Bibliotecas como pandas, numpy, sklearn e matplotlib são utilizadas para manipulação de dados, criação de modelos e visualização de resultados.
2. **Carregamento e exploração dos dados**: O conjunto de dados é carregado e explorado para entender as variáveis envolvidas.
3. **Pré-processamento de dados**: As etapas de limpeza, transformação e normalização dos dados são realizadas.
4. **Criação do modelo preditivo**: Algoritmos de machine learning, como Regressão Logística, Árvores de Decisão e Random Forest, são treinados para prever o risco de crédito (inadimplência).
5. **Avaliação do modelo**: O desempenho do modelo é avaliado com métricas como Acurácia, Precisão, Recall, e AUC-ROC.
6. **Implementação de soluções**: Com base no desempenho do modelo, recomendações para mitigação de risco são feitas.

## Modelos e Algoritmos
Este projeto utiliza diferentes abordagens para análise de risco de crédito, incluindo modelos supervisionados e, se necessário, abordagens não supervisionadas para uma análise mais profunda. Abaixo estão os principais modelos e algoritmos utilizados:

### Modelos Supervisionados
- **Regressão Logística**: Utilizado para prever a probabilidade de inadimplência com base nas variáveis preditoras. A regressão logística é uma das abordagens mais simples e eficazes para classificação binária.
- **Árvores de Decisão**: Um modelo que ajuda a dividir os dados em categorias com base nas variáveis de entrada, ideal para entender como as decisões de crédito são tomadas de maneira visual.
- **Random Forest**: Um modelo de aprendizado em conjunto que utiliza múltiplas árvores de decisão para melhorar a precisão da classificação, proporcionando maior robustez e desempenho.
- **SVM (Máquinas de Vetores de Suporte)**: Um modelo poderoso para encontrar a melhor fronteira de decisão entre classes, usado quando os dados são mais complexos e não linearmente separáveis.

### Abordagens Não Supervisionadas (se aplicável)
- **Análise de Componentes Principais (PCA)**: Para redução de dimensionalidade e extração de características mais importantes para uma análise mais eficiente.
- **Clustering (K-means)**: Pode ser utilizado para segmentação de clientes com características semelhantes, agrupando-os em clusters com base em seu perfil financeiro. Isso pode ajudar a identificar padrões ocultos no comportamento dos clientes.

### Avaliação de Modelos
Cada modelo será avaliado utilizando métricas como:
- **Acurácia**: Percentual de previsões corretas.
- **Precisão**: Capacidade do modelo de prever corretamente os inadimplentes (positivos).
- **Recall**: Capacidade do modelo de capturar todos os inadimplentes reais.
- **F1-Score**: Média harmônica entre precisão e recall, útil para desequilíbrios entre classes.
- **AUC-ROC**: Área sob a curva ROC, que fornece uma visão geral da capacidade de distinção entre as classes.

## Conjunto de Dados
O conjunto de dados utilizado neste projeto contém informações sobre clientes, como idade, renda anual, histórico de crédito, dívidas acumuladas, número de dependentes, entre outras variáveis. A coluna **Risco de Crédito** é a variável alvo, que indica se o cliente é considerado um bom pagador (0) ou inadimplente (1).

O arquivo de dados utilizado para o treinamento e teste do modelo é o `analise_risco_credito.csv`, que pode ser baixado do repositório.

### Exemplos de variáveis no conjunto de dados:
- **Idade**: Idade do cliente.
- **Renda Anual**: Renda anual do cliente.
- **Empréstimo Atual**: Valor do empréstimo atual.
- **Número de Dependentes**: Quantidade de dependentes do cliente.
- **Histórico de Crédito**: Histórico de crédito do cliente (positivo, negativo ou sem histórico).
- **Score de Crédito**: Pontuação de crédito do cliente.

## Objetivos
O principal objetivo deste projeto é prever se um cliente será inadimplente ou não, com base nas informações fornecidas, utilizando técnicas de machine learning.

## Bibliotecas Requeridas
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Como Executar
1. Clone este repositório.
2. Instale as dependências necessárias com o comando:
    ```
    pip install -r requirements.txt
    ```
3. Execute o Jupyter Notebook `credit_risk_analysis.ipynb` para reproduzir o processo de análise e treinamento do modelo.

## Conclusões
Com base no modelo treinado, a previsão do risco de crédito pode ser usada para auxiliar na tomada de decisões sobre concessão de crédito e minimizar os riscos de inadimplência.

## Licença
Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Desenvolvedor: **Henrique Carvalho**  
E-mail: [henrique.t.s.carvalho@gmail.com](mailto:henrique.t.s.carvalho@gmail.com)  
GitHub: [https://github.com/HenryCarvalho](https://github.com/HenryCarvalho)
