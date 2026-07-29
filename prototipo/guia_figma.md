# Guía del prototipo — CulturaUAE (Figma)

Solo se evalúa la correspondencia con los requisitos, no el diseño gráfico. Mantén cada pantalla simple: título, campos y botones.

## Pantalla 1 — Publicar taller (RF-01) · rol: Coordinador cultural
- Título: "Nuevo taller cultural"
- Campos: Nombre del taller, Fecha, Ubicación, Cupos disponibles
- Botón: "Publicar taller"

## Pantalla 2 — Inscribirse a un taller (RF-02) · rol: Estudiante
- Título: "Talleres disponibles"
- Lista de talleres con: nombre, fecha, cupos restantes
- Botón por cada taller: "Inscribirme"
- Pantalla emergente de confirmación: "Inscripción confirmada" + código

## Pantalla 3 — Lista de inscritos (RF-03) · rol: Coordinador cultural
- Título: "Inscritos — [nombre del taller]"
- Tabla: nombre del estudiante, correo, fecha de inscripción
- Botón: "Exportar / actualizar lista"

## Pasos en Figma
1. Crea un archivo nuevo (cuenta gratuita) y arma las 3 pantallas de arriba.
2. Conecta los botones con el modo **Prototype**: Pantalla 1 → Pantalla 2 → confirmación, y acceso a Pantalla 3 desde un menú del coordinador.
3. Genera el enlace público de solo lectura (Share → Anyone with the link → View).
4. Toma una captura de cada pantalla y guárdala en `/prototipo/capturas/`.
5. Pega el enlace público en `enlace_figma.md`.
