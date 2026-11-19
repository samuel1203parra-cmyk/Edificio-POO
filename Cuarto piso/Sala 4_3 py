from app.modelo.mision import Mision


# Builder: arma una Mision paso a paso y con nombres claros, en vez de un constructor con muchos parámetros
# >>> SALA 4.3
class MisionBuilder:
    def __init__(self):
        self._titulo = "Sin título"
        self._recompensa = 0
    def titulo(self, titulo):
        self._titulo = titulo
        return self
    def recompensa(self, recompensa):
        self._recompensa = recompensa
        return self
    def construir(self):
        return Mision(self._titulo, self._recompensa)
# <<< FIN SALA 4.3
