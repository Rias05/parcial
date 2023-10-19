
# Integrantes:
- justin prado
- eybraham perez
# PROYECTO:Contador de 0 a 99 con Display 7 Segmentos y Multiplexación
[![trabajo-1.png](https://i.postimg.cc/YCb505r8/trabajo-1.png)](https://postimg.cc/RWJsbbnn)
# DESCRIPCION:
Modo de Contador (Interruptor en posición "Encendido"): La función principal en este modo es contar. Los botones "SUBE" y "BAJA" permiten aumentar y disminuir un número mostrado en un display de 7 segmentos. El botón "RESET" restablece el número a cero. La función principal es llevar un seguimiento y visualización de un contador de 2 dígitos.

Modo de Números Primos (Interruptor en posición "Apagado"): La función principal en este modo es mostrar números primos. Comienza con el número primo 2 y muestra secuencialmente números primos en el display. Si no es un número primo, simplemente pasa al siguiente número hasta encontrar otro número primo. El botón "RESET" restablece el proceso al número primo inicial (2). En este modo, la función principal es identificar y mostrar números primos en el display.
# FUNCION PRINCIPAL:

 

Se llama a keypressed() para detectar si se han presionado los botones (SUBE, BAJA o RESET) y se almacena el resultado en la variable pressed.

Luego, se verifica el valor de pressed para realizar las siguientes acciones:

Si pressed es igual a SUBE, el valor de countDigit se incrementa. Si countDigit supera 99, se reinicia a 0.

Si pressed es igual a BAJA, el valor de countDigit se decrementa. Si countDigit es menor que 0, se establece en 99.

Si pressed es igual a RESET, el valor de countDigit se restablece a 0.

Se llama a printCount(countDigit) para mostrar el número actual en los displays LED.
# PROYECTO :Modificación con Interruptor Deslizante y Números Primos
[![trabajo-2.png](https://i.postimg.cc/mr38hMy4/trabajo-2.png)](https://postimg.cc/Jynb2sFY)
# DESCRIPCION:
 la función del proyecto es conmutar entre dos modos de operación: contar o mostrar números primos. Esto se logra mediante la posición del interruptor "RESET_SWITCH." En el modo de contador, puedes usar los botones para aumentar, disminuir o restablecer el contador, mientras que en el modo de números primos, el proyecto muestra números primos de manera continua. El proyecto ofrece una forma de entretenimiento o visualización de datos dependiendo de la preferencia del usuario y de la posición del interruptor.
# FUNCION PRINCIPAL:

  la función principal del proyecto se adapta a dos modos de operación diferentes: contar o mostrar números primos, dependiendo de la posición del interruptor "RESET_SWITCH." La principal función en el modo de contador es el conteo, y en el modo de números primos, es la identificación y visualización de números primos.

# INVESTIGACION:
## 🔗 Links
https://aprendiendoarduino.wordpress.com/2017/06/24/motores-arduino/

https://motoresygeneradores.com/como-funciona-un-motor-de-corriente-continua/


