# Crear Matriz de Cobertura entre Requerimientos y Casos de Prueba

## Objetivo

Generar una matriz que permita validar si los requerimientos están cubiertos por casos de prueba.

## Cuándo usarlo

Úsalo cuando necesites revisar cobertura funcional antes de ejecutar pruebas o antes de enviar una conformidad QA.

## Prompt

Actúa como un QA Lead con experiencia en trazabilidad y cobertura de pruebas.

Analiza los siguientes requerimientos y casos de prueba. Genera una matriz de cobertura e identifica gaps.

Requerimientos:

```text
[PEGA AQUÍ LOS REQUERIMIENTOS]
```

Casos de prueba existentes:

```text
[PEGA AQUÍ LOS CASOS DE PRUEBA]
```

## Formato de salida esperado

| ID Requerimiento | Descripción | Caso(s) asociado(s) | Nivel de cobertura | Gap identificado | Recomendación |
|---|---|---|---|---|---|

## Variables a reemplazar

- `[PEGA AQUÍ LOS REQUERIMIENTOS]`
- `[PEGA AQUÍ LOS CASOS DE PRUEBA]`
