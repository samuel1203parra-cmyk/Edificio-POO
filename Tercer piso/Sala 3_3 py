from app.modelo.personaje import Personaje


class Arquero(Personaje):
    def __init__(self, nombre, vida_maxima, flechas):
        super().__init__(nombre, vida_maxima)
        self._flechas = flechas

    # Un Arquero debe poder usarse donde se espera un Personaje: atacar() nunca rompe el contrato
    # >>> SALA 3.3
    def atacar(self):
        if self._flechas == 0:
            return 1
        self._flechas -= 1
        return 9
    # <<< FIN SALA 3.3
