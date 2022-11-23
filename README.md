# DetectorDeEmocoes
Utilizando a rede neural yolov4 para detectar expressões faciais


![resultado](https://user-images.githubusercontent.com/103445424/203555838-9ac037fb-e814-46fc-ba5c-a28855eb7763.jpg)


As Big Techs como o Google e o Facebook tem acesso à camera do usuário, isso permite que elas rodem algoritmos de expressões faciais para saber se o usuário está feliz, triste ou curioso e ter um retorno sobre quais são as publicações mais efetivas para este usuário.

Este modelo pretende ser uma reconstrução simplificada desses algoritmos de expressões faciais. Foram utilizadas duas classes, triste e feliz. Fiz um banco de dados com as duas classes que se encontram neste repositório com o nome de obj.zip

A partir deste banco de dados, fiz um mapeamento em forma de quadrados de onde se encontram os rostos tristes e felizes para rodar a rede yolov4 com detecção e classificação de imagens.

Este projeto visa demonstrar que o problema do reconhecimento de expressões faciais e detecção de sentimentos pode ser feita de maneira razoavelmente simples e com um banco de dados pequeno.


Código base:

https://colab.research.google.com/drive/1zqRb08ljHvIIMR4fgAXeNy1kUtjDU85B

Para rotular imagens utilizei:

https://www.makesense.ai/

Tutorial de como utilizar a rede yolov4 no youtube:

https://www.youtube.com/watch?v=SCAgktactKE&t=748s


Este é um exercício proposto pelo professor Diego Bruno como parte do curso de Machine Learning da Digital Innovation One
