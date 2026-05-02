# Solano-post2-u7

Este laboratorio explora dos mecanismos fundamentales del hardware en modo real x86: la lectura de teclado a nivel de BIOS mediante la interrupción INT 16h, y el control directo de la pantalla escribiendo en el segmento de memoria de video B800h, todo implementado en ensamblador NASM y ejecutado en DOSBox.

**Programas**

- post2a.asmLee teclas con INT 16h y muestra el scan code y código ASCII en hexadecimal. Sale con ESC.
- post2b.asmEscribe caracteres con colores distintos directamente en el segmento de video B800h.
- post2c.asmRellena toda la pantalla con fondo azul usando REP STOSW y muestra un mensaje centrado.post2d.asmMini editor de una línea: integra INT 16h con escritura directa en B800h.

**Compilación y ejecución**

- nasm -f bin post2a.asm -o post2a.com
- post2a.com
- remplazar post2a por post2b, post2c, post2d según el programa a ejecutar
