# Cyberlabs-Challange
Trata-se do desenvolvimento de uma inteligência artifical de classificação binária com o objetivo de distinguir entre Cervejas e Refrigerantes utilizando o programa Keras e Tensorflow para atender ao desafio proposto pela empresa Cyberlabs.
Todos os links encontram-se ao final deste relatório.

Foram utilizadas as seguintes bibliotecas:
Keras,
TensorFlow.


O dataset foi obtido por pesquisa no Google Images, utilizando um script em python para download do mesmo. O IDE utilizado foi o SPYDER.
Primeiro foi feito um "Image Augmented" para que o aprendizado nunca seja o mesmo e a máquina começe a decorar o dataset em vez de aprende-lo. 
A arquitetura da rede neural escolhida foi a LE_NET, que consiste em três camadas de "convnet" e "pooling" com tamanho das imagens (150,150).
O modo de saída escolhido foi o SOFTMAX.Foram utilizadas 500 fotos de cervejas e 500 fotos de refrigerantes para o treino da máquina e um dataset de validação de 198 fotos de cervejas e 338 fotos de refrigerantes, tendo uma eficiência de 97% de acerto.

Para rodar a inteligência artificial basta baixar o dataset e, no código, escrever o endereço do dataset de treino e validação.

Link para dataset: https://www.dropbox.com/s/llkvgbwdemc1f6z/beer%20and%20soda.zip?dl=0

