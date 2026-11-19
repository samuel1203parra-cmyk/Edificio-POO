package rpg.modelo;

public class Personaje {
    private final String nombre;

    // Strategy: la forma de atacar es un objeto intercambiable en tiempo de ejecución
    // >>> SALA 4.4
    private EstrategiaAtaque estrategia = new AtaqueBasico();
    public void setEstrategia(EstrategiaAtaque estrategia) {
        this.estrategia = estrategia;
    }
    public int atacar() {
        return estrategia.calcular();
    }
    // <<< FIN SALA 4.4
}
