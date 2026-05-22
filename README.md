# Alto Cauce — versión actualizada (Saltos del Laja)

Sitio rehecho como **una sola página HTML autónoma**, sin React/Vite.
Drop directo en `public_html` y listo. Sin `npm`, sin build, sin dependencias.

---

## Cambios principales respecto al sitio anterior

### Posicionamiento del hero
- **Antes**: "Desarrollo web con criterio humano" (genérico)
- **Ahora**: **"Web, ventas, comunicación. *Optimizamos tu negocio.*"**

### Foco geográfico y sectorial
Reposicionado hacia el comercio local de Saltos del Laja: cabañas,
minimarkets, supermercados, ferreterías, restaurantes/turismo y pymes en
general. Sección "Para quién es esto" con tarjetas para cada rubro.

### Experiencia como argumento principal
Reemplazadas todas las frases del tipo "no tenemos años de historia" por la
afirmación opuesta: **"Llevamos años acompañando y potenciando proyectos y
emprendimientos."**

### Proyectos destacados
1. **Bellavista** (`bellavista-topaz.vercel.app`) — caso principal, mismo
   Saltos del Laja, multi-negocio (camping + minimarket + servicios). Captura
   en `img/proyecto-bellavista.jpg`.
2. **Paesaggio Vivero** (`vivero-xi-flax.vercel.app`) — segundo destacado,
   catálogo B2B/B2C de Mendoza. Captura en `img/proyecto-paesaggio.jpg`.
3. New Hotel Cruz del Sur + control operativo multi-región + slot abierto.

### Equipo Alto Cauce
Sección simplificada: solo el título **"Equipo Alto Cauce."** (sin eyebrow,
sin párrafo introductorio).

Sin fotos por decisión de marca. Tres tarjetas con nombre, rol y bio breve:

| Persona | Rol | WhatsApp |
|---|---|---|
| **Marco Carbonetti** | Developer | +56 9 8267 5903 |
| **Pía Faundez** | Administración | +56 9 8267 5903 |
| **Ignacio Echegaray** | Gerente Comercial y Ventas | +56 9 5784 5292 |

### CTA final
Reducido al mínimo: eyebrow "Contacto", título **"Conversemos."**, los dos
botones de WhatsApp y la tarjeta de datos a la derecha. Se eliminó el copy
conversacional que pedía explicar el problema.

---

## Cómo desplegar

1. Sube **todo el contenido** de esta carpeta a `public_html/`.
2. **Borra estos archivos viejos** del despliegue anterior:
   - `assets/index-*.js`
   - `assets/index-*.css`
   - `package-lock.json`
   - La carpeta `assets/` completa puede irse.
3. Verifica que el `.htaccess` haya quedado en su sitio (incluido, igual al
   original: redirect www→no-www y forzado de HTTPS).
4. Listo. No requiere build ni proceso de despliegue.

## Archivos del paquete

```
altocauce-public_html/
├── index.html                    ← nuevo (autónomo, ~49 KB)
├── .htaccess                     ← preservado del original
├── alto-cauce-logo.svg
├── alto-cauce-isologo.svg        ← favicon
├── alto-cauce-isologo.png        ← apple-touch-icon
├── alto-cauce-social.png         ← OG image (mismo del original)
├── avatar-marco.png              ← NO usado en esta versión, conservado
├── avatar-pia.png                ← NO usado en esta versión, conservado
├── avatar-ignacio.svg            ← NO usado en esta versión, conservado
├── README.md                     ← este archivo
└── img/
    ├── proyecto-bellavista.jpg   ← captura 1600×1000, 167 KB
    └── proyecto-paesaggio.jpg    ← captura 1600×1000, 99 KB
```

**Nota sobre los avatars**: La versión actual del sitio NO muestra fotos
del equipo. Los archivos quedaron en el paquete por si en el futuro se
decide volver a mostrarlos.

---

## Cambios menores que quizás quieras hacer

- **OG image** (`alto-cauce-social.png`): es la misma del sitio anterior. Si
  quieres que refleje el nuevo titular ("Web, ventas, comunicación. Optimizamos
  tu negocio."), conviene regenerarla.
- **Capturas de proyectos**: tomadas el 22 de mayo 2026. Si los sitios cambian
  visualmente, regenera ambos JPG con la misma proporción 16:10.
- **Bios del equipo**: están escritas en tono general. Si los tres quieren
  ajustar las suyas con palabras propias, son cambios de una línea cada uno.

---

## Stack técnico

- HTML + CSS inline + 30 líneas de JS plano (menú móvil + scroll-reveal).
- Fuentes desde Google Fonts: **Plus Jakarta Sans** (body) + **Instrument
  Serif** (acentos editoriales en headlines).
- Paleta original preservada (navy/sky/ember).
- Sin bundle, sin build step, sin dependencias.
