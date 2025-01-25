# Detecção de Textos Tóxicos e Benignos com BERT

Este repositório apresenta um projeto que utiliza o modelo **BERT** para classificação de textos como **tóxicos** ou **benignos**. Este projeto foi desenvolvido como uma prova de conceito (PoC) para demonstrar a viabilidade de detectar linguagem tóxica de maneira automatizada.

## **Objetivo**

Desenvolver uma solução de IA baseada no modelo **BERT** para classificar textos em:
- **Tóxicos**: Textos com linguagem ofensiva, odiosa ou depreciativa.
- **Benignos**: Textos positivos ou neutros.

## **Funcionalidades**
- Classificação de textos em duas classes: tóxico e benigno.
- Gera pontuações de confiança para cada previsão.
- Treinamento do modelo com um dataset balanceado e variado.

## **Tecnologias Utilizadas**
- **Python 3.8+**
- **Hugging Face Transformers**: Framework para manipulação de modelos baseados em BERT.
- **Torch**: Biblioteca para treinamento e execução de modelos de machine learning.
- **scikit-learn**: Métricas de avaliação (F1-score, matriz de confusão).
- **Google Colab**: Ambiente para execução do treinamento com suporte a GPU.
