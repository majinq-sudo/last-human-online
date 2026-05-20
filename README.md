# Last Human Online: Terminal Survival 📡

Un prototipo de videojuego web de supervivencia e investigación desarrollado íntegramente en JavaScript puro (Vanilla JS), HTML5 y CSS3, sin motores ni librerías externas.

## 🚀 Características Técnicas Destacadas

* **Motor Gráfico Isométrico Personalizado:** Renderizado 3D en <canvas> utilizando el Algoritmo del Pintor para gestionar la superposición de capas y la profundidad de los muros procedurales y entidades móviles.
* **Generación Procedural de Entornos:** Algoritmo de creación de laberintos por sectores que aumenta la densidad de los obstáculos y enemigos dinámicamente, asegurando rutas matemáticas válidas ("Flood fill").
* **Sintetizador Web Audio API:** Todo el diseño sonoro del juego (pasos, radares, alertas, interfaz) se genera de forma procedural mediante funciones de onda de JavaScript sin usar archivos de audio externos.
* **IA de Comportamiento Reactivo:** Los "Drones" tienen estados de deambulación aleatoria y estados de persecución inteligente basados en la acumulación de la variable global de Ruido.
* **Gestión Asíncrona:** Integración de bucles independientes de temporización (requestAnimationFrame vs setTimeout) para gestionar animaciones fluidas, colisiones físicas y conversaciones de chat asíncronas con la terminal.

## 🎮 Mecánicas de Juego
1. **Deducción de Terminal:** Analiza los metadatos y respuestas del chat de perfiles aleatorios. Deduce si son Bots o Humanos para avanzar.
2. **Sistema de Sigilo y Energía:** Cada paso gasta recursos. Clicar lejos duplica el ruido que generas, atrayendo a los drones cazadores.
3. **Radar Cinemático de CSS:** Interfaz UI de teléfono móvil funcional superpuesta sobre el Canvas que gestiona inventarios y revela elementos invisibles.
