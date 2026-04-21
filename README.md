# 🎮 BuddyDice — Simon Dice

Un juego clásico de Simon Dice construido con HTML, CSS y JavaScript puro. Sin dependencias externas, sin frameworks — solo un archivo.

## Demo

Abre `index.html` directamente en tu navegador. No requiere servidor.

## Cómo jugar

1. Selecciona la dificultad: **Fácil**, **Normal** o **Difícil**
2. Presiona **▶ Iniciar**
3. Observa la secuencia de colores que se ilumina
4. Repite la secuencia tocando los botones en el mismo orden
5. Cada ronda agrega un paso más — ¿hasta dónde puedes llegar?

## Características

- **4 colores** con efectos de glow y sonido único por botón
- **3 niveles de dificultad** (velocidad de la secuencia)
- **Puntaje** acumulativo por ronda (`ronda × 10 pts`)
- **Récord local** guardado en `localStorage`
- **Sonidos** generados con Web Audio API (sin archivos de audio)
- **Diseño Mobile First** — funciona en cualquier pantalla sin scroll
- **Sin dependencias** — un solo archivo `index.html`

## Estructura

```
BuddyDice/
├── index.html   # App completa (HTML + CSS + JS)
└── favicon.svg  # Ícono con los 4 colores del tablero
```

## Tecnologías

- HTML5 semántico
- CSS3 (custom properties, flexbox, `clamp()`, `min()`, `dvh`)
- JavaScript ES6+ (Web Audio API, localStorage, async/await)

## Licencia

MIT
