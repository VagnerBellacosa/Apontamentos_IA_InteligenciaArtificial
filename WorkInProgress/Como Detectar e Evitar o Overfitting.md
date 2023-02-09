**Fundamentos de Inteligência Artificial**



![img](https://lwfiles000.mycourse.app/datascienceacademy-public/ebook/f97876241139635c4a28bbe51d49ab5d/image1.png)



**Como Detectar e Evitar o Overfitting?**

**
**





   Para entender a precisão dos modelos de aprendizado de máquina, é importante testar a adequação do modelo. A validação cruzada K-fold é uma das técnicas mais populares para avaliar a precisão do modelo.





   Na validação cruzada de k-fold, (fold = dobras), os dados são divididos em k subconjuntos de tamanhos iguais, também chamados de "dobras". Uma das dobras k atuará como o conjunto de teste, também conhecido como conjunto de validação ou conjunto de validação, e as dobras restantes treinarão o modelo.





   Esse processo se repete até que cada uma das dobras tenha agido como uma dobra de retenção. Após cada avaliação, uma pontuação é retida e, quando todas as iterações são concluídas, é calculada a média das pontuações para avaliar o desempenho do modelo geral.





   Embora o uso de um modelo linear nos ajude a evitar **Overfitting**, muitos problemas do mundo real são não lineares. Além de entender como detectar o overfitting, é importante entender como evitar o overfitting completamente. Abaixo estão algumas técnicas que você pode usar para **evitar o overfitting**:







- **Fazer Parada Antecipada**: como mencionamos anteriormente, esse método busca pausar o treinamento antes que o modelo comece a aprender o ruído dentro do modelo. Essa abordagem corre o risco de interromper o processo de treinamento muito cedo, levando ao problema oposto de subajuste. Encontrar o “ponto ideal” entre underfitting e overfitting é o objetivo final aqui.

- **Treinar Com Mais Dados**: Expandir o conjunto de treinamento para incluir mais dados pode aumentar a precisão do modelo, fornecendo mais oportunidades para analisar a relação dominante entre as variáveis de entrada e saída. Dito isso, esse é um método mais eficaz quando dados limpos e relevantes são injetados no modelo. Caso contrário, você poderia simplesmente continuar a adicionar mais complexidade ao modelo, fazendo com que ele superajustasse.

- **Aumentar os Dados**: embora seja melhor injetar dados limpos e relevantes em seus dados de treinamento, às vezes dados ruidosos são adicionados para tornar um modelo mais estável. No entanto, esse método deve ser feito com moderação.

- **Fazer a Seleção de Recursos**: ao construir um modelo, você terá vários parâmetros ou recursos que são usados para prever um determinado resultado, mas muitas vezes esses recursos podem ser redundantes. A seleção de recursos é o processo de identificar os recursos mais importantes nos dados de treinamento e, em seguida, eliminar os irrelevantes ou redundantes. Isso é comumente confundido com redução de dimensionalidade, mas é diferente. No entanto, ambos os métodos ajudam a simplificar seu modelo para estabelecer a tendência dominante nos dados.

- **Realizar a Regularização**: Se o overfitting ocorre quando um modelo é muito complexo, faz sentido reduzirmos o número de recursos. Mas e se não soubermos quais entradas eliminar durante o processo de seleção de recursos? Se não soubermos quais recursos remover de nosso modelo, os métodos de regularização podem ser particularmente úteis. A regularização aplica uma “penalidade” aos parâmetros de entrada com coeficientes maiores, o que subsequentemente limita a quantidade de variação no modelo. Embora existam vários métodos de regularização, como regularização L1, regularização Lasso e dropout, todos procuram identificar e reduzir o ruído nos dados.

- **Utilizar Métodos Ensemble**: Os métodos de aprendizado ensemble são compostos por um conjunto de classificadores, por exemplo, árvores de decisão, e suas previsões são agregadas para identificar o resultado mais popular. Os métodos de ensemble mais conhecidos são **bagging** e **boosting**. No bagging, uma amostra aleatória de dados em um conjunto de treinamento é selecionada com substituição, o que significa que os pontos de dados individuais podem ser escolhidos mais de uma vez. Depois que várias amostras de dados são geradas, esses modelos são treinados independentemente e dependendo do tipo de tarefa, ou seja, regressão ou classificação, a média ou a maioria dessas previsões produz uma estimativa mais precisa. Isso é comumente usado para reduzir a variação dentro de um conjunto de dados ruidoso.



























Muito Obrigado!







Equipe DSA