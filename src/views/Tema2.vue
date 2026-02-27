<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Asertividad en la comunicación

    .row.justify-content-center.mb-4
      .col-lg-6.col-md-8.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/t2/1.png', alt='')
      .col-lg-6  
        p En ambientes laborales es frecuente enfrentarse a situaciones complejas en las que surgen dudas sobre: qué decir, cómo decirlo, cuándo hacerlo y si es conveniente expresar lo que se piensa o se siente. Todas estas decisiones comunicativas influyen directamente en las relaciones de trabajo, el clima organizacional y la resolución de conflictos.
        .cajon.color-primario.bg1.p-4.mb-4
          p.mb-0 Es por esta razón que, la asertividad es una forma de comunicación que permite expresar pensamientos, emociones, necesidades y opiniones de manera clara, directa y oportuna, sin vulnerar los derechos de los demás ni renunciar a los propios. 

    .row.justify-content-center.mb-4
      .col-lg-8(data-aos="fade-down")
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Figura 2. 
          span Firmeza al comunicar
        figure
          img(src='@/assets/curso/temas/t2/fig2.png', alt='Representa la asertividad como un proceso equilibrado de comunicación, donde la firmeza guía la capacidad de decidir conscientemente cuándo aceptar o rechazar una solicitud. Se integra la habilidad de decir sí y decir no de manera clara y respetuosa, manteniendo coherencia entre decisiones, lenguaje corporal y propósito comunicativo.')

    p.mb-4 La asertividad en la comunicación laboral se refiere a la capacidad de defender los puntos de vista personales y manifestar desacuerdos de manera clara, directa y respetuosa, evitando conductas pasivas que inhiben la expresión de ideas, así como actitudes agresivas que pueden deteriorar las relaciones interpersonales. 

    .bloque-texto-g.bg9.p-3.p-sm-4.p-md-5.mb-4(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image':`url(${require('@/assets/curso/temas/t2/3.jpg')})`}"
      )
      .bloque-texto-g__texto.p-4.p-lg-5
        p.mb-0 Comunicar de forma asertiva permite expresar lo que se piensa, siente o necesita sin vulnerar los derechos de los demás, favoreciendo un clima de confianza y respeto mutuo.

    .row.justify-content-center.mb-5
      .col-lg-6.mb-3.mb-lg-0(data-aos="fade-right")
        .bg1.p-4.h-100.d-flex.align-items-center
          p.mb-0 Ser asertivo no implica imponer opiniones ni aceptar todas las demandas del entorno, sino encontrar un equilibrio entre el respeto por uno mismo y el respeto por los otros. Este equilibrio se construye a partir del desarrollo de habilidades comunicativas que integran tanto el lenguaje verbal como el no verbal, el manejo adecuado de las emociones y la capacidad de autorregulación frente a situaciones de tensión o conflicto.
      .col-lg-6.col-md-10(data-aos="fade-left")
        img(src='@/assets/curso/temas/t2/4.png', alt='')


    .subt.mb-4(data-aos="fade-right")
      img(src='@/assets/curso/temas/t1/subt.svg', alt='')
      h3.mb-0.p-2.ps-lg-4.pe-lg-5 Tipos de conducta en la comunicación

    .row.justify-content-center.align-items-center.mb-4(data-aos="fade")
      .col-lg-1.col-md-2.col-3
        img(src='@/assets/curso/temas/t2/5.svg', alt='')
      .col-lg-11.col-md-10.col-9
        p.mb-0 Desde la infancia, las personas aprenden patrones de comportamiento influenciados por su entorno familiar, social y educativo; todas estas experiencias, pueden favorecer estilos de comunicación agresivos, sumisos o asertivos, los cuales pueden manifestarse de manera distinta según la etapa de la vida o la situación enfrentada.

    .bg-img2.tarjeta.p-4.mb-4(data-aos="fade-down")
      SlyderA(tipo='b')
        .row.justify-content-center.align-items-center
          .col-lg-5.col-11
            h4 Conducta agresiva
            p La persona con conducta agresiva prioriza sus propios intereses sin considerar los de los demás. Suele comunicarse de forma impositiva, con tono elevado, interrupciones constantes y un lenguaje corporal invasivo. Aunque expresa lo que piensa, lo hace sin sensibilidad hacia el impacto emocional que genera, lo que deteriora las relaciones laborales y favorece el conflicto.
          .col-lg-5.col-md-8
            img(src='@/assets/curso/temas/t2/slider1-1.png', alt='')
        .row.justify-content-center.align-items-center
          .col-lg-5.col-11
            h4 Conducta sumisa
            p La conducta sumisa se caracteriza por la dificultad para defender los propios derechos. Estas personas evitan el conflicto, temen desagradar y suelen anteponer las opiniones ajenas a las propias. Su comunicación es insegura, con voz baja, escaso contacto visual y una actitud corporal rígida. A largo plazo, este estilo afecta la autoestima y limita la toma de decisiones autónomas.
          .col-lg-5.col-md-8
            img(src='@/assets/curso/temas/t2/slider1-2.png', alt='')
        .row.justify-content-center.align-items-center
          .col-lg-5.col-11
            h4 Conducta asertiva
            p La persona asertiva reconoce y defiende sus derechos respetando los de los demás. No busca ganar o perder, sino llegar a acuerdos. Se comunica con fluidez, mantiene contacto visual adecuado, adopta una postura relajada y escucha activamente. Expresa tanto desacuerdos como reconocimientos, toma decisiones objetivas y promueve el diálogo constructivo.
          .col-lg-5.col-md-8
            img(src='@/assets/curso/temas/t2/slider1-3.png', alt='')
    
    p Reconocer los derechos personales en la comunicación es fundamental para interactuar con respeto y seguridad. La siguiente tabla organiza los derechos asertivos y explica su aporte a la comunicación efectiva.

    .row.justify-content-center.mb-5(data-aos="fade")
      .col-lg-8
        .titulo-sexto.color-acento-contenido.mb-3
          h5 Tabla 3.
          span Derechos asertivos en la comunicación
        .tabla-a.color-acento-contenido.t2
          table
            thead
              tr
                th Derecho asertivo
                th ¿Qué permite en la comunicación?
            tbody
              tr
                td Expresar opiniones
                td Manifestar ideas y sentimientos con claridad y respeto.
              tr
                td Cambiar de parecer
                td Ajustar puntos de vista sin temor al juicio.
              tr
                td Cometer errores
                td Aprender sin culpa ni desvalorización personal.
              tr
                td Decir "no"
                td Establecer límites de forma firme y respetuosa.
              tr
                td Pedir aclaraciones
                td Evitar malentendidos y mejorar la comprensión.
              tr
                td Tomar decisiones propias
                td Actuar con autonomía y responsabilidad.

    .subt.mb-4(data-aos="fade-right")
      img(src='@/assets/curso/temas/t1/subt.svg', alt='')
      h3.mb-0.p-2.ps-lg-4.pe-lg-5 Comunicación asertiva en el trabajo

    .row.justify-content-center.align-items-center.mb-5(data-aos="fade")
      .col-lg-1.col-md-2.col-3
        img(src='@/assets/curso/temas/t2/6.svg', alt='')
      .col-lg-11.col-md-10.col-9
        p.mb-0 La asertividad no es un acto aislado, sino un proceso continuo de comunicación positiva y constructiva. Implica escuchar activamente, interpretar el lenguaje no verbal del interlocutor y ajustar el mensaje para lograr una retroalimentación efectiva. Además, está estrechamente relacionada con la autoestima: una alta confianza personal facilita la expresión asertiva, mientras que una autoestima baja suele derivar en conductas pasivas.

    .subt2.mb-4(data-aos="fade-right")
      h3.mb-0.px-4 Pautas clave para una comunicación asertiva

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6.col-md-9.mb-3.mb-lg-0(data-aos="fade-right")
        img(src='@/assets/curso/temas/t2/7.png', alt='')
      .col-lg-6(data-aos="fade-left")
        ul.lista-ul--color.fa-lista
          li
            i.fas.fa-puzzle-piece
            span.mb-0 #[b Adaptación:] ajustar el lenguaje, el tono y la postura al interlocutor para generar empatía, sin exagerar ni imitar de forma artificial.
          li
            i.fas.fa-puzzle-piece
            span.mb-0 #[b Lenguaje claro y directo:] expresar ideas sin ambigüedades, evitando tecnicismos innecesarios o generalizaciones ofensivas.
          li
            i.fas.fa-puzzle-piece
            span.mb-0 #[b Responsabilidad comunicativa:] hablar en primera persona y asumir lo que se piensa y se siente.
          li
            i.fas.fa-puzzle-piece
            span.mb-0 #[b Entonación y coherencia:] variar el tono de voz según la intención del mensaje y mantener congruencia con el lenguaje corporal.
        
    .subt2.mb-4(data-aos="fade-right")
      h3.mb-0.px-4 Manejo de personas problemáticas

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-6(data-aos="fade-right")
        p En espacios laborales existen personas que, por su comportamiento recurrente, se convierten en #[b focos de problemas] y se pueden encontrar en cualquier nivel jerárquico y en ocasiones, uno mismo puede adoptar este rol sin notarlo. No existen fórmulas universales para tratarlas, pero sí estrategias asertivas fundamentales: controlar la ira, comprender las causas del comportamiento, usar un lenguaje respetuoso, cuidar el lenguaje corporal y reconocer los propios aspectos a mejorar.
        .bg1.p-4
          p.mb-0 Identificar estos estilos y responder con asertividad contribuye a reducir tensiones, mejorar la convivencia laboral y fortalecer relaciones profesionales saludables.
      .col-lg-6.d-none.d-lg-block(data-aos="fade-left")
        img(src='@/assets/curso/temas/t2/8.png', alt='')



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
