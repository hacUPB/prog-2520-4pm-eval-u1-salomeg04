# Ejercicios de bucles:  

## Ejercicio 2:  
se requiere un algoritmo para determinar, de N cantidades, cuantas son cero, cuantas son menores que cero y cuantas son mayores que cero.
Realice el diagrama de flujo y el pseudocodigo. 

```  
inicio  
leer N  
cero=0  
mayores=0  
menores=0  
mientras N>0:  
  leer cant  
  si cant >0:  
     mayores=mayores+1  
  si no  
     si cant=0  
       ceros=ceros+1   
    si no  
       menores=menores+1  
    fin si  
  fin si  
  N= N-1  
fin mientras  
mostrar ceros,mayores, menores  
fin  
```


