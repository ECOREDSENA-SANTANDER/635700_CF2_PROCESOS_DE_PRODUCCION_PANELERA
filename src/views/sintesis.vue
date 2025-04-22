<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    p El siguiente mapa integra los criterios y especificidades de los conocimientos expuestos en el presente componente formativo. 
    

    .row.justify-content-center
      .col-lg-10.mb-5.bgs.p-4.brad
        figure
          img(src="@/assets/curso/sintesis.svg", alt="Efectos de la temperatura en la producción panelera. En Colombia la producción de panela es una actividad de las más importantes y se realiza a través de tres procesos de hornillas: 1. Hornilla de clarificación: Se llevan los jugos en el tanque de almacenamiento a prelimpieza y luego al proceso de evaporación. 2. Hornillas de evaporación: Se evaporan los jugos durante 30 minutos y se llevan a las hornillas de concentración. 3. Hornillas de concentración: Se elimina agua residual del jugo, se concentran las mieles y se obtiene la panela. En la producción de panela es importante tener en cuenta: 1. No logra la eficiencia energética. 2.Uso de combustibles adicionales como el bagazo, madera y llantas. 3. Evaluar técnicos de gestión de la producción panelera. 4. Identificar efectos generados en cada etapa del proceso de producción. 5. Genera residuos que impactan de manera negativa al medio ambiente.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/bullets/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
