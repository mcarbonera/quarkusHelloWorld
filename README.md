Hello World de um projeto Quarkus.

Instruções para gerar um ambiente de desenvolvimento em container (dev container).

```
-> Instalar extensão "Remote - Containers"
-> Abrir pasta do projeto em container configurado para Java 11 e Gradle.
-> Instalar extensão Quarkus Tools for Visual Studio (dentro do container de desenvolvimento).
-> Utilizar o "Quarkus Tools" para gerar o projeto (essa etapa utiliza a jdk Java instalada no container, não
sendo necessário instalar na máquina host).
-> Rodar o comando ./gradlew quarkusDev dentro do container.
```

Devem ter mais detalhes que eu ainda não compreendi. Mas por enquanto é isso.
