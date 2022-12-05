#  Presentación
##  Problemas resueltos en clase con Diagrama de flujo de datos Parcial 3
###  Ejercicio 1. Utilizar 2 vectores para capturar edad y semestre de N estudiantes
####  1.1 Análisis
Requerimos vectores, 2 en especifico, en uno de ellos vamos a ir almacenando la edad de N estudiantes que preguntemos,
al tener el dato se ira guardando en cada uno de los espacios de array, que tendremos que preguntar cuanto mide el array,
y hacer lo mismo con otra matriz para los semestres de cada estudiante.
####  1.2 Diagrama
![ dfd1P2 ](https://user-images.githubusercontent.com/113472808/205503715-780a14b7-79c8-4177-b1ae-14fcafa25b20.png)
####  1.3 Prueba de escritorio
![ imagen ](https://user-images.githubusercontent.com/113472808/205508967-441f72bf-abd5-4cb4-88ba-504dc356fbe0.png)
####  1.4 Entradas
Requerimos un array para los semestres, uno para la edad, preguntar el tamaño del array o la cantidad de estudiantes, preguntar edades y semestres.
####  1.5 Salidas
Imprimir los 2 arreglos.
###  Ejercicio 2. Almacenar en una matriz el semestre y la edad de N estudiantes.
####  2.1 Análisis
Ocupamos una matriz para almacenar 2 datos, el semestre y la edad, ya con esto sabemos que solo son 2 columnas de matriz, se ocupa preguntar la cantidad
de filas mediante saber cuantos estudiantes son, una vez sabiendo los estudiantes preguntamos la edad y almacenamos el dato al igual con el semestre, para
después imprimirlo.
####  2.2 Diagrama
![ dfd2P2 ](https://user-images.githubusercontent.com/113472808/205503873-e9143d7f-acd8-4191-8f06-3aecf147819b.png)
####  2.3 Prueba de escritorio
![ imagen ](https://user-images.githubusercontent.com/113472808/205508976-959377df-1fad-42b0-a672-ebfe2f046123.png)
####  2.4 Entradas
Usamos una matriz 100,2 para dar libertad de tamaño, sabiendo que son 2 columnas nomas, N para cantidad de estudiantes, E para preguntar edad
y Sem para preguntar semestre.
####  2.5 Salidas
Imprimimos la matriz mostrando edad y semestre
###  Ejercicio 3. Rellenar una matriz cuadrada NxN con un numero leído del teclado.
####  3.1 Análisis
Ocupamos una matriz que tenga la misma cantidad de filas que de columnas (NxN) pedir el tamaño, y con preguntar un numero rellenar toda la matriz con ese numero.
####  3.2 Diagrama
![ dfd3P2 ](https://user-images.githubusercontent.com/113472808/205504304-3021c2dc-c881-47b2-b8bc-dd3e76fbde40.png)
####  3.3 Prueba de Escritorio
![ imagen ](https://user-images.githubusercontent.com/113472808/205509001-45439bc4-3911-4d80-8d95-0eb0daa39d31.png)
####  3.4 Entradas
M[100,100] para insertar la matriz, N para preguntar el número del tamaño de la matriz y Num para preguntar el número con el que rellenaremos la matriz.
N=3
número=5
####  3.5 Salidas
####  Saldra la matriz rellenada con el numero.
####  [5,5,5]
####  [5,5,5]
####  [5,5,5]
###  Ejercicio 4. Rellenar una matriz cuadrada NxN con numeros consecutivos.
####  4.1 Análisis
Requerimos una matriz cuadrada, preguntar el tamaño, y con un contador que empiece en 1 y vaya sumando ir yendo cada renglon de cada columna sumando 1
####  4.2 Diagrama
![ dfd4P2 ](https://user-images.githubusercontent.com/113472808/205504440-bafd7917-27df-4342-b2b0-091a2510d6d6.png)
####  4.3 Prueba de escritorio
![ imagen ](https://user-images.githubusercontent.com/113472808/205509010-f60cd5a7-a324-4b41-8c1f-4d40ab4c9ec2.png)
####  4.4 Entradas
Una matriz M[100,100] y un contador C=0, Tamaño de la matriz T y sumar el contador
T=3
####  4.5 Salidas
Imprimir la matriz
####  [1,2,3]
####  [4,5,6]
####  [7,8,9]
###  Ejercio 5. Rellenar una matriz cuadrada NxN con un mismo numero en cada renglon
####  5.1 Análisis
Teniendo una matriz cuadrada, ir rellenando cada renglon completo con un mismo numero y al brincar al siguiente renglon cambiar el numero con un contador.
####  5.2 Diagrama
![ dfd5P2 ](https://user-images.githubusercontent.com/113472808/205504582-e9b82c22-a3d1-4d09-b568-c428f49c7b3f.png)
####  5.3 Prueba de escritorio
![ imagen ](https://user-images.githubusercontent.com/113472808/205509022-065885b6-d24b-4ac0-b2fd-73c115ca50f5.png)
####  5.4 Entradas
Matriz M[100,100] C=1 para contador, N para preguntar tamaño.
N=3
####  5.5 Salidas
####  [1,1,1]
####  [2,2,2]
####  [3,3,3]
###  Ejercicio 6. Generar una matriz NxN
###  [1,0,0]
###  [0,2,0]
###  [0,0,3]
####  6.1 Análisis
En una matriz cuadrada NxN Ocupamos que el primer numero del renglon sea 1 y los demas 0, en el siguiente renglon el primer sea 0 el siguiente 2 y los demas 0
y asi sucesivamente.
####  6.2 Diagrama
![ dfd6P2 ](https://user-images.githubusercontent.com/113472808/205505028-82673542-6c8c-4ed1-80b7-9bfbab4e706d.png)
####  6.3 Prueba de escritorio
![ imagen ](https://user-images.githubusercontent.com/113472808/205509032-6e09b0e3-2183-4323-8880-83de9f4d8dbb.png)
####  6.4 Entradas
T para tamaño de matriz, M[100,100] para la matriz.
T=3
####  6.5 Salidas
Imprimir la matriz
####  [1,0,0]
####  [0,2,0]
####  [0,0,3]
###  Ejercicio 7. Convertir una matriz con numeros establecidos a Vector
####  7.1 Análisis
En una matriz de NxN constituida convertir cada fila a 1 misma matriz de manera consecutiva
####  7.2 Diagrama
![ dfd7P2 ](https://user-images.githubusercontent.com/113472808/205505279-0dcf8995-4150-4fe4-a8c7-9344c11b7b9a.png)
####  7.3 Prueba de escritorio

![ imagen ](https://user-images.githubusercontent.com/113472808/205520309-a5f43643-9592-4f9b-a792-d849f4a66f89.png)
####  7.4 Entradas
M[] tamaño de matriz, V[] tamaño del vector, Contador C=1, N para tamaño
####  7.5 Salidas
@@ -122,7 +122,7 @@ Necesitamos una matriz con 33 estudiantes, y 10 columnas para los datos de alumno
####  8.2 Diagrama
![ dfd8P2 ](https://user-images.githubusercontent.com/113472808/205505620-c1de1a28-7fbc-42a9-a1fd-1e31e9f5368b.png)
####  8.3 Prueba de escritorio

![ imagen ](https://user-images.githubusercontent.com/113472808/205521328-799bc5fa-0c74-4a4c-8f4c-b690a86ce09e.png)
####  8.4 Entradas
Ingresar la matriz con los tamaños establecidos, que alumno es, materia, y alumnos en riesgo y promedios
####  8.5 Salidas
@@ -136,7 +136,7 @@ e imprimir la suma de los numeros en la diagonal inversa, despues comparar los v
####  9.2 Diagrama
![ dfd9P2 ](https://user-images.githubusercontent.com/113472808/205506939-d10459eb-a692-4a5d-a186-1564eb42fae6.png)
####  9.3 Prueba de escritorio

![ imagen ](https://user-images.githubusercontent.com/113472808/205521880-52426396-af85-419f-bd46-b65fda910179.png)
####  9.4 Entradas
M[] SumaD=0 SumaI=0 N para el rango, Num para los numeros.
N=2
@@ -153,7 +153,7 @@ en un vector.
####  10.2 Diagrama
![ dfd10P2 ](https://user-images.githubusercontent.com/113472808/205507387-45de0103-bfd3-4cdb-b6ec-0fb151cba77a.png)
####  10.3 Prueba de escritorio

![ imagen ](https://user-images.githubusercontent.com/113472808/205522170-d470697f-9663-4fac-b625-16e3d7ac9872.png)
####  10.4 Entradas
A[] M[] N para el numero de filas, M para numero de COlumnas.
####  10.5 Salidas
@@ -165,7 +165,7 @@ Si N=3 El arreglo deberia ser [1,3,6]
####  11.2 Diagrama
![ dfd11P2 ](https://user-images.githubusercontent.com/113472808/205507622-7540808b-86f2-4b6c-9e55-64d50322f299.png)
####  11.3 Prueba de escritorio

![ imagen ](https://user-images.githubusercontent.com/113472808/205522312-dc07a459-a090-4d18-a25f-f1a58b278a6b.png)
####  11.4 Entradas
A[100] N para tamaño.
N=6
####  11.5 Salidas
imprimir la matriz
[1,3,6,10,15,21]
