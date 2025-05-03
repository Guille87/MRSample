## MR Interaction Setup Variant

Objeto principal que configura la base de la experiencia XR.

### Componentes incluidos:
- **Input Action Manager**: gestiona las entradas del usuario (controladores, manos, etc.).
- **XR Interaction Manager**: coordina las interacciones entre el usuario y los objetos.
- **AR Session**: activa y controla la sesión de AR, necesaria para funcionalidades como la detección de planos.
- **Goal Manager**: controla el progreso y comportamiento de la UI de bienvenida (coaching).
- **Object Spawner**: permite generar objetos en el espacio virtual tras interacciones concretas (por ejemplo, contacto con la palma de la mano).
- **XR Origin (XR Rig)**: define la posición y orientación del usuario en el espacio XR.
- **Camera Offset**: estructura que contiene la cámara principal y los controladores (mano izquierda y derecha).
- **Locomotion**: gestiona movimientos como teletransporte o rotaciones en el espacio virtual.

---

## UI (Interfaz)

Contiene elementos de interfaz de usuario y herramientas de interacción espacial.

### Componentes destacados:
- **Locomotion Mediator**: conecta los sistemas de locomoción con la interfaz.
- **XR Body Transformer**: adapta posiciones u orientaciones de objetos según el cuerpo del usuario.
- **Coaching UI**: interfaz de bienvenida que guía al usuario en los primeros pasos.
- **Spatial Panel Manipulator**: panel flotante que muestra un vídeo e permite interacción espacial directa.
- **Tap Tooltip**: componente que muestra mensajes contextuales al usuario.
- **Hand Menu Setup MR Template Variant**: menú flotante que aparece al mostrar la palma de la mano.