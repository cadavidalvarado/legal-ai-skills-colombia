# AI Skills para Abogados Colombianos

Instrucciones listas para usar con Claude, ChatGPT u otros LLMs. Cada `SKILL.md` le dice al modelo exactamente cómo comportarse para una tarea jurídica concreta.

---

## ¿Qué es un skill y cómo funciona?

Un skill es un archivo de instrucciones que se le entrega al LLM **antes** de que el abogado haga su consulta. El modelo lo lee y adopta el rol, el marco normativo y las reglas de calidad definidas en el skill. Es como contratar un asistente que ya viene entrenado para una tarea específica.

---

## Cómo usarlo

### Opción A — Claude Projects (recomendado)
1. Vaya a [claude.ai](https://claude.ai) y cree un **Proyecto nuevo**
2. En la configuración del proyecto, busque "Instrucciones del proyecto"
3. Copie el contenido completo del `SKILL.md` que necesita y péguelo ahí
4. Listo: cada conversación dentro de ese proyecto usará el skill automáticamente

> Cree un proyecto por skill. Por ejemplo: "Contratos", "Escritos", "Investigación", "Clientes".

### Opción B — Cualquier LLM con system prompt
Pegue el contenido del `SKILL.md` como `system prompt` en la configuración del modelo antes del mensaje del usuario.

### Opción C — Al inicio de cada conversación
Si no puede configurar un system prompt, pegue el contenido del `SKILL.md` como **primer mensaje** de la conversación, seguido de su consulta.

---

## Los 4 Skills

| Carpeta | Cuándo usarlo |
|---------|--------------|
| [`analisis-contratos/`](./analisis-contratos/SKILL.md) | Revisar contratos, detectar riesgos, interpretar cláusulas |
| [`redaccion-escritos/`](./redaccion-escritos/SKILL.md) | Tutelas, derechos de petición, demandas, memoriales |
| [`investigacion-juridica/`](./investigacion-juridica/SKILL.md) | Normas aplicables, jurisprudencia, términos de prescripción |
| [`comunicaciones-clientes/`](./comunicaciones-clientes/SKILL.md) | Conceptos, actualizaciones de caso, honorarios, malas noticias |

---

## Marco legal sobre uso de IA en Colombia

- **CONPES 4144 de 2025** — Política Nacional de IA: [dnp.gov.co](https://colaboracion.dnp.gov.co/CDT/Conpes/Econ%C3%B3micos/4144.pdf)
- **Sentencia T-323 de 2024** — La IA no reemplaza el criterio del profesional: [corteconstitucional.gov.co](https://www.corteconstitucional.gov.co/relatoria/2024/t-323-24.htm)
- **Ley 2502 de 2025** — Agravante penal por suplantación con IA: [bu.com.co](https://www.bu.com.co/es/insights/noticias/novedades-regulatorias-en-materia-de-ia-en-colombia)

---

## Licencia

MIT — libre para usar, adaptar y compartir en su consultorio.
