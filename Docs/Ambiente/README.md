# Ambiente Linux

## Instalando Java
Antes de mais nada, Kotlin é rodado em cima da JVM, então você terá que ter instalado alguma versão da JDK.

Se você já tiver instalado o JDK ou tiver alguma experiencia com isso, pode pular esta parte, se não vou passar os comandos para instalar via terminal:

```bash
sudo add-apt-repository ppa:openjdk-r/ppa
sudo apt-get update
sudo apt-get install openjdk-11-jdk
```

Depois de seguir os comandos acima, podemos testar para ver se deu tudo certo com esse comando:
```
java -version
```

Se ocorreu tudo certo, em seu terminal deve ter aparecido algo como 
```
openjdk version "11.0.10" 2021-01-19
OpenJDK Runtime Environment (build 11.0.10+9-Ubuntu-0ubuntu1.20.10)
OpenJDK 64-Bit Server VM (build 11.0.10+9-Ubuntu-0ubuntu1.20.10, mixed mode, sharing)
```

Depois de concluído o processo de instalação do Java, podemos ir para o que interessa.

## Instalando Kotlin
Basta rodar o comando abaixo para instalar 

```bash
$ sudo snap install --classic kotlin
```

Ps: Essa instalação serve tanto para Ubuntu quanto para as distribuições baseadas nela (Mint, Pop Os, Zorin, etc)

Ps2: Caso não tenha snap instalado, basta clicar [aqui](https://snapcraft.io/docs/installing-snap-on-linux-mint) que vai te levar no tutorial oficial para instalar de qualquer distro linux



