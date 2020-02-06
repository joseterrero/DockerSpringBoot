# DockerSpringBoot

## 1. Necesitaremos un fichero Dockerfile situado en la carpeta raiz del proyecto

## 2. En la carpeta 'target' crearemos dentro una carpeta llamada 'dependency'

## 3. Ejecutamos el siguiente codigo para desempaquetar el jar en la carpeta dependency: mkdir -p target/dependency && (cd target/dependency; jar -xf ../*.jar)

## 4. Ejecutamos el siguiente codigo para crear la imagen: docker build -t springio/gs-spring-boot-docker .
