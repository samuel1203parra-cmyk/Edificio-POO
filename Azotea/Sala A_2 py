from app.modelo.enemigo import Enemigo


# SIMULACRO · Ejercicio 2: un Jefe ES UN Enemigo y TIENE varias Habilidades (herencia + composición + polimorfismo)
# >>> SALA A.2
class Jefe(Enemigo):
    def __init__(self, nombre, vida):
        super().__init__(nombre, vida)
        self._habilidades = []
    def aprender(self, habilidad):
        self._habilidades.append(habilidad)
    def atacar(self, objetivo):
        total = 0
        for h in self._habilidades:
            total += h.calcular_efecto(objetivo)
        return total
# <<< FIN SALA A.2
