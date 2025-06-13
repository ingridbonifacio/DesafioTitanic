Aqui está o README com formatação clara para os títulos e conteúdo do texto:

---

# Titanic - Machine Learning from Disaster

Prever a sobrevivência dos passageiros do Titanic utilizando aprendizado de máquina.

## Índice
- [Introdução](#introdução)
- [Objetivo](#objetivo)
- [Dataset](#dataset)
- [Pré-processamento dos Dados](#pré-processamento-dos-dados)
- [Modelagem](#modelagem)
- [Resultados](#resultados)
- [Conclusão](#conclusão)

---

## Introdução

Esse projeto é uma solução para o desafio **"Titanic - Machine Learning from Disaster"** no Kaggle, um problema clássico de classificação em que o objetivo é prever se um passageiro sobreviveu ao naufrágio do RMS Titanic utilizando aprendizado de máquina.

## Objetivo

Desenvolver um modelo preditivo capaz de identificar a probabilidade de sobrevivência dos passageiros a partir de dados disponíveis, como idade, gênero, classe social, entre outros. Este projeto explora métodos de machine learning e técnicas de manipulação e análise de dados.

## Dataset

O conjunto de dados está disponível no [Kaggle Titanic dataset](https://www.kaggle.com/c/titanic/data) e contém as seguintes informações:

- **Sobrevivência:** 0 = Não, 1 = Sim
- **Classe:** Classe do passageiro (1ª, 2ª, ou 3ª)
- **Idade:** Idade do passageiro
- **Sexo**
- **SibSp:** Número de irmãos/cônjuges a bordo
- **Parch:** Número de pais/filhos a bordo
- **Ticket:** Número do ticket
- **Fare:** Tarifa paga pelo passageiro
- **Cabine:** Número da cabine
- **Embarque:** Porto de embarque (C = Cherbourg; Q = Queenstown; S = Southampton)

## Pré-processamento dos Dados

Para preparar os dados, as seguintes etapas foram seguidas:

1. **Tratamento de valores ausentes**
2. **Conversão de variáveis categóricas em numéricas**
3. **Criação de novas features**, como `FamilySize` e `IsAlone`
4. **Normalização e padronização** de variáveis numéricas

## Modelagem

Diversos algoritmos foram testados para determinar a precisão do modelo preditivo, incluindo:

- Regressão Logística
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gradient Boosting

### Avaliação

Os modelos foram avaliados utilizando métricas como **Acurácia** e **Validação Cruzada** para garantir a consistência dos resultados.

## Resultados

O modelo **Random Forest** foi o mais bem-sucedido.

np.mean(resultados)
0.8041457147175896

np.mean(resultados2)
0.7873121882400362

## Conclusão

Este projeto destaca técnicas essenciais de análise e engenharia de dados, além de comparações entre modelos clássicos de machine learning. A precisão obtida demonstra a capacidade dos modelos em aprender padrões importantes de sobrevivência com base nas características dos passageiros.
