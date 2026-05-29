# Generar Casos de Prueba desde un Requerimiento

## Objetivo

Generar casos de prueba funcionales a partir de un requerimiento, historia de usuario o criterio de aceptación.

## Cuándo usarlo

Úsalo cuando tengas un requerimiento y necesites convertirlo en casos de prueba claros y ejecutables.

## Prompt

Actúa como un QA Engineer con experiencia en análisis de requerimientos y diseño de pruebas.

Tu objetivo es analizar el siguiente requerimiento y generar casos de prueba funcionales, negativos y de borde.

Requerimiento:

```text
[PEGA AQUÍ EL REQUERIMIENTO]
```

Considera lo siguiente:

- Identifica el flujo principal.
- Identifica escenarios alternos.
- Identifica escenarios negativos.
- Identifica validaciones obligatorias.
- Propón datos de prueba.
- Señala dudas o ambigüedades si existen.

## Formato de salida esperado

| ID | Escenario | Tipo de prueba | Precondiciones | Pasos | Resultado esperado | Datos de prueba | Prioridad | Observaciones |
|---|---|---|---|---|---|---|---|---|

## Variables a reemplazar

- `[PEGA AQUÍ EL REQUERIMIENTO]`: requerimiento, historia de usuario o criterio de aceptación.
