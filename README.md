<<<<<<< HEAD
Pacote
teste
=======
Pacote agora vai ou nao
>>>>>>> 423e216668dde282e5c92a29f233435cffe9ef3d

./mvnw package && java -jar target/validarCpf.jar

docker build -t alexandreponte/validadorcpfjava -f Dockerfile .


<<<<<<< HEAD
docker run -d -p 8090:8080 --name validador-cpf-cshar alexandreponte/validadorcpfjava
=======
docker run -d -p 8090:8080 --name validador-cpf-java alexandreponte/validadorcpfjava
>>>>>>> 423e216668dde282e5c92a29f233435cffe9ef3d
