# Taller de algoritmos:

## 1. Verificación de peso de despegue:
En una pista de pruebas de aeronaves, el sistema debe verificar si el peso total de la aeronave, incluyendo combustible y carga, supera el límite máximo permitido para el despegue. Dependiendo del resultado, el sistema deberá indicar si la aeronave está lista para despegar o si debe reducir carga o combustible.

## Tabla: 

| v. entrada | v. salida | constantes | unidad |
|------------|-----------|------------|--------|
|peso_combustible, peso_carga | peso_total | peso_limite | toneladas |

## Pseudocodigo:

``` 
inicio    
  peso_limite = 640    
  escribir "ingrese: peso del combustible:"   
  leer peso_combustible  
  escribir "ingrese peso de la carga:"   
  leer peso_carga 

  peso_total = peso_combustible + peso_carga  

    si peso_total > peso_limite entonces   
     mostrar "error: reducir carga"   
      
      si no   
       mostrar "listo para despegue"  

      fin si   

fin   
``` 

## 3. Registro de altitudes de vuelo:
Un sistema debe registrar la altitud de vuelo cada 10 minutos durante una hora y mostrar todas las mediciones al final.  

## Tabla: 

| v. entrada | v. salida | v. control | constante |  
|------------|-----------|------------|-----------|  
| registro_altitud | registro_altitud | i | 5 |  
 
## Pseudocodigo:   

```    
inicio   
   mientras i < 5   
   leer registro_altitud   
       altitud [i] = registro_altitud  
       i=i+1  
       mostrar "altitud[i]"  
       fin mientras  
fin    
```   

## 7. Simulación de conteo de pasajeros:
Durante el abordaje, un sistema cuenta a los pasajeros que ingresan. Si el número total supera la capacidad máxima, el sistema debe detener el conteo y mostrar un mensaje de alerta.

## Tabla:   

| v. salida | v. control | constante |  
|-----------|------------|-----------|  
| pasajeros_ingresan | i | capacidad_maxima |  


## Pseudocodigo: 

```  
inicio  
i=0  
  capacidad_maxima = 100   
    mientras 0<=i<99  
     
    i=i+1  
      mostrar pasajeros[1]  

        si i > 99  entonces   
        mostrar "error, capacidad superada"  
          
        si no   
          mostrar "listos para despegar"  

        fin si   
    fin mientras    
fin   
```  






