
# 🕹️ Ogres Games Landing Page

**Landing page temática arcade para comunidad gamer con servidores Minecraft Pixelmon, Discord y desarrollo de videojuegos indie retro.**

Este sitio web es la carta de presentación oficial de **Ogres Games**, una comunidad gamer que opera servidores dedicados de Minecraft Pixelmon, mantiene una comunidad activa en Discord, y está incubando el desarrollo de videojuegos independientes con espíritu de los 80/90.

> 🎯 **¿Quieres usar esto para tu propia comunidad?** Siéntete libre de forkearlo, modificarlo y adaptarlo a tu marca. Está bajo licencia MIT.

---

## ✨ Características

| Sección | Descripción |
|---------|-------------|
| **Hero Arcade** | Cabina de arcade animada con efecto typewriter, joystick y botones interactivos |
| **Discord Quest** | Panel tipo "tablón de misiones" para promocionar tu comunidad de Discord |
| **Servidores** | Tarjetas con estado online/offline, IP copiable, versión y jugadores conectados |
| **Equipo RPG** | Selector de miembros del equipo con stats al estilo RPG (HP, MP, SPD, etc.) |
| **Donaciones** | Grid de montos predefinidos con enlace a tienda/donaciones |
| **Efectos CRT** | Scanlines, flicker, viñeta y parrilla retro personalizable |
| **Responsive** | Adaptado a móviles, tablets y desktop |

---

## 🛠️ Stack Tecnológico

- **[Astro](https://astro.build) v7** — Framework web estático
- **CSS personalizado** — Efectos CRT, tipografía pixel art (Press Start 2P, VT323), neones y animaciones retro
- **Sin frameworks JS pesados** — Cero React/Vue/Svelte, solo HTML, CSS y JS vanilla

---

## 🚀 Desarrollo Local

### Requisitos

- Node.js >= 22.12.0
- pnpm

### Instalación

```bash
pnpm install
```

### Comandos

| Comando | Acción |
|---------|--------|
| `pnpm dev` | Inicia servidor de desarrollo en `localhost:4321` |
| `pnpm build` | Construye el sitio en `./dist/` |
| `pnpm preview` | Previsualiza la build localmente |

---

## 🔧 Personalización

Para adaptar esta landing a tu comunidad:

1. **Edita `src/data/config.json`** — URL de Discord, donaciones y beneficios
2. **Edita `src/data/servers.json`** — IPs, nombres, versiones y features de tus servidores
3. **Edita `src/data/team.json`** — Miembros del equipo, avatares, stats y redes sociales
4. **Edita `src/data/shop.json`** — Productos de tu tienda (rangos VIP, monedas, etc.)
5. **Reemplaza el logo** en `src/assets/images/Logo-OG.png` y los avatares en `public/avatars/`

---

## 🌐 Enlaces Oficiales

- **Servidor Minecraft**: `mc.ogresgames.com`
- **Discord**: [discord.gg/ogresgames](https://discord.gg/ogresgames)
- **Donaciones**: [store.ogresgames.com](https://store.ogresgames.com)

---

## 👤 Equipo

| Miembro | Rol |
|---------|-----|
| **Bernardo G. Erramuspe** | Fundador y desarrollador principal ([@Bernard2806](https://github.com/Bernard2806)) |

---

## 📄 Licencia

MIT © 2026 [Bernardo G. Erramuspe](https://github.com/Bernard2806) — Ogres Games.

Puedes usar, modificar y distribuir este proyecto libremente. Se agradece atribución, pero no es requerida.
