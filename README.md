## LaunchDarkly Configuration

Este proyecto usa LaunchDarkly para feature flags.

### Setup

1. Copiar `.env.example` a `.env`
2. Configurar `LD_SDK_KEY` con el SDK Key del entorno Test
3. Ejecutar `node server.mjs`

### Feature Flags

- `feat-new-menu` (Boolean): controla la visualización del nuevo menú
  - `true`: muestra "Feature flag is ON - New menu active!"
  - `false`: muestra "Feature flag is OFF - Original menu"