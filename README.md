# Aiguasol
Python exercise
En este ejercicio veréis dos gráficas, están divididas según las unidades de los datos: minutos, horas y días.
Con el token dado sólo se reciben datos cada 10 minutos porque ha hecho falta hacer la media para el calculo de horas y días.
Están bien ya que en la página web dan los mismos resultados al descargar los archivos de horas y días.
Para la fft se utiliza la librería de scipy, para la fft y la freq.
Para la fft es tan sencillo como meter la señal, los valores por minutos u horas o días y calcula la amplitud. 
Para la función de freq se mete el timestep, en este caso lo he convertido a segundos, para obtener Herzios. 
Todas las gráficas tienen FFTs iguales, la de minutos al tener más datos es más difícil de discernir cuando se repiten las ondulaciones o dicho de otro modo, las repeticiones en la señal para determinadas frecuencias que marca la amplitud.
A través de la frecuencia se podría sacar el período, y ver cuando la señal se repite en formato tiempo, sobre todo para aquellas con una señal más grande.
Decir que en las gráficas FFT se ha eliminado la primera señal, la cual correspondía al mínimo de frecuencia porque la amplitud era demasiado grande para poder valorar el resto de amplitudes.
