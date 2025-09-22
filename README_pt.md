# Reconhecimento-de-Captcha
Reconhecimento de Captcha utilizando uma CNN

## Introdução

Este projeto tem como objetivo desenvolver um modelo de aprendizado de máquina para reconhecer imagens de CAPTCHA. CAPTCHAs (Completely Automated Public Turing test to tell Computers and Humans Apart) são usados para garantir que um usuário seja humano e não um computador. No entanto, eles podem ser difíceis de ler para os humanos ou também ser vulneráveis a ataques. O objetivo deste projeto é desenvolver um modelo que possa reconhecer imagens de CAPTCHA com boa precisão.

## Dados

Os dados utilizados neste projeto são um conjunto de imagens de CAPTCHA e suas respectivas labels. As imagens são no formato PNG e têm uma resolução de 180x50 pixels. Cada imagem contém 6 caracteres e as labels são os caracteres correspondentes na imagem. O conjunto de dados foi dividido em 80% para treinamento e 20% para teste.

Dados: https://www.dropbox.com/s/itfqyh1trx9da7b/dados.zip?dl=0

## Modelo

<img src="./media/graphviz.png"/> 

## Treinamento

O modelo é treinado usando o otimizador Adam com o loss "Categorical Crossentropy" e um tamanho de batch de 50. O treinamento é feito por 21 epochs.

## Conclusão

Este projeto demonstra a eficácia de usar uma CNN para reconhecer imagens de CAPTCHA. O modelo alcançou boa precisão e pode ser potencialmente usado em aplicações reais. Detalhes sobre o resultado podem ser encontrados no corpo do próprio notebook.
