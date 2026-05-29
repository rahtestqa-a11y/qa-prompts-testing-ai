# Generar Escenarios Gherkin

## Objetivo

Convertir un requerimiento o historia de usuario en escenarios Gherkin usando Given, When, Then.

## Cuándo usarlo

Úsalo cuando necesites documentar escenarios para BDD, automatización o trazabilidad funcional.

## Prompt

Actúa como un QA Engineer con experiencia en BDD y diseño de pruebas.

Analiza la siguiente historia de usuario o requerimiento y genera escenarios Gherkin claros.

Información:

```text
[PEGA AQUÍ LA HISTORIA DE USUARIO O REQUERIMIENTO]
```

Considera:

- Escenario exitoso.
- Escenarios negativos.
- Validaciones de campos obligatorios.
- Reglas de negocio.
- Mensajes esperados del sistema.

## Formato de salida esperado

```gherkin
Feature: [NOMBRE DE LA FUNCIONALIDAD]

Background:
  Given [PRECONDICIÓN GENERAL]

Scenario: [NOMBRE DEL ESCENARIO]
  Given [CONTEXTO]
  When [ACCIÓN]
  Then [RESULTADO ESPERADO]
```

## Variables a reemplazar

- `[PEGA AQUÍ LA HISTORIA DE USUARIO O REQUERIMIENTO]`
- `[NOMBRE DE LA FUNCIONALIDAD]`
- `[PRECONDICIÓN GENERAL]`
