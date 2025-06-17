# maquinatragamonedas

Este programa es una simulación de una máquina tragamonedas, cuyos tiros se almacenarán para un posterior análisis de datos.

Índice
Máquina Tragamonedas
Índice
Especificación
Instalación
Requisitos
Pasos
Manual de uso
Leer datos recopilados
Especificación
Se deberá crear un programa en Python que simule el comportamiento de una máquina tragamonedas con 3 slots, y valores aleatorios entre 1 y 6. Al iniciar el programa, se deberá mostrar todos los slots en 0, con el texto ¡Haga su primer tiro!en color azul claro, y un botón con el texto Tirar. El usuario podrá visualizar un sistema de apuesta, con el cual deberá interactuar. En primer lugar, contaremos con una casilla donde el usuario indicará el monto a ingresar, para así luego introducirlo presionando el botón depositar. Una vez depositado, el usuario podrá ver la cantidad de dinero disponible en el apartado de balance. A la hora de apostar, abrirá otro casillero donde el usuario deberá ingresar un monto con el cual poder apostar. Este tendrá que ser mayor que 0 y que no supere lo disponible en el saldo. Al hacer clic en tirar, se deben generar números aleatorios del 1 al 6 en cada ranura. En caso de que todos coincidan, se mostrará el texto ¡Usted ganó!en color verde claro; El usuario será el ganador, por fin, será recompensado con un multiplicador de x5 hacia la apuesta anteriormente introducida. En su defecto, deberá mostrarse el texto ¡Siga participando!en color azul claro, y el usuario perderá su apuesta. Cada tiro, deberás almacenarse en un archivo en formato CSV , localizado en el mismo directorio que el programa y con el nombre shoots.csv.

Instalación
Requisitos
Git
Python 3.9 o superior
Tkinter (según el método de instalación de Python, puede ya estar incluido).
Pasos
Clonar el repositorio.
Abrir una terminal en el directorio raíz del repositorio.
Ejecutar python3 tragamonedas.pyo python tragamonedas.py(en caso de tener Python 3 instalado por defecto).
Manual de uso
Una vez ejecutado el programa, escoja un monto a ingresar y presione el botón "depositar".
Luego de haber depositado, podrás empezar a jugar, eligiendo la cantidad de dinero que se pondrá a juego.
En caso de que no desee continuar, el usuario podrá retirar el total de su saldo dándole clic en "retirar".
Leer datos recopilados
Los datos recopilados se almacenarán en el archivo shoots.csv(localizado en el mismo directorio que el programa). Éste se creará automáticamente cuando se realice el primer tiro. Cada tiro se registra en una nueva línea, y cada valor separado por una coma (siguiendo el formato estándar de un archivo CSV ).
