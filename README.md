# Classificação de Imagens de Esportes Utilizando Redes Neurais Convolucionais

## Descrição

Este repositório contém o código e a documentação do projeto de classificação de imagens de esportes utilizando redes neurais convolucionais (CNNs). O objetivo é identificar o esporte representado em cada imagem de um dataset composto por 100 esportes distintos. Foram desenvolvidos dois modelos de CNNs: o primeiro utilizando uma arquitetura convolucional tradicional e o segundo com uma camada de concatenações paralelas similar à arquitetura GoogleLeNet.

## Motivação

Este projeto foi desenvolvido como parte da disciplina Redes Neurais Profundas do Programa de Pós Graduação em Engenharia Elétrica e de Computação (PPGEEC) da Universidade Federal de Goiás (UFG).

## Dataset

O dataset utilizado foi retirado do Kaggle (link: [Sports Classification Dataset](https://www.kaggle.com/datasets/gpiosenka/sports-classification)) e é composto por 14.493 imagens, distribuídas da seguinte forma:
- Treinamento: 13.493 imagens
- Teste: 500 imagens
- Validação: 500 imagens

## Modelos

### Modelo 1

Utiliza uma arquitetura convolucional tradicional com um total de 904.420 parâmetros e obteve uma acurácia no conjunto de validação: 92,20%

### Modelo 2

Inclui camadas com concatenações paralelas, similar à arquitetura GoogleLeNet, com um total de 3.024.788 parâmetros e obteve uma acurácia no conjunto de validação: 98,40%.

## Técnicas de Data Augmentation

Para aumentar a diversidade do conjunto de dados e melhorar a generalização dos modelos, foram aplicadas as seguintes técnicas de data augmentation:
- Giro horizontal
- Giro vertical
- Rotação de imagens
- Ajustes de brilho e contraste
- Translação
- Zoom
- Corte aleatório
