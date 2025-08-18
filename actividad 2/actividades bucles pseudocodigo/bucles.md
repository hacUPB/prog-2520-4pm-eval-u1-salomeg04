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
 

<img width="682" height="900" alt="Diagrama 1 drawio" src="https://github.com/user-attachments/assets/979b6cc5-7a25-494d-a0f9-d03b275fe202" />  

## Ejercicio 3:   
calcular el factorial de un numero entero ingresado por el ususario.  

|variable de entrada |
|--------------------|
|N|

|variable de salida|
|------------------|
|factorial|

|variable de control |
|-------------------|
|i|

```
inicio  
leer N  
  fact=1  
 mientras N>0  
   fact=fact*N  
   N=N-1  
    fin mientras  
  mostarar fact  
fin  
```
<img width="444" height="622" alt="Diagrama 3 drawio" src="https://github.com/user-attachments/assets/1f16a77a-e0f6-4a19-b07c-926459f740b7" />









