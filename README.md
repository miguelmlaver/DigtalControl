# Control Digital
Se hace una breve introduccion de  el control digital dando comparacion con la aplicacion con control analgo, en exactitud, errores de implementacion, flexibilidad, velocidad y costos, tambien se hace una retroalimentacion de lo visto en los cursos anteriores de control. Tambien se abarca brevemente la estructura de bloques en control digital, y se empieza la explicacion de el procedimiento para la conversion analoga digital y viceversa.
## 1. ¿Por que control digital?
-> Es mas exacta que la señal analogica
-> Errores de implementacion:Se puede hacer cambio en el codigo mientras que en la analogica se cambian los componentes
-> Es mas flexible
-> en velocidad la tecnologia analogica es mejor que la velocidad de la digital
-> reduce los costos ya que cambia el codigo mas no el componente
## 1.2. Convercion analogico a igital
## 1.2.1. Procedimiento de conversion
## 1.2.1.1 Muestreo
Es medir valores de voltaje cada cierto tiempo, su unidad es en Hz y puede ser periodico de tasa multiple o aleatorio
## 1.2.1.2 Cuantizacion
La señal analogica se convierte en una serie de valores que coresponde a cada una de las medidas tomadas en el muestreio
## 1.2.1.3 Codificacion
se asigna valores de tipo binario a cada uno de los valores de la cuantizacion 
## 1.2.1.4 Tiempos de muestreo
ta(tiempo de adquisicion): es el tiempo transcurrido desde la orden de muestreo hasta un margen de tolerancia, este es ajustable

tp(tiempo de apertura): : el tiempo que transcurre desde que se inicia la retención hasta que abre el muestreador, es ajustable

ts(tiempo de establecimiento):El tiempo necesario para que la oscilación desaparezca se conoce como tiempo de establecimiento, no es ajustable
## 1.3. Conversor digital/analogico
## 1.3.1. Resolucion DAC
la resolucion depende de los bits de representacion y se entiende en voltaje o porcentaje FS(fondo de escala
🔑 Ejemplo
Para FS=15v

## 2. Definiciones
>🔑*Muestreo:* medir valores cada cierto tiempo, entre mas alta sea la tasa de muestras mas informaciom se procesa y si es muy baja se pierde informacion.
>
>🔑*Cuantizacion:* procesa las señales para reducir la cantidad de datos necesarios para representar una señal.
>
>🔑*Codificacion:* se asignan numeros binarios a cada valor de la cuantizacion.


## 3. Metodos de conversioan
### 3.1 Resistencias ponderadas:
se utilizan para controlar y ajustar la tension y corriente de circuitos, su configuracion es muy facil pero no es muy exacta
 ![](images/plantilla/rp.png)

Figura 1. resistencias ponderadas
### 3.1.2 Red escalera R-2R
Es  efectiva para la convercion digital-analogica ofreciendo una mejor precision, su configuracion en mas comploicada
 ![](images/plantilla/rr.gif)


 ![](images/plantilla/rr1.gif)

Figura 2. R-2R




## 9. Ejercicios
Deben agregar 2 ejercicios con su respectiva solución, referentes a los temas tratados en cada una de las clases. Para agregar estos, utilice la etiqueta #, es decir como un nuevo título dentro de la clase con la palabra 'Ejercicios'. Cada uno de los ejercicios debe estar numerado y con su respectiva solución inmediatamente despues del enunciado. Antes del subtitulo de cada ejercicio incluya el emoji 📚

## 10. Conclusiones
Agregue unas breves conclusiones sobre los temas trabajados en cada clase, puede ser a modo de resumen de lo trabajado o a indicando lo aprendido en cada clase

## 11. Referencias
Agregue un subtítulo al final donde pueda poner todas las referencias consultadas incluyendo el origen o fuente de los ejercicios planteados. Tambien dentro del texto referencie los textos o artículos consultados y las figuras y tablas dentro de la explicación de las mismas.
