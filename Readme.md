Esse desafio é muito empolgante principalmente se você nunca trabalhou com a linguagem Go! Você terá que publicar uma imagem no docker hub. Quando executarmos:

docker run /codeeducation

Temos que ter o seguinte resultado: Code.education Rocks!

Lembrando que a Go Lang possui imagens oficiais prontas, vale a pena consultar o Docker Hub.

A imagem de nosso projeto Go precisa ter menos de 2MB =)

Build
```bash
    docker build -t kafernandesdev/fullcycle .
```
Pull
```bash
docker pull kafernandesdev/fullcycle
```

Executar o container

```bash
docker run --rm kafernandesdev/fullcycle
```