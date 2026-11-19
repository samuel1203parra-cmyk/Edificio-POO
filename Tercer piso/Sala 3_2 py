from app.modelo.efecto import Efecto


# Un efecto nuevo SIN tocar Personaje ni el motor de turnos: se extiende, no se modifica
# >>> SALA 3.2
class Veneno(Efecto):
    def __init__(self, dano):
        self._dano = dano
    def aplicar(self, objetivo):
        objetivo.recibir_dano(self._dano)
# <<< FIN SALA 3.2
