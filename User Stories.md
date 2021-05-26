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

# User Story Specification: US2

## 1.	Descripción

Como ciudadano quiero depositar materiales en el centro de acopio para contribuir con la cooperativa.

## 2.	Criterios de Aceptación
>>- Indicar cuantos kilos de que materiales deposita

>>- Los materiales se imputan a un usuario generico denominado “vecino buena onda”

>>- De ser posible que los kilos se pasen automaticamente al sistema a traves de la balanza bluetooth

# User Story Specification: US3

## 1.	Descripción

Como ciudadano quiero poder ofrecer transporte en la cartelera virtual para transporte de materiales de otras personas que lo necesiten.

## 2.	Criterios de Aceptación
>>- El ciudadano debe ingresar los siguientes datos:
>>>o	Nombre

>>>o	Teléfono

>>>o	Dirección

>>>o	Correo

>>>o	Espacio Disponible

>>>o	Texto libre

>>- Se generara un post que incluya la zona geográfica, el espacio disponible y el texto libre.

>>- Requiere que la cartelera este creada.

# User Story Specification: US4

## 1.	Descripción

Como ciudadano quiero poder postularme en la cartelera virtual para hacer uso del servicio de transporte compartido.

## 2.	Criterios de Aceptación
>>- El ciudadano debe ingresar los siguientes datos:
>>>o	Nombre

>>>o	Teléfono

>>>o	Dirección

>>>o	Volumen de los materiales a retirar

>>- Indicar el volumen de los materiales a retirar, entre las opciones:
>>>o	a) entra en una caja

>>>o	b) entra en el baúl de un auto

>>>o	c) entra en la caja de una camioneta

>>>o	d) es necesario un camión

>>- Se debe enviar un mail al ciudadano que genero la oferta con los datos cargados.

# User Story Specification: US5

## 1.	Descripción

Como ciudadano quiero poder rechazar o acepar una postulacion a mi oferta para controlar las personas involucradas.

## 2.	Criterios de Aceptación
>>- El ciudadano que genero la oferta puede aceptar o rechazarla.

>>- Si se acepta la postulacion se enviaran los datos del ofertor al postulante.

>>- Si se rechaza la postulacion se enviara una notificación al postulante.

# User Story Specification: US6

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

>>- Recibe Id único de cartonero generado por el sistema

# User Story Specification: US7

## 1.	Descripción

Como secretaria quiero eliminar los datos de un cartonero para imposibilitar a este el uso del servicio.

## 2.	Criterios de Aceptación
>>- Indicar Id del cartonero

>>- Una vez borrado, no debe figurar en el listado de Cartoneros

# User Story Specification: US8 - **EPICA**

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

# User Story Specification: US9 - **EPICA**

## 1.	Descripción

Como secretaria quiero recibir el listado de recorridos de los cartoneros para poder informales sus rutas.

## 2.	Criterios de Aceptación
>>- Se debera ser equitativo con todos los cartoneros registrados.

>>- No se deberá asignar de forma diaria a un cartonero más de lo que puede transportar en su vehículo.

>>- En caso de asignarse varias viviendas a un cartonero, el total del recorrido (incluido el viaje hasta el depósito) no debe superar los 6km.

>>- Indicar el volumen de los materiales a retirar, entre las opciones:
>>>o	a) entra en una caja

>>>o	b) entra en el baúl de un auto

>>>o	c) entra en la caja de una camioneta

>>>o	d) es necesario un camión

# User Story Specification: US10

## 1.	Descripción

Como secretaria quiero poder cambiar los datos de la seccion que explica como entregar el material para que los ciudadanos sepan las restricciones y cuidados necesarios.

## 2.	Criterios de Aceptación
>>- Indica la forma de presentar los materiales

>>- Indica que materiales se aceptan en la cooperativa

# User Story Specification: US11

## 1.	Descripción

Como secretaria quiero conocer el porcentaje de la venta que le corresponde a cada cartonero para efectuar los pagos de manera correcta.

## 2.	Criterios de Aceptación
>>- Listar por cada cartonero los kilos acopiados de un material dado junto con el porcentaje del total acopiado

# User Story Specification: US12

## 1.	Descripción

Como secretaria quiero registrar la cantidad de kilos vendidos para que se pueda calcular los porcentajes de venta.

## 2.	Criterios de Aceptación
>>- Restar de forma equitativa de lo acopiado por cada cartonero los kilos vendidos.

# User Story Specification: US13

## 1.	Descripción

Como secretaria quiero poder iniciar sesión para acceder como "Administrador" al sistema.

## 2.	Criterios de Aceptación
>>- Usuario y Contraseña dedicados a ésta funcionalidad

# User Story Specification: US14

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

>>- Recibe Id único de cartonero generado por el sistema

# User Story Specification: US15 - **EPICA**

## 1.	Descripción

Como cartonero quiero registrar la cantidad de materiales que dejo y que casas del recorrido visité para contabilizar mi trabajo.
## 2.	Criterios de Aceptación
>>- Indicar cuantos kilos de que materiales deposita

>>- Indicar que casa de su recorrido visito

# User Story Specification: US16

## 1.	Descripción

Como cartonero quiero tener acceso a la lista de rutas para saber a donde ir.

## 2.	Criterios de Aceptación
>>- Debe ingresar su ID para acceder al sistema

>>- Podra ver su propia ruta generada por el sistema