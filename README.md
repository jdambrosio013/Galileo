# Galileo
TDS
PAra solventar lo planteado en la tarea 2, me vi en la necesidad de utilizar la funcion Switch case, para no confundirme con la funcion if else, que en este caso deberia ir anidada.

La ventaja de utilizar un Switch case, es que podemos realizar lo solicitado de una manera sencilla, aunque ocupe màs lineas.
El valor de la variable es 10, y en este caso, el programa mostrarà unicamente "Es Otoño". a pesa de contener todas las demas sentencias para otros valores.

var mes=10;
switch (mes){
  case 1:
  case 2:
  case 12:
     document.write("Es Invierno");
    break;   
  case 3:
  case 4:
  case 5:
     document.write("Es Primavera");
    break;
  case 6:
  case 7:
  case 8:
    document.write("Es Verano");
   break
  case 9:
  case 10:
  case 11:
   document.write("Es OtoÃ±o");
    break
    default:
    document.write("Verifique mes");
}

    document.write("16005017