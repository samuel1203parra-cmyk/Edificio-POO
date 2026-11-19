package rpg.modelo;

public class Arquero extends Personaje {
    private int flechas;

    public Arquero(String nombre, int vidaMaxima, int flechas) {
        super(nombre, vidaMaxima);
        this.flechas = flechas;
    }

    // Un Arquero debe poder usarse donde se espera un Personaje: atacar() nunca rompe el contrato
    // >>> SALA 3.3
    @Override
    public int atacar() {
        if (flechas == 0) {
            return 1;
        }
        flechas--;
        return 9;
    }
    // <<< FIN SALA 3.3
}
