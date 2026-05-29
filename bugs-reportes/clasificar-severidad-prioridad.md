# Clasificar Severidad y Prioridad de un Bug

## Objetivo

Ayudar a clasificar un defecto según su severidad, prioridad e impacto.

## Cuándo usarlo

Úsalo cuando no tengas claro si una incidencia debe clasificarse como crítica, alta, media o baja.

## Prompt

Actúa como un QA Lead con experiencia en gestión de defectos.

Analiza el siguiente defecto y sugiere severidad, prioridad e impacto.

Defecto:

```text
[PEGA AQUÍ EL DEFECTO]
```

Considera:

- Impacto funcional.
- Impacto en negocio.
- Frecuencia del error.
- Existencia de workaround.
- Usuarios afectados.
- Riesgo para salida a producción.

## Formato de salida esperado

| Criterio | Evaluación |
|---|---|
| Severidad sugerida | |
| Prioridad sugerida | |
| Impacto funcional | |
| Impacto en negocio | |
| Riesgo productivo | |
| Justificación | |
| Recomendación QA | |

## Variables a reemplazar

- `[PEGA AQUÍ EL DEFECTO]`
