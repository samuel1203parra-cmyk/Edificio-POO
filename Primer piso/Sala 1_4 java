package rpg.servicio;

import java.util.List;
import rpg.modelo.Personaje;

public class CombateService {
    // El mismo mensaje (atacar) produce resultados distintos según el objeto real
    // >>> SALA 1.4
    public void turno(List<Personaje> equipo, Personaje enemigo) {
        for (Personaje p : equipo) {
            int dano = p.atacar();
            enemigo.recibirDano(dano);
            System.out.println(p.getNombre() + " causa " + dano);
        }
    }
    // <<< FIN SALA 1.4
}
