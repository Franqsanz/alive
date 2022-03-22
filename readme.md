# Alive for [Windows Terminal](https://github.com/microsoft/terminal)
🎨 Mi tema oscuro para Windows Terminal. Inspirado en el tema [Cobalt2](https://github.com/wesbos/cobalt2-vscode).

![screenshot1](./img/1.png)
![screenshot2](./img/2.png)
![screenshot3](./img/3.png)
![screenshot4](./img/4.png)

### Descarga
Descargue el repositorio comprimido desde aquí o copié el esquema.

### Instalación
Pegue en `schemes` el `alive.json` en su configuración de Windows Terminal. Para abrir la configuración presioné `Ctrl + ,` o presione en abrir una nueva pestaña y luego navegue hasta "Configuración"
![screenshot5](./img/5.png)
Esto le abrirá lo siguiente:
![screenshot6](./img/6.png)
Luego navegue hasta "Combinaciones de colores"
![screenshot7](./img/7.png)

### Esquema de colores

```json
"schemes": [
  {
    "name": "Alive",
    "background": "#01131F",
    "black": "#000000",
    "blue": "#127ACE",
    "brightBlack": "#079BFF",
    "brightBlue": "#0045FF",
    "brightCyan": "#FF8D39",
    "brightGreen": "#00AD00",
    "brightPurple": "#FF00FF",
    "brightRed": "#FF3131",
    "brightWhite": "#FFFFFF",
    "brightYellow": "#FFF11B",
    "cursorColor": "#FFC700",
    "cyan": "#FF8400",
    "foreground": "#FFFFFF",
    "green": "#00FF00",
    "purple": "#FF0082",
    "red": "#E30B0B",
    "white": "#FFFFFF",
    "yellow": "#FFC700",
    "selectionBackground": "#000000"
  }
]
```

### Activar desde el JSON
Solo debe colocar el nombre del `schemes` en el campo `list` que se encuentra dentro del campo `profiles`.

Ejemplo:

```json
{
  "profiles": {
    "list": [
      {
        "colorScheme": "Alive",
      }
    ]
  }
}
```

### Recomendación
Esta es mí preferencia personal pero quizás te guste.

```json
{
  "profiles": {
    "list": [
      {
        "colorScheme": "Alive",
        "cursorShape": "filledBox",
        "font": {
          "face": "Inconsolata for Powerline",
          "size": 16
        },
        "padding": "15, 0, 0, 15",
      }
    ]
  }
}
```

### Fuentes recomendadas
* MesloLGS NF
* Cascadia Code PL
* Inconsolata for Powerline