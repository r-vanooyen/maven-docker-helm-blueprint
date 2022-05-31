# maven-docker-helm-blueprint

my blueprint for a maven webapp, with a dockerimage and helm chart

## content

- spring boot starter webapp
- dockerfile from https://spring.io/guides/gs/spring-boot-docker/

## install

```shell
helm repo add blueprint https://r-vanooyen.github.io/maven-docker-helm-blueprint/
helm repo update
helm install tmp blueprint/maven-docker-helm-blueprint
```
