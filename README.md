# Introdução ao Processamento Digital de Imagens
Este repositório contém o código-fonte e os resultados do módulo 2 do trabalho prático do curso de Processamento Digital de Imagens, ministrado pelo professor Leonardo. A data de entrega do trabalho é 08/06/2022.

## Descrição do Trabalho
O objetivo deste trabalho é implementar a DCT (Transformada Discreta de Cosseno) de 1D e 2D (direta e inversa) sem o uso de bibliotecas prontas para esse fim. O trabalho é dividido em três partes:

### 1. Processamento de Imagens
Nesta parte do trabalho, é necessário implementar um programa para processar uma imagem em níveis de cinza. O programa deve exibir o módulo normalizado da DCT da imagem, sem o nível DC, e o valor do nível DC. Além disso, o programa deve encontrar e exibir uma aproximação da imagem original preservando o coeficiente DC e os n coeficientes AC mais importantes, e zerando os demais. O parâmetro n é um inteiro no intervalo [0, RxC-1], onde R e C são as dimensões da imagem.

### 2. Filtro Passa-Baixas
Nesta parte do trabalho, é necessário implementar um programa para filtrar uma imagem utilizando um filtro de Butterworth passa-baixas no domínio da frequência. O programa deve calcular a função de transferência do filtro, que é dada por uma equação que depende da distância euclidiana do coeficiente até a origem, da distância de corte e da ordem do filtro. O resultado do filtro deve ser a imagem filtrada.

### 3. Filtro Passa-Baixas para Áudio
Nesta parte do trabalho, é necessário implementar um programa para filtrar um sinal de áudio em formato .wav utilizando um filtro de Butterworth passa-baixas no domínio da frequência. O programa deve calcular a função de transferência do filtro, que é dada por uma equação que depende da frequência do sinal, da frequência de corte e da ordem do filtro. O resultado do filtro deve ser o sinal de áudio filtrado.
