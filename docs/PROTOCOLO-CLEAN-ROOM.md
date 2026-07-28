# Protocolo clean-room

**Propósito:** separar de forma verificable el trabajo profesional propio del trabajo institucional, de modo que ningún producto publicado dependa de datos, instrumentos o estructuras que pertenezcan al empleador.

**Origen:** el contrato vigente contiene cláusula de propiedad intelectual sobre herramientas y metodologías desarrolladas para la organización, y prohibición de uso de datos institucionales. No existe restricción sobre actividad externa. Este protocolo traduce esa condición en reglas operativas.

**Vigencia:** permanente, con independencia de que exista o no un cliente externo.

---

## 1. La línea que separa

| Pertenece al empleador | Pertenece al profesional |
|---|---|
| Los datos | La competencia para analizarlos |
| Los instrumentos construidos para la organización | El conocimiento de cómo se construye un instrumento |
| Las plantillas, matrices y formularios específicos | Los principios de diseño de bases y formularios |
| Los reportes y sus estructuras | El formato de análisis de elaboración propia |
| Los nombres de programas, cohortes y sedes | Nada de esto sale |

**Criterio de decisión ante la duda:** si el artefacto podría reconstruirse desde cero por alguien con la misma formación y sin acceso a la organización, es método. Si requiere haber visto un archivo interno, es institucional y no sale.

---

## 2. Reglas operativas

| # | Regla |
|---|---|
| 1 | Todo material publicable se produce en equipo personal, fuera de la jornada laboral |
| 2 | Cero datos reales. Los datos publicados son sintéticos, generados con supuestos declarados |
| 3 | Ningún instrumento institucional se reutiliza. Si se necesita uno equivalente, se reconstruye desde principios y se documenta esa reconstrucción |
| 4 | No se mencionan nombres de la organización, programas, cohortes, sedes ni personas |
| 5 | La organización no se usa como caso, cliente ni referencia en material comercial |
| 6 | No se prospecta a organizaciones con relación contractual con el empleador |
| 7 | Todo hallazgo se publica como metodología, nunca como caso institucional |
| 8 | Se conserva registro de cuándo y cómo se creó cada instrumento propio |

---

## 3. La arquitectura de doble versión

Un mismo análisis produce dos versiones que nunca se mezclan:

```
              MÉTODO (propio, transferible)
                        │
        ┌───────────────┴───────────────┐
        ▼                               ▼
  VERSIÓN INTERNA                 VERSIÓN EXTERNA
  datos reales                    datos sintéticos
  equipo institucional            equipo personal
  audiencia: organización         audiencia: pública
  no sale nunca                   repositorio, LinkedIn
```

El método es lo único que cruza. Los datos, nunca.

---

## 4. Trazabilidad

Cada instrumento propio lleva una nota de origen en su encabezado:

```
Construido desde principios el [fecha].
Datos: sintéticos, generador en /datos-sinteticos/.
No deriva de instrumentos institucionales.
```

El historial de commits del repositorio funciona como registro de autoría fechado. Esa es su función secundaria y no es menor: establece prioridad temporal verificable frente a cualquier réplica posterior.

---

## 5. Qué hacer ante una duda concreta

1. Escribir la duda en una línea.
2. Aplicar el criterio de la Sección 1.
3. Si sigue sin resolverse: **no publicar**, y consultar.

El costo de retrasar una publicación es de días. El costo de un incidente de propiedad intelectual o de datos es el proyecto entero y la relación laboral.
