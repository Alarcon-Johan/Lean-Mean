# Arch XFCE
# By Johan-Alarcon

# Este es el "rice" de mi Arch Linux. Una configuración optimizada para alto rendimiento en hardware modesto (una pc de carton incluso), 
# priorizando FPS y una estética minimalista "Dark Pro".



## Especificaciones del Sistema
- **OS:** Arch Linux x86_64
- **Host:** Lenovo G480
- **DE:** XFCE 4.18
- **WM:** Xfwm4
- **Compositor:** Picom (XRender backend)
- **Terminal:** XFCE Terminal

## Apariencia
- **Iconos:** Papirus-Dark
- **Tema GTK:** Arc-Dark (Recomendado)
- **Fuente:** JetBrains Mono (o tu fuente actual)
- **Fondo:** Incluido en la carpeta `/wallpapers`

## Instalación

1. **Instalar dependencias:**
   ```bash
   sudo pacman -S xfce4 xfce4-goodies picom papirus-icon-theme fastfetch ttf-jetbrains-mono
