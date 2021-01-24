# pasos
- Importar los datos muestreados e una hoja excel a un dataframe de pandas, tiempo y amplitud y otra variable factor de los campios de period de muestreo
- Para las formulas en markdown uasar [latex](https://en.wikipedia.org/wiki/Wikipedia:LaTeX_symbols)
- algunos metodos resaltables de pandas que se han usado son, el de hacer la media movil `.rolling(2).mean()` con la celda anterior, o el de hacer la diferencia con la celda anterior `.diff()`
- Para imprimir el ejrcicio sin que se vean las celdas de entrada o salida vacias se ha usado el plugin de jupyter 'voila'
- para el calculo dela regresion hay varios paquetes, el mas simple me parece el polyfit de numpy, pero para calcular el $r^2$ he usado el `from sklearn.metrics import r2_score`