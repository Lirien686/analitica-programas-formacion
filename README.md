# Analítica de operación de programas de formación

Métodos reproducibles para medir lo que los sistemas de monitoreo y evaluación de programas sociales normalmente no ven: quién queda fuera antes de entrar, cuánto trabajo humano consume la coordinación, y por qué se va quien se va.

## Por qué existe

Los sistemas de MEL miden resultados sobre quienes completaron el programa. La información sobre por qué el programa falla está, casi siempre, en la población que nunca entró al registro y por lo tanto nunca fue medida.

Este repositorio documenta métodos para instrumentar esa capa: descomposición de embudos de participación, distinción entre activación y retención, y cuantificación del trabajo de coordinación.

## Contenido

| Carpeta | Qué hay |
|---|---|
| `analisis/` | Análisis reproducibles, con datos sintéticos |
| `datos-sinteticos/` | Generadores de datos y sus supuestos declarados |
| `instrumentos/` | Plantillas y checklists de diagnóstico |
| `docs/` | Notas de método |

## Sobre los datos

**Todos los datos de este repositorio son sintéticos.** Se generan con supuestos explícitos y documentados, inspirados en patrones observados en operación real pero sin ninguna correspondencia con registros, personas u organizaciones concretas.

Cada análisis declara qué transfiere de su contexto de origen y qué no. Un hallazgo sobre dos aulas no es un hallazgo sobre todas las aulas: es una ilustración de un mecanismo y una hipótesis verificable en más unidades.

## Método

Cada análisis sigue el mismo formato:

1. **Pregunta de decisión** — qué se decidirá distinto según el resultado
2. **Método y supuestos** — explícitos, incluidas las limitaciones
3. **Hallazgos** — máximo tres
4. **Recomendación** — una, con cifra
5. **Qué no puede concluirse** — sección obligatoria

## Autor

Carlos — Quito, Ecuador.
Análisis de datos aplicado a programas de formación y empleabilidad.

## Licencia

Los instrumentos y metodologías se publican bajo Creative Commons BY-NC-SA 4.0. El código, bajo MIT.
