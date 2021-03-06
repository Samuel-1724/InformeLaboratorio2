# InformeLaboratorio2
**1. TEMA:**

Análisis de Mallas

**2. OBJETIVO**

**2.1. Objetivo General**

Comprobar experimentalmente el Análisis de Mallas.

**2.2. Objetivos Específicos**

- Definir lo que es malla, rama y nodo.
- Entender cómo se utiliza el análisis de malla y cómo se lo aplica en un circuito.
- Apender a identificar las mallas de un circuito.
- Realizar el circuito propuesto de manera correcta y funcional.
- Tomar las medidas de las corrientes en cada malla en Tinkercad, Multisim y de forma manual para aplicar el método de mallas.
- Analizar los resultados obtenidos de cada programa y compararlos para definir si el análisi de mallas es funcional o no.


**3. MARCO TEÓRICO**

**3.1. Rama, Mallas y Nodos**

[![Ramas-Mallas-y-Nodos.png](https://i.postimg.cc/d0x7Dqyy/Ramas-Mallas-y-Nodos.png)](https://postimg.cc/jWyqFYvx)

**3.2. Ley de Kirchhoff en mallas**

Las leyes de Kirchhoff, junto con la Ley de Ohm, son las principales herramientas con las cuales se cuenta para analizar el valor de los parámetros eléctricos de un circuito. Mediante el análisis de mallas (segundo ley) es factible hallar los valores de las corrientes y las caídas de tensión que se presenten en cualquier punto del montaje.

[![M-todo-de-An-lisis-de-Mallas.png](https://i.postimg.cc/hGjrHtnz/M-todo-de-An-lisis-de-Mallas.png)](https://postimg.cc/hXkTmgfc)

**3.3. Análisis de Mallas**

Para el análisis de mallas solo es necesaria la segunda ley de Kirchhoff, ya que esta se enfoca en circuitos cerrados.
[![An-lisis-de-Mallas.png](https://i.postimg.cc/MZdy88s1/An-lisis-de-Mallas.png)](https://postimg.cc/14Vgpb1z)

**4. EXPLICACIÓN DEL PROCEDIMIENTO**

**4.1.** Se realizará el siguiente circuito mixto en Tinkercad. Se utilizarán las siguientes herramientas:
- Una Placa de pruebas pequeña.
- Cinco Resistencias.
- Dos Suminitrador de Energía.
- Un multímetro.

[![cg.png](https://i.postimg.cc/sfYh4GGj/cg.png)](https://postimg.cc/kD5Gn4yz)

**4.2.** Conectaremos los dos suministradores de energía en la placa pequeña de tal forma que los dos negativos (tierra) se unan, esto debido a que seguiemos el mismo modelo dado en el diagrama.

[![23.png](https://i.postimg.cc/vZNV8cm5/23.png)](https://postimg.cc/fVYLBWmb)

**4.3.** Ahora posicionaremos los resistores y los conectaremos con un cable celeste, siguiendo el modelo. Al final conectaremos los resistores 3 y 4 al cable negro (negativo) para poder cerrar el circuito con los dos suministradores de energía.

[![hy.png](https://i.postimg.cc/MGBbhyYn/hy.png)](https://postimg.cc/068wSKFv)

[![1.png](https://i.postimg.cc/cC2p4RPV/1.png)](https://postimg.cc/SYLTgMSr)

**5. RESULTADOS OBTENIDOS**

**5.1**. Para poder medir las corrientes de cada malla, primero debemos reconocer todas las mallas que tenemos en nuestro circuito.

[![890.png](https://i.postimg.cc/jjGKjrN8/890.png)](https://postimg.cc/94tsxKLT)

**5.2.** Una vez establecidas las mallas tomaremos medidas de las corrientes en cada malla. Primero lo haremos a través de Tinkercad.

[![gujk.png](https://i.postimg.cc/cHLnmw6g/gujk.png)](https://postimg.cc/jWB2qWHt)

**5.3.** Ahora tomaremos las medidas de voltaje del circuito realizado en el simulador multisim.

[![nkj.png](https://i.postimg.cc/GhfnhCvZ/nkj.png)](https://postimg.cc/Mv1FdgPD)

**5.4.** Ahora realizaremos manualmente el análisis de mallas, para observar si los resultados varian o no.

[![yu.png](https://i.postimg.cc/RhNGyYCw/yu.png)](https://postimg.cc/1V1pNJqz)

[![oj.png](https://i.postimg.cc/dQpzvRMJ/oj.png)](https://postimg.cc/mh3dyH2n)

**5.5.** Cómo ya poseemos todos los datos necesarios; rellenamos la tabla con las corrientes de las mallas. (Recordar que los resultados están en miliamperios).

| MALLA  | Resultados Analíticos  | Resultados Experimentales  | Resultados Simulados  |
| ------------ | ------------ | ------------ | ------------ |
| 1  | 11.4546  | 11.5  | 11.455  |
|  2 | 2.8473  | 2.85  | 2.8474  |
| 3  | 0.4881  | 0.488  | 0.48812  |

**6. CONCLUSIONES**

En este informe de laboratorio se definió qué es un análisis de malla y cómo se lo puede usar en un circuito cotidiano para calcular, en este caso, las corrientes de todas las mallas correspondientes al circuito. También entendimos el concepto de mallas, ramas y nodos y sus diferencias en un circuito. Por último analizamos el procedimeinto del método de mallas para resolver las corrientes de un circuito e identificamos la importancia de las leyes de Kirchhoff en este análisis y de las leyes de Ohm. 

Logramos reproducir el circuito con exito en el programa Tinkercad al igual que simularlo en multisim, y de esta manera lograr analizar las corrientes de cada malla; esto nos lleva al hecho de que también se logró identificar con exito las mallas de este circuito establecido. También se indico el análisis de mallas de forma manual, con los pasos necesarios para llevarla a cabo. 

Al final vimos que los resultados puestos en la tabla eran similares, solo habían pequeñas variaciones de décimas; sin embargo, en cada uno de los procesos el resultado fue el mismo, comprobando así la eficacía del análisis de mallas, y el previó conocimiento de Kirchhoff y Ohm para realizar las medídas. 

**7. BIBLIOGRAFÍA**

- Circuit. (2010). Multisim. Obtenido de https://www.multisim.com/create/
- Gallo, H. (12 de Enero de 2019). Hetpro. Obtenido de https://hetpro-store.com/TUTORIALES/ley-de-kirchhoff-analisis-de-mallas/
- Ministerio de Educaión . (2011). inet. Obtenido de http://www.inet.edu.ar/wp-content/uploads/2020/07/ELECTRONICA_Gu--a07-Mallas-y-Nodos.pdf
- Zapata, F. (1 de Noviembre de 2019). Lifeder. Obtenido de https://www.lifeder.com/analisis-de-mallas/

