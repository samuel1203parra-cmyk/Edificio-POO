package rpg.servicio;

import rpg.modelo.InventarioLlenoException;
import rpg.modelo.Item;
import rpg.modelo.Personaje;

public class RecolectorService {
    // Una excepción avisa de un problema; quien llama decide cómo recuperarse
    // >>> SALA 5.1
    public boolean recoger(Personaje p, Item item) {
        try {
            p.recoger(item);
            return true;
        } catch (InventarioLlenoException e) {
            System.out.println("No cabe: " + e.getMessage());
            return false;
        }
    }
    // <<< FIN SALA 5.1
}
