Desafio de Docker realizado durante o treinamento "Formaçao Kubedev", ministrado pelo Fabricio Veronez pela Kubedev.io <https://kubedev.io/>.

O desafio consiste em criar uma imagem Docker de uma aplicação em NodeJS que foi passada pelo professor. 

Da aplicação, temos apenas o código fonte, sendo necessário entender como a linguagem trabalha para realizar a criação da imagem e em seguida executá-la em container na máquina local.

A aplicação utilizada nesse desafio é a "Conversão de Temperatura", acessível via web na porta 8080.

No repositório encontra-se o arquivo dockerfile utilizado para criação da imagem Docker, a qual está disponível em meu repositório dockerhub:
docker pull breinerhenrique/desafio-conversor-temperatura:v1