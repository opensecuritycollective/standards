# Metodología de Auditoría y Evaluación de OSC

Este repositorio contiene los estándares técnicos y procedimientos operativos que el **Open Security Collective** utiliza para validar la seguridad de los sistemas investigados.

## Fases de la Investigación
Nuestra metodología se divide en 5 etapas críticas para garantizar resultados precisos y éticos:

1. **Reconocimiento (Passive Recon):** Recolección de información de fuentes abiertas (OSINT) sin interactuar directamente con los sistemas.
2. **Enumeración (Active Mapping):** Identificación de servicios, puertos y subdominios autorizados en el alcance (scope).
3. **Análisis de Vulnerabilidades:** Uso de herramientas automatizadas y análisis manual para identificar vectores de ataque.
4. **Validación (PoC):** Creación de una Prueba de Concepto no intrusiva para confirmar la existencia del fallo.
5. **Reporte y Triaje:** Documentación técnica siguiendo el estándar CVSS.

## Herramientas Estándar
Para asegurar la consistencia, nuestros investigadores utilizan herramientas de industria, incluyendo pero no limitado a:
* **Análisis Web:** Burp Suite, OWASP ZAP, Ffuf, etc.
* **Escaneo de Red:** Nmap, Masscan, Nuclei, Rustscan, etc.
* **OSINT:** Maltego, Shodan, Censys, etc.

---
*Nota: El uso de estas herramientas fuera de los entornos autorizados por el Manifiesto de OSC está estrictamente prohibido.*
