 ![](https://sites.google.com/site/manualdeusuarioc/home/BorlandC++.png)
  
# **BIENVENIDOS A PROGRAMAS EN C++ DE CORTEZ JEAN**
**Github**
> GitHub es una forja para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador.

**INFORMACION DEL AUTOR**
###### `Autor: Cortez Jean`
######  `Enlace video:`  https://www.youtube.com/watch?v=HTro6WV5IU8&t=7
###### `Correo: sc834374@gmail.com`
# PROGRAMAS
**Compara de dos números**

###### Descripción del problema
Diagrama de flujo y programa en C++ que permita ingresar dos valores y los compara para saber cuál es el mayor en caso de que sean iguales, indique que son iguales.

1. Debe ingresar los numeros a comparar.
2. El programa realizará una comparación de los numeros ingresados
3. El programa designará cual es el mayor o si son iguales.
4. Finalmente mostrará el resultado por pantalla.
###### Funcionalidad
`float ct_x, ct_y;`
###### Salida
`if(ct_x==ct_y)  son iguales
if(ct_x<ct_y)   a es el mayor`

**Suma de varios números**
###### Descripción del programa
Diagrama de flujo y programa en C++ en C++ que permite sumar varios números el usuario debe ingresar la cantidad de número que quiere sumar y el programa debe mostrar la suma total de los números.
1. Ingresa los 2 numeros para hacer la sumarespectiva.
2. El programa realizara la suma de los numeros ingresados.
3. Finalmente el programa mostrara el resultado de aquella suma.
###### Funcionalidad
`int ct_c=0, ct_n;
    float ct_s=0, ct_x;`
###### Salida
`cout<<"Ingrese un número para sumarlo: "<<ct_s<<endl;`

**Calcula la edad**
###### Descripción del programa
Diagrama de flujo y programa en C++ que permite calcular de edad de una persona, el programa debe permitir ingresar la fecha actual, la fecha de nacimiento y mostrar cuantos años, meses y días tiene la persona.

 1.Ingresa los datos pedido por el programa.
 
 2.El programa se encargá de hacer los calculos respectivos.
 
  3.El programa mostrará el resultado del calculo realizado.

###### Funcionalidad
`int ct_AA,ct_MA,ct_DA,ct_AN,ct_MN,ct_DN,ct_A,ct_M,ct_D;`
###### Salida
`cout<<"Usted tiene "<<ct_A<<" años "<<ct_M<<" meses  y"<<ct_D<<" dias ";`

**Punto de Venta**
###### Descripción del programa
Diagrama de flujo y programa en C++ que permita ingresar el precio de varios productos y calculo el IVA a cobrar el descuento y el valor final a pagar, el programa mostrara total valor bruto, valor del IVA, valor del descuento y valor final a pagar.
1. Ingrese cuantos productos comprará.
2. Ingrese el valor de cada producto.
3. Realizará el respectivo calculo para sacar el el valor de su compra con el iva incluido.
4. Realizará otro calculo para hacerle un descuento del valor con iva.
5. El programa por ultimo mostrará el resultado del valor correspondiente a su compra
###### Funcionalidad
`float ct_A=0, ct_x, ct_Tb, ct_Piva, ct_Pdsc, ct_iva=0.12, ct_desc=0.30, ct_vt;`
###### Salida
`cout<<"El valor total es de: $"<<ct_vt<<endl;`

**Cuenta moneda**

Diagrama de flujo y programa en C++ que permita ingresar varias monedas de 2 tipos diferentes (10ctv y 25ctv) y presentara cuantas monedas de cada denominación se ingresaron, cuanto es la cantidad en dinero de cada denominación; así como la cantidad de dinero total que se ingresaron.
1. Ingresa la cantidad de monedas por contar.
2. Selecciona cuantas monedas son de 0.25 y cuantas son de 0.10.
3. El programa hará la contabilidad de las monedas ingresadas.
4. Por ultimo mostrará el resultado de todas las monedas ingresadas.
###### Funcionalidad
`int ct_n, ct_c=0, ct_c1=0, ct_c2=0;
	float ct_x, ct_a=0, ct_a1=0, ct_a2=0, ct_m=0.10;`
###### Salida
`if(ct_x==ct_m)
if (ct_c1=ct_c1+1)
if (ct_a1=ct_a1+ct_x)
while(ct_c<ct_n)`
# INSTALACION
###### Descripción del programa
- Descargar F-Droid

`https://f-droid.org`

- Descargar la terminal(Termux)

`Dentro de la aplicación F-Droid`

- Instalar paquetes en la terminal(Termux)

`pkg install git`

`pkg install vim`

`pkg install g++`

`pkg install clang`

`apt update`

`apt upgrade`

- Clonar el repositorio en la maquina local.

` git clone https://github.com/SamuelC13/ACTIVIDAD-E2`

- Acceder al repositorio

`cd ACTIVIDAD-E2`

# COMPILAR Y EJECUTAR
`g++  CortezJean-Compara.cpp -o CortezJean-Compara`

`./CortezJean-Compara`
