Punto 1.
A continuación encontrarán 5 archivos que describo en el que podrán encontrar la siguiente información

plataforma.csv: Plataforma en la que se extraen los datos (Rappi, Éxito, D1, etc)

sitios.csv: Nombre del sitio (Éxito, Jumbo, D1, etc)

zonas.csv: Ciudades

puntos_venta.csv: Puntos de venta de cada sitio

productos.csv: Información histórica de una semana con productos presentes en los puntos de venta

Con estos 5 archivos se debe poder crear un dashboard en la herramienta que quieran, donde tengamos filtros por plataforma, sitio, zona, fecha y los siguientes análisis

Número de productos por punto de venta,zona, sitio, plataforma y general
Comparativa de productos por sitio
Top 10 puntos de venta con más productos
Top 10 productos más recurrentes a nivel general, por plataforma, por sitio y por zona
Top 20 ofertas por sitio por cantidad de descuento y por porcentaje de descuento a nivel general, por plataforma, por sitio y por zona

Adicional un reporte con los datos atípicos o novedades que encontraron de los datos entregados.

Punto 2. Realizar un programa en cualquier lenguaje de programación donde dado el vector letras, desplazamiento y dirección desencripte el mensaje.

En la empresa de construcciones ABC, los ingenieros civiles mantienen contratos con muchas empresas para elaborar diversas obras. Ellos necesitan transmitir información entre las mismas y han contratado a un Ingeniero Mecatrónico para que invente los dispositivos que controlarán la comunicación. Pero como la información es confidencial y es inseguro transmitir la información como texto normal, contratan a un Ingeniero Industrial para que planifique la estrategia y la forma como debe realizarse la comunicación. Se reúnen y deciden codificar los mensajes de la siguiente manera.
Se tiene un vector con las letras del alfabeto de la a..z. Primero se envía el vector letras que contiene las letras presentes en el mensaje sin importar el orden en que vayan (sin repetición), luego transmiten el vector desplazamiento y finalmente el vector direccion. A cada posición del vector desplazamiento le corresponde como pareja el dato que está en la misma posición del vector direccion, y esta pareja finalmente será la clave para desencriptar el mensaje: cada letra del vector desplazamiento tiene una posición en el vector alfabeto, posición que indica el número de caracteres a desplazarse en el vector letras y el vector direccion indica hacia dónde va el desplazamiento (1: adelante 0: atrás).
 
Para desencriptar el mensaje, se parte desde la primera posición del vector letras y se desplaza tantas casillas como indique el vector desplazamiento en la dirección que indique el vector direccion.
Por ejemplo, si se tiene la siguiente información:

Vector alfabeto
Vector_alfabeto = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'ñ', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x','y', 'z']

Vector letras:
Vector_letras = ['V', 'E', 'r', 'o', 'g', 'n', 'a', 'b', ' ', 'P', 'B', 's', 'd', 'i', 'l']

Vector desplazamiento:
Vector_desplazamiento = ['j', 'i', 'n', 'b', 'j', 'c', 'b', 'f', 'h', 'e', 'd', 'g', 'i', 'c', 'f', 'e', 'f', 'e', 'c', 'c', 'i', 'l', 'c', 'f', 'f', 'd', 'e', 'l', 'n', 'g', 'i', 'd', 'l', 'i', 'g', 'j', 'b']

Vector direccion:
Vector_direccion = [1, 0, 1, 0, 0, 0, 1, 1, 0, 1, 1, 1, 0, 1, 0, 1, 0, 1, 1, 1, 0, 1, 0, 0, 1, 0, 1, 0, 1, 0, 0, 1, 1, 0, 1, 0, 0]
