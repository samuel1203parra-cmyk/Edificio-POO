# SIMULACRO · Ejercicio 1: la clase Mision completa (encapsulamiento + constructor con validación + __repr__)
# >>> SALA A.1
class Mision:
    def __init__(self, titulo, recompensa):
        if recompensa < 0:
            raise ValueError("La recompensa no puede ser negativa")
        self._titulo = titulo
        self._recompensa = recompensa
    @property
    def recompensa(self):
        return self._recompensa
    def __repr__(self):
        return f"{self._titulo} ({self._recompensa} monedas)"
# <<< FIN SALA A.1
