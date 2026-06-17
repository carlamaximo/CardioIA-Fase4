# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# Nome do projeto
Fase 4 - Assistente Cardiológico Virtual com Visão Computacional

## Nome do grupo
Grupo 56

## Integrantes: 
- <a href="https://www.linkedin.com/in/anacornachi/">Ana Cornachi</a>
- <a href="https://www.linkedin.com/in/carlamaximo/">Carla Máximo</a>

## Professores:
### Tutor(a) 
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/andregodoichiovato/">André Godoi Chiovato</a>

## Sobre o Projeto

O CardioIA é uma iniciativa voltada à aplicação de Inteligência Artificial na área da saúde. Nesta Fase 4, foi desenvolvido um protótipo de Assistente Cardiológico Virtual capaz de analisar imagens de ECG utilizando técnicas de Visão Computacional.

A solução realiza o pré-processamento das imagens, treinamento de modelos de Deep Learning e classificação automática de exames simulados, apoiando a interpretação de padrões cardíacos.

## Objetivos

* Aplicar técnicas de pré-processamento em imagens médicas.
* Implementar uma CNN treinada do zero.
* Implementar Transfer Learning utilizando ResNet50.
* Avaliar o desempenho dos modelos utilizando métricas de classificação.
* Apresentar os resultados em um protótipo simples e interpretável.

## Dataset

Foi utilizado um dataset público contendo imagens de ECG organizadas nas seguintes categorias:

* Abnormal Heartbeat
* Myocardial Infarction
* Normal
* Previous Myocardial Infarction

Total aproximado: 885 imagens.

## Tecnologias Utilizadas

* Python
* TensorFlow / Keras
* Scikit-Learn
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Arquiteturas Implementadas

### CNN Treinada do Zero

* Conv2D
* MaxPooling2D
* Dropout
* Dense
* Softmax

### Transfer Learning

* ResNet50 pré-treinada na ImageNet
* Camadas finais customizadas para classificação das imagens de ECG

## Métricas Avaliadas

* Accuracy
* Precision
* Recall
* F1-Score
* Matriz de Confusão

## Estrutura do Projeto

```text
CardioIA-Fase4/
│
├── CardioIA_Fase4.ipynb
├── dataset/
├── prints/
├── relatorio/
└── README.md
```

## Aviso

Este projeto possui finalidade exclusivamente acadêmica e educacional. Os resultados apresentados não devem ser utilizados para diagnóstico médico real.
