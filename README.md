# Ozone Graph App v2.2.0.10
Aplicación de escritorio para la adquisión de datos del sensor de ozono BMT 960 por medio de Arduino, para uso en el Laboratorio de Investigación en Ingeniería Química Ambiental (LAIIQA - ESIQIE - IPN).

![](app.gif)

## Adquisición
![](adquisicion.png)

- Una vez conectado el arduino a la computadora, y al hacer click en `Conectar`, el programa se conetará automaticamente al puerto `COM` detectado del Arduino. Se recomienda desconectar cualquier otro dispositivo `USB`.

- El botón `Conectar` cambiará a `Iniciar` para comenzar la lectura de la señal.

## Visor de archivos
![](visor.png)

 - Al finalizar se puede observar el ozonograma generado en la pestaña `Visor`.

 - La opción `Color de linea` da a elegir entre 7 colores de línea distintos.

 - La opción `grid` activa o desactiva las líneas de cuadrícula del gráfico.

- En el recuadro se muestra el ozono **Consumido**, **Residual** y **Total** (a un flujo de `0.5 L/min` con una concentración máxima aproximada de `35 g/Nm^3`, gramos / metros cúbicos Normales: 0°C a nivel del mar).

 - La opción `Ozono en ` `g/Nm^3 | g/L` cambia las unidades para el cálculo del ozono **Consumido**, **Residual** y **Total**.

 - El selector de tiempo en la parte inferior `min | seg` cambia la escala del eje x.

 - La barra de `Titulo` modifica el titulo del gráfico (**opcional**).

 - La barra de `Subtitulo` modifica el subtitulo del gráfico (**opcional**).

 - Con el botón `abrir` se pueden visualizar archivos `.mat` creados previamente.

 - Con el botón `guardar` se puede guardar el ozonograma generado en los formatos: `.mat`, `.xlsx`, `.csv` y `.txt`.
