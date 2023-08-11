# TFG_JMF "Modelado de la Contaminación Atmosférica en una Ciudad Mediante el Uso de la Inteligencia Artificial"

En este repositorio se encuentran alojados los notebooks que se implementaron para el desarrollo del Trabajo Fin de Grado del autor Javier Martín Fernández.

Los notebooks que se pueden encontrar en el repositorio son los siguientes:
- SARIMA.
- SARIMAX.
- Modelos RNN Una Dim Salida Sin Codificación.
- Modelos RNN Una Dim Salida One Hot.
- Modelos RNN Una Dim Salida Características Cíclicas.
- Modelos RNN N Dim Salidas V1.
- Modelos RNN N Dim Salidas V2.

  En los notebooks "SARIMA" y "SARIMAX" se encuentran implementados éstos dos modelos. Se pueden cambiar los valores de las constantes start_date, end_date y start_date_dt para ampliar o reducir las muestras con las que se entrenarán los modelos.

  En el notebook "RNN Una Dim Salida Sin Codificación" se implementan las redes neuronales de tipo LSTM y GRU con una salida sin aplicar codificación en las caracrerísticas temporales.
  
  En el notebook "RNN Una Dim Salida One Hot" se implementan las redes neuronales de tipo LSTM y GRU con una salida aplicando la codificación One-Hot en las caracrerísticas temporales.

  En el notebook "Modelos RNN Una Dim Salida Características Cíclicas" se implementan las redes neuronales de tipo LSTM y GRU con una salida aplicando la codificación cíclica en las caracrerísticas temporales.

  En el notebook "Modelos RNN N Dim Salidas V1" se implementan las redes neuronales de tipo LSTM y GRU con n salidas. En esta versión se entrenan los modelos con un índice combinado, compuesto por la fecha y el número de estación. El vector de características contiene una sola estación.

  En el notebook "Modelos RNN N Dim Salidas V2" se implementan las redes neuronales de tipo LSTM y GRU con n salidas. En esta versión se entrenan los modelos con un índice simple, añadiendo al vector de caracerísticas la información de las n estaciones.

Para ejecutar los códigos usted puede abrir los notebooks en el entorno colaborativo "Google Colaboratory" o abrirle directamente con "Jupyter" y ejecutar las celdas con código.

Si desea ponerse en contacto con el autor puede escribir un correo electrónico a la dirección jamarnandez@gmail.com.


