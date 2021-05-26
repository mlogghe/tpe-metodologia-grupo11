# Nombre caso de uso: Generar recorridos

## 1.Descripción: El sistema genera los recorridos de los cartoneros

>o Actor primario: Reloj

>o Trigger: El caso de uso se activa todos los días habiles a las 8 am.

## 2. Curso básico:
	1. El sistema asigna a cada cartonero viviendas
	2. El sistema comprueba el total del recorrido
	3. El sistema comprueba el volumen de materiales a retirar por el cartonero
	4. El sistema envia el listado de recorridos por mail a la secretaria
	5. El caso de uso finaliza

## 3. Cursos alternativos:
	2. El sistema comprueba el total del recorrido
		2.1 El sistema identifica que el recorrido total del cartonero supera los 6 km con varias viviendas
		2.2 El sistema quita viviendas en el recorrido del cartonero
		2.3 Ir al paso 3

	3. El sistema comprueba el volumen de materiales a retirar por el cartonero
		3.1 El sistema identifica que se le esta asignando mas de lo que puede transportar el cartonero
		3.2 El sistema quita materiales a retirar en el recorrido del cartonero
		3.3 Ir al paso 4

## 4. Post-condición:
>- La generacion de recorridos es equitativa para todos los cartoneros registrados
