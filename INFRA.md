# Seguridad en Infraestructura y Redes

Metodología OSC para evaluación de infraestructura y redes autorizada.

## Objetivo

Identificar exposición de servicios, configuraciones inseguras y caminos de ataque en entornos de red/infra dentro del alcance.

## Referencias

* OSSTMM (como marco de referencia)
* Buenas prácticas de hardening y segmentación

## Flujo resumido

1. Confirmar alcance IP/CIDR y ventanas de prueba.
2. Enumeración autorizada de hosts y servicios.
3. Análisis de configuraciones y vulnerabilidades conocidas.
4. Validación cuidadosa (sin explotación destructiva).
5. Reporte con severidad CVSS y recomendaciones.

## Restricciones

* No realizar pruebas que degraden servicio salvo autorización explícita.
* Separar claramente hallazgos de reconocimiento vs. explotación.

## Estado

Documento base v1.0 — se ampliará con playbooks por tipo de entorno (cloud, on-prem, híbrido).
