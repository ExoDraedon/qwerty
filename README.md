# Project Rivals Launcher

Launcher web para Minecraft Bedrock con efectos CRT/VHS retro.

![Preview](https://i.imgur.com/ygLNkvg.png)

## Configuracion

Edita `app/page.tsx`:

\`\`\`tsx
// Imagen de fondo
const BACKGROUND_IMAGE = "/tu-imagen.jpg"

// Servidor de Minecraft
const SERVER_CONFIG = {
  ip: "tu-servidor.com",
  port: 19132,
  name: "Project Rivals",
}
\`\`\`

Edita `components/settings-panel.tsx` para los creditos.

## Instalacion Local

\`\`\`bash
npm install
npm run dev
\`\`\`

Abre [http://localhost:3000](http://localhost:3000)

## Deploy

### Vercel (Recomendado)
1. Sube a GitHub
2. Conecta el repo en [vercel.com](https://vercel.com)
3. Deploy automatico

### GitHub Pages
\`\`\`bash
npm run build
# Sube la carpeta 'out' a GitHub Pages
\`\`\`

## Imagenes

Coloca tus imagenes en la carpeta `public/`:
- `/public/mi-fondo.jpg` -> usa como `/mi-fondo.jpg`

## Caracteristicas

- Pantalla de carga estilo CMD
- Animacion de TV encendiendo
- Efectos CRT/VHS configurables (Suave, Normal, Fuerte, Extremo)
- Efecto parallax con el mouse
- Musica ambient de fondo
- Conexion directa a servidor Minecraft Bedrock
- Responsive (fuerza modo horizontal en moviles)

## Licencia

MIT - Qwerty Studios
