# Organización y revisión del repositorio

Fecha: 2026-09-19. Base inspeccionada: `1af43cc20e700296327ce4a00702063e5f85af98`.

## Clasificación conceptual

**Portafolio público**. Esta clasificación no modifica la visibilidad del repositorio.

## Metadatos propuestos para About

Descripción:

> Presentación de discusión técnica sobre seguridad estructural, inspección y lecciones del caso Real Plaza Trujillo.

Topics:

`portfolio`, `structural-engineering`, `structural-analysis`, `engineering-education`, `inspection`.

Estos metadatos son una propuesta documentada. No se han aplicado a la configuración de GitHub; fusionar este PR no los aplica automáticamente.

## Hallazgos y decisiones

- El README indicaba una carpeta imagenes/ inexistente; el inventario se corrigió sin mover archivos.
- La diapositiva 3 atribuye causas sin acompañarlas de evidencia primaria identificable; requiere revisión antes de uso pericial.
- Las comparaciones de normas carecen de trazabilidad completa de edición y cláusula; no se certifica su exactitud.
- El HTML tiene una etiqueta img sin cierre > en la imagen de Algo Centre Mall y elementos strong/p mal cerrados; corregir y comprobar visualmente en una mejora del sitio.
- No existen archivos de cálculo, planos o informes periciales dentro del árbol inspeccionado.
- Mantener las rutas actuales. Una futura migración a assets/imagenes/ debe actualizar referencias y verificar las 12 diapositivas.

## Higiene y documentación

Se añade un .gitignore limitado a temporales del sistema, archivos de bloqueo de Office y configuración local de secretos. No excluye modelos, resultados, CSV, imágenes ni documentos de ingeniería de forma global.

No se encontró licencia en la base inspeccionada. La selección de una licencia y los permisos de recursos de terceros quedan por definir por su titular.

No se eliminan ni renombran archivos. Comparación de SHA de los archivos existentes: sin duplicados exactos detectados dentro de este repositorio. Esta comprobación no identifica similitud semántica, visual ni duplicados entre repositorios.

## Verificación y límites

Revisión del árbol completo y de los archivos de texto pertinentes: README cuando existía, HTML, JavaScript y CSS según el repositorio. Se comprobó la ausencia de .gitignore y documentación complementaria en la base.

Los cambios de este PR se limitan a README.md, .gitignore y este documento. Se debe comprobar que el diff conserve los archivos originales restantes y que los enlaces relativos nuevos resuelvan.

No se ejecutaron aplicaciones, no se inspeccionaron visualmente imágenes o presentaciones y no se validaron resultados de ingeniería. Las propuestas funcionales y de revisión técnica anteriores quedan pendientes; no deben interpretarse como correcciones ya implementadas.
