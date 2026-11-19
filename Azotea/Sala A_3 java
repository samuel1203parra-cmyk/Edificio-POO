package rpg.servicio;

import rpg.modelo.Personaje;
import rpg.repositorio.PersonajeRepositorio;

// SIMULACRO · Ejercicio 3: reclutar sin duplicados (inversión de dependencias + excepciones + responsabilidad única)
// >>> SALA A.3
public class ReclutamientoService {
    private final PersonajeRepositorio repositorio;
    public ReclutamientoService(PersonajeRepositorio repositorio) {
        this.repositorio = repositorio;
    }
    public Personaje reclutar(String nombre) {
        if (repositorio.existe(nombre)) {
            throw new IllegalStateException("Ya existe: " + nombre);
        }
        Personaje nuevo = new Personaje(nombre, 100);
        repositorio.guardar(nuevo);
        return nuevo;
    }
}
// <<< FIN SALA A.3
