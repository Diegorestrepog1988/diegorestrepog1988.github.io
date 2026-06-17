# diegorestrepog1988.github.io

Mi nombre es Diego Alexis Restrepo Giraldo Soy técnico en sistemas 📺 informáticos, estudiante de tecnología en desarrollo de software; apasionado de los computadores.

Hablar de un computador es hablar de qué se compone de dos elementos indispensables el Hardware y el software en donde ambos se complementan.

el hardware en una palabra simple es lo tangible mientras que el software es lo intangible la parte lógica. El uno no puede subsistir sin el otro por lo tanto se complementan. Hoy por hoy vemos que los computadores son máquinas que utilizamos día a día en todos nuestros quehaceres.

El primer computador que existió fue el ábaco que se utilizaba para hacer cuentas y hasta hace poco se usó en mi caso particular lo usé hasta segundo grado.

El ábaco puede estar formado por columnas divididas desde 10^0 que son las unidades, 10^1 las decenas, 10^2 centenas y así sucesivamente.

Ejemplo para desglosar el 1988 en un ábaco sería así.

En la primer columna desde la que empezamos a contar de derecha a izquierda será 10^0 se colocan 8 cuentas, en la segunda secuencia que es 10^1 8 cuentas, en la tercera en secuencia que es 10^2 se colocan 9 cuentas y en la cuarta columna de izquierda a derecha que es 10^3 se coloca 1 cuenta.

Para poder programar debemos tener algo tan simple como la lógica en programación que no es más que utilizar el método inductivo y deductivo para llegar a un resultado en pocas palabras vemos un patrón y llegamos a una conclusión.

Las compuertas lógicas Son circuitos electrónicos que realizan operaciones lógicas básicas sobre una o más entradas binarias (generalmente 0 o 1) para producir una única salida binaria.

Al hablar de modelos de lenguaje es hablar del lenguaje natural que es el que hablamos los seres humanos en nuestro idioma nativo o en el que aprendamos a lo largo de la vida y el lenguaje formal es el que utilizamos en programación.

Una variable es un espacio de memoria en el que ingreso un dato y puede ser de tipo entero, reales, cadenas y buleanos.

ejemplo sacado de chat gpt

PROGRAMA PARA CALCULAR EL IMC (INDICE DE MASA CORPORAL)

def calcular_imc(peso, altura):
    imc = peso / (altura**2)
    return imc

def interpretar_imc(imc):
    if imc < 18.5:
        return "bajo peso"
    elif 18.5 <= imc < 25:
        return "peso normal"
    elif 25 <= imc < 30:
        return "sobrepeso"
    else:
        return "obesidad"

#entrada de datos de usuario
peso = float(input("ingresa tu peso en kilogramos: "))
altura = float(input("ingresa tu altura en metros: "))

#cálculo e interpretación
imc = calcular_imc(peso, altura)
resultado = interpretar_imc(imc)

print(f"Tu imc es: {imc:.2f}")
print(f"Clasificación: {resultado}")


Reflexión 

Hasta el momento lo que he aprendido considero que ha sido muy fructífero para ir aprendiendo a programar ya que a mí me gusta bastante programar lo hago por pasión espero seguir aprendiendo para crecer como profesional en el área de la programación.

utilicé google ai studio para buscar conceptos y chat gpt para el código de python lo transcribí para ir aprendiendo.

https://github.com/Diegorestrepog1988/mini_turtle_ootask
https://github.com/Diegorestrepog1988/mini_turtle_task
