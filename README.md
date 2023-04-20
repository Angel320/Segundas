# Segundas
 SH U2

Breve descripción de la función del programa

 
El sistema consta de 3 opciones para registrar, alumnos, otra para profesores y la ultima para maestros, en la siguiente captura se muestra el registro de la opción alumnos, consta de un formulario sencillo y un botón para enviar la solicitud del registro, una vez aceptado se le muestra al usuario un mensaje en donde le indique que el registro había sido guardado, así con cada una de las opciones de registro que se muestran en las siguientes capturas.



Como mencionamos anteriormente, en las siguientes capturas se muestra el registro de las 3 opciones mencionadas, para nuestro diseño MVC, primero el usuario ingresa los datos correspondientes, este envia la solicitud del registro en donde en nuestro controlador se encarga de verificar los datos y una vez que se haya guardado en el modelo, se envia una respuesta grafica mediante un mensaje que indique que el registro fue guardado correctamente.
 
 
 














En los siguientes códigos tenemos el controlador que presenta varias funciones para poder guardar correctamente el registro, desde la conexión a la BD y comprobar los datos del registro, una vez se haya guardado correctamente, se envía una respuesta a la vista del formulario en donde si la respuesta es afirmativa entonces se mostrara el susodicho mensaje que se ve en las anteriores capturas. 
