# Trabajo Práctico en R y Python. Econometría I.


## Consignas del trabajo:
1. Realizar un análisis estadístico de las variables bajo estudio en forma individual y de manera bivariada. Puntualmente: Calcular medidas de posición, de variabilidad, características
superiores y realizar gráficos que presenten las series y muestren su grado de vinculación con las demás variables.
2. Presentar el modelo a estimar. Comentar sus características salientes y explicar la razonabilidad de la magnitud y signo esperado de los coeficientes de regresión a obtenerse.
3. Realizar una salida de regresión y comentar los resultados y de los indicadores estadísticos obtenidos, juzgando su razonabilidad.
4. Especificar e interpretar el Coeficiente de Determinación Múltiple.
5. Estimar Intervalos de Confianza y Test de Hipótesis para los coeficientes de regresión, suponiendo un margen de error del 5%.
6. Realizar una predicción puntual y otra por intervalos y asumir un margen de error del 5%.
7. Comprobar la presencia de multicolinealidad en caso de corresponder.
8. Reexpresar el modelo en logaritmos. Estimar el modelo en su versión logarítmica tomando con tal finalidad la variable dependiente como logaritmo y una (o dos) variables explicativas a elección en logaritmos. Concluir sobre la interpretación de los coeficientes estimados y sobre la incidencia de dicha transformación sobre las pruebas de validación y de bondad de
ajuste.
9. Verificar si existe un error de especificación.

## Metodología General

La metodología del trabajo se centró en el análisis de datos a partir de la base gpa1 del paquete wooldridge, realizando un estudio econométrico aplicado que incluyó análisis exploratorio, estimación de modelos de regresión lineal y evaluación estadística de los resultados. Se trabajó tanto en Python como en R, seleccionando las variables según los criterios teóricos vistos en clase.

Durante el desarrollo del trabajo se aplicaron herramientas estadísticas para interpretar la relación entre variables, realizar inferencias, validar los supuestos del modelo, y explorar transformaciones funcionales que mejoren el ajuste y la interpretación de los resultados. Todo el proceso fue implementado de forma reproducible en notebooks, documentando cada etapa del análisis.

El desarrollo completo del trabajo práctico en Python, incluyendo el análisis estadístico, la estimación de modelos y los comentarios de resultados, puede consultarse en el siguiente enlace a Google Colab:

[Enlace al Notebook de Análisis en Google Colab](https://drive.google.com/file/d/1Zi_sc6qak4y59HLRrdIh8o-0ch2X_8UE/view?usp=sharing)

Este notebook contiene el código documentado y los outputs generados, permitiendo reproducir todos los pasos del análisis realizado.


## Insights Clave y Hallazgos Principales

* Para el desarrollo de este trabajo práctico se seleccionó como principal la base de datos gpa1, ya que consideramos que se ajusta de manera adecuada a la mayoría de los requerimientos planteados en los ejercicios.
 
* En el Ejercicio 1, se realizó un análisis de las cinco bases propuestas (gpa1, hprice2, wage1, ceosal1 y crime1). Luego, en el Ejercicio 4, se contrastó gpa1 con hprice2, ya que esta última presentó un coeficiente de determinación (R²) considerablemente más alto.
  
Para el Ejercicio 7, que aborda el problema de la multicolinealidad, se realizó el diagnóstico tanto sobre gpa1 como sobre hprice2. En este caso, se eligió hprice2 como comparación porque mostró valores de VIF más elevados. 

* Finalmente, en el Ejercicio 8, se exploró la utilidad de transformar los modelos a su forma logarítmica. Además del análisis en gpa1, se incorporó el caso de la base ceosal1.

---
**Participantes:** Sebastian Silva, Yuri Sittner y Pablo Antinarelli.

**Fecha de entrega:** 16 de junio de 2025
