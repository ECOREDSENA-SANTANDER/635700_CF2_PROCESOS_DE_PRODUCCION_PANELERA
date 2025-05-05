<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 3
        h1 Gestión ambiental y residuos en el proceso productivo de la panela
  
      .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down")
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/T3/img-1.png')})`}"
        )
        .bloque-texto-g__texto.p-4.py-lg-5
          p.mb-0 A lo largo de los años, la industria de la panela ha evolucionado su proceso de producción a través de la artesanía sin agregar valor a sus productos ni realizar cambios importantes en el proceso de producción. A continuación, se presenta un video que muestra cómo se ve la gestión ambiental y de residuos del proceso de producción de panela en Colombia. 
  
      figure(data-aos="fade")
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/f_Vk-TuAcFI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption.mb-5 Video. Gestión ambiental y residuos del proceso de producción de panela

        
      .row.justify-content-center.align-items-center.t3-3(data-aos='fade')
        .col-lg-4.col-md-6.mb-3.mb-lg-0
          img(src="@/assets/curso/temas/T3/img-2.svg")
        .col-lg-6
          .tarjeta.tarjeta-amarillo.p-4.py-lg-5.t-3
            p.mb-0 Recuerde explorar los demás recursos que se encuentran disponibles en este componente formativo; para ello, diríjase al menú principal, donde encontrará la síntesis, una actividad didáctica para reforzar los conceptos estudiados, material complementario, entre otros.
  
  
  </template>

<script>
export default {
  name: 'Tema3',
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
