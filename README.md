# DISRUPTIVE ARCHITECTURES: IOT, IOB & GENERATIVE IA

### Integrantes
- **Vinicius Malavia Lorenzetti** - RM: 553121
- **João Pedro Fontana** - RM: 553343
- **Marcelo Galli** - RM: 553654

### Vídeo
[Link do vídeo](#)

## Tema
O tema escolhido para o nosso projeto foi: **Prevenção de Sinistros em Odontologia com Análise Preditiva**.

## Problemas
O setor odontológico enfrenta desafios significativos relacionados à gestão de sinistros, incluindo:
- **Excesso de consultas e tratamentos desnecessários**: Resulta de diagnósticos inadequados ou uso indevido de serviços, levando a custos elevados para seguradoras e pacientes.
- **Fraudes**: Práticas como faturamento de serviços não realizados ou desnecessários prejudicam a sustentabilidade do negócio.
- **Dificuldade na identificação de padrões de risco**: A abordagem reativa atual gera custos elevados e prejudica a experiência do paciente.

## Objetivo da Solução
Desenvolver uma solução baseada em análise preditiva para identificar e mitigar riscos associados a sinistros, utilizando ML e IA. A proposta é implementar um sistema que:
- Monitore dados de pacientes e dentistas.
- Identifique comportamentos de risco em tempo real.
- Sugira intervenções preventivas para reduzir a ocorrência de sinistros.

## Aplicação de Conceitos e Técnicas de ML/IA

1. **Modelos Preditivos**
   - **Regressão Logística**: Para prever a probabilidade de sinistros, ideal para classificação binária.
   - **Árvores de Decisão e Random Forests**: Permitem identificar características chave que podem levar a sinistros, oferecendo boa interpretabilidade.

2. **Detecção de Anomalias**
   - **Isolation Forest**: Eficaz para identificar comportamentos suspeitos em dados de alta dimensionalidade.
   - **One-Class SVM**: Modela o comportamento normal dos pacientes e detecta desvios.

3. **Análise de Clusterização**
   - **K-means**: Segrega pacientes em grupos com base em comportamentos, facilitando a identificação de padrões de risco.
   - **DBSCAN**: Identifica grupos de pacientes semelhantes, mesmo em dados com ruídos.

4. **Séries Temporais**
   - **ARIMA**: Útil para prever o número de atendimentos ao longo do tempo.
   - **LSTM**: Rede neural que captura padrões complexos em dados temporais.

As técnicas descritas acima serão usadas durante todo nosso projeto, já que são fundamentais para construir um sistema eficaz que antecipe e mitigue riscos no setor odontológico.

## Frameworks e Bibliotecas

1. **Pandas**
   - **Uso**: Manipulação e análise de dados, essencial para pré-processamento, limpeza e análise exploratória.
   - **Motivo**: A facilidade em lidar com DataFrames torna a manipulação de dados mais intuitiva.

2. **Scikit-Learn**
   - **Uso**: Implementação de modelos de ML, incluindo classificação, regressão e clusterização.
   - **Motivo**: Sua simplicidade e a diversidade de algoritmos disponíveis facilitam a prototipagem rápida.

3. **TensorFlow/Keras**
   - **Uso**: Desenvolvimento de modelos de deep learning para problemas complexos como detecção de anomalias e séries temporais.
   - **Motivo**: A flexibilidade e escalabilidade permitem o treinamento de modelos em grandes volumes de dados.

4. **Matplotlib e Seaborn**
   - **Uso**: Visualização de dados e resultados de modelos.
   - **Motivo**: Gráficos e visualizações ajudam na interpretação de padrões e na apresentação de resultados.

5. **Statsmodels**
   - **Uso**: Análise estatística e modelagem de séries temporais.
   - **Motivo**: Permite realizar testes estatísticos e construir modelos de regressão de maneira robusta.

## Dataset
O dataset utilizado no nosso modelo de análise preditiva foi gerado pelo ChatGPT. Definimos as colunas e seus valores relevantes, contendo 200 registros relacionados à área de odontologia.

## Ferramenta de Desenvolvimento
A ferramenta escolhida para o desenvolvimento deste projeto foi o **Google Colab**, uma vez que todos os integrantes do grupo já estavam familiarizados com a ferramenta, evitando a necessidade de adaptação a novas plataformas.

## Considerações Finais do Projeto
Ao longo deste projeto, exploramos como a aplicação de técnicas de Machine Learning e Inteligência Artificial pode transformar a forma como abordamos a redução de sinistros no setor odontológico. Utilizando modelos preditivos, como a regressão logística e as árvores de decisão, buscamos entender melhor os fatores que levam a sinistros, permitindo intervenções mais direcionadas e eficazes.

A implementação de técnicas de detecção de anomalias, como o Isolation Forest, permitirá identificar comportamentos suspeitos que podem indicar fraudes, enquanto a análise de clusterização com K-means ajudará a segmentar pacientes, facilitando a personalização dos serviços.

Além disso, a análise de séries temporais com ARIMA e LSTM será crucial para prever tendências e padrões de atendimento, possibilitando um planejamento mais eficiente. Acreditamos que, ao integrar essas soluções, poderemos criar um sistema mais inteligente e responsivo no setor odontológico, contribuindo para um futuro mais seguro e eficiente.
