# Alto Cauce — versión optimizada

Sitio estático de una sola página. Listo para subir directo a `public_html/`.
No requiere React, Vite, npm ni proceso de build.

## Qué se optimizó

- Se redujo el volumen de texto y se eliminaron explicaciones genéricas.
- El hero quedó enfocado en lo que Alto Cauce hace: **webs, catálogos por WhatsApp y sistemas internos**.
- Se pulió la tarjeta visual principal para evitar la frase “web / catálogo / control” como pieza central y comunicar mejor: presencia clara, venta directa y control interno.
- Se reforzó la idea central: no hacer sitios decorativos, sino herramientas que ayuden a vender, responder y ordenar la operación.
- Se cambió “Para quién” por una sección más directa: problemas reales que Alto Cauce resuelve.
- La sección de proyectos ahora funciona como prueba comercial, no como lista decorativa.
- Se incorporaron proyectos activos y demostrables, separando los públicos de los sistemas privados.
- El proceso se resumió en cuatro pasos concretos: diagnóstico, primera entrega útil, implementación y mejora.
- Equipo y contacto quedaron más claros: Marco y Pía aparecen como equipo de trabajo, pero el único contacto público por WhatsApp es Ignacio.

## Proyectos mostrados

### Destacados

1. **Luminart Chile**  
   Web corporativa, tienda virtual/catálogo y sistemas internos de operación.

2. **Bellavista**  
   Sitio multi-servicio para ordenar camping, minimarket, eventos y servicios locales.

3. **Paesaggio Vivero**  
   Catálogo para vivero productor, con enfoque minorista y mayorista.

### Complementarios

- **Comanda Simple / New Hotel Cruz del Sur** — sistema interno de pedidos y estados para hotelería.
- **Gantt Vivo** — seguimiento de planificación por link o QR.
- **Red Nativa** — estructura digital para preinscripciones y gestión comercial de internet rural.
- **localhost:3000** — laboratorio público de proyectos desplegados.

## Cómo desplegar

1. Sube todo el contenido de esta carpeta a `public_html/`.
2. Mantén el archivo `.htaccess` incluido.
3. Si venías desde una versión con build, elimina archivos viejos de `assets/` que ya no se usen.
4. Verifica que carguen correctamente:
   - `/alto-cauce-isologo.svg`
   - `/img/proyecto-bellavista.jpg`
   - `/img/proyecto-paesaggio.jpg`
   - `/avatar-marco.png`
   - `/avatar-pia.png`
   - `/avatar-ignacio.svg`

## Archivos incluidos

```txt
altocauce-public_html/
├── index.html
├── .htaccess
├── README.md
├── alto-cauce-logo.svg
├── alto-cauce-isologo.svg
├── alto-cauce-isologo.png
├── alto-cauce-social.png
├── avatar-marco.png
├── avatar-pia.png
├── avatar-ignacio.svg
└── img/
    ├── proyecto-bellavista.jpg
    └── proyecto-paesaggio.jpg
```

## Notas rápidas

- El sitio usa HTML, CSS inline y JS mínimo para menú móvil y animaciones.
- Las fuentes siguen siendo Google Fonts: Plus Jakarta Sans e Instrument Serif.
- La paleta original se mantiene: navy, sky y ember.
- Los sistemas internos se comunican sin exponer datos privados de clientes.
- Todos los enlaces de WhatsApp apuntan a Ignacio Echegaray: +56 9 5784 5292.
