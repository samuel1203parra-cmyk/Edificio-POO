package rpg.modelo;

// Un efecto nuevo SIN tocar Personaje ni el motor de turnos: se extiende, no se modifica
// >>> SALA 3.2
public class Veneno implements Efecto {
    private final int dano;
    public Veneno(int dano) {
        this.dano = dano;
    }
    @Override
    public void aplicar(Personaje objetivo) {
        objetivo.recibirDano(dano);
    }
}
// <<< FIN SALA 3.2
