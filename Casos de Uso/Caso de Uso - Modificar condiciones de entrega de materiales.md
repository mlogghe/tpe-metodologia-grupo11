# Nombre del caso de uso: Modificar condiciones de entrega de materiales.


## 1. Descripción breve: El caso de uso describe el proceso por el cual la secretaria quiere modificar condiciones de entrega de materiales.

>o Actor primario: Secretaria.
>o Trigger: El caso de uso comienza cuando la secretaria quiere modificar los datos que se muestran para la entrega de materiales.

## 2. Curso Básico:

	1. El sistema muestra las opciones disponibles:
	- Eliminar material
	- Agregar material
	- Modificar material
	3. La secretaria selecciona una opción.
	4. El caso de uso finaliza.


## 3.1. Curso alternativo: La secretaria selecciona eliminar material.

	3. La secretaria selecciona una opcion.
   		3.1. La opción seleccionada es eliminar material.
  		3.3. La secretaria ingresa el tipo de material.
        	3.4. El sistema elimina el tipo de material.
   		3.5. Ir a 4.


## 3.2. Curso alternativo: La secretaria selecciona agregar material

	3. La secretaria selecciona una opcion.
   		3.1. La opción seleccionada es agregar material.
   		3.2. El sistema pide el estado y tipo de material a añadir.
   		3.3. La secretaria ingresa el estado y tipo de material.
   		3.4. El sistema añade el material.
   		3.5. Ir a 4.


## 3.3. Curso alternativo: La secretaria selecciona Modificar material

	3. La secretaria selecciona una opcion.
   		3.1. La opción seleccionada es modificar material.
   		3.2. El sistema solicita el tipo de material a modificar
  		3.3. La secretaria ingresa el tipo de material.
   		3.4. El sistema solicita el nuevo estado del material
		3.5. La secretaria ingresa el nuevo estado
		3.6. El sistema actualiza el estado del material
		3.7. Ir a 4.


## 3.4. Curso alternativo: La secretaria ingresa un tipo de material incorrecto
        
        3.3  La secretaria ingresa el tipo de material.
                3.3.1 El sistema comprueba que el tipo de material no existe
                3.3.2 El sistema notifica a la situacion.
                3.3.3 El sistema solicita reingresar el tipo de material.
                3.3.4 Ir al paso 3.3.


## 4. Suposiciones: 
>- La secretaria está logueada.
