package rpg.modelo;

// Una habilidad define QUÉ hace (el contrato) sin decir CÓMO lo hace cada tipo
// >>> SALA 1.2
public abstract class Habilidad {
    private final String nombre;
    private final int costo;
    protected Habilidad(String nombre, int costo) {
        this.nombre = nombre;
        this.costo = costo;
    }
    public abstract int calcularEfecto(Personaje objetivo);
    public String getNombre() { return nombre; }
    public int getCosto() { return costo; }
}
// <<< FIN SALA 1.2
