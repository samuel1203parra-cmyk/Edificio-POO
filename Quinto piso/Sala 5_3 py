class Item:
    def __init__(self, nombre):
        self._nombre = nombre

    # Dos Item con el mismo nombre son «el mismo» para el juego: se comparan por contenido, no por dirección
    # >>> SALA 5.3
    def __eq__(self, otro):
        if not isinstance(otro, Item):
            return NotImplemented
        return self._nombre == otro._nombre
    def __hash__(self):
        return hash(self._nombre)
    # <<< FIN SALA 5.3
