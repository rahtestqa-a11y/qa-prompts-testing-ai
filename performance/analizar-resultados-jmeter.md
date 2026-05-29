# Analizar Resultados de JMeter

## Objetivo

Analizar resultados de pruebas de performance y generar conclusiones claras.

## Cuándo usarlo

Úsalo cuando tengas métricas de JMeter como promedio, percentiles, throughput, errores, min, max y desviación estándar.

## Prompt

Actúa como un QA Performance Tester.

Analiza los siguientes resultados de JMeter y genera conclusiones profesionales.

Resultados:

```text
[PEGA AQUÍ LOS RESULTADOS DE JMETER]
```

SLA o criterio esperado:

```text
[PEGA AQUÍ EL SLA O CRITERIO ESPERADO]
```

Considera:

- Tiempo promedio.
- Percentiles.
- Throughput.
- Porcentaje de error.
- Comportamiento bajo carga.
- Riesgo para producción.
- Recomendaciones.

## Formato de salida esperado

| Métrica | Resultado | Interpretación | Cumple SLA | Observación |
|---|---|---|---|---|

Incluye además:

- Resumen ejecutivo.
- Hallazgos.
- Riesgos.
- Recomendaciones.
- Conclusión QA.

## Variables a reemplazar

- `[PEGA AQUÍ LOS RESULTADOS DE JMETER]`
- `[PEGA AQUÍ EL SLA O CRITERIO ESPERADO]`
