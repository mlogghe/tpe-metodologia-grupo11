# Nombre caso de uso: Acceder a las rutas asignadas

## 1. Descripción: Este caso de uso describe el proceso por el cual un cartonero desea acceder a las rutas asignadas

>o Actor primario: Cartonero

>o Trigger: El caso de uso comienza cuando el cartonero quiere acceder a las rutas asignadas en el sistema

## 2. Curso básico
	1. El cartonero ingresa un identificador unico
	2. El sistema verifica el identificador ingresado
	3. [INCLUDE] Obtener recorrido de cartonero
	4. El sistema presenta las rutas asignadas al cartonero
	5. El caso de uso finaliza

## 3. Curso alternativo
	2. El sistema verificara el identificador ingresadi
		2.1 El sistema comprueba que no hay un cartonero registrado con el identificador ingresado
		2.2 El sistema informa la situacion
		2.3 El sistema solicita reingresar el identificador unico
		2.4 Ir a 1

>o Caso de uso incluido: Obtener recorrido de cartonero
