# Nombre del caso de uso: Modificar condiciones de entrega de materiales.


## 1. Descripción breve: La secretaria quiere modificar los tipos y el estado en la que se deben entregar los materiales.


>o Actor primario: Secretaria.


>o Trigger: El caso de uso comienza cuando la secretaria quiere modificar los datos que se muestran para la entrega de materiales.


## 2. Curso Básico:


	1. El caso de uso comienza cuando la secretaria quiere modificar los datos que se muestran para la entrega de materiales.

	2. El sistema muestra las opciones.
	>o Eliminar material
	>o Agregar material
	>o Modificar material
	3. La secretaria selecciona una opción.

	4. El sistema ejecuta la función seleccionada.

	5. Finaliza caso de uso.


## 3.1. Curso alternativo: La secretaria selecciona eliminar material.


	4. El sistema ejecuta la función seleccionada.
   		4.1. La opción seleccionada es eliminar material.
  		4.2. El sistema solicita el tipo de material a eliminar.
  		4.3. La secretaria ingresa el tipo de material.
   		4.4. El sistema elimina el material.
   		4.5. Ir al paso 5.


## 3.2. Curso alternativo: La secretaria selecciona agregar material


	4. El sistema ejecuta la función seleccionada.
   		4.1. La opción seleccionada es agregar material.

   		4.2. El sistema pide el estado y tipo de material a añadir.

   		4.3. La secretaria ingresa el estado y tipo de material.

   		4.4. El sistema añade el material.

   		4.5. Ir al paso 5.


## 3.3. Curso alternativo: La secretaria selecciona Modificar material


	4. El sistema ejecuta la función seleccionada.
   		4.1. La opción seleccionada es modificar material.
   		4.2. El sistema pide el tipo de el material a agregar.
  		4.3. La secretaria ingresa el tipo de material.
   		4.4. El sistema muestra en un cuadro de texto el estado del material.
  		4.5. La secretaria modifica el estado del material.
  		4.6. El sistema modifica el estado del material.
  		4.7. Ir al paso 5.


## 3.4. Curso alternativo: La secretaria ingresa un tipo de material incorrecto
        
        4.3  La secretaria ingresa el tipo de material.
                4.3.1 La secretaria ingresa un tipo incorrecto de material.
                4.3.2 El sistema notifica a la secretaria.
                4.3.3 El sistema solicita reingresar el tipo de material.
                4.3.4 Ir al paso 4.3.


## 4. Suposiciones: La secretaria está logueada.
