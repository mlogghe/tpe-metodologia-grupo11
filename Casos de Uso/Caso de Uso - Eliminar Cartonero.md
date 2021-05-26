#Nombre del caso de uso: Eliminar Cartonero.

## 1. Descripción Breve: La secretaria quiere dar de baja a un cartonero eliminando sus datos de la lista de cartoneros.

>o Actor primario: Secretaria.

>o Trigger: El caso de uso comienza cuando la secretaria quiere eliminar los datos de un cartonero.

## 2. Curso básico:

	1. El caso de uso comienza cuando la secretaria quiere eliminar los datos de un cartonero.

	2. El sistema solicita el número de documento del cartonero.
	3. La secretaria ingresa el número de documento del cartonero.
	4. El sistema verifica el número de documento ingresado.
	5. El sistema muestra los datos del cartonero.
	6. El sistema solicita confirmación de la baja.
	7. La secretaria debe confirmar la eliminación del cartonero.
	8. La secretaría válida la eliminación del cartonero.
	9. El sistema actualiza la lista de los cartoneros.
	10. Finaliza el caso de uso.

## 3.1. Curso Alternativo: El documento ingresado no existe.

	4. El sistema verifica el número de documento ingresado.
   		1. El sistema verifica que existe un cartonero con ese número de documento.
  		2. El sistema informa a la secretaría de la situación.
  		3. El sistema pide reingresar el número de documento.
  		4. La secretaría vuelve a ingresar el número de documento.
  		5. Ir al paso 5.

## 3.2. Curso Alternativa: La secretaria no confirma la baja del cartonero.
	7. La secretaria  debe confirmar la eliminación del cartonero.
   		1. La secretaria no confirma la baja del cartonero.
   		2. Ir al paso 9.

## 4. Precondición: Debe haber por lo menos un cartonero registrado.

## 5. Suposiciones: La secretaria está logueada.
