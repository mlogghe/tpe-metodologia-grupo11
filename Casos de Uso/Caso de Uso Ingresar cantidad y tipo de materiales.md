
# Nombre de caso de uso: Ingresar cantidad y tipo de materiales
## 1. Descripción breve: Un cartonero quiere registrar la cantidad y el tipo de materiales recolectados en el acopio.

>o Actor primario: Cartonero

>o Actor secundario: Balanza

>o Trigger: El caso de uso comienza cuando un cartonero quiere registrar la cantidad y tipo de materiales recolectados en el sistema.

## 2. Curso básico

    1. El Caso de Uso comienza cuando un Cartonero quiere registrar la cantidad y tipo de materiales recolectados en el sistema
    2. El Cartonero coloca los materiales recolectados sobre la balanza
    3. El Sistema obtiene el peso de dichos materiales a través de conexión bluetooh con la balanza
    4. El Sistema solicita el tipo de material recolectado
    5. El Cartonero ingresa el tipo de material
    6. PtoExt
    6. El Cartonero ingresa su identificador único
    7. El Sistema verifica el identificador ingresado
    8. El Sistema solicita los domicilios visitados para el recorrido asignado al Cartonero
    9. El Cartonero ingresa los domicilios visitados
    10. El Sistema actualiza los domicilios no visitados
    11. El Sistema guarda la información del pesaje
    12. El Sistema calcula el porcentaje de participación del Cartonero
    13. El Caso de Uso termina

## 3.1 Curso alternativo

    7. El sistema verifica el identificador ingresado
      7.1. El sistema comprueba que el identificador ingresado no existe
      7.2. El sistema informa del error
      7.3. El sistema solicita reingresar el identificador
      7.4 Ir a 6
>

## 4. Suposiciones
Los tipos de materiales recolectados por el Cartonero ya se encuentran registrados en el Sistema
