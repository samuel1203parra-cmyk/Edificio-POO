package rpg.modelo;

// Mago ES UN Personaje: hereda nombre, vida y recibirDano()
// >>> SALA 1.3
public class Mago extends Personaje {
    private int mana;
    public Mago(String nombre, int vidaMaxima, int mana) {
        super(nombre, vidaMaxima);
        this.mana = mana;
    }
    @Override
    public int atacar() {
        mana = Math.max(0, mana - 5);
        return 12 + mana / 10;
    }
}
// <<< FIN SALA 1.3
