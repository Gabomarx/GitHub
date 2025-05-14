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
