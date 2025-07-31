# Ejercicios Finales de Repaso

## 1. Explica, en tus propias palabras, por qué es necesario que las computadoras representen los datos en binario. 
Las computadoras funcionan con electricidad y solo pueden reconocer dos estados: encendido (1) y apagado (0). Por eso, utilizan el sistema binario para representar toda la información. Cada número, letra o imagen se convierte en una secuencia de ceros y unos que la computadora puede entender y procesar mediante circuitos electrónicos.   

## 2. Convierte el número binario 10011011 a decimal y a hexadecimal. 
## Decimal:  
|128 |64 |32 |16 |8 |4 |2 |1 |  
|---|---|---|---|---|---|---|---|  
|1 |0 |0 |1 |1 |0 |1 |1 |

1+2+8+16+128=155 
## Hexadecimal: 
Se divide en dos grupos de 4 bits: 1001 1011  
1001 = 9  
1011 = B  
Entonces: 9B  

## 3. Investiga y describe cómo se representa una imagen en formato PNG en el disco.
Una imagen PNG se guarda en el disco como una serie de bytes que siguen un formato específico. Este formato incluye:  
-Cabecera: información sobre el tipo de archivo.  
-Metadatos: ancho, alto, profundidad de color, etc.  
-Datos comprimidos: cada píxel (con color y transparencia) se guarda y se comprime usando un algoritmo llamado DEFLATE.  
-CRC: códigos para verificar la integridad del archivo.  
-Todo esto permite que el archivo PNG sea ligero, sin perder calidad y con soporte para transparencia.  

## 4. Analiza la siguiente situación: ¿Qué sucede si intentas almacenar un número mayor al que puede representar un byte (por ejemplo, 300)? ¿Cómo lo maneja Python?
Un byte solo puede representar valores entre 0 y 255 (8 bits). Si intentas guardar el número 300 en un solo byte, ocurre un desbordamiento: se pierde parte de la información y el número cambia.

En Python, si usas una estructura como bytes, te dará un error:

bytes([300])
#### ValueError: bytes must be in range(0, 256)
Pero Python puede manejar números grandes sin problema en variables normales, porque internamente usa estructuras más complejas para almacenar enteros de cualquier tamaño.

## Ejercicio adicional clase:  
tenemos 3 archivos:  
texto - 52794 caracteres  
76931 - datos enteros  
105230 - datos punto flotante  

¿cuantos bytes?

R//:  52,794 caracteres×1 byte= 52,794 bytes  
76,931×4 bytes= 307,724 bytes  
105,230×4 bytes= 420,920 bytes  
total= 781,438 bytes  

781,438/1,024= 763,123 KB​	  
 

​	
 

