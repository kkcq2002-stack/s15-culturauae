# CulturaUAE

Sistema de inscripciones a talleres culturales universitarios. Permite al **coordinador cultural** publicar talleres con cupos disponibles, y a los **estudiantes** inscribirse en ellos y consultar la lista de inscritos.

Proyecto desarrollado para el Taller Grupal — Semana 15, Ingeniería de Software I (Universidad Agraria del Ecuador).

## Integrantes del grupo (Grupo 10)

| Nombre | Rol en el proyecto |
|---|---|
| Kerly Katherine Cabello | Responsable de SRS |
| Mariela Elizabeth Cedeño | Responsable de UML |
| Diana Carolina Mosquera | Prototipo — Pantalla 1 (RF-01) |
| Allison Nicole Cobos | Prototipo — Pantalla 2 (RF-02) |
| Pedro Xavier Holguín | Prototipo — Pantalla 3 (RF-03) |
| Richard Yeandry Figueroa | Responsable de repositorio |

## Alcance

- Publicar talleres culturales con cupos.
- Inscribir estudiantes en un taller con cupos disponibles.
- Generar la lista de inscritos de un taller.

El sistema **no** gestiona pagos ni certificados de participación.

## Artefactos

- 📄 SRS completo: [`/docs/SRS_CulturaUAE.pdf`](./docs/SRS_CulturaUAE.pdf)
- 🖼 Diagramas UML: [`/uml`](./uml)
- 🎨 Prototipo Figma: _(pegar aquí el enlace público del prototipo)_

## Tabla de trazabilidad

| Requisito | Caso de uso | Pantalla Figma | Commit |
|---|---|---|---|
| RF-01 | Publicar taller cultural | Pantalla 1: formulario de nuevo taller | `feat: pantalla de publicación de taller (RF-01)` |
| RF-02 | Inscribirse a un taller | Pantalla 2: lista de talleres e inscripción | `feat: flujo de inscripción (RF-02)` |
| RF-03 | Generar lista de inscritos | Pantalla 3: vista del coordinador con inscritos | `feat: lista de inscritos (RF-03)` |

## Estructura del repositorio

```
s15-culturauae/
├── README.md
├── docs/
│   └── SRS_CulturaUAE.pdf
├── uml/
│   ├── casos_uso.png
│   └── clases.png
└── prototipo/
    ├── capturas/
    └── enlace_figma.md
```

## Cómo colaboró cada integrante

Cada integrante debe registrar al menos un commit descriptivo referenciando el requisito o artefacto que trabajó (ver tabla de trazabilidad). Ejemplo de historial esperado:

```
docs: SRS mínimo CulturaUAE                        — Kerly Cabello
docs: diagramas UML (casos de uso y clases)        — Mariela Cedeño
feat: pantalla de publicación de taller (RF-01)    — Diana Mosquera
feat: flujo de inscripción (RF-02)                 — Allison Cobos
feat: lista de inscritos (RF-03)                   — Pedro Holguín
docs: README y tabla de trazabilidad               — Richard Figueroa
```
