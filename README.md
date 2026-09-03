# Custom Discord Rich Presence for Java (VS Code)

Configuración personalizada y lista para usar de **Discord Rich Presence** enfocada en desarrollo en **Java** para Visual Studio Code.

Muestra un estado elegante en Discord indicando que estás programando en Java con un icono temático personalizado, tiempo transcurrido y detalles de edición.

---

## Vista previa

<img width="222" height="268" alt="JAVA - Discord" src="https://github.com/user-attachments/assets/b709836f-58d3-4b91-9145-88fd30472271" />

---

## Instalación y Configuración

Sigue estos 3 sencillos pasos para activarlo en tu entorno:

### 1. Instalar la extensión en VS Code
Abre Visual Studio Code e instala la extensión base:
* **Nombre:** `Discord Rich Presence`
* **Autor:** `leonardssh`
* **ID de extensión:** `leonardssh.vscord`

*(Puedes buscarla directamente en la pestaña de Extensiones presionando `Ctrl + Shift + X`).*

### 2. Aplicar la configuración
1. En VS Code, presiona `Ctrl + Shift + P`.
2. Escribe y selecciona: `Preferences: Open User Settings (JSON)`.
3. Pega el siguiente bloque de configuración dentro de las llaves principales `{ ... }` (recuerda poner una coma `,` en la línea anterior si ya tenías otros ajustes):

```json
"vscord.app.id": "1544865135963803780",
"vscord.status.image.large.editing.key": "java",
"vscord.status.image.large.idle.key": "java",
"vscord.status.image.large.debugging.key": "java"
