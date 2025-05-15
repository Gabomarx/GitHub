# Introduciéndonos a los Pull Requests en GitHub🔄

## ¿Qué son los Pull requests?😯✨

Un **Pull Request** en GitHub es una solicitud que un usuario hace para que sus cambios en el código
sean revisados e incorporados en un proyecto. De esta manera los cambios se fusionan en un repositorio
Git Hub. Es una forma de colaborar en proyectos de software, especialmente en código abierto.

## ¿Por qué son importantes los Pull Requests?🤔

Los **Pull Requests** son importantes para el desarrollo colaborativo porque permiten:

1. *Revisión de código* antes de que sea incorporado al proyecto principal🔍
2. *Colaboración entre desarrolladores* sin afectar directamente el código original👩‍💻
3. *Discusión sobre los cambios*, lo que mejora la calidad del software✅
4. *Historial claro* de quién hizo qué cambios y por qué✍️

## Diferencias entre *push* y *pull requests*😼

El comando *git pull* en GitHub permite a los desarrolladores descargar y actualizar su código local
con los últimos cambios que han sido añadidos en el repositorio remoto. Esta herramienta sirve 
para mantener el trabajo sincronizado en equipos colaborativos. Cuando un proyecto es modificado por 
otros desarrolladores, git pull obtiene esas actualizaciones y las fusiona automáticamente con el 
código que tienes en tu máquina. Esto ayuda a evitar conflictos y garantiza que siempre estés 
trabajando con la versión más reciente del proyecto.

### Comparación entre `git push` y Pull Request en GitHub💡

| Concepto 👁️‍🗨️     | `git push` | Pull Request |
|--------------|------------|--------------|
| **Descripción** | Envía cambios desde el repositorio local al remoto. | Solicita la revisión e integración de cambios en un repositorio remoto. |
| **Función principal** | Subir cambios a una rama del repositorio remoto. | Facilitar la revisión y aprobación de cambios antes de fusionarlos. |
| **Uso** | Se ejecuta con el comando `git push` en la terminal. | Se crea dentro de GitHub mediante la interfaz web. |
| **Modificación directa** | Los cambios se aplican directamente en la rama remota. | Los cambios requieren aprobación antes de ser fusionados. |
| **Interacción con el equipo** | No incluye revisión previa; los cambios pueden ser automáticos. | Permite discusión, revisión y aprobación por otros colaboradores. |
| **Cuándo se usa** | Cuando se quiere compartir cambios con el repositorio remoto. | Cuando se quiere proponer modificaciones en un proyecto sin afectar la rama principal directamente. |

También, `git push` es un comando de Git, mientras que un **Pull Request** es una función propia 
de GitHub, ambos sirven para administrar cambios colaborativos.😊

##  🌿 Crear una rama nueva

Antes de hacer cambios importantes, es recomendable trabajar en una rama (branch) distinta a la rama principal (main o master).

```bash
git checkout -b nombre-de-tu-rama
```
## 🛠️ Hacer cambios en esa rama
Realiza las modificaciones necesarias en tu proyecto (añadir funciones, corregir errores, etc.) y guarda tus cambios.

Luego, guarda esos cambios en el repositorio local:

```bash
git add .
git commit -m "Descripción clara de los cambios"
```

## 🚀 Subir cambios al repositorio
Después de confirmar tus cambios localmente, necesitas subirlos al repositorio remoto en GitHub:
```bash
git push origin nombre-de-tu-rama
```
## 🔃 Crear un Pull Request desde esa rama
En GitHub, ve a tu repositorio y haz clic en el botón verde "Compare & pull request" que aparece cuando subes una rama nueva.
1. *Elige la rama base (por lo general main) y la rama con tus cambios.
2. *Agrega un título y una descripción explicando qué hiciste.
3. *Haz clic en "Create pull request".

## 💬 Comentar, revisar y aprobar o rechazar cambios
Otros colaboradores pueden revisar tu PR, dejar comentarios, sugerencias o aprobar los cambios. Esto es clave para el trabajo en equipo. 🧠🤝

## 🤝 Colaboración y resolución de conflictos en Pull Request

### 👀 ¿Cómo revisar el código de otro miembro?

Una de las grandes ventajas de los Pull Request es que permiten revisar el código de otros compañeros antes de que se mezcle con el proyecto prinicipal. Eso se puede hacer directamente desde GitHub:

1. Abre el Pull Request.
2. Lee los archivos modificados en la pestaña Files changed".
3. Deja comentarios línea por línea si algo no se entiende o se puede mejoras.
4. Usa reacciones (✅❌💬) para interactuar con los comentarios de otros.

Así evitamos errores y aprendemos mutuamente💡.

---

### 💬 Usar comentarios en línea en un Pull Request

GitHub permite escribir comentarios directamente sobre líneas de código específicas. Esto es bueno para:

- 🛠️ Hacer sugerencias precisas.
- 🤔 Preguntar por decisiones del código.
- 📈 Proponer mejoras.

Un comentario bien hecho puede evitar muchos problemas más adelante. Recordar siempre el ser claro, respetuoso y contructivo con tus compañeros.

---

### 🔥 Resolver conflictos de fusión (merge conflicts)

A veces, dos personas editan el mismo archivo o línea de código. Cuando eso pasa, GitHub no sabe cuál versión mantener ¡y aparece un conflicto! 😱 

### ¿Cómo resolverlo?

1. GitHub te avisará que hay un conflicto.
2. Debes ir al archivo en conflicto y ver algo como esto:

![image](https://github.com/user-attachments/assets/ecffe4f5-69f5-418e-9391-993747c5960d)

3. Elimina los maracadores <<<<<<<, ======= y >>>>>>>, y decide cuál versión conservar (o fusionar lo mejor de ambas).
4. Guarda el archivo, haz un git add y luego un git commit.
5. Por último, sube los cambios (git push) y listo.

### ✅ Hacer el merge final al aprobar un Pull Request

Cuando todo este revisado y aprobado:
1. Se hace clic en "Merge pull request".
2. Puedes elegir el tipo de merge (merge commit, squash, rebase).
3. Finalmente, se borra la rama si ya no se necesita (opcional).

🎉 ¡Y así los cambios pasan oficialmente a formar parte del proyecto!

## 🧠 Refelexión final

La colaboración en GitHub no solo se trata de escribir un buen código, **¡sino de trabajar en equipo!** Saber cómo revisar, comentar y resolver conflictos es tan importante como programar.
Los Pull Request nos enseñan que el código mejora cuando muchas menten trabajan juntas. 🔄✨
