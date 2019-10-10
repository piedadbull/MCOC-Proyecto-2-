# MCOC-Proyecto-2-

En este proyecto se busca poder simular el transporte de sedimento minero de fondo de ríos. Esto se realizará en base a métodos langrangianos, es decir, que estudia el movimiento de cada partícula de forma individual

Se tomarán como supuestos las siguientes condiciones:

- Diámetros de la partícula (d)= 1 mm
- Densidad de la partícula (rho_particula) = 2650 kg/(_m**3)
- Densidad del agua (rho_agua) = 1000 kg/(_m**3)
- Constante de drag (Cd) = 0.47   
- Constante de lifting (Cl) = 0.2    
- Constante de peso (Cm) = 0.5    

Se tomará la ecuación de fuerza:  F=m*a 
Intervalo de tiempo en los que grafica la posición de la partícula (dt) = 0.001 s   
Tiempo máximo de simulación (tmax) = 1 s   
Tiempo actual (ti) = 0 s


# Computador

Mi computador es un MacBook Pro de 13-inch con un procesador 2 GHz Intel Core i5. Tiene 8 GB de memoria ram y un almacenamiento flash de 251 GB. Además, tiene una tarjeta gráfica Intel Iris Graphic 540 de 1536 MB.

# Resultados

El código se corrió con tres cantidades distintas de partículas.
Primero se hizo la simulación con 4 partículas, con el cual se demoró 0,4 segundo en correr. Luego se volvió a realizar la simulación, pero con 11 partículas demorándose un tiempo de 34,7 segundos. Finalmente, el número de partículas fue 20, con el que demoró un tiempo mayor, el cual fue 194,9 segundos.

Los gráficos se muestran a continuación:
![al text](https://github.com/piedadbull/MCOC-Proyecto-2-/blob/master/Grafico_con_4_particulas_(n=4).png)
![al text](https://github.com/piedadbull/MCOC-Proyecto-2-/blob/master/Grafico_con_11_particulas_(n=11).png)
![al text](https://github.com/piedadbull/MCOC-Proyecto-2-/blob/master/Grafico_con_20_particulas_(n=20).png)

