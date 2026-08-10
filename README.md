# Estándares técnicos y metodologías — OSC

Este repositorio centraliza las **metodologías técnicas** y procedimientos operativos que **Open Security Collective** utiliza para auditorías precisas, repetibles y éticas.

## Marcos de referencia

* **Web:** OWASP Top 10 y WSTG.
* **Redes:** lineamientos OSSTMM.
* **Reporte / severidad:** CVSS v3.1/v4.0 y, cuando aplique, [vulnera-calc](https://github.com/opensecuritycollective/vulnera-calc).

## Fases de la investigación

1. **Reconocimiento (pasivo):** OSINT sin interacción directa con el objetivo.
2. **Enumeración (activa):** servicios, puertos y activos autorizados en el alcance.
3. **Análisis de vulnerabilidades:** automatizado + manual.
4. **Validación (PoC):** prueba mínima no destructiva.
5. **Reporte y triaje:** documentación técnica y puntuación CVSS.

Detalle por área:

* [Metodología de Reconocimiento (OSINT)](./RECON.md)
* [Auditoría de Aplicaciones Web](./WEB.md)
* [Seguridad en Infraestructura y Redes](./INFRA.md)

## Herramientas

Las herramientas OSS avaladas por el colectivo se listan en:

* [awesome-security-tools](https://github.com/opensecuritycollective/awesome-security-tools)

El uso de software “crackeado” está estrictamente prohibido en operaciones oficiales de OSC.

## Gobernanza

* [Manifiesto](https://github.com/opensecuritycollective/governance/blob/main/MANIFIESTO.md)
* [Política CVD](https://github.com/opensecuritycollective/governance/blob/main/DIVULGACION.md)
* [Código de conducta](https://github.com/opensecuritycollective/.github/blob/main/CODE_OF_CONDUCT.md)

## Licencia

[Apache License 2.0](./LICENSE)
