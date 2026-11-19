from app.modelo.personaje import Personaje


# Mago ES UN Personaje: hereda nombre, vida y recibir_dano()
# >>> SALA 1.3
class Mago(Personaje):
    def __init__(self, nombre, vida_maxima, mana):
        super().__init__(nombre, vida_maxima)
        self._mana = mana
    def atacar(self):
        self._mana = max(0, self._mana - 5)
        return 12 + self._mana // 10
# <<< FIN SALA 1.3
