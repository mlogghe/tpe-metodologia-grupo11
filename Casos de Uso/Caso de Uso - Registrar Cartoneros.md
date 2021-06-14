# Nombre Caso de Uso: Registrar Cartonero

## 1. Descripción breve: La secretaria quiere registrar un cartonero en el sistema para que el mismo figure de manera correcta.

>o Actor primario: Secretaria

>o Actor secundario: Cartonero

>o Trigger: El caso de uso comienza cuando la secretaria quiere registrar un cartonero en el sistema.

## 2. Curso básico: 
	1. Se piden el nombre, apellido, DNI, dirección, fecha de nacimiento y capacidad de volumen.

	2. Se ingresan el nombre, apellido, DNI, dirección, fecha de nacimiento y capacidad de volumen.

	3.El sistema verifica que el cartonero no este ya registrado.

	4.El sistema devuelve una id asociada al cartonero.

	5.El caso de uso termina.

## 3. Curso Alternativo: los datos personales del Cartonero ya se encuentran registrados
	3. El Sistema verifica los datos ingresados
		3.1	El Sistema identifica que existe alguien ingresado con esos datos
		3.2	El Sistema informa de la situación
		3.3	El Sistema solicita reingresar los datos personales
		3.4	El Cartonero ingresa nombre, apellido, DNI, dirección y fecha de nacimiento nuevos
		3.5	Ir al paso 4

>o Casos de uso extendidos: Extiende el caso de uso Ingresar cantidad y tipo de materiales cuando el cartonero se quiere registrar, en el punto de extension PtoExt.
