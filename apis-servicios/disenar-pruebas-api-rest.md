# Diseñar Pruebas para API REST

## Objetivo

Generar escenarios de prueba para validar un servicio API REST.

## Cuándo usarlo

Úsalo cuando tengas un endpoint, Swagger, contrato o documentación de API y necesites casos de prueba.

## Prompt

Actúa como un QA Engineer especializado en API Testing.

Diseña casos de prueba para el siguiente servicio API REST.

Información del API:

```text
[PEGA AQUÍ ENDPOINT, MÉTODO, REQUEST, RESPONSE O SWAGGER]
```

Considera:

- Casos exitosos.
- Validaciones de campos obligatorios.
- Validaciones de tipos de dato.
- Códigos HTTP.
- Mensajes de error.
- Seguridad/autenticación.
- Casos negativos.
- Casos límite.

## Formato de salida esperado

| ID | Escenario | Método | Endpoint | Request/Data | Resultado esperado | Código HTTP esperado | Tipo de prueba | Observaciones |
|---|---|---|---|---|---|---|---|---|

## Variables a reemplazar

- `[PEGA AQUÍ ENDPOINT, MÉTODO, REQUEST, RESPONSE O SWAGGER]`
