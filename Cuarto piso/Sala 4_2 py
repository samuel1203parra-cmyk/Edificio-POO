from app.modelo.guerrero import Guerrero
from app.modelo.mago import Mago


# Factory: quien necesita un Personaje no decide la clase concreta; la fábrica lo hace por él
# >>> SALA 4.2
class PersonajeFactory:
    @staticmethod
    def crear(tipo, nombre):
        if tipo == "guerrero":
            return Guerrero(nombre, 120)
        if tipo == "mago":
            return Mago(nombre, 80, 50)
        raise ValueError(f"Tipo desconocido: {tipo}")
# <<< FIN SALA 4.2
