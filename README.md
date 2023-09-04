# TFG_JMF "Modelado de la Contaminación Atmosférica en una Ciudad Mediante el Uso de la Inteligencia Artificial"

En este repositorio se encuentran alojados los notebooks que se implementaron para el desarrollo del Trabajo Fin de Grado del autor Javier Martín Fernández.

Los notebooks que se pueden encontrar en el repositorio son los siguientes:
- SARIMA.
- Modelos RNN Una Dim Salida Sin Codificación.
- Modelos RNN Una Dim Salida One Hot.
- Modelos RNN Una Dim Salida Características Cíclicas.
- Modelos RNN 3 Dim Salidas V1 One-Hot.
- Modelos RNN 3 Dim Salidas V1 Codificación Cíclica.

  En los notebooks "SARIMA" se encuentran implementado el modelo SARIMA. Se pueden cambiar los valores de las constantes start_date, end_date y start_date_dt para ampliar o reducir las muestras con las que se entrenarán los modelos.

  En el notebook "RNN Una Dim Salida Sin Codificación" se implementan las redes neuronales de tipo LSTM y GRU con una salida sin aplicar codificación en las caracrerísticas temporales.
  
  En el notebook "RNN Una Dim Salida One Hot" se implementan las redes neuronales de tipo LSTM y GRU con una salida aplicando la codificación One-Hot en las caracrerísticas temporales.

  En el notebook "Modelos RNN Una Dim Salida Características Cíclicas" se implementan las redes neuronales de tipo LSTM y GRU con una salida aplicando la codificación cíclica en las caracrerísticas temporales.

  En el notebook "Modelos RNN 3 Dim Salidas V1 One-Hot" se implementan las redes neuronales de tipo LSTM y GRU con n salidas. En esta versión se entrenan los modelos con un índice combinado, compuesto por la fecha y el número de estación. Se aplica codificación One-Hot.

  En el notebook "Modelos RNN 3 Dim Salidas V1 Codificación Cíclica" se implementan las redes neuronales de tipo LSTM y GRU con n salidas. En esta versión se entrenan los modelos con un índice combinado, compuesto por la fecha y el número de estación. Se aplica codificación cíclica.

Para ejecutar los códigos usted puede abrir los notebooks en el entorno colaborativo "Google Colaboratory" o abrirle directamente con "Jupyter" y ejecutar las celdas con código.
Se ha implementado para que se ejecute en GPU en caso de que exista, pero en este modo de ejecución da un error al entrenar los modelos. No se ha conseguido la correcta ejecución con la implementación en GPU.

Si desea ponerse en contacto con el autor puede escribir un correo electrónico a la dirección jamarnandez@gmail.com.
