# Observer: quien quiera enterarse del combate se suscribe; el combate avisa sin conocer a nadie
# >>> SALA 4.5
class EventoCombate:
    def __init__(self):
        self._observadores = []
    def suscribir(self, observador):
        self._observadores.append(observador)
    def notificar(self, mensaje):
        for o in self._observadores:
            o.actualizar(mensaje)
# <<< FIN SALA 4.5
