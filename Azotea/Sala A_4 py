import pytest

from app.modelo.equipo import Equipo
from app.modelo.personaje import Personaje


# SIMULACRO · Ejercicio 4: un Equipo admite como máximo 3 personajes (pruebas + excepciones + agregación)
# >>> SALA A.4
def test_no_admite_mas_de_tres_miembros():
    equipo = Equipo("Alfa")
    equipo.agregar(Personaje("Aria", 50))
    equipo.agregar(Personaje("Bruno", 50))
    equipo.agregar(Personaje("Cleo", 50))
    with pytest.raises(ValueError):
        equipo.agregar(Personaje("Dante", 50))
    assert equipo.tamano() == 3
# <<< FIN SALA A.4
