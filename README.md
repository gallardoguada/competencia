# 🧮 Ejercicio 4 – Promedio de Arreglo Bidimensional

## 👥 Grupo 5 – Integrantes del equipo
- Kevin Piña  
- Emmanuel Ruiz  
- Guadalupe Gallardo  

## 🎯 Objetivo del ejercicio
Solicitar al usuario que ingrese una **matriz de 3x3 con enteros**, y luego:
- Calcular el **promedio de cada fila** utilizando una función.
- Calcular el **promedio general** de toda la matriz con otra función.

Este ejercicio permite practicar:
- Declaración y uso de **arreglos bidimensionales**.
- Uso de **subprogramas (funciones)** en C.
- Cálculo y manejo de **valores promedios**.
- Organización del código para que sea claro y modular.

## 🧠 Conceptos trabajados
- Arreglos bidimensionales (int matriz[3][3])
- Recorridos con bucles anidados (for)
- Funciones con parámetros (void, float, arreglos como argumentos)
- Buenas prácticas: uso de nombres claros, comentarios, modularización

## 📄 Descripción de la solución

El programa está dividido en tres partes:

1. **Ingreso de datos**  
   Se solicita al usuario que ingrese valores enteros para cada posición de la matriz de 3x3.

2. **Cálculo de promedios por fila**  
   Se utiliza la función calcularPromedioFila que recibe una fila y su tamaño, y devuelve el promedio como float.

3. **Cálculo del promedio general**  
   Se utiliza la función calcularPromedioGeneral, que recorre todos los elementos de la matriz para sumar sus valores y luego divide por 9.

### 🔧 Funciones utilizadas:

- float calcularPromedioFila(int fila[], int tamaño);  
  Calcula el promedio de una fila específica.

- float calcularPromedioGeneral(int matriz[3][3]);  
  Calcula el promedio de todos los elementos de la matriz.

## 🛠️ Instrucciones para compilar y ejecutar

1. Compilar el código:
   
bash
   gcc ejercicio4.c -o ejercicio4
