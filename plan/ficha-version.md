# Ficha de verificación de versiones · Grupo 05

## Zorin OS (VM gráfica · g05-grafica)

| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha | Zorin OS 18.1 Core, lanzada el 15 de abril de 2026 (serie 18 basada en Ubuntu 24.04 LTS) | https://zorin.com/os/details/ |
| Actualizaciones de seguridad | Hasta el 1 de junio de 2029 | https://zorin.com/os/details/ |
| Requisitos y VirtualBox | CPU 2 núcleos 1 GHz, 2 GB RAM (usaré 2-4 GB) y 15 GB disco (usaré 25 GB). Funciona en VirtualBox | https://help.zorin.com/docs/getting-started/system-requirements/ |
| Particionado manual | Sí, con la opción «Más opciones» (Something else) | https://help.zorin.com/docs/getting-started/install-zorin-os/ |
| Guía oficial Docker Engine | Sí, usa la guía oficial de Docker para familia Ubuntu | https://docs.docker.com/engine/install/ubuntu/ |
| Imagen base en Docker Hub | No tiene imagen oficial en Docker Hub; para el Dockerfile del grupo se usa Ubuntu | https://hub.docker.com/ |

## Fedora Server (VM consola · g05-consola)

| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha | Fedora Server 45, lanzada el 3 de noviembre de 2026 | https://fedoraproject.org/server/download |
| Actualizaciones de seguridad | Soporte de unos 13 meses (hasta diciembre de 2027) | https://docs.fedoraproject.org/en-US/releases/lifecycle/ |
| Requisitos y VirtualBox | 2 CPU, 2 GB RAM (3 GB en Sprint 3) y 20 GB disco (usaré 25 GB). Funciona en VirtualBox | https://docs.fedoraproject.org/en-US/fedora-server/installation/ |
| Particionado manual | Sí, en el instalador Anaconda con la opción «Personalizado» (Custom) | https://docs.fedoraproject.org/en-US/fedora-server/installation/interactive-local/ |
| Guía oficial Docker Engine | Sí, Docker tiene guía y repositorio oficial para Fedora | https://docs.docker.com/engine/install/fedora/ |
| Imagen base en Docker Hub | Sí, imagen oficial `fedora` (`fedora:45`) | https://hub.docker.com/_/fedora |

## Ubuntu (Imagen base del Dockerfile)

| Pregunta | Respuesta | Enlace |
|---|---|---|
| Versión elegida y fecha | Ubuntu 26.04.1 LTS (26.04 lanzada el 23 de abril de 2026) | https://ubuntu.com/about/release-cycle |
| Actualizaciones de seguridad | Hasta mayo de 2031 (5 años de soporte estándar LTS) | https://ubuntu.com/about/release-cycle |
| Requisitos y VirtualBox | Como contenedor corre sobre el kernel de la VM consola usando pocos MB | https://hub.docker.com/_/ubuntu |
| Particionado manual | No aplica como imagen de contenedor (en instalación VM sí lo permite) | https://documentation.ubuntu.com/server/ |
| Guía oficial Docker Engine | Sí, Docker tiene guía y repositorio oficial para Ubuntu | https://docs.docker.com/engine/install/ubuntu/ |
| Imagen base en Docker Hub | Sí, imagen oficial `ubuntu` (`ubuntu:26.04`) | https://hub.docker.com/_/ubuntu |
