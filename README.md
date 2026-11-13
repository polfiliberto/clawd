# `>_` clawd

Fondo de pantalla animado e interactivo en pixel art protagonizado por **Clawd**.  
Un único archivo (`index.html`), cero dependencias, listo para **Lively Wallpaper**, **Wallpaper Engine** o el navegador.

---

## `>_` features

```txt
tamaño        2x .. 12x  (Diminuto 3x · Medio 7x · Gigante 11x)
estilos       Clawd · Gafas · Traje · Mago · Elegante · Navidad · Auriculares
modos         Centro · Pasear · Seguir · DVD
fondos        Negro (OLED) · Estrellas · Terminal
extras        Borde blanco sticker · Modo sueño automático (zZz) · Mirada al cursor
```

---

## `>_` install

Descarga el repositorio (**Code → Download ZIP**) o clónalo:

```bash
git clone https://github.com/polfiliberto/clawd.git
```

Guarda la carpeta en un sitio fijo de tu ordenador y carga **`index.html`** en tu programa de fondos:

### Lively Wallpaper (Windows · Gratis)
1. Abre [Lively Wallpaper](https://www.rocksdanister.com/lively/).
2. Pulsa **`+` Añadir fondo** y arrastra `index.html`.

### Wallpaper Engine (Windows · Steam)
1. Pulsa **Abrir fondo → Abrir desde archivo** abajo a la izquierda.
2. Selecciona `index.html`.

### Navegador / macOS / Linux
- Abre `index.html` directamente en cualquier navegador o úsalo en apps de fondos web como [Plash](https://sindresorhus.com/plash) (macOS) o *HTML Wallpaper* (KDE).

---

## `>_` controls

| Input | Acción |
| :--- | :--- |
| `[ESC]` | Abrir / cerrar la terminal de ajustes (`>_ clawd --settings`) |
| `Clic en Clawd` | Salto con partículas pixeladas |
| `Clic en el fondo` | Caminar hacia ese punto *(en modo Pasear)* |
| `Sin mover el ratón` | Clawd se duerme (`zZz`) y despierta al volver a moverlo |

> **Nota para Lively Wallpaper:** si el escritorio no envía la tecla `[ESC]` al fondo, abre `index.html` en tu navegador para ver cómo queda tu configuración preferida y edita el bloque `DEFAULTS` al inicio del `<script>`.

---

## `>_` config

Puedes cambiar los valores iniciales editando `DEFAULTS` dentro de `index.html`:

```js
const DEFAULTS = {
    pixelSize: 4,            // 2..12 (3 Diminuto, 7 Medio, 11 Gigante)
    outfit: 'sunglasses',    // 'classic', 'sunglasses', 'suit', 'wizard', 'gentleman', 'santa', 'headphones'
    mode: 'center',          // 'center', 'wander', 'follow', 'dvd'
    bgEffect: 'pure',        // 'pure', 'stars', 'matrix'
    stickerBorder: false
};
```

---

## `>_` disclaimer

Proyecto fan-made sin fines comerciales. No afiliado ni respaldado por Anthropic.
