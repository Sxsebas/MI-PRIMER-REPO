- 1. ¿Qué diferencia hay entre preparar un archivo y confirmarlo?
  #### Preparar un archivo lo deja listo para realizar el commit y confirmarlo lo añade en la rama.
- 2. ¿Cuándo puedes usar Descartar cambios y qué riesgo tiene?
  #### Para retroceder al estado anterior de la rama, especialmente útil para corregir errores, aunque puede suponer perder progreso, pudiendo ser un riesgo.
- 3. ¿Qué pasa con tu trabajo cuando cambias de una rama a otra?
  #### Que se puede desarrollar en distintas líneas de tiempo, especialmente útil si se trabaja con otras personas para que cada uno trabaje por su cuenta desde un estado, y también se puede utilizar para experimentar con distintas ramas. 
- 4. ¿Por qué no hubo conflicto al fusionar rama-a pero sí al fusionar rama-b?
  #### Porque la rama-a era una adición a la rama main, el problema por el que se crea el conflicto es que la rama-b trataba de añadir el mismo tipo de adición que hace la rama-a. Al fianal se ha solucionado el conflicto vinculando ambas partes, pero en un caso real puede que se deba de borrar alguna parte, sobreescribir, o vincular ambas como este caso.
- 5. ¿Para qué sirve crear una rama de experimento, aunque luego se borre?
  #### Para realizar todo tipo de modificaciones sin correr el riesgo de obtener un mal resultado. Simplemente si hay algo bueno en toda la reescritura y adiciones se añade, sino se borra por completo.  
- 6. Si descubres hoy un error cometido hace cinco commits, ¿qué haces para arreglarlo?
  #### Retrocedo a la línea del tiempo para poder visualizar el código de aquel momento,concretamente 5 commits atrás. Ahora simplemente basta con copiar el código que si funcionaba y remplazar el que falla y finalmente publicar un nuevo commit con correcciones,. 