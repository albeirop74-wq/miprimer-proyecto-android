# Mi primer proyecto Android

Pantalla de bienvenida multilenguaje (ES por defecto, EN, FR, DE) con fondo nine-patch
y diseño adaptable a distintos tamaños y orientaciones de pantalla.

- **Idiomas:** `res/values` (es), `values-en`, `values-fr`, `values-de`
- **Fondo:** `res/drawable-nodpi/background.9.png` (el Android no se deforma)
- **Pantallas:** ConstraintLayout con guías en porcentaje + `values-sw600dp` / `values-sw720dp`
- **Orientación:** el mismo layout funciona en vertical y horizontal
