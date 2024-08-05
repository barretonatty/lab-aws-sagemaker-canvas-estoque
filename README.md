# Previsão de Estoque Inteligente na AWS com SageMaker Canvas

Este repositório documenta o processo de criação de um modelo de previsão de estoque utilizando o Amazon SageMaker Canvas.

## Objetivo

Desenvolver um modelo de previsão de estoque utilizando o SageMaker Canvas e documentar o processo em um repositório no GitHub.

## Passo a Passo

### 1. Selecionar Dataset

1. **Acessar o SageMaker Canvas:**
   - Faça login na sua conta AWS e acesse o Amazon SageMaker Canvas através do [Console da AWS](https://console.aws.amazon.com/sagemaker/).

2. **Navegar até a Seção de Datasets:**
   - No painel do SageMaker Canvas, vá para a seção de "Datasets" (Conjuntos de Dados).

3. **Escolher um Dataset:**
   - Na pasta `datasets` deste repositório, escolha um dataset que será utilizado para treinar seu modelo de previsão de estoque.
   - Exemplo de datasets: `estoque.csv`, `vendas_mensais.xlsx`, etc.

4. **Fazer o Upload do Dataset:**
   - Clique em "Upload dataset" e selecione o arquivo do dataset que você escolheu.
   - O SageMaker Canvas irá carregar e processar o dataset.

### 2. Construir e Treinar

1. **Importar o Dataset:**
   - No SageMaker Canvas, vá para a seção "Projects" e clique em "Create new project" para iniciar um novo projeto.
   - Selecione o dataset que você carregou e importe-o para o projeto.

2. **Configurar as Variáveis:**
   - Configure as variáveis de entrada e saída. Por exemplo:
     - **Variável de Entrada**: `Data de Compra`, `Quantidade`
     - **Variável de Saída**: `Previsão de Estoque`

3. **Configurar o Modelo:**
   - Escolha o tipo de modelo apropriado para previsão de estoque. O SageMaker Canvas pode sugerir um modelo adequado baseado no seu dataset.

4. **Iniciar o Treinamento:**
   - Clique em "Train model" para iniciar o treinamento do modelo.
   - O processo pode levar algum tempo, dependendo do tamanho do dataset e da complexidade do modelo.

### 3. Analisar

1. **Examinar Métricas de Performance:**
   - Após o treinamento, vá para a seção "Model performance" para revisar as métricas do modelo.
   - Analise métricas como precisão, recall e F1 score para entender a performance do modelo.

2. **Verificar Características Importantes:**
   - No SageMaker Canvas, analise as características mais influentes que afetam as previsões.

3. **Ajustar o Modelo:**
   - Se necessário, ajuste os parâmetros do modelo ou refine o dataset.
   - Re-treine o modelo até obter um desempenho satisfatório.

### 4. Prever

1. **Fazer Previsões:**
   - Use o modelo treinado para fazer previsões sobre novos dados.
   - Vá para a seção "Predictions" e insira os dados que deseja prever.

2. **Exportar e Analisar Resultados:**
   - Exporte os resultados das previsões em formato CSV ou Excel.
   - Analise as previsões geradas para insights sobre o estoque.

### Conclusões

- **Insights e Observações:**
  - Documente quaisquer insights ou conclusões obtidas a partir das previsões de estoque.
  - Por exemplo: "O modelo prevê um aumento na demanda para o próximo trimestre, sugerindo a necessidade de aumentar o estoque."

## Recursos Adicionais

- [Documentação Oficial do SageMaker Canvas](https://docs.aws.amazon.com/sagemaker/latest/dg/canvas.html)
- [Guia de Introdução ao SageMaker](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html)
- [Tutoriais e Exemplos Práticos](https://aws.amazon.com/getting-started/hands-on/)
- [Repositório de Exemplo](https://github.com/awslabs/amazon-sagemaker-examples)

## Contato

Para mais informações, entre em contato:
- [Natália Barreto](https://www.linkedin.com/in/natáliabarreto/)
- [GitHub](https://github.com/barretonatty)
