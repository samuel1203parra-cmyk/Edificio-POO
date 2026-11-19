class CombateService:
    # El mismo mensaje (atacar) produce resultados distintos según el objeto real
    # >>> SALA 1.4
    def turno(self, equipo, enemigo):
        for p in equipo:
            dano = p.atacar()
            enemigo.recibir_dano(dano)
            print(f"{p.nombre} causa {dano}")
    # <<< FIN SALA 1.4
