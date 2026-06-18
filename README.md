# web-proyectoing
Panel de control para sistema de fitoestabilización automatizada mediante dispersión aérea con drones tecnificados.
# FitoControl — Panel de Fitoestabilización Automatizada

Dashboard interactivo para el monitoreo en tiempo real de misiones de fitoestabilización mediante dispersión aérea con drones tecnificados. Diseñado para faenas mineras con suelos contaminados por metales pesados.

## ¿Qué es la fitoestabilización?

La fitoestabilización es una técnica de fitorremediación en la que especies vegetales nativas inmovilizan metales pesados (Pb, Cd, Zn, Cu) directamente en el suelo mediante sus raíces, reduciendo la movilidad de contaminantes sin necesidad de extracción.

Este sistema automatiza el proceso mediante drones que dispersan cápsulas inteligentes de semillas sobre zonas de difícil acceso o alto riesgo.

## Características del panel

- **Panel general** — métricas en tiempo real, mapa de cobertura animado con posición de drones, progreso por sectores y alertas
- **Telemetría** — altitud, velocidad, batería, señal GPS RTK y parámetros de vuelo por dron
- **Resultados** — historial de misiones, indicadores de recuperación ecológica y tasas de germinación
- **Configuración** — parámetros de vuelo, densidad de dispersión, alertas automáticas y datos del lote de cápsulas

## Tecnología

- HTML5 + CSS3 + JavaScript vanilla
- Chart.js 4.4.1 para visualización de datos
- Tabler Icons para iconografía
- Sin dependencias de backend — funciona como archivo estático

## Cápsula inteligente de semillas

Cada cápsula contiene:
- Semilla nativa de bajo consumo hídrico
- Hidrogel de retención de agua
- Nutrientes de liberación gradual (30 días)
- Recubrimiento biodegradable 100%

## Especificación del dron

| Parámetro | Valor |
|-----------|-------|
| Navegación | GPS RTK ±2 cm |
| Evitación de obstáculos | Automática |
| Dispensador | Alta precisión |
| Telemetría | Tiempo real |
| Drones por misión | 3 |

## Uso

Abrir `fitoestabilizacion.html` directamente en cualquier navegador moderno. No requiere servidor ni instalación.

También puede desplegarse en cualquier hosting estático:
- GitHub Pages
- Netlify
- Vercel

## Caso de uso ejemplo

| Parámetro | Valor |
|-----------|-------|
| Área total | 25.4 ha |
| Cápsulas estimadas | 1.250.000 |
| Tiempo estimado | 45 min |
| Drones en operación | 3 |

## Licencia

MIT
