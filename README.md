## Otimização de Imagem Go no docker 🚀

<h1 align="center"> Docker e Go </h1> 

## 📝 Sobre o projeto

Desafio Go Fullcycle para criar uma imagem otimizada rodando em Go com menos de 2Mb de tamanho.

O objetivo principal do desafio realizar a otimização de uma imagem Go do docker que normalmente fica em torno de 778Mb

## 🔗 Tecnologias utilizadas

O presente projeto foi desenvolvido utilizando as seguintes tecnologias:
- [Go](https://go.dev/)
- [Docker](https://www.docker.com/)

## 🎯 Principais funcionalidades

- [x] exibir via CLI a mensagem "Full Cycle Rocks!"

## 📁 Como baixar a imagem e rodar o projeto 

1. baixar a imagem hospedad no Docker hub via terminal
```
docker pull leodf41/fullcycle
```

2. executar o comando no terminal
```
docker run leodf41/fullcycle
```

## Como executar o projeto baixando do github

1. clonar este repositório

2. executar o build da imagem via terminal
```
docker build -t <seu user>/fullcycle:dev .
```

3. executar o container om a imagem
```
docker run <seu user>/fullcycle
```

