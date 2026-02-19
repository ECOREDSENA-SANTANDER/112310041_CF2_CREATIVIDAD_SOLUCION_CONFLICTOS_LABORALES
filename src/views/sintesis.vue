<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    p.mb-4 La gestión adecuada de los conflictos laborales exige una mirada integral de la comunicación, entendida no solo como transmisión de información, sino como un proceso estratégico que articula lenguaje, actitudes y análisis reflexivo. Comprender cómo se comunican las personas, identificar los elementos que intervienen en ese proceso y reconocer la importancia de la asertividad permite abordar los conflictos de manera consciente, preventiva y orientada a la solución, favoreciendo relaciones laborales más equilibradas y constructivas.

    .row.justify-content-center
      .col-lg-12.mb-5
        figure
          img(src="@/assets/curso/sintesis.svg", alt="La síntesis integra la comunicación asertiva como eje central de la gestión de conflictos, relacionando el proceso comunicativo (verbal, no verbal y paraverbal) con sus elementos y posibles barreras, el ejercicio de la asertividad basada en el respeto mutuo y el equilibrio de derechos, y el análisis del conflicto mediante la identificación del problema, el estudio de sus causas y la priorización de variables clave para una intervención efectiva. ")
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
