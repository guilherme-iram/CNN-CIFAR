﻿# Deep Learning com CNN

### **Conjunto de Dados CIFAR-10**

O Conjunto de Dados CIFAR (Canadian Institute for Advanced Research) é amplamente reconhecido e utilizado em visão computacional e aprendizado de máquina. Neste trabalho, utilizamos uma das versões mais conhecidas, o CIFAR-10.

### Descrição do CIFAR-10:

- **Imagens:** 60.000 imagens coloridas (RGB) de 32x32 pixels.
  
- **Classes:** As imagens estão distribuídas em 10 classes, cada uma representando um tipo específico de objeto ou animal.

   1. Avião     (classe 0)
   2. Automóvel (classe 1)
   3. Pássaro   (classe 2)
   4. Gato      (classe 3)
   5. Cervo     (classe 4)
   6. Cachorro  (classe 5)
   7. Sapo      (classe 6)
   8. Cavalo    (classe 7)
   9. Navio     (classe 8)
   10. Caminhão (classe 9)

- **Distribuição de Imagens por Classe:** Cada uma das 10 classes possui 6.000 imagens, proporcionando uma variedade representativa.

- **Conjunto de Treinamento e Teste:** O conjunto de treinamento contém 50.000 imagens, enquanto o conjunto de teste possui 10.000 imagens.

### Desafios e Relevância:

A diversidade de classes e a resolução relativamente baixa das imagens contribuem para tornar o CIFAR-10 um desafio envolvente para algoritmos de aprendizado de máquina, especialmente no contexto de classificação de imagens. Este conjunto de dados é comumente utilizado como benchmark em pesquisas e competições, proporcionando uma base sólida para avaliação de modelos e algoritmos relacionados à visão computacional.


### Proposta de resolução

Não utilizar nenhum modelo pré-treinado, mas sim uma rede simples e funcional, capaz de sem treinada com maior facilidade.

## Arquitetura da CNN
![Alt text](img//arquitetura-CNN.png)

## Curva de Loss
![Alt text](img//loss-cifar.png)

## Curva de Acurácia
![Alt text](img//acc-cifar.png)

## Matriz de Confusão e Resultados: Validação
![Alt text](img//mc-val.png)
 
 ## Relatório de Resultados - Validação

|           | Precision | Recall  | F1-Score | Support |
|-----------|-----------|---------|----------|---------|
| 0         | 0.8246    | 0.7557  | 0.7887   | 479     |
| 1         | 0.9465    | 0.8374  | 0.8886   | 486     |
| 2         | 0.8216    | 0.6667  | 0.7361   | 525     |
| 3         | 0.7039    | 0.7180  | 0.7109   | 500     |
| 4         | 0.7559    | 0.8261  | 0.7894   | 506     |
| 5         | 0.7071    | 0.7678  | 0.7362   | 478     |
| 6         | 0.8569    | 0.8787  | 0.8676   | 511     |
| 7         | 0.8676    | 0.8561  | 0.8618   | 528     |
| 8         | 0.8593    | 0.9121  | 0.8849   | 489     |
| 9         | 0.8265    | 0.9277  | 0.8742   | 498     |
| Accuracy  |           |         | 0.8144   | 5000    |
| Macro Avg | 0.8170    | 0.8146  | 0.8138   | 5000    |
| Weighted Avg | 0.8173 | 0.8144  | 0.8139   | 5000    |


## Matriz de Confusão e Resultados: Teste 
![Alt text](img//mc-test.png)

 ## Relatório de Resultados - Teste

|           | Precision | Recall  | F1-Score | Support |
|-----------|-----------|---------|----------|---------|
| 0         | 0.8462    | 0.7812  | 0.8124   | 521     |
| 1         | 0.9478    | 0.8482  | 0.8953   | 514     |
| 2         | 0.7867    | 0.6989  | 0.7402   | 475     |
| 3         | 0.7021    | 0.6600  | 0.6804   | 500     |
| 4         | 0.7500    | 0.8381  | 0.7916   | 494     |
| 5         | 0.7331    | 0.7682  | 0.7502   | 522     |
| 6         | 0.8709    | 0.8691  | 0.8700   | 489     |
| 7         | 0.8161    | 0.8178  | 0.8169   | 472     |
| 8         | 0.8587    | 0.9041  | 0.8808   | 511     |
| 9         | 0.8155    | 0.9243  | 0.8665   | 502     |
| Accuracy  |           |         | 0.8114   | 5000    |
| Macro Avg | 0.8127    | 0.8110  | 0.8104   | 5000    |
| Weighted Avg | 0.8130 | 0.8114  | 0.8108   | 5000    |
