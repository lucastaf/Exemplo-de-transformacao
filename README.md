# Exemplo-de-transformacao

O código utilizado para exemplo é escrito em Python utilizando a biblioteca OpenCV, que serve para realizar processamento de imagens, também é utilizado a biblioteca NumPy, para o uso de matrizes e a função “cv2_imshow” para exibição das imagens no google Colab. O código consiste em uma série de operações matriciais realizadas em uma imagem escolhida pelo programador. As bibliotecas são importadas na primeira parte do código. 
Na segunda parte do código temos exemplos da aplicação do código em ambiente desktop.
Na terceira parte do código, é gerada uma imagem com os canais RGB ponderados, para fazer isso os canais são separados em 3 variáveis B, G e R, depois as variáveis são somadas entre si por meio de uma média ponderada e o resultado é uma imagem preto e branco com prioridade dos verdes, depois nos verdes e com menos intensidade os vermelhos.
Na quarta parte do código é gerado uma imagem negativa, para fazer isso é definido que os pixels da imagem serão todos (255,255,255) (branco) e depois é subtraído o pixel original.
Na quinta parte do código temos variáveis ajustadas que, quando multiplicadas ou somadas a imagem original, são capazes de realizar ajustes de brilho e contraste.
Na sexta parte do código é utilizado uma operação mais complexa de desfoque, para isso é utilizado um Kernel 5X5 de valores 0.25 que quando define cada pixel como sendo a média dos pixels na sua volta multiplicados por 0.25.
