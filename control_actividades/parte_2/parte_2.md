# Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier operación que consideres necesaria.
1. Fork: Guardas una copia del repositorio del desarrollador en tu propia cuenta de GitHub para trabajar sin afectar el proyecto original.
2. Clone: Descargas esa copia de GitHub a tu computadora para poder abrirla en tu editor y trabajar en local.
3. Branch: Creas una rama nueva para separar tus cambios de la versión principal y no romper nada.
4. Modificar archivos: Abres el código en tu editor, haces los cambios o mejoras necesarias y guardas los archivos.
5. Commit: Guardas un punto de control en tu computadora con un mensaje corto explicativo de lo que hiciste.
6. Push: Subes la rama con tus cambios guardados desde tu computadora a tu repositorio en GitHub.
7. Pull Request: Mandas una solicitud desde GitHub al dueño del proyecto original para que revise tus cambios.
8. Review: El dueño del repositorio o el equipo revisa tu código y te da retroalimentación si hace falta ajustar algo.

# Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta y explica la diferencia entre Fork y Clone.
La afirmacion no seria correcta 
1. Clone: No crea nada en tu cuenta de GitHub; lo que hace es descargar una copia del proyecto directamente a la carpeta de la computadora para que pueda trabajar en él.
2. Diferencia: Fork se hace en la página de GitHub para duplicar un proyecto ajeno dentro de mi propia cuenta en la nube, mientras que Clone se usa para bajar el proyecto desde GitHub hasta mi computadora.

# Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?
1. No, los cambios todavía no forman parte del repositorio original. 
Mis modificaciones solo están guardadas en mi copia en GitHub.
Crear un Pull Request: Mandar una solicitud desde GitHub al dueño del repositorio original para proponerle mi cambio.
El dueño del proyecto revisa mi código para asegurarse de que todo esté bien.
Si me aprueba mi trabajo, el dueño le da al botón de "Merge" y mis cambios finalmente se unen al repositorio original.

# Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear otro Pull Request y qué ocurre cuando realizas nuevamente push.
1. Tengo que leer los comentarios o correcciones que dejó el propietario en GitHub, abrir mi proyecto local, hacer los ajustes necesarios en los archivos, guardarlos y hacer un nuevo Commit.
2. Al hacer Push de mis correcciones a la misma rama, los nuevos cambios se suben automáticamente al mismo Pull Request que ya había enviado. La página de GitHub se actualiza sola para que el propietario pueda revisar mi código corregido.

# Merge y Repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no contiene los cambios. Explica por qué sucede y qué operación debe realizarse.
1. El Merge se realizó directamente en GitHub, por lo que la rama principal de GitHub ya tiene los cambios actualizados, pero la computadora del propietario todavía tiene guardada la versión anterior que no incluye ese Merge.
2. El propietario debe hacer un Pull (git pull) en la terminal de su computadora.
Esta operación descarga automáticamente las modificaciones recién fusionadas en GitHub y las junta con los archivos de su repositorio local.

# Sync fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.
Registra este cambio en un cuarto commit con un mensaje descriptivo y súbelo a github.
1. Herramienta a utilizar: Usaría la opción Sync Fork directamente desde la página web de GitHub.
2. Se actualiza mi Fork en GitHub, poniéndolo al día con los últimos cambios que el dueño le hizo al proyecto original.
3. Sync Fork: Trabaja de nube a nube. Sincroniza el repositorio original con mi propia copia. No modifica nada de lo que tengo en mi computadora.
4. git pull: Trabaja de la nube a mi computadora. Trae los cambios guardados en GitHub y los une directamente con los archivos de  mi repositorio local.

