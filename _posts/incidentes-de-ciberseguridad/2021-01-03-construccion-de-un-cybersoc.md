---
title: "UD 3 - Construcción de un CyberSOC"
permalink: /ceti/incidentes-de-ciberseguridad/construccion-de-un-cybersoc
categories:
  - IC
tags:
  - Incidentes
# Relacionado con la tabla de contenidos
toc: true
toc_label: "Contenido"
toc_icon: "file-code"
---

#### Contenidos

Bloque 2 - Auditoría de incidentes de ciberseguridad:

- Controles, herramientas y mecanismos de monitorización, identificación, detección y alerta de incidentes: tipos y fuentes
- Clasificación, valoración, documentación, seguimiento inicial de incidentes de ciberseguridad.

#### Resultados de aprendizaje

2. Analiza incidentes de ciberseguridad utilizando herramientas, mecanismos de detección y alertas de seguridad.

##### Criterios de evaluación

- b) Se han establecido controles, herramientas y mecanismos de monitorización, identificación, detección y alerta de incidentes
- e) Se ha realizado una clasificación, valoración, documentación y seguimiento de los incidentes detectados dentro de la organización.

#### Herramientas y recursos para trabajar los conceptos

- **Criterio de evaluación b**: se puede montar un SIEM, con el stack de Elastic (ElasticSearch, Logstash y Kibana) para la monitorización de incidentes. Dado que el montaje del sistema es complejo, se recomienda emplear [la siguiente imagen de docker para ello](https://elk-docker.readthedocs.io/).
- **Criterio de evaluación e**: se puede montar [una herramienta de ticketing, como FIR,](https://github.com/certsocietegenerale/FIR/) para llevar el control de los incidentes, desde su origen hasta su resolución. Recomiendo que se despliegue con Docker, por lo que los alumnos deben haber visto Docker en este momento (aunque sea a nivel básico).
