from app.modelo.personaje import Personaje


# Con números se copia el VALOR; con objetos se copia la REFERENCIA (a dónde apunta)
# >>> SALA B.4
def main():
    nivel = 1
    otro_nivel = nivel
    otro_nivel = 5
    aria = Personaje("Aria", 100)
    copia = aria
    copia.recibir_dano(30)
    print(nivel, aria.vida)
# <<< FIN SALA B.4


if __name__ == "__main__":
    main()
