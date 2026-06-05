import random

def tirar_dados():
    return random.randint(2, 12)

def pedir_respuestas():
    print("Ingresa tu predicción")
    print("1. Par")
    print("2. Impar")
    print("3. Salir del juego")

    return int(input())

def imprimir_resultado(numero, prediccion):
    print("Número de los dados:", numero)

    if (numero % 2 == 0 and prediccion == 1) or (numero % 2 != 0 and prediccion == 2):
        print("¡Ganaste!")
    else:
        print("Perdiste.")

while True:
    numero = tirar_dados()
    prediccion = pedir_respuestas()

    if prediccion == 3:
        break

    imprimir_resultado(numero, prediccion)

print("Gracias por jugar")
