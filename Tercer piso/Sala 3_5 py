from app.modelo.personaje import Personaje


# El servicio depende de la ABSTRACCIÓN (el repositorio que recibe), no de MySQL ni de un archivo concreto
# >>> SALA 3.5
class GremioService:
    def __init__(self, repositorio):
        self._repositorio = repositorio
    def reclutar(self, nombre):
        nuevo = Personaje(nombre, 100)
        self._repositorio.guardar(nuevo)
        return nuevo
# <<< FIN SALA 3.5
