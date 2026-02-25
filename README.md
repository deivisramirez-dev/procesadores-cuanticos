# Arquitectura de Procesadores Cuánticos

Una inmersión visual en la estructura, componentes y desafíos de la próxima revolución computacional. Desde el qubit físico hasta la corrección de errores.

## Contenido

- **1. La Unidad Fundamental** — Bits clásicos vs Qubits (superposición, entrelazamiento).
- **2. Tecnologías de Qubits** — Comparación de superconductores, iones atrapados y fotónicos (gráfico radar).
- **3. Topología del Chip** — Disposición tipo Heavy-Hex (similar a IBM Eagle) con visualización de qubits y acopladores.
- **4. La Pila Cuántica** — De la capa de aplicación al QPU: compilador, control electrónico y plano físico.
- **5. Escalabilidad y Ruido** — Evolución del número de qubits y tasas de error por operación.

## Cómo ejecutar

Es una página estática. Abre `index.html` en tu navegador o sirve la carpeta con cualquier servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js (npx)
npx serve
```

Luego visita `http://localhost:8000` (o la ruta que indique tu servidor).

## Stack

- **HTML5**
- **Tailwind CSS** (CDN)
- **Chart.js** (CDN) — gráficos radar, scatter, línea y barras
- **CSS** — tema oscuro "Quantum Neon", glassmorphism, responsive

## Estructura

```
procesadores-cuanticos/
├── index.html   # Página única con contenido y scripts
└── README.md
```

## Licencia

Proyecto de uso educativo. Basado en datos de la industria (IBM, Google, IonQ).
