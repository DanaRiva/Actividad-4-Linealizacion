# Actividad-4-Linealizacion

#### Dana Marian Rivera Oropeza - A00830027

##### Simulación (código)
Dentro de la simulación generamos dos modelos para calcular las velocidades en X y en Y, estos a primera vista son idénticos, sin embargo las funciones que generan las velocidades cambian en cada uno de los bloques,
para X utilizamos las ecuaciones de estado que obtenemos a partir de las derivadas parciales de las ecuaciones de movimiento del robot diferencial, se linearizan en dos versiones, continuo y discreto, en el caso de 
la linearización continua utilizamos "-v*sin(theta)*theta" para X y "v*cos(theta)*theta" para Y. Y para el tiempo discreto "x -v*sin(theta)*theta" para X y "y + v*cos(theta)*theta" para Y.
En el modelo integramos la salida de las funciones para calcular las entradas de las mismas, integramos para calcular las velocidades y alimentar a las mismas funciones, de igual manera se alimenta de las velocidades
iniciales para generar las gráficas de salida.
##### Resultados
