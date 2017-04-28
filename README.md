# lab-dw-2017-1
Laboratório de Desenvolvimento de Software para a Web de 2017/1.

## Obtendo o projeto

`git clone https://github.com/walison-moreira-ufg/lab-dw-2017-1`

## Executando a aplicação

`mvn org.apache.tomcat.maven:tomcat7-maven-plugin:run -Dmaven.tomcat.port=9090`

ou

`./mvnw tomcat7:run`

## Acessando a aplicação

Acesse `http://localhost:9090/exercicio em qualquer navegador.

Digite o peso em kg (Exemplo: 70), a altura com ponto (Exemplo: 1.73) e escolha o sexo.
Ao clicar em calcular, será aberta uma caixa de alerta com o resultado do calculo do IMC.

## Como o projeto foi construído

### "Embutindo" o Maven

Para que não seja necessário instalar e configurar o Maven, ele foi embutido no projeto com o seguinte comando:

`mvn io.takari:maven:0.3.3:wrapper -Dmaven=3.3.9`

## Pendências na documentação

* Documentar instalação do Git no Windows.
* Documentar instalação do Git no Linux.
* Documentar instalação do Java no Windows.
* Documentar instalação do Java no Linux.