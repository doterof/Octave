# Octave
- *clc* :deja en blanco la ventana de comandos, borrando de la pantalla todas las órdenes introducidas
- *clear all* :(o simplemente clear) sirve para borrar las instrucciones de la memoria y por lo tanto también del espacio de trabajo. Si solo quieres borrar un variable pones clear x (siendo x una variable cualquiera)

- Para interrumpir la ejecución de una instrucción se deben pulsar las teclas Ctrl+c
- *Inf* denota el símbolo infinito (∞)
- *NaN* es la abreviatura de Not a Number.
- *I, i, j, y J* sirven para denotar la unidad imaginaria
Para acceder a la ayuda podemos teclear help o doc (con help nos aparecerá directamente con doc nos moverá a la pestaña de documentación)
Para poner un comentario ponemos “*%*” 

## Formatos.
	- *format short* (es el formato que emplea, por defecto): formato en punto fijo con 4 dígitos en la parte decimal,
	- *format rat*: cociente de dos números enteros,
	- *format long*: punto fijo con 15 dígitos en la parte decimal,
	- *format long e*: formato en coma flotante con 15 dígitos en la parte decimal

## Comandos.
	- *factor* divide el número en sus factores
	- *factorial* hace el factorial del número
	- *fix* redondea por truncamiento de la unidad
	- *floor* redondea por truncamiento los positivos y a los negativos les suma -1 a la unidad.
	- *hold* mantener una gráfica abierta.
	- *abs* calcula el valor absoluto de su argumento
	- *rats* aproxima su argumento por una fracción
	- *sqrt* calcula la raíz cuadrada de su argumento
	- *nthroot* calcula la raíz de cualquier base de un argumento
	- *exp* calcula la exponencial (con base e) de su argumento
	- *log* calcula el logaritmo neperiano (su argumento debe ser un número real positivo). Idem para el logaritmo en base 10, log10, o en base 2, log2. En las restantes bases deberemos usar la expresión que relacione la base con una de estas tres.
	- *sin, cos, tan, sec, csc, cot* calculan las razones trigonométricas de sus argumentos medidos en radianes.
	- *asin, acos, atan, asec, acsc, acot* son las funciones trigonométricas inversas de las anteriores.
	- El comando *sum* calcula la suma de las componentes de su vector por columnas
	- El comando *max* calcula el valor máximo entre las componentes de un vector por columnas
	- El comando *min* calcula el valor mínimo entre las componentes de un vector por columnas
	- El comando *sort* ordena las componentes de un vector en orden creciente por columnas
	- El comando *length* dice la cantidad de columnas del vector.
	- *plot* dibuja puntos del plano generados al utilizar las componentes del primer vector introducido ver sus las componentes del segundo vector
		- *title*('Para titular')
		- *xlabel*('esta es la etiqueta del eje de abscisas')
		- *ylabel*('esta es la etiqueta del eje de ordenadas')
		- *text*(a, b, 'este es el punto (a,b)')
		- *legend*('este texto identifica una linea')
		- *legend*('texto_1', 'texto_2', ... , 'texto_n')
	- *figure* para añadir ventanas para los gráficos
	- *set* Si se desea cambiar el color o el trazo de la gráfica
	- *solve* Resuelve la ecuación
 	- *zeros*Crea una matriz de ceros con filas=x y columnas= y
	- *disp* +-= printf en c
	- *fprintf*=printf en c
	- *error* muestra en pantalla el mensaje de error
	- *findsym* busca las variables simbólicas en una expresión
	- *num2str* para convertir valores numéricos en strings
	- *subs* resuelve la ecuación para un valor concreto