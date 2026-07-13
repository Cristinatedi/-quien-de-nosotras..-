# 🍷 ¿Quién de nosotras...?

> El juego oficial de las noches que acaban en *"no se lo cuentes a nadie"* 🤫

Juego de fiesta **para grupos de amigas** (de 3 a 12 jugadoras) en un único archivo HTML. Sin instalaciones, sin servidor, sin registro: se abre en el móvil y a jugar. Diseñado con mecánicas virales integradas para crecer en redes sociales mientras el grupo se ríe.

---

## 🎮 Cómo se juega

1. **Apuntad los nombres** de las jugadoras (mínimo 3 valientes, máximo 12)
2. **Elegid nivel de cachondeo:**
   - 🍼 **Suave** — risas garantizadas, dignidad intacta (de momento)
   - 🍷 **Picante** — aquí ya salen trapos sucios
   - 🔥 **Sin filtro** — lo que pasa en la habitación, se queda en la habitación
3. Sale la carta *"¿Quién de nosotras...?"* → cuenta atrás **3, 2, 1... ¡SEÑALAD!** 👉
4. La más señalada recibe su **prenda** o carta especial
5. Al final: **ranking con premios y castigos** 🏆

## ✨ Características

- **60+ preguntas** en 3 niveles de picante, barajadas en cada partida
- **20 prendas** clásicas (leer tu último audio, enseñar el historial...)
- **Cartas especiales:**
  - 🌀 Trabalenguas picantes con **cronómetro de 15 segundos**
  - 🎭 ¿Verdad o trola? con votación y **contador de mentirosas**
  - 🤬 Taco inventado (estilo RAE)
  - 📞 Misiones exteriores (llamadas y presentaciones absurdas)
  - 💑 Zona pareja (confesiones sobre parejas y personas de confianza)
- **Retos virales** cada X pilladas: stories, encuestas, retar a otros grupos
- **Ranking final triple:** la más pillada (castigo), la más santa (recompensa) y la mejor mentirosa (fama eterna)
- Botones para **compartir el podio** en stories y **retar a amigas**
- 100% responsive, pensado para jugar desde el móvil
- **Un solo archivo HTML** — cero dependencias, cero backend

## 🚀 Cómo publicarlo (gratis)

### Opción A: GitHub Pages
1. Renombra el archivo del juego a `index.html`
2. Súbelo a este repositorio
3. Ve a **Settings → Pages → Source: Deploy from a branch → main → / (root)**
4. En 1-2 minutos tu juego estará en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`

### Opción B: Netlify
1. Entra en [netlify.com](https://netlify.com) y arrastra la carpeta con el `index.html`
2. Listo. Puedes conectar un dominio propio después.

## ⚙️ Configuración de marca

Todo lo viral se configura editando **4 líneas** al principio del `<script>` en el HTML:

```js
const MARCA = {
  cuenta: "@tumarca",                 // tu cuenta de Instagram/TikTok
  hashtag: "#QuienDeNosotras",        // hashtag oficial del juego
  urlWeb: "https://tumarca.com",      // tu web, tienda o linktree
  urlIG: "https://instagram.com/tumarca"
};
const FRECUENCIA_VIRAL = 3;           // cada cuántas pilladas salta un Reto Viral
```

Los retos virales, el botón de compartir y el pie de página usarán automáticamente estos datos.

## 🗂️ Estructura

```
├── index.html    ← el juego completo (HTML + CSS + JS)
└── README.md     ← este archivo
```

## 🛠️ Tecnología

- HTML5 + CSS3 + JavaScript vanilla (sin frameworks)
- Fuentes: [Titan One](https://fonts.google.com/specimen/Titan+One) y [Outfit](https://fonts.google.com/specimen/Outfit) vía Google Fonts
- Web Share API para compartir en redes
- Funciona offline una vez cargado (salvo las fuentes)

## 🗺️ Próximamente

- [ ] Versión Premium "Sin Filtro Extremo" (Stripe Payment Links)
- [ ] Preguntas personalizadas escritas por el grupo
- [ ] Sonidos en la cuenta atrás
- [ ] Modo "verdad o prenda" clásico

## ⚠️ Aviso

Juego pensado para mayores de edad. Las prendas con bebida pueden sustituirse por retos (versión sobria incluida en las cartas). Bebed con cabeza y señalad sin piedad. 😄

## 📄 Licencia

© Todos los derechos reservados. Si quieres usar el juego para tu marca o evento, contacta primero. 💌

---

**Hecho con 💖, cachondeo y cero vergüenza ajena.**
*Si jugáis, etiquetadnos — compartimos los mejores momentos.* 📲
