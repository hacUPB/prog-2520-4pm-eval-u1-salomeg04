# Ejercicios de repaso: 

## Ejercicio 1: 
Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo.

### Analisis

| variables de entrada | descripcion | 
|----------------------|-------------|
| cantidad de lapices | cuantos lapices se compran |

|variables de salida | descripcion | 
|--------------------|-------------|
|precio | valor que hay que pagar |

| constantes | descripcion |
|------------|-------------|
| 1000 | cantidad limite de lapices |
| $85, $90 | valor individualsegun la cantidad |

### Pseudocodigo

´´´  
inicio  
leer cantidad_de_lapices   
si cantidad_de_lapices >=1000  
   valor_unidad = 85  
si no   
   valor_unidad = 90  
fin si   
precio = valor_unidad * cantidad_de_lapices  
escribir "valor total: ", precio   
fin  

´´´  
### Diagrama de flujo

![actividad repaso 1](./Diagrama%20ejercicio%20repaso%201.drawio.png)  


## Ejercicio 2:
Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo.

### Analisis: 

| variables de entrada | descripcion | 
|----------------------|-------------|
| valor_compra | costo parcial de las prendas |

|variables de salida | descripcion | 
|--------------------|-------------|
|precio_final | valor que hay que pagar |
| descuento | valor del descuento |

| constantes | descripcion |
|------------|-------------|
| 250000 | valor a partir del cual se da el descuento |
| 15% , 8% | descuentos |

## Pseudocodigo:

´´´  
inicio  
leer valor_compra  
si valor_compra > 250000  
   descuento = valor_compra *0.15  
si no  
   descuento = valor_compra * 0.08  
fin si  
precio_final = valor_compra - descuento  
mostrar "valor a pagar: $ ", precio_final  
fin  

´´´  

### Diagrama de flujo

![actividad repaso 2](./Diagrama%20ejercicio%20repaso%202.drawio.png)  


## Ejercicio 3: 
El director de una escuela está organizando un viaje de estudios, y requiere determinar cuánto debe cobrar a cada alumno y cuánto debe pagar a la compañía de viajes por el servicio. La forma de cobrar es la siguiente: si son 100 alumnos o más, el costo por cada alumno es de $65.00; de 50 a 99 alumnos, el costo es de $70.00, de 30 a 49, de $95.00, y si son menos de 30, el costo de la renta del autobús es de $4000.00, sin importar el número de alumnos.

## Pseudocodigo:

´´´  
inicio  
leer alumnos  
si alumnos >= 100  
   costo alumno = 65  
si no    
   si alumnos >= 50  
       costo_alumno = 70  
    si no   
       costo_alumno = 95   
       si no costo_alumno = 4000/autobus  
fin si    
costo_total = alumnos * costo alumno   
mostar costo_total / costo_alumno  
fin    

´´´    
![actividad repaso 3](./Diagrama%20ejercicio%20repaso%203.drawio.png)  

## ejercicio 4:
una tienda de ropa tiene la siguiente promocion: por la compra de 3 productos, la prenda de menor valor, tiene un 70% de descuento. 
calcular cual fue el descuento aplicado y cuanto tiene que pagar la persona

## Pseudocodigo: 

 ´´´   
inicio    
leer cantidad_prendas     
si cantidad_prendas >= 3      

   leer prenda_1     
   leer prenda_2    
   leer prenda_3    
   
si (prenda_1 <= prenda_2) y (prenda_1 <= prenda_3) entonces      
            descuento = prenda_1 * 0.70   


sino si (prenda_2 <= prenda_3) y (prenda_2 <= prenda_1) entonces   
             descuento = prenda_2 * 0.70    
  

sino si (prenda_3 <= prenda_1) y (prenda_3 <= prenda_2) entonces   
             descuento = prenda_3 * 0.70    

fin si  
   
costo_total = ( prenda_1 + prenda_2 + prenda_3 ) - descuento  
mostrar "El descuento aplicado es: ", descuento  
        mostrar "El total a pagar es: ", costo_total  

 sino  
        mostrar "La promoción aplica solo para 3 o más prendas"  
  fin si   
fin  

´´´   

![actividad repaso 4](.)  



