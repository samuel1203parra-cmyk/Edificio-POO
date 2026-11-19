package rpg.servicio;

import java.util.ArrayList;
import java.util.List;
import rpg.modelo.Personaje;

public class Equipos {
    // List<Personaje> garantiza que solo caben personajes: el error se detecta al compilar
    // >>> SALA 5.2
    public static List<Personaje> vivos(List<Personaje> equipo) {
        List<Personaje> resultado = new ArrayList<>();
        for (Personaje p : equipo) {
            if (p.getVida() > 0) {
                resultado.add(p);
            }
        }
        return resultado;
    }
    // <<< FIN SALA 5.2
}
