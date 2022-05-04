# conversao-distancia

Desafio Docker

Passos para criar o container da aplicação em Python:

* Criar o arquivo dockerfile utilizando a imagem do python como base.

* Rodar o comando **"docker build -t _\<imagem:versao\>_ ."** para criar a imagem onde:

1. _\<imagem:versao\>_ = É o nome da imagem e sua versão seguindo a convensão id_docker/nome:v1.

* Rodar o comando **"docker container run -d -p 5000:5000 --name _\<container\>_ _\<imagem:versao\>_"** onde:

1. _\<container\>_ = nome do container.

2. _\<imagem:versao\>_ = O nome da imagem criada e sua versão.

* Acessar o aplicativo pelo browser no camlinho localhost:5000