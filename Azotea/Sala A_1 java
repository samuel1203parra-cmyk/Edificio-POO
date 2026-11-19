package rpg.modelo;

// SIMULACRO · Ejercicio 1: la clase Mision completa (encapsulamiento + constructor con validación + toString)
// >>> SALA A.1
public class Mision {
    private final String titulo;
    private final int recompensa;
    public Mision(String titulo, int recompensa) {
        if (recompensa < 0) {
            throw new IllegalArgumentException("La recompensa no puede ser negativa");
        }
        this.titulo = titulo;
        this.recompensa = recompensa;
    }
    public int getRecompensa() {
        return recompensa;
    }
    @Override
    public String toString() {
        return titulo + " (" + recompensa + " monedas)";
    }
}
// <<< FIN SALA A.1
