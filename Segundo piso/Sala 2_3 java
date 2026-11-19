package rpg.modelo;

public class Personaje {
    private final String nombre;

    // Composición: el Inventario NACE y MUERE con su Personaje; nadie más lo comparte
    // >>> SALA 2.3
    private final Inventario inventario;
    public Personaje(String nombre, int capacidad) {
        this.nombre = nombre;
        this.inventario = new Inventario(capacidad);
    }
    public boolean recoger(Item item) {
        return inventario.agregar(item);
    }
    // <<< FIN SALA 2.3
}
