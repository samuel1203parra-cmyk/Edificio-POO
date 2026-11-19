package rpg.eventos;

import java.util.ArrayList;
import java.util.List;

// Observer: quien quiera enterarse del combate se suscribe; el combate avisa sin conocer a nadie
// >>> SALA 4.5
public class EventoCombate {
    private final List<Observador> observadores = new ArrayList<>();
    public void suscribir(Observador o) {
        observadores.add(o);
    }
    public void notificar(String mensaje) {
        for (Observador o : observadores) {
            o.actualizar(mensaje);
        }
    }
}
// <<< FIN SALA 4.5
