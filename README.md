# Segundas
 SH U2

Breve descripción de la función del programa

 
El sistema consta de 3 opciones para registrar, alumnos, otra para profesores y la ultima para maestros, en la siguiente captura se muestra el registro de la opción alumnos, consta de un formulario sencillo y un botón para enviar la solicitud del registro, una vez aceptado se le muestra al usuario un mensaje en donde le indique que el registro había sido guardado, así con cada una de las opciones de registro que se muestran en las siguientes capturas.

<img src="https://github.com/Angel320/Segundas/blob/main/menu.jpg">

------
Como mencionamos anteriormente, en las siguientes capturas se muestra el registro de las 3 opciones mencionadas, para nuestro diseño MVC, primero el usuario ingresa los datos correspondientes, este envia la solicitud del registro en donde en nuestro controlador se encarga de verificar los datos y una vez que se haya guardado en el modelo, se envia una respuesta grafica mediante un mensaje que indique que el registro fue guardado correctamente.
 
 <img src="https://github.com/Angel320/Segundas/blob/main/registro1.jpg">
 <img src="https://github.com/Angel320/Segundas/blob/main/registro2.jpg">
 <img src="https://github.com/Angel320/Segundas/blob/main/registro3.jpg">



En los siguientes códigos tenemos el controlador que presenta varias funciones para poder guardar correctamente el registro, desde la conexión a la BD y comprobar los datos del registro, una vez se haya guardado correctamente, se envía una respuesta a la vista del formulario en donde si la respuesta es afirmativa entonces se mostrara el susodicho mensaje que se ve en las anteriores capturas. 

 <img src="https://github.com/Angel320/Segundas/blob/main/codigo1.jpg">
 <img src="https://github.com/Angel320/Segundas/blob/main/codigo2.jpg">





En esta vista, se tiene una condición IF que valida la respuesta del controlador ya una vez guardo el registro en nuestro modelo, en caso de que sea así, se mostrara el mensaje de que el registro se ah guardado con éxito, en caso contrario, no muestra nada o muestra algún mensaje de error que indique que hubo un problema al guardar o falta algun campo por llenar.
 
   <img src="https://github.com/Angel320/Segundas/blob/main/codigo3.jpg">


------



En la opción de reportes, se presentan 3 tipos de tablas con información registrada (Profesor, Alumno, Materia), en donde cada uno de estos datos puede ser modificado o eliminado, una vez que se haya eliminado o modificado, se envía la petición al servidor y se actualiza las tablas juntos a un mensaje que indica que se a realizado la acción con éxito, Además, se puede hacer una petición para generar un reporte en formato PDF.
  
   <img src="https://github.com/Angel320/Segundas/blob/main/reporte.jpg">
  
 	
Para poder gestionar las acciones de las tablas que muestran los registros, creamos un controlador el cual dependiendo de la acción enviara al modelo (nuestra base de datos) la petición de la acción que el usuario hizo, devolviéndole una respuesta grafica en la vista donde este se actualiza en caso de modificar el registro, o este se borra en caso de eliminar el registro, dependiendo de la tabla, se usara una función u otra.

   <img src="https://github.com/Angel320/Segundas/blob/main/codigo4.jpg">




