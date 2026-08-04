# DECISION_TREE

# Objetivo

Este documento ayuda a Claude a seleccionar automáticamente el patrón y los componentes correctos según el pedido del usuario.

Nunca comenzar un diseño sin recorrer este árbol de decisiones.

---

# PASO 1

¿Qué tipo de contenido solicita el usuario?

IF Instagram Feed

→ Continuar

IF Reel

→ Utilizar PATTERN_INSTAGRAM_REEL

IF Story

→ Utilizar PATTERN_INSTAGRAM_STORY

IF Carrusel

→ Utilizar PATTERN_INSTAGRAM_CAROUSEL

---

# PASO 2

¿Cuál es el objetivo?

IF Mostrar una obra

→ PATTERN_INSTAGRAM_PROJECT

IF Mostrar beneficios

→ PATTERN_INSTAGRAM_BENEFITS

IF Presentar un producto

→ PATTERN_INSTAGRAM_PRODUCT

IF Hablar de la empresa

→ PATTERN_INSTAGRAM_CORPORATE

IF Mostrar una instalación

→ PATTERN_INSTAGRAM_INSTALLATION

IF Presentar un proyecto destacado

→ PATTERN_INSTAGRAM_HERO

---

# PASO 3

¿Qué fotografía utilizar?

Prioridad:

1. Obras reales de Aberturas VC.
2. Fotografías propias.
3. Material producido por el equipo.
4. Banco de imágenes relacionado con arquitectura (solo si no existe material propio).

Nunca utilizar imágenes genéricas si existe contenido propio.

---

# PASO 4

Seleccionar componentes

Siempre utilizar:

- TITLE_PRIMARY
- LOGO_PLACEMENT_STANDARD

Opcionales según el caso:

- BADGE_PRIMARY
- CARD_STANDARD
- CTA_PRIMARY
- ICON_STANDARD

Nunca agregar componentes sin una función clara.

---

# PASO 5

Redactar el mensaje

Preguntarse:

¿Qué beneficio obtiene el cliente?

El beneficio debe aparecer antes que la característica técnica.

---

# PASO 6

Verificar identidad

Antes de finalizar comprobar:

□ Parece una publicación de Aberturas VC.

□ Mantiene la identidad visual.

□ Utiliza el tono correcto.

□ El logo funciona como firma.

□ La fotografía domina la composición.

□ Existe un único mensaje principal.

---

# SI EXISTEN DUDAS

Si existen varias opciones posibles:

Elegir siempre la alternativa más simple.

La consistencia tiene prioridad sobre la creatividad.

---

# REGLA FINAL

Nunca improvisar.

Si una decisión ya está documentada en este repositorio, seguir la documentación antes de inventar una solución.