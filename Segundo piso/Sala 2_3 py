from app.modelo.inventario import Inventario


class Personaje:
    # Composición: el Inventario NACE y MUERE con su Personaje; nadie más lo comparte
    # >>> SALA 2.3
    def __init__(self, nombre, capacidad):
        self._nombre = nombre
        self._inventario = Inventario(capacidad)
    def recoger(self, item):
        return self._inventario.agregar(item)
    # <<< FIN SALA 2.3
