# Guacamole(Docker)

## Iniciar

Hay que levantar dos contenedores.
- Base de datos (en database).
- Aplicación web (en app).

___¡¡¡ Ingresar individualmente a cada directorio y seguir las instrucciones de sus README.md !!!.___

__Nota:__ Para una nueva instancia hay que inicializar la base de datos como se indica en el __README.md__.

## Versiones

    * Docker:           Docker version 20.10.9

### Instalación de docker en ubuntu 18.04/20.04

Fuente: [Instalación docker ubuntu](https://docs.docker.com/engine/install/ubuntu).

```bash
$ sudo apt-get update
$ sudo apt-get install \
    ca-certificates \
    curl \
    gnupg \
    lsb-release

$ curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg

$ echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

$ sudo apt-get update
$ sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
```
