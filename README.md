## **Projeto de Regressão Linear para Prever Notas de Alunos**

### **1\. Introdução**

Este projeto tem como objetivo desenvolver um modelo de regressão linear para analisar a relação entre o tempo de estudo (em horas) e as notas de alunos. A regressão linear é uma técnica estatística que busca modelar a relação entre uma variável dependente (a nota do aluno) e uma ou mais variáveis independentes (o tempo de estudo).

### **2\. Metodologia**

1. **Importação das Bibliotecas:**

   * `numpy` foi utilizado para manipulação eficiente de arrays.  
   * `sklearn.linear_model` foi utilizado para criar e treinar o modelo de regressão linear.  
2. **Preparação dos Dados:**

   * Os dados de entrada (`x`) representam o tempo de estudo em horas e foram organizados em um array 2D, onde cada linha representa um aluno.  
   * Os dados de saída (`y`) representam as notas correspondentes a cada tempo de estudo.  
3. **Criação e Treinamento do Modelo:**

   * Um modelo de regressão linear foi instanciado utilizando `LinearRegression()`.  
   * O modelo foi treinado com os dados de entrada (`x`) e saída (`y`) utilizando o método `fit()`.  
4. **Previsão:**

   * O modelo treinado foi utilizado para prever a nota de um aluno que estudou 5 horas, demonstrando a aplicação do modelo em novas instâncias.  
5. **Visualização:**

   * A biblioteca `matplotlib.pyplot` foi utilizada para visualizar os dados e a reta de regressão.  
   * Um gráfico de dispersão foi gerado para mostrar os dados originais, e a reta de regressão foi sobreposta para ilustrar a relação linear modelada.

### **3\. Resultados**

* O modelo de regressão linear foi capaz de aprender a relação entre o tempo de estudo e as notas dos alunos.  
* A previsão para um aluno que estudou 5 horas foi de aproximadamente 67.5.  
* O gráfico de dispersão mostra uma tendência de aumento nas notas conforme o tempo de estudo aumenta, confirmando a adequação do modelo de regressão linear.

### **4\. Conclusão**

Este projeto demonstrou a aplicação da regressão linear para modelar a relação entre tempo de estudo e notas de alunos. Os resultados indicam que o tempo de estudo tem uma influência positiva nas notas, conforme previsto pelo modelo.
