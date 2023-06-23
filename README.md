# Trabalho de Introducao a Matematica Computacional.
O código apresentado em Python trata-se da representação da imagem de WebCam do computador, se utilizando de algumas bibliotecas para manipulação de imagens, como o OpenCv, NumPy e Matplotlib. 
Também fazendo referência a uma biblioteca especifica do Google Collab para exibição de imagens. 
Basicamente essas primeiras linhas de código (Conversão de imagem RGB em imagem Grayscale) estão relacionadas á leitura e exibição de uma imagem usando uma biblioteca OpenCV img=cv2.imread('t1.jpg',1').
A função 'cv2.imread()'é usada para ler uma imagem de um arquivo, nesse caso, o arquivo é chamado de "t1.jpg". 
O segundo parâmetro, que é igual a 1, especifica que a imagem deve ser carregada em cores, ou armazenado na variável ímg'.2. O split(img) serve para separar as linhas string introduzidas no código. Tudo isso para então gerando cv2_imshow(img_greyscale_pondered) para gerar a imagem em pretoo e branco. Como foi mostrado na aula no laboratório,onde o professor utilizou-se da WebCam de seu computador e através dela foi possível mudar as cores da imagem, nesse caso, do vídeo. Já na segunda parte do código ele estará inativo com aspas, no caso se retirar as aspas ele vai estar gerando uma imagem colorida em um ambiente de Python local. 
E na terceira parte desse código, ele faz o processo de uma aplicação de conversão ponderada em uma imagem colorida para poder então converte-la em preto e branco.
Com relação a segunda sequência de códigos (Transformações), cada parte desses códigos estão relacionados á criação do negativo de uma imagem, ou seja, vai pegar uma imagem e irá converte-la em uma imagem negativa.

E então, na outra parte na sequência do código, está relacionado aos ajustes de brilho de uma imagem. 

Na última sequência de códigos (Filtros Especiais), cada parte desse código está relacionada à aplicação de um filtro de suavização em uma imagem, processando e executando tudo e dando forma a imagem através do kernel=np.ones, utilizando o recurso para alterar a intensidade dos pixels de uma imagem, sendo esse o filter2D, mostrando a imagem no final com o comando cv2_imshow.
Concluindo, todos esses códigos são basicamente códigos que alteram e convertem as cores de imagem para depois serem mostradas.



