## Flujo de trabajo en GitHub e IntelliJ

1. **Detecto el error de la interfaz**:
    - Primero, detecté un error en la interfaz de usuario de la aplicación.

2. **Creo un Issue en GitHub**:
    - Voy a GitHub y creo un **issue** explicando el error encontrado.

3. **Revertir el último commit**:
    - Realizo un `undo` para revertir el último commit que afectaba a la interfaz y corregir el error.

4. **Hago un nuevo commit para cerrar el issue**:
    - Realizo un nuevo **commit** con el mensaje `closes #<número del issue>`, de forma que este commit cierre el issue automáticamente en GitHub.

5. **Creo un nuevo Issue**:
    - Creo un **nuevo issue** en GitHub, que menciona que nos falta la interfaz y la base de datos.

6. **Trabajo en las ramas**:
    - Me aseguro de estar en la rama **main** y luego hago un **merge** de la rama de base de datos (**BD**) creando un Pull Request (PR).
    - Repito el proceso de Pull Request para la rama de interfaz.

7. **añadidas BS e interfaz**:
    - hice el commit con el mensaje `closes #3` para cerrar el segundo issue.

8. **Actualización del archivo `.gitignore`**:
    - Aproveché para cambiar el archivo `.gitignore` y añadir las reglas para que ignore las carpetas `.idea` y el archivo `ExamenCODfinal.iml` escribiendo exactamente esas 2 cosas, que a veces me causaban problemas.

9. **Commit final con nombre de la versión**:
    - Realicé el último commit con el nombre de la **versión** actual del proyecto.

10. **pullrequest**:
    - cuando hice ñps **pull request**, hicieron merge a la rama *main* en vez de *main origin*, y cuando hice push a esta ultima hicieron un merge entre ellas, pero sin conflictos.
