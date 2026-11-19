class Personaje:
    # Un atributo de clase pertenece a la CLASE: existe una sola copia compartida
    # >>> SALA B.3
    total_creados = 0
    def __init__(self, nombre):
        self._nombre = nombre
        Personaje.total_creados += 1
    @classmethod
    def total(cls):
        return cls.total_creados
    # <<< FIN SALA B.3
