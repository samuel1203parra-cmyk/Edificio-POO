package rpg.modelo;

public class Guerrero extends Personaje {
    public Guerrero(String nombre, int vidaMaxima) {
        super(nombre, vidaMaxima);
    }

    // Asociación: el Guerrero CONOCE a un Arma, pero el arma existe por su cuenta
    // >>> SALA 2.1
    private Arma arma;
    public void equipar(Arma arma) {
        this.arma = arma;
    }
    @Override
    public int atacar() {
        if (arma == null) {
            return 1;
        }
        return arma.getDano();
    }
    // <<< FIN SALA 2.1
}
