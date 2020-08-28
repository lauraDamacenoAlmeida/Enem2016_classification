# Descubra quem fez o ENEM 2016 apenas para treino

Este projeto foi construído para descobrir quais estudantes estão fazendo a prova apenas para treino, e ele foi solicitado para o bootcamp realizado na codenation.

## Requisitos

Você precisará de python 3.6 (ou superior) e do gerenciador de pacotes pip.

Para instalar os requisitos, execute o comando como no exemplo abaixo:

    pip install -r requirements.txt

## Detalhes

O contexto do desafio gira em torno dos resultados do ENEM 2016 (disponíveis no arquivo train.csv). Este arquivo, e apenas ele, deve ser utilizado para todos os desafios. Qualquer dúvida a respeito das colunas, consulte o [Dicionário dos Microdados do Enem 2016](https://s3-us-west-1.amazonaws.com/acceleration-assets-highway/data-science/dicionario-de-dados.zip).

Alguns estudantes decidem realizar prova do ENEM de forma precoce, como um teste (coluna IN_TREINEIRO). E para identificá-los foi criado um modelo de classificação binária retornando “0” se não é treineiro ou “1” se é treineiro.

A resposta será salva em um arquivo chamado answer.csv com duas colunas: `NU_INSCRICAO` e `IN_TREINEIRO`.
