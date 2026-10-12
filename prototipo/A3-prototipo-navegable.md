# A3 · Prototipo navegable, prueba de uso y video

## Foto de la hoja 5 · seis bocetos de pantalla
Pendiente: la foto la tiene el equipo.

## Forma del prototipo
☒ Aplicación navegable

## Enlace o archivo del prototipo
- Enlace: https://claude.ai/artifact/QB49m9CRsGgRLyG2DJtzNa (compartir como enlace público desde el menú «Compartir» antes de entregarlo).
- Archivo: `TheBackOffice-prototipo.html` (se abre con doble clic en un computador).

El prototipo simula el MVP «Mago de Oz»: la empresa se registra, configura sus datos, su equipo y su propio panel de tareas. Cada tarea tiene una pauta. El colaborador la completa desde el celular; si todo calza y el monto está bajo el límite, se cierra sola; si algo no calza, vuelve a quien la hizo; si supera el límite o es crítica, llega al dueño. En computador se ve como página web y en el celular como app.

## Enlace del video (30 a 60 segundos, sin narración)
Archivo: `video-prototipo-the-back-office.mp4` (58 segundos, 1280×720, sin audio, con rótulos en pantalla). Subirlo a YouTube como «No listado» o a Drive con acceso por enlace y pegar aquí el enlace.

Recorrido del video:
1. Crear cuenta con nombre, empresa y teléfono.
2. Datos de la empresa: sin los campos obligatorios no se avanza.
3. Equipo cargado desde un archivo CSV.
4. Armar el panel: una tarea con su pauta (cantidad esperada y foto).
5. El colaborador registra una cantidad distinta y la tarea vuelve; la corrige y se cierra sola.
6. El dueño ve sus 13 tareas, aprueba la que supera su límite y filtra el panel.

## Prueba de uso cruzada · registro del equipo observador
Lo completa el equipo observador durante la prueba, con las palabras textuales del usuario. Pantallas sugeridas para las filas:

| Pantalla | ¿Se detuvo? | Lo que dijo el usuario (textual) |
|---|---|---|
| Crear cuenta y datos de la empresa | | |
| Equipo y panel de tareas (configuración) | | |
| Panel del dueño: aprobar una tarea | | |
| Vista del colaborador: cerrar una tarea contra la pauta | | |

## ¿Llegó a la petición sin ayuda?
☐ Sí ☐ No — según lo que ocurra en la prueba. Nota: desde la versión 4 la petición («Probar con mi empresa») ya no está en el panel; solo se llega a ella desde la guía de prueba.

## Lo que corrigieron en el prototipo después de la prueba
Cambios hechos en el prototipo, por versión:

- **Versión 1** (desde el informe): panel del dueño del mockup, vista del colaborador en el celular, regla de cierre por pauta y límite, reasignación cuando alguien no está, diferencias entre lo pedido y lo recibido, historial de quién hizo qué, petición para probar con una tarea real.
- **Versión 2:** registro e inicio de sesión; configuración en 3 fases (empresa, colaboradores y tareas) con campos obligatorios y opcionales, sin opciones predefinidas; carga de colaboradores y tareas desde Excel o CSV, o carga asistida para otros formatos; panel de tareas propio y editable (crear, editar, repetir y quitar tareas, cada una con su pauta); el panel muestra la totalidad de las tareas.
- **Versión 3:** el límite de aprobación acepta montos mayores o iguales a $0; los filtros del panel de tareas se deslizan horizontalmente.
- **Versión 4:** el registro pide solo nombre, empresa y teléfono, y se inicia sesión con el teléfono; se quitó el teléfono de los datos de la empresa; correo y WhatsApp del colaborador en campos separados; se quitó «¿Lo probamos con una tarea real?» del panel.
- **Versión 5:** correo y WhatsApp uno debajo del otro y obligatorios, con correo sin dominio; fondo blanco y texto negro en todas las pantallas; formato de página web en computador.
