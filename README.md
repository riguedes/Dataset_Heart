# Classificação de Pacientes com Problemas Cardíacos usando Redes MLP, KNN e Naive Bayes

**Introdução:**
A aplicação da Inteligência Artificial (IA) na área da saúde tem conquistado grande destaque devido à sua capacidade de auxiliar médicos e profissionais da área a tomarem decisões mais precisas e eficientes. Neste trabalho, exploramos a aplicação de três algoritmos de aprendizado de máquina - Redes MLP, KNN e Naive Bayes - para classificar pacientes com relação à presença de problemas cardíacos. O objetivo é comparar o desempenho desses algoritmos na tarefa de diagnóstico médico.

**Metodologia:**
Foram utilizados dados médicos de um conjunto de pacientes, incluindo variáveis relevantes como idade, gênero, pressão arterial, níveis de colesterol e outros indicadores de saúde. O conjunto de dados foi dividido em conjuntos de treinamento e teste para avaliar a capacidade de generalização dos modelos.

1. **Redes MLP (Multilayer Perceptron):**
   As redes MLP são uma classe popular de redes neurais artificiais. Elas consistem em camadas de neurônios interconectados, incluindo uma camada de entrada, uma ou mais camadas intermediárias (ocultas) e uma camada de saída. Para o diagnóstico de problemas cardíacos, a rede MLP foi treinada com os dados de treinamento, ajustando os pesos das conexões entre os neurônios. A função de ativação, a taxa de aprendizado e o número de neurônios nas camadas ocultas foram otimizados para alcançar o melhor desempenho.

2. **KNN (K-Nearest Neighbors):**
   O algoritmo KNN é um método de classificação baseado em instâncias, ou seja, ele classifica novos pontos de dados com base na maioria das classes das instâncias vizinhas mais próximas. Neste caso, os pacientes são classificados com base na similaridade de suas características em relação aos vizinhos mais próximos. O valor de "k" (número de vizinhos) foi escolhido após experimentação.

3. **Naive Bayes:**
   O classificador Naive Bayes é baseado no Teorema de Bayes e assume que todas as variáveis são independentes, o que é uma simplificação forte, mas muitas vezes funciona bem na prática. Ele calcula a probabilidade de um paciente pertencer a uma classe (com problema cardíaco ou sem problema cardíaco) com base na probabilidade das características observadas nos dados de treinamento.

**Resultados:**
Após treinamento e teste, os três algoritmos foram avaliados em termos de métricas de desempenho, como acurácia, precisão, recall e F1-score. Os resultados foram comparados para determinar qual algoritmo teve o melhor desempenho na tarefa de classificação de pacientes com problemas cardíacos.

**Conclusão:**
Este trabalho demonstrou a aplicação de três algoritmos de aprendizado de máquina - Redes MLP, KNN e Naive Bayes - na classificação de pacientes quanto à presença de problemas cardíacos. Através da comparação de desempenho, foi possível identificar qual algoritmo se saiu melhor para a tarefa em questão. A aplicação de IA no diagnóstico médico promete melhorar a precisão e a eficiência do processo de tomada de decisão, auxiliando os profissionais de saúde a oferecerem um tratamento mais direcionado e eficaz aos pacientes.
