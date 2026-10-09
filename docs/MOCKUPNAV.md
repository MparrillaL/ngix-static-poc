## Mockup (versión escritorio)

Referencia visual única para el desarrollo de la landing. Todos los valores están pensados para escritorio; el comportamiento responsive se definirá en CSS.

### Paleta de colores

| Rol | Hex | Uso |
|---|---|---|
| Primario | `#1e3a8a` | Fondo del CTA final |
| Acento | `#2563eb` | Botones, hover, iconos |
| Fondo base | `#ffffff` | Header, hero, prueba social |
| Fondo alterno | `#f8fafc` | Sección de servicios |
| Texto principal | `#0f172a` | Títulos y párrafos |
| Texto secundario | `#64748b` | Subtítulos y descripciones |
| Borde suave | `#e2e8f0` | Separadores y bordes |
| Fondo oscuro | `#0f172a` | Footer |
| Texto sobre oscuro | `#94a3b8` | Texto del footer |

### Tipografía

- Familia: **Inter** (fallback `system-ui, sans-serif`).
- Pesos: 400, 500, 600, 700.

| Elemento | Tamaño | Peso |
|---|---|---|
| H1 hero | `3.5rem` | 700 |
| H2 sección | `2.25rem` | 700 |
| H3 tarjeta | `1.25rem` | 600 |
| Subtítulo hero | `1.125rem` | 400 |
| Cuerpo | `1rem` | 400 |
| Footer | `0.875rem` | 400 |

### Espaciado, radios y sombras

- Ritmo: múltiplos de 8 px.
- Padding vertical de sección: 96 px.
- Gap entre tarjetas: 32 px.
- Ancho máximo de contenido: 1100 px, centrado.
- Radio tarjetas y botones: 12 px. Inputs: 8 px.
- Sombra: `0 1px 2px rgba(0,0,0,.04), 0 8px 24px rgba(15,23,42,.06)`.
- Hover botón: `translateY(-2px)`, fondo más oscuro, transición 0.2 s.

### Secciones

#### Header

- Barra única horizontal, fondo blanco, borde inferior `1px solid #e2e8f0`.
- Altura 72 px.
- Logo a la izquierda: "Guadalquivir Cloud", peso 700, "Cloud" en `#2563eb`.
- Enlaces a la derecha: "Servicios" y "Contacto", peso 500, hover `#2563eb`.
- Contenido dentro de contenedor de 1100 px centrado.

#### Hero

- Fondo blanco, padding vertical 96 px.
- Grid de 2 columnas 50/50 con gap 64 px.
- Columna izquierda: H1, subtítulo y botón, alineados a la izquierda y centrados verticalmente.
- Columna derecha: ilustración SVG centrada.
- Botón: fondo `#2563eb`, texto blanco, radio 12, padding 14 px 28 px.

#### Servicios

- Fondo `#f8fafc`, padding vertical 96 px.
- H2 centrado, subtítulo corto debajo.
- 3 tarjetas en fila, gap 32 px, misma altura.
- Tarjeta: fondo blanco, radio 12, sombra suave, padding 32 px.
- Dentro: icono SVG 40x40 en `#2563eb`, H3 y párrafo `#64748b`.
- Hover: `translateY(-4px)` con sombra más marcada.

#### Prueba social

- Fondo blanco, padding vertical 96 px.
- Título pequeño centrado: "CONFÍAN EN NOSOTROS", mayúsculas, `#64748b`, letter-spacing.
- 4 logos SVG monocromo `#94a3b8`, altura 32 px, en fila con gap 48 px.
- Cifra grande centrada: "+50", `4rem`, peso 700, `#1e3a8a`.
- Etiqueta debajo: "proyectos entregados", `#64748b`.

#### CTA final

- Fondo `#1e3a8a`, padding vertical 96 px.
- H2 blanco centrado, subtítulo `#cbd5e1` debajo.
- Formulario centrado, ancho máximo 560 px, gap 16 px entre campos.
- Inputs: fondo blanco, radio 8, padding 14 px, borde `#e2e8f0`.
- Textarea mensaje con altura mínima 120 px.
- Botón ancho completo: fondo `#2563eb`, texto blanco, radio 12.
- Foco input: borde `#2563eb` + sombra suave.

#### Footer

- Fondo `#0f172a`, padding vertical 48 px.
- Texto `#94a3b8`, tamaño 0.875rem.
- Tres columnas: marca, enlaces legales, contacto, gap 48 px.
- Contenido dentro de contenedor de 1100 px.

### Estados a contemplar

- Botón: reposo y hover.
- Input: vacío y con foco.
- Tarjeta de servicio: reposo y hover.

---

### Porque usamos rem

Se utiliza rem como unidad principal para tipografía y espaciados porque es una unidad relativa al tamaño de fuente del elemento raíz. Esto permite que toda la interfaz escale de forma coherente cuando el usuario modifica el tamaño de fuente por defecto en su navegador, cumpliendo con el criterio de accesibilidad WCAG 2.1 (1.4.4) que exige que el texto pueda escalarse hasta un 200 % sin pérdida de contenido ni funcionalidad. Además, facilita mantener una escala tipográfica consistente y ajustar todo el diseño desde un único punto de referencia. Los bordes y sombras se mantienen en px por precisión visual.