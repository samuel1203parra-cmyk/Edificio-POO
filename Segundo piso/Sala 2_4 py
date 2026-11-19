class CombateService:
    # Dependencia: usa a Habilidad solo mientras dura el método; no la guarda en un atributo
    # >>> SALA 2.4
    def usar_habilidad(self, origen, habilidad, objetivo):
        efecto = habilidad.calcular_efecto(objetivo)
        objetivo.recibir_dano(efecto)
        print(f"{origen.nombre} usa {habilidad.nombre}")
        return efecto
    # <<< FIN SALA 2.4
