from app.modelo.personaje import Personaje


# SIMULACRO · Ejercicio 3: reclutar sin duplicados (inversión de dependencias + excepciones + responsabilidad única)
# >>> SALA A.3
class ReclutamientoService:
    def __init__(self, repositorio):
        self._repositorio = repositorio
    def reclutar(self, nombre):
        if self._repositorio.existe(nombre):
            raise ValueError(f"Ya existe: {nombre}")
        nuevo = Personaje(nombre, 100)
        self._repositorio.guardar(nuevo)
        return nuevo
# <<< FIN SALA A.3
