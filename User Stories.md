# User Story Specification: US1 - **EPICA**

## 1.	Descripción

Como ciudadano quiero dar aviso de que tengo materiales que pueden ser retirados para que los cartoneros puedan buscarlos.

## 2.	Criterios de Aceptación
>>- Se deben ingresar los datos personales del ciudadano:
>>>o	Nombre

>>>o	Apellido

>>>o	Dirección

>>>o	Teléfono

>>- Indicar franja horaria de preferencia para que retiren los materiales, entre las opciones:
>>>o	De 9 a 12hs

>>>o	De 13 a 17hs

>>- Indicar el volumen de los materiales a retirar, entre las opciones:
>>>o	a) entra en una caja

>>>o	b) entra en el baúl de un auto

>>>o	c) entra en la caja de una camioneta

>>>o	d) es necesario un camión

>>- Posibilidad de Adjuntar una foto de los materiales

>>- En caso de que el lugar este a mas de 6km del centro de acopio el sistema debe denegar la solicitud

>>- Si se deniega la solicitud se debe informar al ciudadano de que lo acerque personalmente al centro de acopio.

# User Story Specification: US1.1

## 1. Descripcion
Como ciudadano quiero dar aviso de que tengo materiales para que algun asociado de la cooperativa los retire

## 2. Criterios de aceptacion
>>- Indicar nombre, apellido, direccion y telefono

>>- Indicar franja horaria de preferencia para que retiren los materiales, de 9 a 12hs o de 13 a 17hs.

>>- Indicar el volumen de los materiales a retirar, hay 4 categorias de volumen: 
>>>o a) entra en una caja 

>>>o b) entra en el baúl de un auto

>>>o c) entra en la caja de una camioneta

>>>o d) es necesario un camión

>>- Adjuntar una foto de los materiales

>>- Implementar método que calcule la distancia desde la dirección del ciudadano hasta el centro de acopio.

>>- En caso de que el lugar este a mas de 6km del centro de acopio el sistema debe denegar la solicitud

>>- Si se deniega la solicitud se debe informar al ciudadano de que lo acerque personalmente al centro de acopio.

# User Story Specification: US1.2

## 1. Descripcion
Como ciudadano quiero poder confirmar el retiro de los materiales junto con una reseña para poder avisar a la cooperativa que mis materiales fueron retirados exitosamente.

## 2. Criterios de aceptacion
>>- Confirmar la operacion desde la plataforma diseñada o otro metodo de comunicacion.

>>- ingresar reseña si lo desea.

>>- ingresar valoracion del servicio.

# User Story Specification: US1.3

## 1. Descripcion
Como cidadano quiero poder dar de baja a mi aviso de materiales para poder avisar a la cooperativa de que no pase por mi casa

## 2. Criterios de aceptacion
>>- Confiramar que el ciudadano debe tener un retiro de materiales programado.

>>- Cidadano debe poder mediante plataforma o correo electronico enviar notificacion de cancelacion de retiro.

>>- Eliminar del sistema la direccion y si ya se calculo una ruta con esa direccion se la elimina.

>>- Si el recolector asignado tiene un medio de comunicacion electronico se avisa que se modifico su ruta del dia.

# User Story Specification: US2

## 1.	Descripción

Como ciudadano quiero depositar materiales en el centro de acopio para contribuir con la cooperativa.

## 2.	Criterios de Aceptación

>>- Diseñar formulario para que el usuario ingrese los datos de los materiales

>>- Implementar método que obtenga el peso de la balanza bluetooth

>>- Implementar un método que registre los materiales con su respectivo peso en la base de datos

>>- Indicar cuantos kilos de que materiales deposita

>>- Los materiales se imputan a un usuario generico denominado “vecino buena onda”

>>- De ser posible que los kilos se pasen automaticamente al sistema a traves de la balanza bluetooth

# User Story Specification: US2.1

## 1.	Descripción

Como ciudadano quiero depositar materiales en el centro de acopio para contribuir con la cooperativa.

## 2.	Criterios de Aceptación

>>- Ciudadano se identifica como "Vecino buena onda".

>>- Los materiales se imputan a un recolector generico denominado “vecino buena onda”

>>- Ingresar detalles de materiales.

>>o Tipos.

>>o Volumenes.


# User Story Specification: US2.2

## 1.	Descripción

Como ciudadano quiero que el peso de los materiales se registren automaticamente para facilitar el proceso de deposito.

## 2.	Criterios de Aceptación

>>- Ingresar tipo de material.

>>- Calcular peso del material.

>>- Implementar método que obtenga el peso de la balanza bluetooth

>>- Implementar un método que registre los materiales con su respectivo peso en la base de datos

>>- Los kilos y otros datos de interes se pasan automaticamente al sistema a traves de la balanza bluetooth

# User Story Specification: US3 - **EPICA**

## 1.	Descripción

Como ciudadano quiero poder ofrecer transporte en la cartelera virtual para transporte de materiales de otras personas que lo necesiten.

## 2.	Criterios de Aceptación
>>- Diseñar formulario para que el usuario cargue los datos

>>- El ciudadano debe ingresar los siguientes datos:
>>>o	Nombre

>>>o	Teléfono

>>>o	Dirección

>>>o	Correo

>>>o	Espacio Disponible

>>>o	Texto libre

>>- Implementar método que genere un post con los datos ingresados

>>- Se generara un post que incluya la zona geográfica, el espacio disponible y el texto libre.

>>- Requiere que la cartelera este creada.

# User Story Specification: US3.1

## 1.	Descripción

Como ciudadano quiero poder ofrecer transporte de materiales en la cartelera virtual para facilitar el transporte de materiales para otros ciudadanos

## 2.	Criterios de Aceptación
>>- El ciudadano debe ingresar los siguientes datos:
>>>o	Nombre

>>>o	Teléfono

>>>o	Dirección

>>>o	Volumen de los materiales a retirar

>>- Indicar el volumen de capacidad libre en el transporte, entre las opciones:
>>>o	a) entra en una caja

>>>o	b) entra en el baúl de un auto

>>>o	c) entra en la caja de una camioneta

>>>o	d) es necesario un camión

>>- Se carga en el sistema su oferta.

>>- Se generara un post que incluya la zona geográfica, el espacio disponible y el texto libre.

>>- Requiere que la cartelera este creada.

# User Story Specification: US3.2

## 1.	Descripción

Como ciudadano quiero poder postularme en la cartelera virtual para hacer uso del servicio de transporte compartido.

## 2.	Criterios de Aceptación
>>- El ciudadano debe ingresar los siguientes datos:
>>>o	Nombre

>>>o	Teléfono

>>>o	Dirección

>>>o	Volumen de los materiales a retirar

>>- Indicar el volumen de los materiales a retirar, entre las opciones:

>>o 	a) entra en una caja

>>o 	b) entra en el baúl de un auto

>>o 	c) entra en la caja de una camioneta

>>o 	d) es necesario un camión

>>- Adjuntar imagen de los materiales

>>- Implementar método que genere un post con los datos ingresados

>>- Requiere que la cartelera este creada.


# User Story Specification: US3.3

## 1.	Descripción

Como ciudadano que ofrece transporte quiero poder rechazar o aceptar a un postulante para controlar las personas involucradas.

## 2.	Criterios de Aceptación
>>- El ciudadano que se postulo puede aceptar o rechazar ofertas.

>>- Si se acepta la oferta se enviaran los datos del ofertor al postulante.

>>- Si se rechaza la oferta se enviara una notificación al ciudadano que se postulo.

# User Story Specification: US3.4

## 1.	Descripción

Como ciudadano quiero poder rechazar o aceptar un ciudadano que ofrecio transporte para controlar las personas involucradas.

## 2.	Criterios de Aceptación
>>- El ciudadano que genero la oferta puede aceptar o rechazarla.

>>- Si se acepta la postulacion se enviaran los datos del ciudadano al postulante que ofrecio el transporte.

>>- Si se rechaza la oferta se enviara una notificación al ciudadano postulante.

# User Story Specification: US3.5

## 1. Descripcion

Como ciudadano que se postulo quiero tener acceso a la del ciudadano que ofrece transporte para poder coordinar con el a la hora de transportar los materiales

## 2. Criterios de aceptacion
>>- Ciudadano que ofrece transporte ingresa datos requeridos.

>>- Implementar método que genere un post con los datos ingresados del ciudadano que ofrece transporte

>>- Ciudadano postulante debe haber ingresado su correo electronico de contacto con anterioridad

# User Story Specification: US3.6

## 1. Descripcion

Como ciudadano que ofrece transporte quiero saber los datos de los postulados para coordinar con el y estar seguro.

## 2. Criterios de aceptacion
>>- Ciudadano que se postula debe haber ingresado datos requeridos.

>>- Ciudadano que ofrece tranporte recibe correo electronico con datos ingresados del postulante.

# User Story Specification: US4

## 1. Descripcion

Como ciudadano quiero tener acceso a la lista actualizada de materiales aceptados por la cooperativa para poder reciclar correctamente

## 2. Criterios de aceptacion
>>- Secretaria debe poder ingresar la informacion de reciclado

>>- Ciudadano debe tener acceso a la plataforma con las indicaciones de reciclado


------------------------------------------------------------------------------------------------

# User Story Specification: US5 - **EPICA**

## 1.	Descripción

Como secretaria quiero modificar los datos de un cartonero para mantener actualizado el listado de cartoneros.

## 2.	Criterios de Aceptación
>>- Se deben poder modificar los siguientes datos del cartonero:
>>>o	Nombre

>>>o	Apellido

>>>o	DNI

>>>o	Dirección

>>>o	Fecha de Nacimiento

>>>o	Capacidad de Volumen

>>- El cartonero debe estar registrado en el sistema

>>- Si se quiere eliminar se saca de la lista de cartonero y se borran sus recorridos.

>>- Si no esta registado, se lo da de alta.

# User Story Specification: US5.1

## 1.	Descripción

Como secretaria quiero dar de alta un cartonero para permitir a éste utilizar el servicio.

## 2.	Criterios de Aceptación
>>- Se deben ingresar los datos personales del cartonero:
>>>o	Nombre

>>>o	Apellido

>>>o	DNI

>>>o	Dirección

>>>o	Fecha de Nacimiento

>>>o	Capacidad de Volumen

>>- No debe estar registrado en el sistema

>>- Recibe su acceso único de cartonero generado por el sistema

# User Story Specification: US5.2

## 1.	Descripción

Como secretaria quiero eliminar los datos de un cartonero para imposibilitar a este el uso del servicio.

## 2.	Criterios de Aceptación
>>- Indicar acceso único del cartonero

>>- Una vez borrado, no debe figurar en el listado de Cartoneros

>>- Se borran todas los datos relaciados con el cartonero.

# User Story Specification: US5.3

## 1.	Descripción

Como secretaria quiero mantener actualizados los datos de un cartonero para corregir errores o cambios.

## 2.	Criterios de Aceptación
>>- Se deben poder modificar los siguientes datos del cartonero:
>>>o	Nombre

>>>o	Apellido

>>>o	DNI

>>>o	Dirección

>>>o	Fecha de Nacimiento

>>>o	Capacidad de Volumen

>>- El cartonero debe estar registrado en el sistema


# User Story Specification: US6

## 1.	Descripción

Como secretaria quiero recibir el listado de recorridos de los cartoneros para poder informales sus rutas.

## 2.	Criterios de Aceptación
>>- Se debera ser equitativo con todos los cartoneros registrados.

>>- El sistema debe haber generado los recorridos.

>>- Secretaria identifico su correo electronico personal.

>>- Se envia un correo con la lista generada por el sistema.

# User Story Specification: US7

## 1.	Descripción

Como secretaria quiero poder cambiar los datos de la seccion que explica como entregar el material para que los ciudadanos sepan las restricciones y cuidados necesarios.

## 2.	Criterios de Aceptación
>>- Indica la forma de presentar los materiales

>>- Indica que materiales se aceptan en la cooperativa

# User Story Specification: US8

## 1.	Descripción

Como secretaria quiero conocer el porcentaje de la venta que le corresponde a cada cartonero para efectuar los pagos de manera correcta.

## 2.	Criterios de Aceptación
>>- Listar por cada cartonero los kilos acopiados de un material dado junto con el porcentaje del total acopiado

>>- Tiene que haber registrado una venta de materiales. 

# User Story Specification: US9

## 1.	Descripción

Como secretaria quiero registrar la cantidad de kilos vendidos para que se pueda calcular los porcentajes de venta.

## 2.	Criterios de Aceptación
>>- Restar de forma equitativa de lo acopiado por cada cartonero los kilos vendidos.

# User Story Specification: US10

## 1.	Descripción

Como secretaria quiero poder iniciar sesión para acceder como "Administrador" al sistema.

## 2.	Criterios de Aceptación
>>- Usuario y Contraseña dedicados a ésta funcionalidad

>>- se le concede permisos de "administrador"

# User Story Specification: US11

## 1.	Descripción

Como secretaria quiero que el sistema genere los recorridos para simplificar mi trabajo.

## 2.	Criterios de Aceptación
>>- El sistema debe generar recorridos de manera equitativa para todos los cartoneros registrados a las 8 AM de lunes a viernes

>>- El sistema no debe asignar de forma diaria a un cartoner mas de lo que puede transportar en su vehiculo

>>- El sistema debe comprobar que el total del recorrido del cartonero no supera los 6km

>>- El sistema debera enviar el listado completo de los recorridos al correo de la secretaria

>>- En caso que el volumen a retirar por el cartonero corresponda a la categoría “a”, el sistema deberá asignarle el mismo en caso de que el lugar de recolección quede
en su camino a otras viviendas con categorías de volumen mayores (es decir, “b”, “c” y “d”)

------------------------------------------------------------------------------------------------------

# User Story Specification: US12

## 1.	Descripción

Como cartonero quiero registrarme en el sistema con el objetivo de dar de alta los materiales recolectados.

## 2.	Criterios de Aceptación
>>- Se deben ingresar los datos personales del cartonero:
>>>o	Nombre

>>>o	Apellido

>>>o	DNI

>>>o	Dirección

>>>o	Fecha de Nacimiento

>>>o	Capacidad de Volumen

>>- No debe estar registrado en el sistema

>>- Recibe su acceso único de cartonero generado por el sistema

# User Story Specification: US13 - **EPICA**

## 1.	Descripción

Como cartonero quiero registrar la cantidad de materiales que dejo y que casas del recorrido visité para contabilizar mi trabajo.

## 2.	Criterios de Aceptación
>>- Indicar el tipo de material.

>>- Indicar que casa de su recorrido visito

>>- Balanza bluetooth calcula el peso del material ingresado.

>>- recalcular el porcentaje de participacion y actualizar los datos del deposito.


# User Story Specification: US13.1

## 1.	Descripción

Como cartonero quiero registrar la cantidad de materiales que dejo para contabilizar mi trabajo.

## 2.	Criterios de Aceptación
>>- Indicar identificador personal de recolector. 

>>- Indicar los tipos de material.

>>- Balanza calcula el peso de cada material ingresado.

>>- Nota avisa al cartonero los datos ingresados y calculados.

# User Story Specification: US13.2

## 1.	Descripción

Como cartonero quiero registrar que casas del recorrido visité para contabilizar mi trabajo.

## 2.	Criterios de Aceptación

>>- Indicar que casa de su recorrido visito

>>- Identifica casas que no confirmaron el retiro de los materiales

>>- Casas recorridas se eliminan del sistema.

>>- Casas no recorridas se consideran en el proximo dia.

# User Story Specification: US13.3

## 1.	Descripción

Como cartonero quiero usar una balanza conectada al sistema para asegurarme de que el peso de los materiales se registra correctamente

## 2.	Criterios de Aceptación

>>- Se indica el tipo de material.

>>- La balanza es inalambrica y esta conectada al sistema

>>- El sistema registra el tipo de material ingresado y el peso relacionado a este.

>>- recalcular el porcentaje de participacion del recolector identificado.

>>- actualizar los datos del deposito con los nuevos materiales depositados.



# User Story Specification: US14

## 1.	Descripción

Como cartonero quiero tener acceso a la lista de rutas para saber a donde ir.

## 2.	Criterios de Aceptación
>>- Debe ingresar al sistema

>>- Identificar credenciales.

>>- Podra ver su propia ruta generada por el sistema.

