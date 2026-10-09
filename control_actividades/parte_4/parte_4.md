# Conceptos
1. Explica la diferencia entre Git y GitHub.
Respuesta: Git es el programa que instalo en mi computadora para ir guardando los cambios y versiones de mi código. GitHub es la página web donde subo esos proyectos para tener un respaldo en la nube, compartirlos o trabajar en equipo con otros compañeros.

2. Explica para qué sirve .gitignore.
Respuesta: Es un archivo donde pongo el nombre de las cosas que no quiero que Git suba ni rastree. Sirve para evitar subir archivos basura, contraseñas o carpetas muy pesadas que no hacen falta en el proyecto.

3. Explica por qué .venv no debe almacenarse normalmente en GitHub.
Respuesta: Porque la carpeta .venv tiene los archivos del entorno virtual y las librerías instaladas en mi compu, así que pesa mucho y depende de mi sistema operativo. No se sube a GitHub porque le quitaría espacio innecesario al repo y a otra persona no le servirá igual en su compu; mejor se sube solo el requirements.txt.

4. Explica para qué sirve requirements.txt.
Respuesta: Es un archivo de texto con la lista de librerías y sus versiones que necesita el proyecto para funcionar. Sirve para que cualquier compañero (o yo en otra compu) pueda instalar todo rápido con el comando pip install -r requirements.txt.

5. Explica la diferencia entre Stage, Commit y Push.
Respuesta:

Stage (Staging Area): Es la zona donde elijo y preparo qué archivos modificados van a entrar en el siguiente guardado.

Commit: Es el guardado o "foto" de esos cambios en el historial local de mi computadora, junto con un mensaje donde explico qué hice.

Push: Es la acción de subir todos esos commits que guardé en mi compu hacia el repositorio remoto en GitHub.

6. Explica por qué un repositorio puede tener varios commits antes de realizar un push.
Respuesta: Porque puedo ir trabajando en varias cosas a lo largo del día y hacer varios commits para guardar mis avances paso a paso en mi compu sin necesitar internet. Ya cuando termino de trabajar o al final del día, hago un solo push y subo todo ese grupo de commits juntos a GitHub.