import pytest

from app.modelo.personaje import Personaje


# Una prueba unitaria revisa UNA regla de forma automática: preparar, actuar, comprobar
# >>> SALA 5.4
def test_recibir_dano_no_baja_de_cero():
    p = Personaje("Aria", 50)
    p.recibir_dano(80)
    assert p.vida == 0
def test_dano_negativo_se_rechaza():
    p = Personaje("Aria", 50)
    with pytest.raises(ValueError):
        p.recibir_dano(-1)
# <<< FIN SALA 5.4
