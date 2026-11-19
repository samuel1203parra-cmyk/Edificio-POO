package rpg.modelo;

// Builder: arma una Mision paso a paso y con nombres claros, en vez de un constructor con muchos parámetros
// >>> SALA 4.3
public class MisionBuilder {
    private String titulo = "Sin título";
    private int recompensa = 0;
    public MisionBuilder titulo(String titulo) {
        this.titulo = titulo;
        return this;
    }
    public MisionBuilder recompensa(int recompensa) {
        this.recompensa = recompensa;
        return this;
    }
    public Mision construir() {
        return new Mision(titulo, recompensa);
    }
}
// <<< FIN SALA 4.3
