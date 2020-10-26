# Alive for Windows Terminal

Mi Tema para Windows Terminal.

### Descarga
Descargue el repositorio comprimido desde aquí o copié el `scheme`.

### Instalación
Pegue en `schemes` el `colors.json` en su configuración de Windows Terminal. Para abrir la configuración presioné `Ctrl + ,`, esto le abrirá el `settings.json`.

Ejemplo:

```json
"schemes": [
  {
    "name": "Alive",
    "cursorColor": "#FCC700",
    "selectionBackground": "#44475A",
    "background": "#111111",
    "foreground": "#e3e3e3",
    "black": "#1A1A1A",
    "blue": "#61AFEF",
    "cyan": "#0997B3",
    "green": "#00ff00",
    "purple": "#FF79C6",
    "red": "#800000",
    "white": "#F8F8F2",
    "yellow": "#FCC700",
    "brightBlack": "#6272A4",
    "brightBlue": "#D6ACFF",
    "brightCyan": "#A4FFFF",
    "brightGreen": "#00FF00",
    "brightPurple": "#FF00FF",
    "brightRed": "#FF0000",
    "brightWhite": "#FFFFFF",
    "brightYellow": "#FCC700"
  }
]
```

### Activar

Solo debe colocar el nombre del `schemes` en los `profiles`.

Ejemplo:

```json
"profiles": [
  {
    "colorScheme": "Alive",
  }
]
```