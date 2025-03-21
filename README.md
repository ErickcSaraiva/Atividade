# Atividade
Lista de exercício valendo 1 ponto. Para fazer individual ou em dupla sobre matriz de contingência (Matriz da confusão) 
Data de entrega 21/03/20025 na coordenação do curso 

 Aluno: Erick da Costa Saraiva 
Matricula: 03326100

1. Um modelo de aprendizado de máquina foi treinado para identificar se imagens de raios X mostram sinais de pneumonia (Positivo) ou não (Negativo). Após testar o modelo em um conjunto de 200 exemplos, os seguintes resultados foram obtidos: 
 
•	50 imagens foram corretamente classificadas como Positivo. 
•	30 imagens foram erroneamente classificadas como Positivo (falsos positivos). 
•	90 imagens foram corretamente classificadas como Negativo. 
•	30 imagens foram erroneamente classificadas como Negativo (falsos negativos). 
Parte 1: Preencha a matriz de confusão 
Preencha a matriz de confusão com os valores acima. O formato da matriz é o seguinte: 
 
 	Predição Positivo 	Predição Negativo 
Classe Positiva 	 50(VP)	30(FN)
Classe Negativa 	30(FP)	90(VN)
 
Parte 2: Calcule as métricas de desempenho 
Com base na matriz preenchida, calcule as seguintes métricas: 
Acurácia: Proporção de predições corretas em relação ao total de exemplos. 
•  Acurácia mede a proporção total de previsões corretas. 
•  Fórmula: (VP + VN) / (VP + FP + VN + FN) 
•  Cálculo: (50 + 90) / (50 + 30 + 90 + 30) = 140 / 200 = 0.7 ou 70%
Precisão: Proporção de verdadeiros positivos em relação ao total de predições positivas. 
•  Precisão mede a proporção de previsões Positivas corretas em relação a todas as previsões Positivas. 
•  Fórmula: VP / (VP + FP) 
•  Cálculo: 50 / (50 + 30) = 50 / 80 = 0.625 ou 62.5%
Recall (ou Sensibilidade): Proporção de verdadeiros positivos em relação ao total de exemplos realmente positivos. 
•  Recall mede a proporção de casos Positivos reais que foram previstos corretamente pelo modelo. 
•  Fórmula: VP / (VP + FN) 
•  Calculo: 50 / (50 + 30) = 50 / 80 = 0.625 ou 62.5%
F1-Score: Média harmônica entre precisão e recall. 
•  O F1-Score é a média harmônica de precisão e recall. 
•  Formula: 2 * (Precisão * Recall) / (Precisão + Recall) 
•  Calculo: 2 * (0.625 * 0.625) / (0.625 + 0.625) = 0.625 ou 62.5%
Parte 3: Interpretação 
Com base nos resultados obtidos, responda: 
O modelo é mais propenso a produzir falsos positivos ou falsos negativos? Como isso pode impactar no contexto médico? 
Embora o modelo tenha produzido o mesmo número de falsos positivos e falsos negativos, o impacto dos falsos negativos é muito mais grave no contexto médico. Isso destaca a importância de aprimorar o modelo para reduzir os falsos negativos e garantir diagnósticos mais precisos.
O que poderia ser ajustado no modelo para melhorar essas métricas? 
Para melhorar as métricas do modelo, ajuste hiperparâmetros, use mais dados, equilibre classes e utilize validação cruzada.
 
 
 
