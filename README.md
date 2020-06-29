# raya

[![Run on Repl.it](https://repl.it/badge/github/Sam-Flynn/raya)](https://repl.it/github/Sam-Flynn/raya)

def presentar_1():
    print()
    print("Tres en raya")
    print()
    print("Escoja una ficha jugador1 (X o O):")
    ficha1=""
    while ficha1!="O" and ficha1!="X":
        ficha1=input(" ").upper()
    if ficha1=="X":
        jugador1="X"
        jugador2="O"
    else:
        jugador1="O"
        jugador2="X"
    return jugador1, jugador2

def mostrar_tablero(tablero):
    print()
    print()
    print()
    print("    1     |2     |3")
    print("      {}    |{}    | {}".format(tablero[0],tablero[1],tablero[2]))
    print("          |      |")
    print("-------------------------")
    print("    4     |5     |6")
    print("      {}    |{}    | {}".format(tablero[3],tablero[4],tablero[5]))
    print("          |      |")
    print("    ---------------------")
    print("    7     |8     |9")
    print("      {}    |{}   | {}".format(tablero[6],tablero[7],tablero[8]))
    print("          |      |")
    print()
def continuar_jugando():
#da true si se quiere sueguir jugando, false si no quieren
    print()
    respuesta=input("Si quieres jugar otra vez escribe "si"").lower()
    if respuesta=="si":
        return True
    else:
        return False
def tablero_completo(tablero):
    for i in tablero
        if i==" ":
            return False
        else:
def casila_vacía(tablero,casilla):
    return tablero[casilla]==" "
            return True
def movimiento_jugador1(tablero):
    posiciones=["1","2","3","4","5","6","7","8","9"]
    posicion=[]
    while True:
        if posicion not in posiciones:
            posicion=input("Escoge entre 1-9: ")
        else:
            posicion=int(posicion)
            if not casilla_libre(tablero,posicion-1):
                print("Ocupada")
            else:
                return posicion-1
def 
juego=True
while juego:
    tablero=[" "]*9
    nivel=presentar_1()
    mostrar_tablero(tablero)
        