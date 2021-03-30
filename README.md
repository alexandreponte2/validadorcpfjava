Pacote

./mvnw package && java -jar target/validarCpf.jar

docker build -t alexandreponte/validadorcpfjava -f Dockerfile .


docker run -d -p 8090:8080 --name validador-cpf-java alexandreponte/validadorcpfjava
