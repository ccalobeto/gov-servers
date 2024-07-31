# [Reporte de servicios y aplicaciones del gobierno Peruano](https://www.geoidep.gob.pe/reporte-de-servicios-y-aplicaciones)

```mermaid
---
title: Reporte de servicios y aplicaciones
---
flowchart LR
PCM-->INEI
INEI-->C(Portal de Infraestructura de Datos Espaciales del INEI)
PCM-->Osinergmin
Osinergmin-->D(Mapa Energético Minero)
DEFENSA-->E(Instituto Geográfico Nacional)
E-->F(GeoPortal de Datos Fundamentales del IGN)
AMBIENTE-->G(Servicio Nacional de Meteorologia e Hidrologia del Perú)
G-->H(Geoportal SENAMHI)
STANDBY-->I(111)

click C "https://ide.inei.gob.pe/"
click D "http://gisem.osinergmin.gob.pe/menergetico/"
click F "https://www.idep.gob.pe/"
click H "http://idesep.senamhi.gob.pe/geovisoridesep"

```