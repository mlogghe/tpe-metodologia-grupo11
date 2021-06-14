# Nombre del caso de uso: Eliminar Cartonero.

## 1. Descripción Breve: Este caso de uso describe el proceso por el cual la secretaria quiere dar de baja a un cartonero.

>o Actor primario: Secretaria.

>o Trigger: El caso de uso comienza cuando la secretaria quiere eliminar los datos de un cartonero.

## 2. Curso básico:

	1. El sistema solicita el número de documento del cartonero.
	2. La secretaria ingresa el número de documento del cartonero.
	3. El sistema verifica el número de documento ingresado.
	4. El sistema elimina de la lista al cartonero
	5. Finaliza el caso de uso.

## 3.1. Curso Alternativo: El documento ingresado no existe.

	4. El sistema verifica el número de documento ingresado.
   		1. El sistema verifica que existe un cartonero con ese número de documento.
  		2. El sistema informa a la secretaría de la situación.
  		3. Ir a 1

## 4. Precondición
>- Debe haber por lo menos un cartonero registrado.

## 4. Postcondición
>- La lista de cartoneros queda actualizada sin el cartonero eliminado

## 5. Suposiciones
>- La secretaria está logueada.
