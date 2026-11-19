package rpg.modelo;

public class Personaje {
    private final String nombre;

    // static pertenece a la CLASE: existe una sola copia compartida por todos los objetos
    // >>> SALA B.3
    private static int totalCreados = 0;
    public Personaje(String nombre) {
        this.nombre = nombre;
        totalCreados++;
    }
    public static int getTotalCreados() {
        return totalCreados;
    }
    // <<< FIN SALA B.3
}
