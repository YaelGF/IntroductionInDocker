# IntroductionInDocker

First example the containers

# How to Install


``` shell
git clone https://github.com/YaelGF/IntroductionInDocker.git
```

``` shell
cd docker
docker built -t php:v1 .
```

``` shell
cd ..
docker run -it -v $(pwd)/IntroductionInDocker:/web -p8080:8080 --name php_conteiner -h php php:v1
```

``` shell
docker start -i php_conteiner
cd web
php -S 0.0.0.0:8080
```

# Run the project

## Containers
![containers](/assets/contenedores.png)

## Docker
![docker](/assets/docker.png)

## Ubuntu
![ubuntu](/assets/Ubuntu.png)


# License
[Apache License 2.0](https://github.com/YaelGF/IntroductionInDocker/blob/main/LICENSE)