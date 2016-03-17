# setcharat10
Descripción
El java.lang.StringBuilder.setCharAt () método establece el carácter en el índice especificado de ch .El índice argumento debe ser mayor o igual que 0 y menor que la longitud de esta secuencia.
Declaración
A continuación se presenta la declaración dejava.lang.StringBuilder.setCharAt () método
public void setCharAt(int index, char ch)
parámetros
•	Índice - Este es el índice del carácter de modificar.
•	ch - Este es el nuevo carácter.
Valor de retorno
Este método no devuelve ningún valor.
Excepción
•	IndexOutOfBoundsException - si el índice es negativo o mayor que o igual a la longitud ().
Ejemplo
El siguiente ejemplo muestra el uso del método de java.lang.StringBuilder.setCharAt ().
package com.tutorialspoint;

import java.lang.*;

public class StringBuilderDemo {

   public static void main(String[] args) {
  
   StringBuilder str = new StringBuilder("AMIT");
   System.out.println("string = " + str);
   // character at index 3
   System.out.println("character at index 3 = " + str.charAt(3));
  
   // set character at index 3
   str.setCharAt(3, 'L');
  
   System.out.println("After Set, string = " + str);
   // character at index 3
   System.out.println("character at index 3 = " + str.charAt(3));
   }
}
Vamos a compilar y ejecutar el programa anterior, esto producirá el siguiente resultado:
string = AMIT
character at index 3 = T
After Set, string = AMIL
character at index 3 = L
