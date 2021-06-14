US de Ciudadano refinadas (Sprint retrospective 02/06)

# US de Ciudadano refindadas
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

>>>o	Fecha de Nacimiento

>>>o	Capacidad de Volumen

>>- No debe estar registrado en el sistema

>>- Recibe su acceso único de cartonero generado por el sistema

# US de Secretaria refindadas

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


# US Cartonero refindadas

# User Story Specification: US13.1

## 1.	Descripción

Como cartonero quiero registrar la cantidad de materiales que dejo para contabilizar mi trabajo.

## 2.	Criterios de Aceptación
>>- Indicar identificador personal de recolector. 

>>- Indicar los tipos de material.

>>- Balanza bluetooth calcula el peso de cada material ingresado.

>>- recalcular el porcentaje de participacion del recolector identificado.

>>- actualizar los datos del deposito con los nuevos materiales depositados.

# User Story Specification: US13.2

## 1.	Descripción

Como cartonero quiero registrar que casas del recorrido visité para contabilizar mi trabajo.

## 2.	Criterios de Aceptación

>>- Indicar que casa de su recorrido visito

>>- Casas recorridas se eliminan del sistema.

>>- Casas no recorridas se consideran en el proximo dia.