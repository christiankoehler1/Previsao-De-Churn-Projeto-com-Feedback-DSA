# Projeto-com-Feedback-DSA

&nbsp;
Esse projeto faz parte da Formação de Cientista de Dados da Data Science Academy  
&nbsp;

***Nota:*** *Esse é um projeto fictício, de qualquer forma muito semelhante ao real problema enfrentado pelas organizações diariamente.*  
&nbsp;


## Prevendo o Nível de Satisfação dos Clientes do Banco  
&nbsp;





&nbsp;
![santander_custsat_red](https://user-images.githubusercontent.com/66925229/163041135-8e8661b1-c4e3-4d0f-80df-bd4c29ce96a4.png)
&nbsp;




&nbsp;
## Problema de negócio  
&nbsp;
Reduzir o número de clientes que deixam o banco no início do relacionamento.  

&nbsp;
## Objetivo
&nbsp;
O objetivo desse projeto é prever antecipadamente os clientes que estão insatisfeitos já no início do relacionamento,   
e assim adotar medidas proativas, melhorando assim o nível de satisfação dos mesmos e evitando a perda do cliente.   

Acurácia mínima requerida: 70%  

&nbsp;
## Etapas do Projeto:

1 - Definir o problema de negócio

2 - Realizar a coleta dos dados

3 - Preparar os dados

4 - Escolher o algoritmo

5 - Treinar o modelo

6 - Avaliar a acurácia (mínimo de 70%)


&nbsp;
**Dataset:** https://www.kaggle.com/c/santander-customer-satisfaction


&nbsp;
## Resultados Obtidos
&nbsp;
Com o problema de negócio já definido, a fase de coleta de dados se fez via importação de dados em arquivo .csv.
&nbsp;

&nbsp;
Na etapa de análise e preparação dos dados foi identificado que a base de clientes estava desbalanceada, sendo apenas quase 4% de clientes insatisfeitos.
Dessa forma o modelo seria enviezado. Sendo assim, foi aplicado o ***Near Miss*** que é algoritmo de undersampling que consiste em reduzir de forma aleatória os exemplos da classe majoritária, porém ele seleciona os exemplos com base na distância.
&nbsp;


&nbsp;
![image](https://user-images.githubusercontent.com/66925229/163063511-0e7c3b46-9b09-4a54-b62a-265448df491a.png)
&nbsp;



&nbsp;
Após a etapa de análise e preparação de dados concluída, seguimos para a fase de escolha e treinamento do algoritmo. Para o projeto em questão escolhi o modelo de Regressão Logística por sua simples aplicação e por não necessitar de grandes quantidades de recursos computacionais. 
&nbsp;

&nbsp;
O resultado do modelo foi de 81.440% de acurácia, já superior a meta para o desafio proposto que é de 70%.
&nbsp;

&nbsp;
De qualquer forma existia a possibilidade de melhoria da performance do modelo. Por conta disso, foram aplicadas técnicas de *Normalização* e *Padronização* aos dados e o modelo novamente processado.
&nbsp;

&nbsp;
E assim foi atingida a acurácia de 83.490% para o modelo.
&nbsp;

&nbsp;
## Próximos Passos:
- Aplicar a metodologia CRISP para projetos (modelo cíclico).
    - Apresentar novas features aos dados.
    - Aplicarmos outros modelos para melhorar a acurácia.    
&nbsp;




