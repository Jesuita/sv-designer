# AGENTS.md — SV Designer

## Objetivo
SV Designer es un motor determinístico de diseño editorial para generar portadas de Suban El Volumen.

Input:
- imagen
- sección
- título
- bajada

Output:
- PNG 1080x1350
- diseño consistente
- identidad visual fija

## Reglas innegociables
- No usar IA generativa visual.
- No crear diseños aleatorios.
- No inventar logos.
- No cambiar el nombre de marca.
- No modificar dimensiones finales: 1080x1350 px.
- No usar Canvas API salvo instrucción explícita.
- Renderizar con HTML/CSS y exportar con Puppeteer.

## Colores base
- Negro: #0B0B0B
- Gris carbón: #1A1A1A
- Blanco: #FFFFFF
- Rojo marca: #FF2D2D
- Rojo profundo: #A60000

## Colores por sección
- politica: #FF2D2D
- economia: #1E90FF
- tecnologia: #00D1FF
- internacionales: #1C3D7A
- sociedad: #FFC300
- deportes: #28C76F
- cultura: #8E44FF
- policiales: #FF6B00
- opinion: #EAEAEA

## Estructura visual obligatoria
1. Sección arriba izquierda.
2. Imagen protagonista grande.
3. Overlay oscuro para legibilidad.
4. Título principal grande en mayúsculas.
5. Bajada informativa debajo.
6. Línea separadora.
7. Logo abajo centrado: SUBAN en rojo y EL VOLUMEN en blanco.
8. Watermark SV sutil.

## Criterio editorial
El resultado debe parecer una portada de medio periodístico digital: seria, oscura, cinematográfica, de alto contraste y sin estilo flyer.
