+++
date = "2016-02-13T11:32:54-04:00"
description = ""
title = "Instalando Docker en Ubuntu 14.04"
+++

## ¿ Qué es Docker?
[Docker](https://www.docker.com) es un proyecto open source que automatiza el despliege de aplicaciones dentro de contenedores de software. mas información [aquí](http://tinyurl.com/mjecdxq).

##  Instalando Docker en Ubuntu.

Lo primero es actualizar todos los paquetes de Ubuntu antes de instalar algo.

    sudo apt-get update

Ahora instalemos docker con su respectivo paquete:

    sudo apt-get install docker.io

Linkeamos rutas

    sudo ln -sf /usr/bin/docker.io /usr/local/bin/docker
