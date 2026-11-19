package rpg.modelo;

import java.util.ArrayList;
import java.util.List;

// SIMULACRO · Ejercicio 2: un Jefe ES UN Enemigo y TIENE varias Habilidades (herencia + composición + polimorfismo)
// >>> SALA A.2
public class Jefe extends Enemigo {
    private final List<Habilidad> habilidades = new ArrayList<>();
    public Jefe(String nombre, int vida) {
        super(nombre, vida);
    }
    public void aprender(Habilidad habilidad) {
        habilidades.add(habilidad);
    }
    @Override
    public int atacar(Personaje objetivo) {
        int total = 0;
        for (Habilidad h : habilidades) {
            total += h.calcularEfecto(objetivo);
        }
        return total;
    }
}
// <<< FIN SALA A.2
