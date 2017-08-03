# Ultimate-QWERTY

Una configuración mejorada de X.org para teclado PC105 XFree86 español. Diseñada específicamente para programadores y esperantistas, este mapeado de teclado tiene el propósito de adaptarse a MIS necesidades y ser más comprensible, liviano y reconfigurable que el archivo generado por defecto.

## Features
+ Los números del bloque numérico están siempre activados, independientemente de que el num lock esté encendido.
+ Los números del bloque central se activan con `Shift`. La marcación normal devuelve los símbolos.
+ Los corchetes y llaves se activan por marcación simple de las correspondientes teclas.
+ Añadidas las *ĉapelliteroj* del esperanto que se activan con `Alt Gr`.
+ Añadidos símbolos de divisas (£¥) en `Alt Gr+l` y `Alt Gr+y`.
+ Añadido guión largo en `Alt Gr+-`.
+ Limpieza general de todos los keysyms inútiles.

## Knowing issues
+ No he terminado de decidir dónde poner el acento agudo `´`. Temporalmente lo he situado en la tecla a la izquierda del backspace.
+ He eliminado los símbolos de inicio de interrogación y exclamación porque nunca los uso aunque sea un error ortográfico.

## Installation
    git clone https://github.com/edkalrio/Ultimate-QWERTY.git
    cp ~/Ultimate-QWERTY/ultimate_qwerty ~/.Xmodmap
Para que los cambios surtan efecto hay que reiniciar el X server.

## Changelog
0.1 Commit inicial. 

0.1.1 Añadido guión largo a `Alt Gr+-` y tilde corta a su posición inicial. 

1.0 Cambio de `Mode_Switch` a `Alt Gr` con la consiguiente reducción de keysyms triviales. Añadido encabezamiento y pie de página al archivo para facilitar la reconfiguración con las órdenes `clear` y `add`. 
