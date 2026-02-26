<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Problemas en el trabajo


    .row.justify-content-center.mb-4
      .col-lg-6.col-md-8.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/t3/1.png', alt='')
      .col-lg-6  
        p Cuando surge un conflicto en una organización, es común intentar explicarlo rápidamente y proponer soluciones inmediatas. Sin embargo, una revisión más profunda suele revelar que lo visible corresponde solo a la superficie del problema, similar a la punta de un iceberg. Bajo esa apariencia inicial se encuentran múltiples factores interrelacionados (organizacionales, comunicativos, humanos y estructurales), que es necesario analizar para comprender el origen real del conflicto y abordarlo de manera efectiva. 
        .cajon.color-primario.bg1.p-4.mb-4
          p.mb-0 Para avanzar hacia la solución, es indispensable analizar dichas variables, priorizarlas y enfocar los esfuerzos en la construcción de propuestas que contribuyan a restablecer la normalidad y el equilibrio organizacional. Desde una perspectiva gerencial, resolver un problema no garantiza por sí mismo mejores resultados; lo que realmente se logra es eliminar obstáculos que limitan el desempeño de la organización. 

    .subt.mb-4(data-aos="fade-right")
      img(src='@/assets/curso/temas/t1/subt.svg', alt='')
      h3.mb-0.p-2.ps-lg-4.pe-lg-5 Metodología para la solución de conflictos

    p.mb-4 La solución de conflictos laborales requiere una metodología estructurada, sistemática y participativa, que permita pasar del análisis a la acción. Para ello, se propone un ciclo de mejora continua basado en las siguientes fases:

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 4. 
          span Fases del proceso de solución de conflictos en el entorno laboral
        .tabla-a.color-acento-contenido.t2
          table
            thead
              tr
                th.w-25 Fase
                th Descripción por fases
            tbody
              tr
                td Planear
                td Identificación y definición clara del problema, análisis de sus causas, generación de alternativas de solución y planificación de la opción más viable.
              tr
                td Hacer
                td Implementación de la solución o del conjunto de acciones definidas para intervenir el conflicto.
              tr
                td Verificar
                td Evaluación de los resultados obtenidos y análisis del impacto de la solución aplicada en la situación problemática.
              tr
                td Actuar
                td Retroalimentación del proceso, realización de ajustes necesarios y reinicio del ciclo cuando persisten causas no resueltas.

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade")
      .col-lg-1.col-md-2.col-3
        img(src='@/assets/curso/temas/t3/2.svg', alt='')
      .col-lg-11.col-md-10.col-9
        p.mb-0 Este enfoque cíclico reconoce que los conflictos son dinámicos y cambiantes, si no se abordan todas sus causas, pueden reaparecer o transformarse en nuevas problemáticas; por ello, la gestión de conflictos debe entenderse como una tarea permanente de la dirección y al mismo tiempo, como un compromiso colectivo de los colaboradores.

    .subt.mb-4(data-aos="fade-right")
      img(src='@/assets/curso/temas/t1/subt.svg', alt='')
      h3.mb-0.p-2.ps-lg-4.pe-lg-5 Técnicas de análisis de problemas

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-4.d-none.d-lg-block(data-aos="fade-right")
        img(src='@/assets/curso/temas/t3/7.png', alt='')
      .col-lg-8(data-aos="fade-left")
        img.w-75x.mb-4(src='@/assets/curso/temas/t3/3.svg', alt='')
        p Una vez que el problema ha sido claramente definido, el siguiente paso es analizarlo con profundidad. Analizar no significa solo describir lo que ocurre, sino comprender qué causas lo originan, cuáles tienen mayor impacto y en qué punto conviene intervenir para lograr una solución efectiva. Para ello, existen diversas herramientas; a continuación, se explican algunas de las más utilizadas por su utilidad práctica y facilidad de aplicación.

    AcordionA.aa(tipo="a" clase-tarjeta="tarjeta bg2" data-aos="fade-down")
      .row.justify-content-around(titulo="Diagrama de Pareto")
        .col-lg-6
          p El Diagrama de Pareto es una herramienta gráfica que permite priorizar problemas o causas según su nivel de impacto. Se representa mediante barras verticales ordenadas de mayor a menor frecuencia, lo que facilita identificar rápidamente qué situaciones requieren atención inmediata.
          p Este método se basa en el principio de Pareto, conocido como “pocos vitales y muchos triviales”, el cual indica que, en la mayoría de los casos, el 80 % de los efectos proviene del 20 % de las causas. En términos prácticos, esto significa que no todos los problemas tienen la misma relevancia: algunos pocos explican la mayor parte del conflicto. 
        .col-lg-4.col-md-8.mb-3.mb-lg-0
          img(src='@/assets/curso/temas/t3/acord1-1.png', alt='')
        .col-lg-11
          p.mb-5 Este diagrama ayuda a enfocar los esfuerzos en las causas más críticas, evitando dispersar recursos en problemas secundarios que tienen poco impacto en la solución global.
          .subt2.mb-4
            h3.mb-0.px-4 Pautas clave para una comunicación asertiva
          ol.lista-ol--cuadro.fa-lista.mb-4
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 1
              span.mb-0 Identificar y clasificar los problemas o causas relacionadas con la situación analizada.
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 2
              span.mb-0 Recoger datos durante un período determinado, utilizando una hoja de control.
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 3
              span.mb-0 Ordenar los datos de mayor a menor frecuencia, calcular porcentajes y frecuencias acumuladas.
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 4
              span.mb-0 Representar gráficamente los datos: barras para la frecuencia y una línea para la frecuencia acumulada.
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 5
              span.mb-0 Interpretar el gráfico, identificando cuáles causas conforman aproximadamente el 80 % del problema y, por tanto, deben priorizarse.
          .bg-white.p-4
            p.mb-0 De este modo, el análisis permite #[b tomar decisiones basadas en evidencia], concentrándose en los factores que realmente generan el conflicto.
      .row.justify-content-around(titulo="Diagrama de árbol")
        .col-lg-6
          p El Diagrama de árbol, también llamado diagrama sistemático, es una técnica que permite descomponer un problema general en objetivos, criterios y acciones concretas, mostrando de forma visual la relación entre medios y fines.
          p Se utiliza especialmente cuando se requiere planificar soluciones, ya que ayuda a pasar de una meta general a planes de acción específicos, asignando responsabilidades y recursos.
          h5 Cómo elaborarlo:
          ol.lista-ol--cuadro.fa-lista.mb-4
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 1
              span.mb-0 Definir el problema o meta principal, que se ubica como el tronco del árbol.
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 2
              span.mb-0 Identificar criterios clave o grandes líneas de acción, que se representan como las ramas principales.
            li
              .lista-ol--cuadro__vineta
                span.text-dark.fw-bold 3
              span.mb-0 Desglosar cada criterio en acciones más específicas, formando subramas, hasta llegar a actividades operativas claras.
        .col-lg-4.col-md-8.mb-3.mb-lg-0
          img(src='@/assets/curso/temas/t3/acord1-2.png', alt='')
        .col-lg-11
          p Esta herramienta es particularmente efectiva en trabajo en equipo, ya que favorece la participación, la claridad en la planificación y la coherencia entre lo que se quiere lograr y lo que se hace para conseguirlo. 


    Separador
    #t_3_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 3.1 Análisis del campo de fuerzas

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-6.col-md-9.mb-3.mb-lg-0(data-aos="fade-right")
        img(src='@/assets/curso/temas/t3/4.png', alt='')
      .col-lg-6(data-aos="fade-left")
        p El análisis del campo de fuerzas es una técnica que permite evaluar una situación identificando las fuerzas que impulsan el cambio y aquellas que lo dificultan o limitan. Su objetivo es determinar qué tan viable es una solución antes de implementarla.
        p Este análisis resulta especialmente útil cuando existen varias alternativas de solución y se necesita seleccionar la más conveniente.

    p Pasos para realizarlo:

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-4.col-md-6.mb-3.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/temas/t3/tarj1-1.svg' alt='')
          .tarjeta.bg2.w-100
            .text-center.p-4
              p.mb-0 #[b A.] Identificar las fuerzas impulsoras, es decir, los factores que favorecen el éxito de la solución, y las fuerzas limitadoras, que representan resistencias u obstáculos.
      .col-lg-4.col-md-6.mb-3.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/temas/t3/tarj1-2.svg' alt='')
          .tarjeta.bg2.w-100
            .text-center.p-4
              p.mb-0 #[b B.] Asignar un valor a cada fuerza, generalmente en una escala de 1 a 10, según su nivel de influencia.
      .col-lg-4.col-md-6.mb-3.mb-lg-0
        .tarjeta-avatar
          img(src='@/assets/curso/temas/t3/tarj1-3.svg' alt='')
          .tarjeta.bg2.w-100
            .text-center.p-4
              p.mb-0 #[b C.] Comparar el peso total de las fuerzas impulsoras y las limitadoras.
            
    .row.justify-content-center.mb-4(data-aos="fade")
      .col-lg-4.mb-4.mb-lg-0
        .bg3.p-4.h-100.d-flex.align-items-center
          p.mb-0 Si las fuerzas impulsoras tienen mayor peso, la solución presenta mayor probabilidad de éxito; si predominan las fuerzas limitadoras, será necesario reducir resistencias o fortalecer los factores positivos antes de actuar.
      .col-lg-3.d-none.d-lg-block
        img(src='@/assets/curso/temas/t3/5.svg', alt='')
      .col-lg-5
        img.w-75x.mb-4(src='@/assets/curso/temas/t3/6.svg', alt='')
        p En conjunto, estas técnicas permiten analizar los problemas de manera estructurada, objetiva y estratégica. Su correcta aplicación facilita priorizar, planificar y tomar decisiones informadas, aumentando significativamente las posibilidades de resolver los conflictos de forma eficaz y sostenible dentro de la organización.
    
    p.mb-4 Para complementar toda esta información se invita al aprendiz a visitar el siguiente podcast que será de gran utilidad:

    .row.justify-content-center.mb-5
      .col-lg-10
        img(src='@/assets/curso/temas/t3/podcast.svg', alt='')
        .bg3.p-4
          .bg-white.p-3
            TarjetaAudio.color-primario.mb-3(
              texto="Pódcast: El poder en las dinámicas organizacionales"
              :audio="require('@/assets/componentes/audios/audio-ej.mp3')"
              @audio-hover="mostrarIndicadorTarjetaAudio = false"
            )
              .indicador--click(v-if="mostrarIndicadorTarjetaAudio")




</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
    mostrarIndicadorTarjetaAudio: true,
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
