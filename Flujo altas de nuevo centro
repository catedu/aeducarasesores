## Flujo de una petición de alta

### 1. Solicitud

*La dirección de un centro educativo* puede solicitar Aeducar para su centro educativo desde DOCEO (con login).
Las petición realizadas se graban en una tabla en DOCEO (de momento se accede a ella pidiendole a Dani, doceo@catedu.es que la envíe)
Cada petición genera automáticamente una incidencia en el soporte (redmine) y crea un usuario al *Gestor del centro*.
La incidencia se asigna automáticamente al grupo del CP de referencia del centro educativo. Esto se hace con una tabla de DOCEO pero no con integración contínua, es decir, debe actualizarse de vez en cuando (en octubre cuando los CP terminen de configurarse). La incidencia incluye datos de la solicitud.

### 2. Despliegues de solicitudes.

Periódicamente (jueves sobre las 14) se solicitará desde Catedu/Aeducar una copia de la tabla a doceo@catedu.es. Las solicitudes aceptadas se emplearan para rellenar [esta hoja de cálculo](https://docs.google.com/spreadsheets/d/1SQjFfnTrMeGh281k0fAcDIL5oK_Kc2BR91Upr8kUU0E/edit?usp=sharing). Se establece el estado "pendiente" de estos centros. No hay ningún control aún de solicitudes duplicadas. 
Se debe rellenar manualmente el servidor donde se desean desplegar los centros.
Incluir los centros en esta tabla alimenta el desplegable de aeducar.es Ni idea de porqué hay duplicados.
Los despliegues se realizarán a lo largo del viernes (uno semanal). Al realizar el despliegue hay que copiar esos nuevos registros desplegados en  https://docs.google.com/spreadsheets/d/1m7PDIyxf9D_ehj1EBENIVRFk8u1VmwPzIIiMOlIbnzo/edit?usp=sharing y avisar a las asesoría responsables de Aeducar en los CP de que las instancias ya están desplegadas (es mas seguro el mail pero se puede con incidencia con los responsables)

Claramente esta duplicidad de hojas de calculo es mejorable y será mejorada.

### 3. Configuración y entrega al centro.

Es responsabilidad de los CPs, en particular del grupo de asesores responsables de Aeducar del CP.

El CP conoce el usuario administrador y la contraseña facilitada. Debe cambiar esa contraseña en cada instancia de su ámbito para hacerla específica de ese CP.
Creemos que no hay problema en que todos las asesorías de un CP compartan ese usuario/contraseña.

Además debe seguir este proceso de configuración:

Los pasos que hay que dar para cada moodle antes de entregar las credenciales al gestor son:

* Cambiar la contraseña del usuario de administración del CP, en mi opinión conviene usar sólo una por CP para tener un equilibrio entre seguridad y pragmatismo.
* Registrar el sitio (sale nada mas loguearse y simplemente hay que aceptar)
* Configurar la página de inicio para seleccionar "Ninguno" donde aparecían "mostrar la lista de cursos" en el campo frontpage.
Se hace en ejemplodeurldeceip.aeducar.es/admin/settings.php?section=frontpagesettings
* [Configurar en cada instancia de modle](https://drive.google.com/file/d/1f205Esz8xAXY-d3KVCLWSMkKw6hFtAD3/view?usp=sharing): 
    * La página web del centro
    * Sus RRSS (si tienen, hay que consultarles si tienen y pedirles las direcciones y urls, no están en la hoja de cálculo pues se considero que se les estaban pidiendo demasiados datos)
    * Si los centros no tuvieran alguna de las RRSS habría que dejar el campo en blanco y reducir el número de clientes para que no aparezcan esos logos.
    * En esa misma página de “configuración de la página de inicio” poner el nombre del centro educativo en el campo “Título de la diapositiva”


Ya solo queda entregar las credenciales de “gestorae” a la persona responsable de la gestión del centro y ponerse a su disposición para el asesoramiento y la posible administración necesaria. Conviene informarle de la existencia de la plataforma de soporte, [de sus foros](https://soportearagon.catedu.es/projects/aeducar/boards) y de [su sección noticias](https://soportearagon.catedu.es/projects/aeducar/news) para estar al tanto de novedades y buenas prácticas de otros gestores.

Una vez finalizada la entrega, ya es conveniente cerrar el ticket, puesto que los usuarios tienen el acceso y control, una persona de referencia para asesorarle y una plataforma de soporte.

### 4. Seguimiento y asesoramiento.

Es conveniente conocer el estado del uso y configuración del moodle en cada centro, para ello, es bueno que las asesorías documenten [en esta hoja](https://docs.google.com/spreadsheets/d/1m7PDIyxf9D_ehj1EBENIVRFk8u1VmwPzIIiMOlIbnzo/edit?usp=sharing) estos avances.

* Cursos y categorías. El gestor de centro no puede subir csv de cursos, es el CP quien tiene permisos para poder hacer esa subida si fuera necesaria.
* Subida de usuarios. Existe una [normalización de los nombres de usuario](https://soportearagon.catedu.es/boards/2/topics/2) para una posible automatización de procesos futuros. 
Es posible desde el gestor de centros subir el csv para crear usuarios y matricularlos en los cursos. La traducción de los datos de GIR/SIGAD para esa creación de usuarios esta en https://csv.aeducar.es/
* Llegada de nuevos alumnos y gestión diaria. Es competencia del gestor de centro.







