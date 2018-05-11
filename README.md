# Cyberlabs-Challange
Trata-se do desenvolvimento de uma inteligência artifical de classificação binária com o objetivo de distinguir entre Cervejas e Refrigerantes utilizando o programa Keras e Tensorflow para atender ao desafio proposto pela empresa Cyberlabs.
Todos os links encontram-se ao final deste relatório.

Foram utilizadas as seguintes bibliotecas:
Keras
TensorFlow

O dataset foi obtido por pesquisa no Google Images, utilizando um script em python para download do mesmo. O IDE utilizado foi o SPYDER.
Primeiro foi feito um "Image Augmented" para que o aprendizado nunca seja o mesmo e a máquina começe a decorar o dataset em vez de aprende-lo. 
A arquitetura da rede neural escolhida foi a LE_NET, que consiste em três camadas de "convnet" e "pooling" com tamanho das imagens (150,150).
O modo de saída escolhido foi o SOFTMAX para ajudar depois com a implementação de uma câmera, visto que o SIGMOID é uma saída binária. E para a utilização da câmera são necessárias três possibilidades de respostas (beer,soda e nothing). Dado a essa necessidade foi adionado ao dataset 200 imagens de selfies de pessoas.
Foram utilizadas 500 fotos de cervejas e 250 fotos de refrigerantes para o treino da máquina e um dataset de validação de 198 fotos de cervejas e 338 fotos de refrigerantes, tendo uma eficiência de 85% de acerto.

Para rodar a inteligência artificial basta baixar o dataset e, no código, escrever o endereço do dataset de treino e validação.


Link para dataset: 

