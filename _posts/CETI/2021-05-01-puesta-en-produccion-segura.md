---
title: "Puesta en producción segura"
permalink: /ceti/puesta-en-produccion-segura
categories:
  - PPS
tags:
  - General
---

Libros:

- [El libro de Ra-Ma de puesta en producción segura](https://www.ra-ma.es/libro/puesta-en-produccion-segura_140116/) puede ser un buen punto de partida para organizar la estructura del temario.

Recursos:

- [Juego para introducir a la programación](https://www.codingame.com/start)

Herramientas:

- [Git](https://git-scm.com/): nos permite controlar las versiones del código. Es una herramienta imprescindible en cualquier desarrollo.
- [Github actions](https://github.com/features/actions): nos permite realizar la integración continua y el despliegue continuo. Podemos generar `jobs`para la ejecución de los tests tras un commit, así como el despliegue automático de la nueva versión si cumple con los requisitos de calidad.
- [Docker](https://www.docker.com/): ideal como sistema de contenedores para aplicaciones. Tiene diversos usos. En este módulo se puede aplicar para despllegar aplicaciones dentro de contenedores para evitar que las vulnerabilidades web puedan afectar a los sistemas operativos o servicios subyacentes.

Propuesta de temario:

1. Introducción al desarrollo seguro
2. Testing web y móvil
3. Vectores de ataques y OWASP
4. Securización de sistemas web de información
5. Securización de aplicaciones móviles
6. Contenedores en docker
7. Orquestadores con kubernetes
8. Integración continuo/despliegue continuo (CI/CD)

Se solicitan contribuciones. Típicamente se intenta tener los siguientes apartados en cada uno de los módulos profesionales:

- Teoría: en formato editable (como libreoffice, un .odt), o en documentos PDF
- Presentaciones: en formato editable (como libreoffice, un .odp), o en documentos PDF
- Ejercicios: un boletín de ejercicios para practicar en clases.
- Prácticas evaluables: una serie de prácticas evaluables.
- Exámenes: una serie de exámenes

Todas las contribuciones que se realicen deben ser teniendo en cuenta que en esta web se distribuirán bajo la licencia Creative Commons.
