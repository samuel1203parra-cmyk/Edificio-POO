package rpg.modelo;

import static org.junit.jupiter.api.Assertions.assertEquals;
import static org.junit.jupiter.api.Assertions.assertThrows;
import org.junit.jupiter.api.Test;

class EquipoTest {
    // SIMULACRO · Ejercicio 4: un Equipo admite como máximo 3 personajes (pruebas + excepciones + agregación)
    // >>> SALA A.4
    @Test
    void noAdmiteMasDeTresMiembros() {
        Equipo equipo = new Equipo("Alfa");
        equipo.agregar(new Personaje("Aria", 50));
        equipo.agregar(new Personaje("Bruno", 50));
        equipo.agregar(new Personaje("Cleo", 50));
        assertThrows(IllegalStateException.class, () -> equipo.agregar(new Personaje("Dante", 50)));
        assertEquals(3, equipo.tamano());
    }
    // <<< FIN SALA A.4
}
