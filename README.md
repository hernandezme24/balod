# Números Reales — Presentación Web

Presentación interactiva de **Matemática · Unidad 01: Números Reales** (estructura, orden y completitud de la recta), con estética clásica inspirada en el *Álgebra de Baldor*: pergamino, tinta sepia, dorado envejecido, rojo carmesí y ornamentos tipográficos de libro académico.

## Contenido (12 láminas)

1. Portada
2. La Recta Real
3. Taxonomía de los Números (ℕ ⊂ ℤ ⊂ ℚ ⊂ ℝ)
4. Análisis Decimal y Fraccionario
5. Construcción Geométrica de √2
6. Orden Denso
7. Un Cuerpo Ordenado
8. Tramos Continuos (intervalos)
9. El Valor Absoluto Mide Distancia
10. Radicales y Notación Científica
11. Completitud
12. Síntesis

## Controles

| Acción | Tecla / botón |
|---|---|
| Siguiente / anterior | → / ← (o barra espaciadora) |
| Primera / última | Inicio / Fin |
| Pantalla completa | F |
| Índice de láminas | Botón **MENÚ** |
| Reproducción automática | Botón **AUTO** |

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `numeros-reales`).
2. Sube `index.html`, `baldor.css` y `README.md` a la raíz del repositorio (botón **Add file → Upload files**).
3. Ve a **Settings → Pages**.
4. En **Source** elige **Deploy from a branch**, rama `main`, carpeta `/ (root)` y pulsa **Save**.
5. En uno o dos minutos la presentación estará en:
   `https://<tu-usuario>.github.io/numeros-reales/`

## Notas técnicas

## Estructura de archivos

| Archivo | Descripción |
|---|---|
| `index.html` | Estructura, contenido de las 12 láminas y JavaScript de navegación. |
| `baldor.css` | Sistema de estilos "Álgebra de Baldor": variables de paleta (pergamino, sepia, dorado, carmesí), tipografía, marcos ornamentales, tablas, fórmulas y diseño responsivo. |
| `README.md` | Este documento. |

## Notas técnicas

- `index.html` enlaza la hoja de estilos externa con `<link rel="stylesheet" href="baldor.css">`; ambos archivos deben estar en la misma carpeta.
- Para cambiar la paleta basta con editar las variables de `:root` en `baldor.css`.
- Dependencias externas por CDN (importadas desde `baldor.css`): Google Fonts (EB Garamond, JetBrains Mono) y Material Symbols.
- No requiere compilación; también funciona abriendo `index.html` directamente en el navegador.
