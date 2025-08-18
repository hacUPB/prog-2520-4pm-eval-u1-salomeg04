# 2. Control de temperatura del motor
 Durante una inspección de rutina, se mide la temperatura de un motor de turbina. Si la temperatura es mayor a un valor crítico, se debe indicar "Peligro: sobrecalentamiento". Si está dentro del rango seguro, indicar "Operación normal". Si es demasiado baja, indicar "Motor frío – Calentar antes de operar".

 ## Tabla: 

| v. entrada | v. salida | constante | unidades|   
|------------|-----------|-----------|---------|  
| temperatura_motor | indicador | temperatura | celcius |   

## Pseudocodigo:  

```    
inicio  
  temperatura=500  
  escriba "ingrese: temperatura del motor"  
  leer temperatura_motor  

    si temperatura_motor > 500 entonces   
    mostrar "Peligro: sobrecalentamiento"    

         si no si temperatura = 500 entonces  
         mostrar  "Operación normal"    

         si no   
         mostrar "Motor frío – Calentar antes de operar"    

     fin si   
     
fin  
```    


# 4. Control de combustible en pruebas
Durante un ensayo en banco de un motor a reacción, se mide el nivel de combustible cada minuto y se detiene el registro cuando el combustible baja del 10%. Mostrar el tiempo total de operación antes de llegar a ese punto.

 ## Tabla: 

| v. entrada | v. salida | v. control |
|------------|-----------|------------|
| nivel_combustible | tiempo_total | i |

## Pseudocodigo:  

``` 
inicio  
i=0
     escribir "ingrese: nivel de combustible (%)"
     leer nivel_combustible

 
         mientras nivel_combustible >=10
         i=i+1
         escribir "nivel de combustible"
         leer nivel_combustible fin mientras mostrar tiempo_total

fin
```  

# 6. Control de temperatura en cabina
Un sistema mide cada 5 minutos la temperatura en cabina durante una hora. Si en algún momento se detecta una temperatura mayor a 27°C o menor a 18°C, debe indicar que se active el sistema de climatización.

 ## Tabla: 

| v. entrada | v. salida |v.control | constante |
|------------|-----------|------------|---------|
|temperatura| temperatura | i | 12 | 

## Pseudocodigo:

``` 
inicio  
i=0
mientras i< 12
i=i+1
escribir "ingrese: temperatura en cabina"
leer temperatura 
     si temperatura > 27 entonces 
     mostrar activar sistema de climatizacion 

         si no si temperatura < 18 entonces 
         mostrar activar sistema de climatizacion 
    
    fin mientras 
    
     fin si 

fin
```  

