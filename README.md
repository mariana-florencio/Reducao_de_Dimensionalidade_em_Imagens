# Conversão de Imagem para Tons de Cinza e Binárização
Este projeto tem como objetivo demonstrar como converter uma imagem colorida para tons de cinza, sem e com o uso da biblioteca NumPy, e como realizar a binarização (transformação para preto e branco) de uma imagem em tons de cinza. O processo é dividido em três partes principais:

1 - Conversão de imagem colorida para tons de cinza (sem usar NumPy)

2 - Conversão de imagem colorida para tons de cinza (utilizando NumPy)

3 - Binarização de uma imagem em tons de cinza

## Requisitos
Python 3.x
Bibliotecas:
PIL (Python Imaging Library) ou Pillow (fork do PIL)
NumPy (apenas para a versão com NumPy)

## Funcionalidades
1 - Conversão de Imagem Colorida para Tons de Cinza (Sem Usar NumPy)
Este código converte uma imagem colorida para tons de cinza utilizando a fórmula de luminância:

![image](https://github.com/user-attachments/assets/bd991471-651f-41ba-8409-9be668fa9c1a)
A imagem é carregada, convertida em uma matriz de pixels e, em seguida, a conversão para tons de cinza é realizada pixel a pixel. Por fim, a imagem em tons de cinza é salva no disco.

2 - Conversão de Imagem Colorida para Tons de Cinza (Com NumPy)
Neste exemplo, a conversão é feita utilizando a biblioteca NumPy, tornando o código mais eficiente. A imagem é convertida diretamente para uma matriz NumPy, e a operação de conversão para cinza é realizada em vetores. A imagem gerada é salva em formato .jpg.

3 - Binarização de Imagem em Tons de Cinza
A binarização converte uma imagem em tons de cinza para uma imagem binária (preto e branco). Os pixels são comparados a um valor de limiar (default: 128), e, dependendo do valor do pixel, ele se torna preto ou branco. Essa operação pode ser útil para análise de imagens ou para preparar imagens para reconhecimento de padrões.
