# Vapor_en_burbuja_inicial_python
Vapor en la burbuja inicial. Código implementado en Python


El proceso que se busca simular trata de las reacciones químicas en el vapor en una cavidad esférica cuyo radio R(t) depende del tiempo de forma lineal. En definitiva, calcularemos la cinética química hasta la máxima expansión. El objetivo es verificar si en la máxima expansión sólo hay H20 vapor y no otras moléculas. Para esto hay que resolver un sistema de ecuaciones deferenciales, que se basan en las reacciones presentadas en la tabla 2.2.4.1 de la tesis de Gabriela.

Suposiciones:
1. Se está suponiendo que en la cavidad está todo bien mezclado, de manera que todas las moléculas pueden interactuar con todas las demás.




Para resolver el sistema de ecuaciones diferenciales se emplea la función scipy.integrate.solve_ivp (https://docs.scipy.org/doc/scipy/reference/generated/scipy.integrate.solve_ivp.html) de la librería scipy, que se basa en el método rk45 (método de Runge-Kutta-Fehlberg) explicado en detalle en Numerical_Recipes



