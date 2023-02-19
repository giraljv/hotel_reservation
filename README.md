# hotel_reservation
En este dataset nuestro objetivo será de descubrir cuales serán las variables que influyen más en la cancelación de reservas hoteleras.

## Under and over sampling
Aquí practico estos dos metodos para nivelar la cantidad de valores del target objetivo, porque está
mayormente contituido de un valor.
Esto ayuda a que el modelo tenga mejores resultados.
esto lo hice con la librería imblearn que nos ayuda con estos pipelines de procesamiento.

## Regresión logistica
Con ayuda de sklearn se crea un modelo de regresión logística para
predecir cuando es probable que el usuario cancele la reserva.
se llegó a un accuracy de 0.76%


