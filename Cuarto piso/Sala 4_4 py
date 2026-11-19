from app.modelo.ataque_basico import AtaqueBasico


class Personaje:
    # Strategy: la forma de atacar es un objeto intercambiable en tiempo de ejecución
    # >>> SALA 4.4
    def __init__(self, nombre):
        self._nombre = nombre
        self._estrategia = AtaqueBasico()
    def set_estrategia(self, estrategia):
        self._estrategia = estrategia
    def atacar(self):
        return self._estrategia.calcular()
    # <<< FIN SALA 4.4
