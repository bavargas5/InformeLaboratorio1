# InformeLaboratorio1

## 1. OBJETIVOS

**-General**

Aplicar los conocimientos adquiridos sobre corriente, voltaje y resistencia, con la elaboración de un circuito eléctrico básico para comprobar las leyes de Kirchhoff.

**-	Específicos**

1.	Construir un circuito eléctrico con la herramienta Tinkercad
2.	Emplear los ejercicios necesarios para comprobar las leyes de Kirchhoff
3.	Comparar los resultados obtenidos con los valores calculados.

## 2. MARCO TEÓRICO

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/MAP.png)




![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/DIAGRAMA%20CORRIENTES%20KIRCHHOFF.png)


## 3. EXPLICACIÓN DEL PROCEDIMIENTO**

**Materiales utilizados**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/M.png)

**Circuito analizado**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/BASE.png)

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/CIRCUITO.png)

**Toma de medidas**

**Voltaje en R1** 

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/VR1.png)

**Voltaje en R2**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/VR2.png)

**Voltaje en R3**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/VR3.png)

**Voltaje en R4**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/VR4.png)

**Voltaje en R5**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/VR5.png)

**Intensidad en R1**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/IR1.png)

**Intensidad en R2**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/IR2.png)

**Intensidad en R3**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/IR3.png)

**Intensidad en R4**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/IR4.png)

**Intensidad en R5**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/IR5.png)

**Cálculos teóricos**

  **Fórmulas utilizadas:**
  
![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F1.png)

  **Procedimiento:**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F2.png)

Para un circuito mixto primero se debe transformar a un circuito en serie:
Para ello sumar las resistencias R3 y R4
Con ello se forma un circuito en paralelo con la resistencia R2 y R34 
Sumar estas resistencias para obtener un circuito en serie con las resistencias R1, R234 y R5

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F3.png)

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F4.png)

En un circuito en serie la corriente en todas las resistencias es la misma por ello:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F5.png)

Con esto se calcula los voltajes en cada resistencia:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F6.png)

El voltaje en un circuito en paralelo tomando como referencia la resistencia R234 que es la suma de R2 + R34 y que se comportan como un circuito en paralelo, en donde el voltaje para ambas resistencias será el mismo que el de la resistencia R234:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F7.png)

Con estos datos se calcula la intensidad en las resistencias restantes:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F8.png)

Como la resistencia R34 es la suma de dos resistencias en serie R3 y R4 la corriente que circula por ellas siempre será la misma, por lo tanto:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/F9.png)

**TABLA 1.1**

| VARIABLE | VALOR CALCULADO | VALOR MEDIDO|
| ------------- | ------------- | ------------- |
| VR1 (V)  | 2.05 V | 2.05 V |
| IR1 (mA) | 2.05 mA | 2.05 mA |
| VR2 (V)  | 4.24 V | 4.25 V |
| IR2 (mA) | 1.09 mA | 1.09 mA |
| VR3 (V)  | 2.11 V | 2.12 V |
| IR3 (mA) | 0.964 mA | 0.965 mA |
| VR4 (V)  | 2.11 V | 2.12 V  |
| IR4 (mA) | 0.964 mA | 0.965 mA |
| VR5 (V)  | 3.69 V  | 3.70 V |
| IR5 (mA) | 2.05 mA | 2.05 mA |

**Observación**

Los valores medidos son más altos debido a que la simulación funciona como un sistema ideal, no toma en cuenta factores que se dan en la vida real.

## Verificación de la LVK. 

Para esto trazamos las líneas de movimiento del voltaje en el circuito, para guiarnos mejor.

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/diagrama%20K%20c.png)

Usamos la ley del voltaje de Kirchhoff 

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/formula%20K%20C.png)

Entonces

Para la trayectoria 1, realizamos lo mismo, pero en este caso el voltaje es 10

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/1.png)


Para la trayectoria 2, realizamos lo mismo, pero en este caso el voltaje es 0

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/2.png)

Como témenos 2 ecuaciones, procedemos a realizar un sistema de ecuaciones

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/3.png)

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/4.png)

Remplazamos en una de las ecuaciones para así encontrar I1

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/5.png)

Para encontrar el voltaje que tiene cada resistencia utilizamos la ley de ohm

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/6.png)


Con el simulador comprobamos que salen los mismos resultados que calculamos.

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/IMAGENES/diagrama%20semireal.png)



## Verificación de la LCK.

La Ley de corrientes de Kirchhoff es el teorema cuya ecuación expresa que la sumatoria de las intensidades que ingresan a un nodo es igual a cero, o mas en específico la suma de una corriente que entra es igual a la suma de dos corrientes que salen.
Específicamente un nodo es el intervalo o punto de unión entre dos o mas componentes; regla que aplica en su mayoría en los circuitos en serie, no obstante, en circuito en paralelo el nodo es donde se juntan las ramas dispuestas. Los nodos también tienen una clasificación: 

Los Nodos Principales: Son aquellos nodos cuya intersección ocupa mas de componentes y la necesidad de emplear formulas para calcular tanto voltaje como intensidades debido a la división o distribución de magnitudes.

Los Nodos Recíprocos: Son aquellos nodos que, dados por la intersección mínima de dos componentes y la distribución de magnitudes normalmente lineal o dividida, no tiene la necesidad de formulas especiales para centrar estas ecuaciones en su proceso de adquisición de magnitudes.

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/img/lab1_1%20(2).png)

Como se puede apreciar en el primer calculo del nodo a la sumatoria de intensidades en el nodo da cero, esto se explica de modo que los valores de la intensidad que entra se le da valores positivos y aquellos que salen del nodo se les da valores negativos y la respectiva igualdad cero significa que es sentido con el que esta la corriente está bien corroborado.

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/img/lab1_2%20(2).png)

En el caso de que al reemplazar datos no llegue conseguirse una igualdad tiende a expresarse como sentido opuesto de corriente las cuales se las muestra por la ley de signos o incluso este mal desarrollado el proceso no obstante si al con el cambio de signos denota una igualdad o aproximación no muy diferente de la igualdad.

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/img/lab1_3%20(2).png)

Tabla 1.3. Verificación de la LCK.

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/img/lab1_4%20(2).png)

Formula del Error Absoluto 

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/img/lab1_5%20(2).png)

Ejemplos de Calculo del Porcentaje de Error 

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/img/lab1_6%20(2).png)

Tabla del Porcentaje de Error de LKC

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/img/lab1_7%20(2).png)

## 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

**Cálculos del porcentaje de error** 

Para calcular el porcentaje de error de los valores obtenidos se utiliza la siguiente formula:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/E1.png)

Ejemplo del cálculo del porcentaje de error:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/E2.png)

| VARIABLE | VALOR CALCULADO | VALOR MEDIDO | % de error |
| ------------- | ------------- | ------------- | ------------- |
| VR1 (V)  | 2.05 V | 2.05 V | 0 % |
| IR1 (mA) | 2.05 mA | 2.05 mA | 0 % |
| VR2 (V)  | 4.24 V | 4.25 V | 0 % |
| IR2 (mA) | 1.09 mA | 1.09 mA | 0 % |
| VR3 (V)  | 2.11 V | 2.12 V |0.47 % |
| IR3 (mA) | 0.964 mA | 0.965 mA | 0.1 % |
| VR4 (V)  | 2.11 V | 2.12 V | 0.47 %  |
| IR4 (mA) | 0.964 mA | 0.965 mA | 0.1 %  |
| VR5 (V)  | 3.69 V  | 3.70 V | 0.27 % |
| IR5 (mA) | 2.05 mA | 2.05 mA | 0 % |

## 5. VIDEO

## 6. CONCLUSIONES

- En conclusión, el uso de la herramienta Tinkercad facilita la construcción de circuitos eléctricos, en los cuales posteriormente se pueden realizar mediciones y comprobar los resultados calculados. 
- Realizar ejercicios relacionados con las leyes de Kirchhoff ayudan a comprender su aplicación y funcionamiento en un circuito.
- Comparar los valores calculados con los valores medidos permiten comprobar que las leyes de Kirchhoff funcionan, siempre tomando en cuenta que en la vida real estos valores pueden variar mucho más debido a que las resistencias utilizadas tienen ciertos valores de tolerancia.

## 7. BIBLIOGRAFÍA

-Mecafenix, I. (2020, 9 junio). Ley de corriente de Kirchhoff. Ingeniería Mecafenix. https://www.ingmecafenix.com/electronica/ley-de-corriente-de-kirchhoff/
- Khan Academy. (s. f.). Las leyes de Kirchhoff (artículo). https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws
