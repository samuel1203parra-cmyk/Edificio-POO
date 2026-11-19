class Equipo:
    def __init__(self, nombre):
        self._nombre = nombre
        self._miembros = []

    # Agregación: el Equipo AGRUPA personajes que ya existían y que siguen existiendo si el equipo se disuelve
    # >>> SALA 2.2
    def agregar(self, p):
        self._miembros.append(p)
    def quitar(self, p):
        self._miembros.remove(p)
    def ataque_total(self):
        total = 0
        for p in self._miembros:
            total += p.atacar()
        return total
    # <<< FIN SALA 2.2
