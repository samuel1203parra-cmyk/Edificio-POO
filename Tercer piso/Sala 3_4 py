from app.modelo.curador import Curador
from app.modelo.personaje import Personaje


# Interfaces pequeñas: Curador solo exige curar_a(); un Clérigo no está obligado a implementar atacar()
# >>> SALA 3.4
class Clerigo(Personaje, Curador):
    def __init__(self, nombre, vida_maxima):
        super().__init__(nombre, vida_maxima)
    def curar_a(self, aliado, cantidad):
        aliado.curar(cantidad)
# <<< FIN SALA 3.4
