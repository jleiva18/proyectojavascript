# proyectojavascript
//Valores de los recargos 
Var edad_18 = 0.1 // 10%
Var edad_18 = 0.2 // 20%
Var edad_18 = 0.3 // 30%

Var casado_18 = 0.1 // 10%
Var casado_25 = 0.2 // 20%
Var casado_50= 0.3 // 30%
Var hijos_recargo = 0.2 // 20%
//recargo 
Var recargo = 0
Var recargo_total = 0

//precio final 
Var precio_final = 0

//mensajes de alerta para ingresar datos
Var nombre = prompt (“ingrese su nombre, por favor”)
Var nombre = prompt (“¿Cuántos años tiene? Ingrese  únicamente los números ”)

Var nombre = prompt (“¿esta casado actualmente?”)
//comprobamos la edad del conyuge, solamente si esta casado/a
Var edad_conyuge
If(“si” “” casado. Touppercase( ) ) {
Edad_conyuge = prompt(“¿Qué edad tiene su esposo/a?”, “si/no”)
}
//convirtiendo las edades ingresadas  a números
Var edad_numero = parseInt(edad)
Var edad_conyuge_numeros = 0
//convirtiendo la edad del conyuge si esta casado/a
If(“si “” casado. Touppercase.( ) ) {
Edad conyuge numero = parseInt (edad conyuge)
}
Var hijos = prompt(“¿tiene hijos o hijas?”)
//comprobamos que la cantidad de hijos solamente si los tienen 
Var cantidad de hijos 
/**
*1. Convierta la cantidad de hijos a numero 
*/ var hijos_numero = parseInt(hijos)
Var cantidad_hijos_numero = 0
//aquí debe colocar el numero de recargo total basado en las respuestas  ingresadas 
//aquí debe calcular los recargos  y el valor final 
//ejemplo (debe completar los condicionales) : recargo por edad del asegurado 
If(edad_numero>=18 && edad_numeros<25){
//calculamos el recargo en base a la edad 
Recargo = precio_base * edad_18
//sumamos todos los recargos que hemos obtenido 
Recargo_total = recargo_total + recargo 
}
If(edad_numero>-50){
//calculamos el recargo en base a la edad 
Recargo = precio_base  * edad_50
//sumamos todos los recargos que hemos recolectado 
Recargo_total = recargo_total + recargo
}
//aquí  puede colocar un else if ( ) con el siguiente rango 
/**
*2. Recargo  porla edad del conyugue
*/if(edad_numero>=18 && edad_numero <25){
//calculamos el recargo en base a la edad 
Recargo = precio base * casado_18
//sumamos todos  los recargos que hemos obtenido
Recargo_total = recargo_total +recargo
} if(edad_numero>=50){
Recargo = precios_base * casado_25
//sumamos todos los recargos que hemos obtenido
Recargo_total = recargo_total + recargo
}
/**
*3. Recargo por la cantidad de hijos 
*/ recargo = precio_base * 0.2
Precio final = precio_base + recargo_total
//resultado 
Alert (“para el asegurado “+nombre)
Alert (“el recargo total será de: “+recargo_total)
Alert (“el precio será de:  “+precio_final)



<!DOCTYPE html>
<!--
Created using JS Bin
http://jsbin.com

Copyright (c) 2021 by anonymous (http://jsbin.com/wupomatixe/1/edit)

Released under the MIT license: http://jsbin.mit-license.org
-->
<meta name="robots" content="noindex">
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
</head>
<body>

<script id="jsbin-javascript">
//Valores de los recargos 
Var edad_18 = 0.1 // 10%
Var edad_18 = 0.2 // 20%
Var edad_18 = 0.3 // 30%

Var casado_18 = 0.1 // 10%
Var casado_25 = 0.2 // 20%
Var casado_50= 0.3 // 30%
Var hijos_recargo = 0.2 // 20%
//recargo 
Var recargo = 0
Var recargo_total = 0

//precio final 
Var precio_final = 0

//mensajes de alerta para ingresar datos
Var nombre = prompt (“ingrese su nombre, por favor”)
Var nombre = prompt (“¿Cuántos años tiene? Ingrese  únicamente los números ”)

Var nombre = prompt (“¿esta casado actualmente?”)
//comprobamos la edad del conyuge, solamente si esta casado/a
Var edad_conyuge
If(“si” “” casado. Touppercase( ) ) {
Edad_conyuge = prompt(“¿Qué edad tiene su esposo/a?”, “si/no”)
}
//convirtiendo las edades ingresadas  a números
Var edad_numero = parseInt(edad)
Var edad_conyuge_numeros = 0
//convirtiendo la edad del conyuge si esta casado/a
If(“si “” casado. Touppercase.( ) ) {
Edad conyuge numero = parseInt (edad conyuge)
}
Var hijos = prompt(“¿tiene hijos o hijas?”)
//comprobamos que la cantidad de hijos solamente si los tienen 
Var cantidad de hijos 
/**
*1. Convierta la cantidad de hijos a numero 
*/ var hijos_numero = parseInt(hijos)
Var cantidad_hijos_numero = 0
//aquí debe colocar el numero de recargo total basado en las respuestas  ingresadas 
//aquí debe calcular los recargos  y el valor final 
//ejemplo (debe completar los condicionales) : recargo por edad del asegurado 
If(edad_numero>=18 && edad_numeros<25){
//calculamos el recargo en base a la edad 
Recargo = precio_base * edad_18
//sumamos todos los recargos que hemos obtenido 
Recargo_total = recargo_total + recargo 
}
If(edad_numero>-50){
//calculamos el recargo en base a la edad 
Recargo = precio_base  * edad_50
//sumamos todos los recargos que hemos recolectado 
Recargo_total = recargo_total + recargo
}
//aquí  puede colocar un else if ( ) con el siguiente rango 
/**
*2. Recargo  porla edad del conyugue
*/if(edad_numero>=18 && edad_numero <25){
//calculamos el recargo en base a la edad 
Recargo = precio base * casado_18
//sumamos todos  los recargos que hemos obtenido
Recargo_total = recargo_total +recargo
} if(edad_numero>=50){
Recargo = precios_base * casado_25
//sumamos todos los recargos que hemos obtenido
Recargo_total = recargo_total + recargo
}
/**
*3. Recargo por la cantidad de hijos 
*/ recargo = precio_base * 0.2
Precio final = precio_base + recargo_total
//resultado 
Alert (“para el asegurado “+nombre)
Alert (“el recargo total será de: “+recargo_total)
Alert (“el precio será de:  “+precio_final)





</script>
</body>
</html>
