# Actividad-4-Linealizacion

#### Dana Marian Rivera Oropeza - A00830027

### Simulación (código)
Dentro de la simulación generamos dos modelos para calcular las velocidades en X y en Y, estos a primera vista son idénticos, sin embargo las funciones que generan las velocidades cambian en cada uno de los bloques,
para X utilizamos las ecuaciones de estado que obtenemos a partir de las derivadas parciales de las ecuaciones de movimiento del robot diferencial, se linearizan en dos versiones, continuo y discreto, en el caso de 
la linearización continua utilizamos "-v*sin(theta)*theta" para X y "v*cos(theta)*theta" para Y. Y para el tiempo discreto "x -v*sin(theta)*theta" para X y "y + v*cos(theta)*theta" para Y.
En el modelo integramos la salida de las funciones para calcular las entradas de las mismas, integramos para calcular las velocidades y alimentar a las mismas funciones, de igual manera se alimenta de las velocidades iniciales para generar las gráficas de salida.
### Resultados
#### w = 1 v = 1
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/df33c4e3-b45c-463c-9855-b25fa1177e7a)
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/b3702e71-c7c7-4dbe-a472-ce2c6351d526)
#### w = 5 v = 5
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/e4e75815-397a-4f02-96ad-164f1f969cd4)
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/668882d0-f6e7-4646-9e47-15212a9795df)
#### w = 10 v = 10
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/6a506854-c742-4df1-9d99-34a1f0c68ba1)
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/c58fa0ff-bab1-4068-b07a-ff14ecafbb25)
#### w = 6 v = 6
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/3b84d257-f7d3-4992-bc99-d3a3dde5384f)
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/ca01e388-038f-43fb-a0b3-aea5aba1c38d)
#### w = 3 v = 3
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/e3acd0d8-3cf6-4baa-9e7f-ec6ecc93e069)
![image](https://github.com/DanaRiva/Actividad-4-Linealizacion/assets/100874942/cd455549-5529-470a-a8c1-cae32cfc7dc1)

