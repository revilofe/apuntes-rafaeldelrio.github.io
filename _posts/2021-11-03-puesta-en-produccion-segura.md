---
title: "Puesta en producción segura"
permalink: /ceti/puesta-en-produccion-segura
categories:
  - PPS
tags:
  - General
# Relacionado con la tabla de contenidos
toc: true
toc_label: "Contenido"
toc_icon: "file-code"
---

Información sobre el módulo profesional de puesta en producción segura. Esta información se divide en libros recomendados, recursos, herramientas para aplicar conceptos, así como una propuesta de temario. Todo el contenido está supeditado a mejora, pues es solo una propuesta, y se espera que mejore con el tiempo con contribuciones de personas como tú. Si tienes algo interesante que puede mejorar, accede al github del proyecto y crea un pull request con la información. Gracias.

##### Propuesta de temario

En los siguientes enlaces se encuentran los contenidos, resultados de aprendizaje, criterios de evaluación y herramientas para trabajarlos y poder evaluarlos. Es solo una propuesta, pero puede servir de punto de partida inicial.

1. [Introducción al desarrollo seguro](/ceti/puesta-en-produccion-segura/introduccion-al-desarrollo-seguro)
2. [Testing web y móvil](/ceti/puesta-en-produccion-segura/testing-web-y-movil)
3. [Vectores de ataques y OWASP](/ceti/puesta-en-produccion-segura/vectores-de-ataque-y-owasp)
4. [Securización de sistemas web de información](/ceti/puesta-en-produccion-segura/securizacion-de-sistemas-web-de-informacion)
5. [Securización de aplicaciones móviles](/ceti/puesta-en-produccion-segura/securizacion-de-aplicaciones-moviles)
6. [Contenedores en docker](/ceti/puesta-en-produccion-segura/contenedores-en-docker)
7. [Integración continua/despliegue continuo (CI/CD)](/ceti/puesta-en-produccion-segura/ci-cd)
8. [Orquestadores con kubernetes](/ceti/puesta-en-produccion-segura/orquestadores-con-kubernetes)

##### Relación de unidades y resultados de aprendizaje

| Unidad | UD 1 | UD 2 | UD 3 | UD 4 | UD 5 | UD 6 | UD 7 | UD 8 |
| ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| RA 1   | X    | X    |      |      |      |      |      |      |
| RA 2   |      |      | X    |      |      |      |      |      |
| RA 3   |      |      |      | X    |      |      |      |      |
| RA 4   |      |      |      |      | X    |      |      |      |
| RA 5   |      |      |      |      |      | X    | X    | X    |

##### Libros

- [El libro de Ra-Ma de puesta en producción segura](https://www.ra-ma.es/libro/puesta-en-produccion-segura_140116/) puede ser un buen punto de partida para organizar la estructura del temario.

##### Recursos

- [Juego para introducir a la programación](https://www.codingame.com/start)

##### Herramientas

- [Git](https://git-scm.com/): nos permite controlar las versiones del código. Es una herramienta imprescindible en cualquier desarrollo.
- [Github actions](https://github.com/features/actions): nos permite realizar la integración continua y el despliegue continuo. Podemos generar `jobs`para la ejecución de los tests tras un commit, así como el despliegue automático de la nueva versión si cumple con los requisitos de calidad.
- [Docker](https://www.docker.com/): ideal como sistema de contenedores para aplicaciones. Tiene diversos usos. En este módulo se puede aplicar para despllegar aplicaciones dentro de contenedores para evitar que las vulnerabilidades web puedan afectar a los sistemas operativos o servicios subyacentes.
- [Kubernetes](https://kubernetes.io/es/): es un orquestador de contenedores. Nos permite controlar la salud de los distintos microservicios de la aplicación, desplegar o reducir su cantidad en función de la demanda, etc...

##### Contribuir

Se solicitan contribuciones. Típicamente se intenta tener los siguientes apartados en cada uno de los módulos profesionales:

- Teoría: en formato editable (como libreoffice, un .odt), o en documentos PDF
- Presentaciones: en formato editable (como libreoffice, un .odp), o en documentos PDF
- Ejercicios: un boletín de ejercicios para practicar en clases.
- Prácticas evaluables: una serie de prácticas evaluables.
- Exámenes: una serie de exámenes

Todas las contribuciones que se realicen deben ser teniendo en cuenta que en esta web se distribuirán bajo la licencia Creative Commons.
