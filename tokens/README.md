# Design Tokens

## Objetivo

Esta carpeta contiene los valores fundamentales del sistema visual de Aberturas VC.

Los tokens funcionan como una fuente única de referencia para colores, tipografía y reglas visuales fundamentales.

---

## Tokens disponibles

### colors.json

Define los colores oficiales de la identidad.

### typography.json

Define las familias tipográficas y sus usos.

### spacing.json

Define los principios de espaciado y composición.

---

## Regla principal

Los valores definidos en esta carpeta tienen prioridad sobre interpretaciones visuales.

No inventar colores, tipografías o valores que no estén documentados.

Cuando un componente necesite un color, tipografía o regla visual, debe utilizar los tokens disponibles.

---

## Objetivo para IA

Claude debe consultar estos tokens antes de tomar decisiones visuales relacionadas con:

- Color.
- Tipografía.
- Espaciado.
- Contraste.
- Jerarquía visual.

No utilizar valores arbitrarios cuando exista un token correspondiente.