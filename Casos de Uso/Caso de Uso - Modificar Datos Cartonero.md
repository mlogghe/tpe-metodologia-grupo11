# Nombre Caso de Uso: Modificar datos Cartonero

## 1. Descripción breve: Este caso de uso describe el proceso por el cual la secretaria quiere modificar los datos de un cartonero registrado.

>o Actor primario: Secretaria

>o Trigger: El caso de uso comienza cuando la secretaria quiere modificar los datos de un cartonero.

## 2. Curso básico: 

	1. El sistema solicita ingresar el identificador único del cartonero
	2. La secretaria ingresa el identificador unico del cartonero
	3. El sistema verifica el identificador
	4. El sistema solicita los nuevos datos (nombre, apellido, DNI, dirección y fecha de nacimiento)
	5. El sistema actualiza los datos del cartonero
	6. El caso de uso finaliza.
	
## 3. Curso alternativo: No existe un cartonero con el identificador ingresado
	
	3. El sistema verifica el identificador
	    3.1. El sistema comprueba que el identificador ingresado no se corresponde con ningun cartonero
	    3.2. El sistema informa la situacion
	    3.3. Ir a 1.
