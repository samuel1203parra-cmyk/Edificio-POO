package rpg.modelo;

import java.util.Objects;

public class Item {
    private final String nombre;

    public Item(String nombre) {
        this.nombre = nombre;
    }

    // Dos Item con el mismo nombre son «el mismo» para el juego: se comparan por contenido, no por dirección
    // >>> SALA 5.3
    @Override
    public boolean equals(Object o) {
        if (this == o) {
            return true;
        }
        if (!(o instanceof Item)) {
            return false;
        }
        Item otro = (Item) o;
        return nombre.equals(otro.nombre);
    }
    @Override
    public int hashCode() {
        return Objects.hash(nombre);
    }
    // <<< FIN SALA 5.3
}
