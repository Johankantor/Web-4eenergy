# 4E Energy SAS – Sitio web

Sitio corporativo de una sola página: HTML + CSS + JavaScript puro (sin dependencias ni paso de compilación).
Tema oscuro con acentos verde neón. Solo carga las fuentes de Google Fonts (Bricolage Grotesque e Instrument Sans).

## Estructura
```
index.html          Todo el sitio (estilos y scripts incluidos)
assets/4e-wash.jpg  Foto mejorada de 4E Wash
```

## Cómo verlo
1. Abre `index.html` con doble clic en Google Chrome.
2. O desde la carpeta: `npx serve .` (o `python3 -m http.server 8080`) y abre http://localhost:8080

## Cómo publicarlo
- Vercel o Netlify: arrastra la carpeta completa. No requiere configuración.
- GitHub Pages: sube la carpeta a un repositorio y activa Pages sobre la rama principal.

## Datos de la empresa que usa el sitio
- WhatsApp de cotización: 573112440876 (constante `WA` al final de `index.html`, y enlaces `wa.me` del botón flotante)
- Teléfono: (601) 782 6999
- Correo: contacto@4eenergy.com
- Dirección: Carrera 25 # 39-45, Bogotá. NIT 901.804.860-7
- Precio 4E Wash 150 mL: $28.000. Cursos: $200.000 y $300.000

## Pendientes para Devin
1. Reemplazar el logotipo de texto (cuadro "4E" en `.logo`) por el logo real en PNG con fondo transparente, en `assets/`.
2. Confirmar el número de WhatsApp principal (hay tres números en los materiales de la empresa).
3. Agregar fotos reales de proyectos como galería, en `assets/`.
4. Conectar el formulario a un correo (Formspree o Web3Forms) además de WhatsApp.
5. Agregar la imagen `og:image` y el dominio final en las metaetiquetas.

## Notas
- La calculadora de pérdidas es un estimado (4 horas de sol pleno al día). Está en la función `calc()`.
- La sección de inversión no promete rentabilidades; mantener esa redacción.
- Menú Neon Pill: la lógica está en el script (variable `pill`) y los estilos en `.pill`.
