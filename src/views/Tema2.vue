<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Asertividad en la comunicación


    .row.justify-content-center.mb-5
      .col-lg-6.col-md-8.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/t2/1.png', alt='')
      .col-lg-6  
        p En ambientes laborales es frecuente enfrentarse a situaciones complejas en las que surgen dudas sobre: qué decir, cómo decirlo, cuándo hacerlo y si es conveniente expresar lo que se piensa o se siente. Todas estas decisiones comunicativas influyen directamente en las relaciones de trabajo, el clima organizacional y la resolución de conflictos.
        .cajon.color-primario.p-4.mb-4
          p.mb-0 Es por esta razón que, la asertividad es una forma de comunicación que permite expresar pensamientos, emociones, necesidades y opiniones de manera clara, directa y oportuna, sin vulnerar los derechos de los demás ni renunciar a los propios. 




</template>

<script>
export default {
  name: 'Tema2',
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
