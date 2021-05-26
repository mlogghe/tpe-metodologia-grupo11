# Nombre Caso de uso: Registrar cantidad de kilos vendidos.                                                                            
## 1. Descripción breve: Una secretaria quiere registrar la cantidad de kilos vendidos a una empresa recicladora.                                                                                                                                                                      
>o Actor primario: Secretaria.                                                                                                                                                                                  
>o Trigger: El caso de uso comienza cuando una secretaria quiere registrar en el sistema los kilos vendidos.                                                                                                                                                                                                        
## 2. Curso basico:                                                      

    1. El caso de uso comienza cuando una secretaria quiere registrar en el sistema los kilos vendidos.
    2. El sistema solicita el número de kilos vendidos.
    3. La secretaria ingresa la cantidad de kilos vendidos.                                                                              
    4. El sistema verifica el valor de kilos ingresados.                                               
    5. El sistema genera un porcentaje de ventas según la participación de cada cartonero para dividir las ganancias entre ellos.
    6. El sistema resta de forma equitativa de lo acopiado por cada cartonero.                                                  
    7. El caso de uso finaliza.

## 3. Curso alternativo: La cantidad de kilos ingresada no es válida.                                                                                                                             
    4. El sistema verifica el valor de kilos ingresados.
        4.1 El sistema determina que hay un error en la cantidad de kilos informada.                                                
        4.2 El sistema notifica la situación.                                                                                                            
        4.3 El sistema solicita reingresar el número de kilos vendidos.
        4.4 La secretaria informa una nueva cantidad de kilos vendidos.                                                                                  
        4.5  Ir al paso 5.                                                                                                                                                                                         
## 4. Suposición: La secretaria está logueada (Caso de uso:Login)