# InformeLaboratorio1

**1. OBJETIVOS**

-	General

Aplicar los conocimientos adquiridos sobre corriente, voltaje y resistencia, con la elaboración de un circuito eléctrico básico para comprobar las leyes de Kirchhoff.

-	Específicos

1.	Construir un circuito eléctrico con la herramienta Tinkercad
2.	Emplear los ejercicios necesarios para comprobar las leyes de Kirchhoff
3.	Comparar los resultados obtenidos con los valores calculados.

**2. MARCO TEÓRICO**

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/MAP.png)

**3. EXPLICACIÓN DEL PROCEDIMIENTO**

**Materiales utilizados**

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

| VARIABLE | VALOR CALCULADO | VALOR MEDIDO |
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

**4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

**Cálculos del porcentaje de error** 

Para calcular el porcentaje de error de los valores obtenidos se utiliza la siguiente formula:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/E1.png)

Ejemplo del cálculo del porcentaje de error:

![](https://github.com/bavargas5/InformeLaboratorio1/blob/main/Im%C3%A1genes/E2.png)

| VARIABLE | VALOR CALCULADO | VALOR MEDIDO | VALOR MEDIDO |
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

**5. VIDEO**

**6. CONCLUSIONES**

- En conclusión, el uso de la herramienta Tinkercad facilita la construcción de circuitos eléctricos, en los cuales posteriormente se pueden realizar mediciones y comprobar los resultados calculados. 
- Realizar ejercicios relacionados con las leyes de Kirchhoff ayudan a comprender su aplicación y funcionamiento en un circuito.
- Comparar los valores calculados con los valores medidos permiten comprobar que las leyes de Kirchhoff funcionan, siempre tomando en cuenta que en la vida real estos valores pueden variar mucho más debido a que las resistencias utilizadas tienen ciertos valores de tolerancia.

**7. BIBLIOGRAFÍA**
