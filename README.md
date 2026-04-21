# Projeto YOLO (Detecção de Objetos)

## Visão geral

Este projeto tem como objetivo demonstrar a aplicação de um modelo de visão computacional baseado em YOLO (You Only Look Once) para detecção de objetos em imagens, utilizando o ambiente Google Colab e integração com o Google Drive.

O sistema foi treinado para identificar dois objetos distintos, avaliando seu desempenho por meio de diferentes configurações de treinamento.

## Estrutura do projeto

O dataset utilizado está organizado no Google Drive nas seguintes pastas:

* imagens de treino, validação e teste
* arquivos de anotação no formato YOLO (.txt)
* arquivo de configuração dataset.yaml

## Tecnologias utilizadas

- Python
- Google Colab
- Ultralytics YOLOv8
- Google Drive
- Make Sense IA (rotulagem)

## Experimentos realizados

Foram conduzidos dois treinamentos com diferentes configurações de épocas (30 e 60), com o objetivo de comparar o impacto desse parâmetro no desempenho do modelo.

## Avaliação do modelo

A avaliação foi realizada por meio de métricas padrão de detecção de objetos, como precisão, recall e mAP, além de testes com imagens externas ao dataset para análise de generalização.

## Observações importantes

- O notebook deve ser executado com o Google Drive corretamente montado
- O caminho do dataset pode precisar ser ajustado conforme o usuário
- Recomenda-se manter a estrutura de pastas original para evitar erros de leitura

## Objetivo final

Este projeto busca demonstrar, de forma prática, o potencial de modelos YOLO aplicados à detecção de objetos simples, evidenciando a importância da qualidade e diversidade do dataset no desempenho do modelo.
