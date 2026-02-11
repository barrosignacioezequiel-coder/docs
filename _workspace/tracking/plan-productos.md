# Plan de Trabajo — Tab Productos

## Objetivo

Completar cada capítulo NCM con páginas de **tipos de productos** (nivel general) que sean exitosos, vendidos o relevantes para importar desde China y revender al consumidor final en Argentina.

**Ejemplo:** En "Cap. 95 — Juguetes, juegos y deportes" dentro del dropdown Verano, las páginas podrían ser:
- `piletas-inflables.mdx`
- `juguetes-de-agua.mdx`
- `sets-de-playa.mdx`

Cada página documenta un **tipo de producto a nivel general** (no un producto puntual). Para profundizar en un producto específico dentro de ese tipo, se usará en el futuro el template detallado (`template-cap.mdx`).

---

## Reglas generales

1. **Nada se infiere** — Toda la información viene de búsqueda real en internet (MercadoLibre, Alibaba, Google Trends, fuentes del sector)
2. **Avance progresivo** — No se avanza a la siguiente fase/sesión sin verificación del usuario
3. **Diferenciado por temporada** — Cada dropdown tiene tipos de productos específicos para esa época del año
4. **Un archivo de resultados por sesión** — Se guarda en `_workspace/` para revisión

---

## Fase 0: Template de tipo de producto

**Estado:** ✅ Completado
**Descripción:** Antes de empezar la Fase 2, necesitamos definir el template que usarán las páginas de tipos de producto. Este template es diferente al `template-cap.mdx` (que es para producto específico). Será más general y cubrirá:

- Qué es este tipo de producto
- Por qué es relevante para importar
- Rango de precios FOB típico
- Demanda estimada en Argentina
- Competencia general en MercadoLibre
- Regulaciones que aplican a este tipo
- Estacionalidad
- Nivel de dificultad para importar
- Warnings y riesgos principales
- Subtipos o variantes más comunes (que luego podrían profundizarse con template-cap.mdx)

**Entregable:** `app/productos/template-tipo-producto.mdx`
**Momento:** Se crea antes de iniciar la Fase 2

---

## Fase 1: Investigación de tipos de productos por dropdown

Búsqueda exhaustiva en internet de los tipos de productos más vendidos, exitosos o relevantes para importar dentro de cada capítulo NCM, **diferenciado por temporada**.

### Fase 1.1 — Dropdown "Atemporales"

**Estado:** ✅ Completado (34/34 capitulos — 161 tipos de productos identificados)
**Descripción:** Investigar los 34 capítulos buscando tipos de productos que se venden de manera estable durante todo el año, sin dependencia estacional fuerte.
**Criterio de búsqueda:**
- Productos con demanda constante en MercadoLibre todo el año
- Productos que China exporta de forma competitiva en esas categorías
- Tipos de producto (no marcas ni modelos puntuales)

**Entregable:** `_workspace/investigacion/fase-1-1-atemporales.md`
**Contenido del entregable:** Para cada capítulo, lista de tipos de productos con justificación breve de por qué es relevante.

### Fase 1.2 — Dropdown "Verano (Dic–Feb)"

**Estado:** ✅ Completado (34/34 capitulos — 90 tipos de productos identificados, 23 capitulos con productos, 11 sin productos de verano)
**Descripción:** Investigar los 34 capítulos buscando tipos de productos con pico de demanda en verano argentino (diciembre, enero, febrero).
**Criterio de búsqueda:**
- Productos vinculados a calor, vacaciones, aire libre, playa, pileta, fiestas de fin de año
- Productos escolares de inicio de clases (febrero-marzo)
- Regalos de Navidad y Reyes (diciembre-enero)

**Entregable:** `_workspace/investigacion/fase-1-2-verano.md`

### Fase 1.3 — Dropdown "Otoño (Mar–May)"

**Estado:** ✅ Completado (34/34 capitulos — 69 tipos de productos identificados, 31 capitulos con productos, 3 sin productos de otoño)
**Descripción:** Investigar los 34 capítulos buscando tipos de productos con pico de demanda en otoño argentino (marzo, abril, mayo).
**Criterio de búsqueda:**
- Vuelta a clases (marzo) — ~20 productos
- Pascuas (abril) — 3 productos
- Transición al frío (abril-mayo) — ~46 productos
- Inicio de temporada de hogar/interior

**Entregable:** `_workspace/investigacion/fase-1-3-otono.md`

### Fase 1.4 — Dropdown "Invierno (Jun–Ago)"

**Estado:** ✅ Completado (34/34 capitulos — 57 tipos de productos identificados, 28 capitulos con productos, 6 sin productos de invierno)
**Descripción:** Investigar los 34 capítulos buscando tipos de productos con pico de demanda en invierno argentino (junio, julio, agosto).
**Criterio de búsqueda:**
- Día del Padre (junio) — 4 productos regalo
- Vacaciones de invierno (julio) — ~10 productos entretenimiento indoor + ski
- Día del Niño (agosto) — ~12 productos (EL gran evento del invierno)
- Pico de frío + indoor — ~10 productos abrigo pesado, cocina, fitness

**Entregable:** `_workspace/investigacion/fase-1-4-invierno.md`

### Fase 1.5 — Dropdown "Primavera (Sep–Nov)"

**Estado:** ✅ Completado (34/34 capitulos — 40 tipos de productos identificados, 27 capitulos con productos, 7 sin productos de primavera)
**Descripción:** Investigar los 34 capítulos buscando tipos de productos con pico de demanda en primavera argentina (septiembre, octubre, noviembre).
**Criterio de búsqueda:**
- Día de la Madre (octubre) — ~12 productos regalo (2da fecha comercial del año, gasto promedio $46,500)
- Primavera/Jardinería (septiembre-octubre) — ~10 productos (octubre = mayor mes jardinería)
- Preparación Navidad + CyberMonday (noviembre) — ~12 productos ($600 mil millones facturacion CM)
- Halloween (octubre) — disfraces +40% interanual
- Transición ropa de temporada (septiembre-noviembre)

**Entregable:** `_workspace/investigacion/fase-1-5-primavera.md`

---

## Fase 2: Creación de páginas MDX por tipo de producto

Una vez aprobados los 5 archivos de investigación de la Fase 1, se crean las páginas MDX dentro de cada capítulo, basadas en el template de tipo de producto (`template-tipo-producto.mdx`).

**Avance:** Progresivo, capítulo por capítulo o grupo por grupo, verificando con el usuario antes de continuar.

### Fase 2.1 — Páginas del dropdown "Atemporales"

**Estado:** Pendiente
**Descripción:** Crear las páginas MDX para cada tipo de producto identificado en la Fase 1.1.
**Mecánica de avance:** Se trabajará por grupo del sidebar (ej: primero "Máquinas y Electrónica", luego "Textiles", etc.). No se avanza al siguiente grupo sin verificación.

**Subfases sugeridas (por grupo del sidebar):**
- 2.1.A — Industrias Químicas (cap. 33, 34)
- 2.1.B — Plástico y Caucho (cap. 39, 40)
- 2.1.C — Cueros y Marroquinería (cap. 42)
- 2.1.D — Madera y Cestería (cap. 44, 46)
- 2.1.E — Papel y Cartón (cap. 48, 49)
- 2.1.F — Textiles (cap. 56, 57, 61, 62, 63)
- 2.1.G — Calzado y Accesorios (cap. 64, 65, 66, 67)
- 2.1.H — Cerámica y Vidrio (cap. 69, 70)
- 2.1.I — Bisutería (cap. 71)
- 2.1.J — Metales Comunes (cap. 73, 76, 82, 83)
- 2.1.K — Máquinas y Electrónica (cap. 84, 85)
- 2.1.L — Transporte (cap. 87)
- 2.1.M — Óptica, Relojería y Música (cap. 90, 91, 92)
- 2.1.N — Mercancías Diversas (cap. 94, 95, 96)

**Entregable por subfase:** Archivos MDX creados + actualización de `docs.json`

### Fase 2.2 — Páginas del dropdown "Verano"
### Fase 2.3 — Páginas del dropdown "Otoño"
### Fase 2.4 — Páginas del dropdown "Invierno"
### Fase 2.5 — Páginas del dropdown "Primavera"

*(Misma mecánica que 2.1, trabajando por grupo del sidebar)*

---

## Fase 3: Revisión y ajustes

**Estado:** Pendiente
**Descripción:** Revisión integral una vez completadas las Fases 1 y 2.
- Verificar que `docs.json` refleja todas las páginas creadas
- Cross-references entre dropdowns donde un mismo tipo de producto aparece en varias temporadas
- Verificar compilación final con `npx mintlify dev`
- Limpieza de archivos overview placeholder que ya no se usen

---

## Resumen de fases

| Fase | Descripción | Sesiones estimadas | Estado |
|------|-------------|-------------------|--------|
| 0 | Template tipo producto | 1 | ✅ Completado |
| 1.1 | Investigación Atemporales (161 tipos) | 1 | ✅ Completado |
| 1.2 | Investigación Verano (90 tipos) | 1 | ✅ Completado |
| 1.3 | Investigación Otoño (69 tipos) | 1 | ✅ Completado |
| 1.4 | Investigación Invierno (57 tipos) | 1 | ✅ Completado |
| 1.5 | Investigación Primavera (40 tipos) | 1 | ✅ Completado |
| 2.1 | Páginas Atemporales | ~14 (por grupo) | Pendiente |
| 2.2 | Páginas Verano | ~14 (por grupo) | Pendiente |
| 2.3 | Páginas Otoño | ~14 (por grupo) | Pendiente |
| 2.4 | Páginas Invierno | ~14 (por grupo) | Pendiente |
| 2.5 | Páginas Primavera | ~14 (por grupo) | Pendiente |
| 3 | Revisión y ajustes | 1 | Pendiente |

---

## Notas

- La Fase 1 producirá archivos de investigación en `_workspace/investigacion/`. Estos NO se publican, son solo referencia interna.
- La Fase 2 producirá archivos MDX en `app/productos/`. Estos SÍ se publican.
- El template `template-cap.mdx` existente se conserva para uso futuro (cuando se quiera profundizar en un producto específico dentro de un tipo).
- En la Fase 2, cada tipo de producto tendrá su propia página MDX y se actualizará `docs.json` para incluirla en la navegación del capítulo correspondiente.
