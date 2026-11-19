# Singleton: una sola instancia en todo el programa y un único punto de acceso
# >>> SALA 4.1
class Configuracion:
    _instancia = None
    def __new__(cls):
        if cls._instancia is None:
            cls._instancia = super().__new__(cls)
            cls._instancia.vida_inicial = 100
        return cls._instancia
# <<< FIN SALA 4.1
