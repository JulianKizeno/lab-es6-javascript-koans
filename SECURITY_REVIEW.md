# Revisión de seguridad — 2026-10-24

Repositorio: `JulianKizeno/lab-es6-javascript-koans`. Rama: `security/review-2026-10-24`.

## Correcciones

- Remove unused jQuery with known prototype pollution/HTML parsing vulnerabilities (CVE-2019-11358, CVE-2020-11022/11023)

## Auditoría npm después de los cambios

Sin manifiesto npm aplicable; la revisión de bibliotecas vendorizadas se describe en las correcciones.

## Verificación

- Revisión estática del cambio; sin prueba de despliegue ni verificación de servicios externos.

## Límites y configuración

- La auditoría cubre el árbol npm resuelto, no demuestra ausencia de vulnerabilidades de lógica, infraestructura o servicios externos. No se ha desplegado ni fusionado este cambio.
