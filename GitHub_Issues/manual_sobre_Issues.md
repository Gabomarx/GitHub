## 🧩 Introducción a Issues y su función

### ❓ ¿Qué es un Issue?
Un **Issue** en GitHub es una herramienta para reportar errores, sugerir mejoras o gestionar tareas dentro de un repositorio. 🛠️ Es una forma de comunicación estructurada entre los colaboradores de un proyecto.

---

### 🎯 ¿Para qué se usan?
Se usan para:
- 🐛 Reportar bugs o errores detectados en el código.
- 💡 Proponer nuevas funcionalidades o mejoras.
- ✅ Registrar tareas pendientes.
- 💬 Discutir aspectos específicos del desarrollo entre los miembros del equipo.

---

### 🔍 Diferencia entre un Issue y un Pull Request

Aunque ambos se utilizan para colaborar en proyectos, cumplen funciones distintas:

| 📌 Característica       | 📝 Issue                            | 🔃 Pull Request                        |
|-------------------------|-------------------------------------|----------------------------------------|
| Propósito               | Describir un problema o sugerencia  | Proponer cambios al código             |
| Modifica el código      | ❌ No                                | ✅ Sí                                   |
| Se usa para discutir    | ✅ Sí                                | ✅ Sí (pero sobre cambios específicos)  |
| Se puede cerrar con PR  | ✅ Sí, mediante palabras clave       | 🔚 Se cierra al hacer merge             |

---

### 📍 ¿Dónde se crean?
Dentro del repositorio, accede a la pestaña **"Issues"** y haz clic en **"New issue"**. Desde ahí puedes completar un formulario con título, descripción y otros datos relevantes.

Ruta: `Repositorio > Issues > New issue`

---

### 🔄 Propósito en el flujo de trabajo de un equipo
Los Issues son fundamentales para el flujo de trabajo colaborativo, ya que:
- 🗂️ Ayudan a organizar y priorizar tareas.
- 👤 Facilitan la asignación de responsabilidades.
- 🧾 Permiten registrar el historial de problemas y decisiones.
- 🤝 Promueven la transparencia y la participación de todos los miembros del equipo.

Su uso adecuado mejora la productividad y coordinación dentro del equipo de desarrollo 🚀.

---

## 🧩 Uso práctico y propiedad 

## 🚀 Uso prático de Issues en GitHub

### 🛠️ ¿Cómo crear un Issue paso a paso?
👣 Pasos:
1. Ir al repositorio → pestaña Issues → botón New issue
2. Escribir un título claro y una descripción detallada
3. Asignar etiquetas y personas (opcional)

---

## 🏷️ Asignar etiquetas (labels) y personas responsables
### Las etiquetas te ayudan a clasificar los Issues:
| Etiqueta       | Signficado | 
|---------------|----------------|
| bug               | Error en el código  | 
| enhancement      | Propuesta de mejora  | 
| question    | Duda técnica  | 
| documentation  | Falta o mejora de documentación    | 

👉 Para asignarlas, ve al panel derecho del Issue (Labels / Assignees)

📸 Ejemplo: Asignándome un issue con bug y mi nombre como responsable.

![Captura de pantalla 2025-05-14 165113](https://github.com/user-attachments/assets/867f3746-12a3-4daf-a61a-356a0821b9b5)

---

## 🔗 Enlazar un Issue con un commit o Pull Request
### ✨ ¿Por qué es útil?
Permite que GitHub cierre automáticamente el Issue cuando se hace merge del PR (Pull Request).

💻 Ejemplo:

Cuando haces un commit o abres un PR, escribe en el mensaje:

![image](https://github.com/user-attachments/assets/0d1a0a9e-a992-411e-9108-8393ae436511)

✅ Al hacer merge del PR, GitHub cerrará automáticamente el issue #1

---

## 🧩 Issues como herramienta de seguimiento y responsabilidad compartida

## 🔍 ¿Por qué son clave los Issues para el seguimiento del proyecto?
En proyectos colaborativos, especialmente cuando se trabaj en equipo, es fácil que las tareas se olviden, se dupliquen o que alguien no sepa qué le toca hacer.
Los Issues solucionan esto al actuar como una **lista pública de tareas activas**, donde todos pueden ver:
- Qué hay pendiente
- Quién lo esta haciendo
- Qué prioridad tiene
- Cuál es el estado de avance

---

## 💬 Usando comentarios y menciones (@usuario)

Los comentarios permiten que el equipo discuta detalles de cada Issue, den contexto adicional y sugieran soluciones. Se usan para:

- Hacer preguntas o solicitar aclaraciones🤔
- Proporcionar detalles sobre el problema🤓☝️
- Mencionar (@usuario) a personas para que revisen el Issue🗣️
- Adjuntar imágenes, códigos o enlaces relevantes🖼️

### 👯‍♀️Para mencionar a alguien:  
`@usuario` → Notifica al usuario sobre el comentario.

![image](https://github.com/user-attachments/assets/d3dcf296-0160-4577-b19d-398989c07080)

---

## 👥 Fomentan la responsabilidad compartida
Cuando se asigna un Issue a alguien, se está dejando claro quién es el responsable directo, pero como los comentarios están abiertos, todo el equipo puede colaborar con sugerencias, preguntas o revisiones.

Esto crea un entorno de trabajo:

- 📣 Más transparente
- 💬 Más colaborativo
- 🔄 Más controlado

---
## 🤖Automatización de Issues

GitHub permite automatizar acciones en los Issues mediante GitHub Actions o automated workflows dentro de Projects!! Puedes:

- *Mover Issues automáticamente* cuando se les asigne una etiqueta👻
- *Cerrar Issues* cuando un PR con un *commit* de corrección se fusione (`Fixes #XX`)😶‍🌫️
- *Notificar responsables* cuando un Issue esté pendiente por resolver☝️

---

## 💃Buenas prácticas en la gestión de Issues
Un uso eficiente de Issues mejora la organización del equipo y facilita el trabajo colaborativo. Ayudándonos a ser más eficientes!!🦁

Algunas buenas prácticas incluyen:

### 📝Escribir títulos claros
- ❌ _"Error en formulario"_ →  Demasiado general.  
- ✅ _"El botón de envío no responde en Chrome"_ →  Más específico.

### 🔖Usar etiquetas adecuadas
- `bug` → Para errores en el código⛔
- `enhancement` → Para propuestas de mejora🔂
- `documentation` → Para cambios en la documentación✏️

### 📅Asignar responsables y fechas límite
- Agregar *Assignees* para asignar tareas a personas específicas🤫
- Definir una fecha límite usando *GitHub Projects*⏱️
 ---

## 🏁Milestones en Issues

Por último, introduciremos brevemente *Milestone* de GitHub que es una herramienta que nos puede servir para los Issues.

### 📌¿Qué es un Milestone en GitHub?
Un **Milestone** (hito) es una herramienta que permite agrupar varios Issues bajo un mismo objetivo o fecha de entrega⌛. Se usa para planificar versiones, sprints o metas dentro de un proyecto.

### 🛠️¿Cómo crear un Milestone?
1. Ir al repositorio → pestaña *Issues* → sección *Milestones*
2. Hacer clic en *New Milestone*!
3. Asignar un nombre, una descripción y una fecha límite😎
4. Guardar y empezar a asignar Issues!!!

### 🔗Vincular Issues a un Milestone
Para agregar un Issue a un Milestone:
1. Abre un **Issue**
2. En el panel derecho, busca la sección **Milestone**
3. Selecciona el hito al que pertenece el Issue

Y listo!!! tienes tu **Issue** vinculado a tu *Milestone*😎😎

### 🤩Beneficios de usar Milestones
- Facilita la planificación de versiones o entregas🤫
- Agrupa Issues que forman parte de una misma tarea👯‍♀️
- Ayuda a visualizar el progreso del equipo🧐
- Mejora la organización de proyectos grandes🤙

### 📊Seguimiento de Milestones
GitHub permite ver el avance de un Milestone con:
- *Cantidad de Issues abiertos/cerrados*🧐
- *Porcentaje de progreso* de los Issues completados🤖
- *Fecha límite* para saber si el equipo está cumpliendo el objetivo📌

  ![image](https://github.com/user-attachments/assets/eb3e97a1-79e9-4c5a-adf2-3a67b20d5022)

---
Para más info sobre los *Milestones* puedes hacer click [Aquí]([https://ruta-de-la-imagen.png](https://docs.github.com/en/issues/using-labels-and-milestones-to-track-work/about-milestones)🥰


Y recuerda!!

💡 "Los Issues no solo organizan tareas, sino que fomentan la responsabilidad individual y el compromiso grupal. Su uso permite llevar un control claro del avance del proyecto sin depender de recordatorios informales."

