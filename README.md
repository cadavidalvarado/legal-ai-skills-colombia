# AI Skills para Abogados Colombianos

Instrucciones listas para convertir a Claude, ChatGPT u otras IAs en asistentes jurídicos especializados en derecho colombiano. Sin necesidad de saber programación.

---

## ¿De qué se trata esto?

Cuando usted le habla a una IA como Claude o ChatGPT, el modelo no sabe que usted es abogado, ni que trabaja en Colombia, ni qué tipo de tarea necesita. Responde de manera genérica.

Los **skills** de este repositorio resuelven ese problema. Cada skill es un texto de instrucciones que usted le entrega a la IA una sola vez, y a partir de ese momento el modelo sabe exactamente cómo ayudarle: qué rol cumplir, cómo estructurar las respuestas y qué advertencias incluir.

Piénselo como darle un manual de trabajo a un asistente nuevo antes de que empiece a trabajar con usted.

---

## Los 4 skills disponibles

| Skill | Para qué sirve |
|-------|---------------|
| [Análisis de contratos](./analisis-contratos/SKILL.md) | Revisar contratos, detectar riesgos, interpretar cláusulas problemáticas |
| [Redacción de escritos](./redaccion-escritos/SKILL.md) | Tutelas, derechos de petición, demandas, memoriales |
| [Investigación jurídica](./investigacion-juridica/SKILL.md) | Encontrar normas aplicables, entender jurisprudencia, revisar términos |
| [Comunicaciones con clientes](./comunicaciones-clientes/SKILL.md) | Conceptos jurídicos, actualizaciones de caso, cartas de honorarios |

Haga clic en cualquiera de los enlaces para ver el skill.

---

## Cómo usar un skill — paso a paso

### La forma más cómoda: Claude Projects

Si usa [Claude](https://claude.ai), puede configurar un proyecto para que el skill funcione automáticamente en todas sus conversaciones sobre ese tema.

1. Entre a [claude.ai](https://claude.ai) y haga clic en **"Proyectos"** en el menú izquierdo
2. Cree un proyecto nuevo — por ejemplo, llámelo "Contratos"
3. Dentro del proyecto, busque la opción **"Instrucciones del proyecto"** y haga clic en ella
4. Abra el skill que necesita (por ejemplo, [Análisis de contratos](./analisis-contratos/SKILL.md)), seleccione todo el texto con Ctrl+A, cópielo con Ctrl+C
5. Péguelo en el campo de instrucciones del proyecto y guarde
6. Listo. Desde ahora, cada vez que hable con Claude dentro de ese proyecto, funcionará como su asistente de contratos

> Repita el proceso para cada skill: un proyecto para contratos, otro para escritos, otro para investigación, otro para clientes.

---

### La forma más rápida: al inicio de cada conversación

Si prefiere no configurar proyectos, también funciona así:

1. Abra el skill que necesita y copie todo el texto
2. Abra una conversación nueva en Claude, ChatGPT, Gemini o la IA que use
3. Pegue el texto del skill como **primer mensaje** de la conversación
4. En el mismo mensaje o en el siguiente, escriba su consulta

La IA adoptará el rol definido en el skill para esa conversación.

---

## ⚠️ Todo lo que genera la IA requiere su revisión profesional

Estos skills producen borradores de trabajo, no productos terminados. La IA puede cometer errores: citar una norma que fue modificada, mencionar una sentencia con un número incorrecto, o no conocer particularidades de su caso que usted sí conoce.

**Antes de usar cualquier resultado:**
- Verifique que las normas citadas estén vigentes
- Confirme que las sentencias mencionadas existan y digan lo que la IA indica
- Ajuste los hechos y la estrategia según su criterio profesional
- Firme solo lo que usted mismo revisó y respalda

La responsabilidad profesional es siempre suya. La IA es su asistente, no su reemplazo.

---

## ¿Tiene un skill que funciona bien en su práctica?

Este repositorio acepta colaboraciones. Si desarrolló o adaptó un skill que le ha sido útil, puede compartirlo:

1. Haga clic en **"Issues"** en la parte superior de esta página
2. Cree un issue nuevo con el título: `Nuevo skill: [nombre de la tarea]`
3. Pegue el texto del skill y describa para qué casos lo usa
4. Lo revisamos, lo probamos y lo agregamos con crédito para usted

También puede proponer mejoras a los skills existentes o reportar si algo no funciona como esperaba.

---

## Licencia

MIT — libre para usar, adaptar y compartir en su consultorio o firma.
