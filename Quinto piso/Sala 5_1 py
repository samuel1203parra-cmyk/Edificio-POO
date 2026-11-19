from app.modelo.errores import InventarioLlenoError


class RecolectorService:
    # Una excepción avisa de un problema; quien llama decide cómo recuperarse
    # >>> SALA 5.1
    def recoger(self, p, item):
        try:
            p.recoger(item)
            return True
        except InventarioLlenoError as e:
            print(f"No cabe: {e}")
            return False
    # <<< FIN SALA 5.1
