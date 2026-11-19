package rpg.modelo;

import java.util.ArrayList;
import java.util.List;

public class Equipo {
    private final String nombre;

    public Equipo(String nombre) {
        this.nombre = nombre;
    }

    // Agregación: el Equipo AGRUPA personajes que ya existían y que siguen existiendo si el equipo se disuelve
    // >>> SALA 2.2
    private final List<Personaje> miembros = new ArrayList<>();
    public void agregar(Personaje p) {
        miembros.add(p);
    }
    public void quitar(Personaje p) {
        miembros.remove(p);
    }
    public int ataqueTotal() {
        int total = 0;
        for (Personaje p : miembros) {
            total += p.atacar();
        }
        return total;
    }
    // <<< FIN SALA 2.2
}
