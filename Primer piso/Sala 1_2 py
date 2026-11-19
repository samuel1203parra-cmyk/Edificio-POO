from abc import ABC, abstractmethod


# Una habilidad define QUÉ hace (el contrato) sin decir CÓMO lo hace cada tipo
# >>> SALA 1.2
class Habilidad(ABC):
    def __init__(self, nombre, costo):
        self._nombre = nombre
        self._costo = costo
    @abstractmethod
    def calcular_efecto(self, objetivo):
        raise NotImplementedError
    @property
    def nombre(self):
        return self._nombre
# <<< FIN SALA 1.2
