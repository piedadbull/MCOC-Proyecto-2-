# MCOC-Proyecto-2-

En este proyecto se busca poder simular el transporte de sedimento minero de fondo de ríos. Esto se realizará en base a métodos langrangianos, es decir, que estudia el movimiento de cada partícula de forma individual.

Se tomarán como supuestos las siguientes condiciones:

- Diámetros de la partícula (d)= 15 mm
- Densidad de la partícula (rho_particula) = 2650 kg/(m^3)
- Densidad del agua (rho_agua) = 1000 kg/(m^3)
- Constante de drag (Cd) = 0.47   
- Constante de lifting (Cl) = 0.2    
- Constante de peso (Cm) = 0.5 
- Velocidad del flujo en x (vfx) = 5.0 m/s   
- Velocidad del flujo en y (vfy) = 0.1 m/s 


El intervalo de tiempo en los que grafica la posición de la partícula fue de (dt) = 0.001 s, con un tiempo máximo de simulación (tmax) de 1 s. Esto fué igual para las tres pruebas mostradas en los resultados.




### Computador

Mi computador es un MacBook Pro de 13-inch con un procesador 2 GHz Intel Core i5. Tiene 8 GB de memoria ram y un almacenamiento flash de 251 GB. Además, tiene una tarjeta gráfica Intel Iris Graphic 540 de 1536 MB.

### Resultados

El código se corrió con tres cantidades distintas de partículas.
Primero se hizo la simulación con 4 partículas, con el cual se demoró 49.9 segundo en correr. Luego se volvió a realizar la simulación, pero con 11 partículas demorándose un tiempo de 59.4 segundos. Finalmente, el número de partículas fue 20, con el que demoró un tiempo mayor, el cual fue 215.7 segundos.


Los gráficos se muestran a continuación:
![al text](https://github.com/piedadbull/MCOC-Proyecto-2-/blob/master/Grafico_con_4_particulas_(n=4).png)
![al text](https://github.com/piedadbull/MCOC-Proyecto-2-/blob/master/Grafico_con_11_particulas_(n=11).png)
![al text](https://github.com/piedadbull/MCOC-Proyecto-2-/blob/master/Grafico_con_20_particulas_(n=20).png)

