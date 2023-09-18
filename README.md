# iac-atlantico-projeto03

Para criar a imagem e rodar a aplicacao execute:

docker build -t my-apache2 .
docker run -dit --name my-running-app -p 8080:80 my-apache2

