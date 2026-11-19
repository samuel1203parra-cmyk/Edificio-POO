package rpg.modelo;

// Interfaces pequeñas: Curador solo exige curar(); un Clérigo no está obligado a implementar atacar()
// >>> SALA 3.4
public class Clerigo extends Personaje implements Curador {
    public Clerigo(String nombre, int vidaMaxima) {
        super(nombre, vidaMaxima);
    }
    @Override
    public void curar(Personaje aliado, int cantidad) {
        aliado.curar(cantidad);
    }
}
// <<< FIN SALA 3.4
