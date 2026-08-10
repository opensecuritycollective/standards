# Auditoría de Aplicaciones Web

Metodología OSC para pruebas de seguridad en aplicaciones web autorizadas.

## Objetivo

Identificar, validar y documentar vulnerabilidades en aplicaciones web dentro del alcance contractual o VDP autorizado.

## Referencias

* OWASP Top 10
* OWASP Web Security Testing Guide (WSTG)

## Flujo resumido

1. Definir alcance, cuentas de prueba y reglas de engagement.
2. Mapear superficie de ataque (rutas, APIs, roles).
3. Pruebas controladas (inyección, authn/authz, sesión, logic bugs, etc.).
4. PoC mínima y no destructiva.
5. Clasificación CVSS y reporte.

## Restricciones

* Prohibido DoS, destrucción de datos o pivote fuera de alcance.
* Cumplir [DIVULGACION.md](https://github.com/opensecuritycollective/governance/blob/main/DIVULGACION.md).

## Estado

Documento base v1.0 — se ampliará con checklists WSTG adaptados a OSC.
