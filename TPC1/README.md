# TPC1 - Somador ON/Off (Data: 2025-02-07)

## Resumo

**Objetivo:** Criar, em Python, um programa 'somador' que deve somar todos os números que estejam presentes no texto recebido por input.

**Explicação das Funcionalidades:**

1. Quando encontra a palavra **'Off'** (case-insensitive), a função de somar é desligada / posta em pausa.
2. Quando encontra a palavra **'On'** (case-insensitive), a função de somar é ligada / retomada.
3. Sempre que encontrar o sinal **'='** deve ser efetuado um print do total atual da soma para o stdout. A nenhum ponto do programa deve-se dar reset ao total da soma. Após o print o somador continua a somar como se nada tivesse acontecido.


## Restrições da Implementação



## Resultados

1. [Somador (Python)](somador.py)
2. [Ficheiro de Teste](Teste-Somador.txt)

## Como Correr o Programa

Para o programa receber um ficheiro de texto como input (maneira recomendada de interagir com o somador), sugere-se usar o seguinte comando:

> cat ficheiro-de-teste.txt | python3 somador.py

Caso queira correr o programa em modo _debug_ (indo ao ficheiro **somador.py**, na linha 89, substituir **"debug=False"** por **"debug=True"**), recomenda-se guardar o _output_ num ficheiro de texto para facilitar a análise:

> cat ficheiro-de-teste.txt | python3 somador.py > output.txt

## Autor

João Augusto Macedo Moreira A93326