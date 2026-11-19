package rpg.servicio;

import rpg.modelo.Habilidad;
import rpg.modelo.Personaje;

public class CombateService {
    // Dependencia: usa a Habilidad solo mientras dura el método; no la guarda en un atributo
    // >>> SALA 2.4
    public int usarHabilidad(Personaje origen, Habilidad habilidad, Personaje objetivo) {
        int efecto = habilidad.calcularEfecto(objetivo);
        objetivo.recibirDano(efecto);
        System.out.println(origen.getNombre() + " usa " + habilidad.getNombre());
        return efecto;
    }
    // <<< FIN SALA 2.4
}
