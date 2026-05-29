# Identificar Gaps y Ambigüedades en Requerimientos

## Objetivo

Detectar puntos no claros, incompletos o riesgosos en un requerimiento antes del diseño o ejecución de pruebas.

## Cuándo usarlo

Úsalo durante la etapa de análisis QA, refinamiento, revisión de historias de usuario o revisión de documentación funcional.

## Prompt

Actúa como un QA Engineer con experiencia en análisis de requerimientos.

Analiza el siguiente requerimiento e identifica gaps, ambigüedades, riesgos y preguntas para el equipo funcional o negocio.

Requerimiento:

```text
[PEGA AQUÍ EL REQUERIMIENTO]
```

Evalúa:

- Reglas de negocio no claras.
- Campos obligatorios no definidos.
- Validaciones faltantes.
- Flujos alternos no documentados.
- Mensajes del sistema no especificados.
- Integraciones no detalladas.
- Casos límite no considerados.

## Formato de salida esperado

| ID | Tipo | Descripción del gap o ambigüedad | Riesgo | Pregunta sugerida | Impacto QA |
|---|---|---|---|---|---|

## Variables a reemplazar

- `[PEGA AQUÍ EL REQUERIMIENTO]`
