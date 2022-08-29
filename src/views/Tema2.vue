<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 <em>Discourse markers: sequential past time linkers</em> (Marcadores de discurso: conectores secuenciales de tiempo pasado)      
    .row.justify-content-center.mb-5
      .col-lg-5: img(src='@/assets/curso/temas/14.svg')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p.fst-italic There are a lot of different discourse markers in English. Depending on the tense or the context, it is necessary to use the appropriate words. For example, in everyday speech, words such as <b>so, right, well, ok or anyway</b> are common; however, when speaking about the past, there are some other words and expressions that have to be used in order to connect ideas. For example:
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p 
              span.r-5 Hay muchos marcadores del discurso en inglés. Dependiendo del tiempo o del contexto, es necesario utilizar las palabras adecuadas. Por ejemplo, en el discurso cotidiano, palabras como #[i #[b so, right, well, ok o anyway]] son comunes; sin embargo, cuando se habla del pasado, hay otras palabras y expresiones que deben utilizarse para conectar ideas. Por ejemplo:

          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
    .row.justify-content-center.mb-5
      .col-lg-7
        AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta tarjeta-3")
          div(titulo='1. First / Primero')
            .tarjeta.bg-white.p-4
              p <em>It shows the start, the initial phase of the action. </em>
                span.text-gray / Muestra el comienzo, la fase inicial de la acción.
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/15.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="First, I bought a shirt."
                    :audio="require('@/assets/audios/tema2/1.mp3')"
                    )
                  p.ms-3 Primero, compré una camisa.
          div(titulo='2. Then / Luego')
            .tarjeta.bg-white.p-4
              p <em>It shows the following phase. </em>
                span.text-gray / Muestra la fase siguiente.
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/16.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="Then, we sent a box.  "
                    :audio="require('@/assets/audios/tema2/2.mp3')"
                    )
                  p.ms-3 Después, enviamos una caja.
          div(titulo='3. Next / A continuación')
            .tarjeta.bg-white.p-4
              p <em>It shows what occurs immediately after something else. </em>
                span.text-gray / Muestra lo que ocurre inmediatamente después de otra cosa.
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/17.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="Next, she called her sister.   "
                    :audio="require('@/assets/audios/tema2/3.mp3')"
                    )
                  p.ms-3 Después, llamó a su hermana Tom.
          div(titulo='4. After / Después')
            .tarjeta.bg-white.p-4
              p <em>It shows what’s following in time. </em>
                span.text-gray / Muestra lo que sigue en el tiempo.
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/18.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="After eating, I washed my hands. "
                    :audio="require('@/assets/audios/tema2/4.mp3')"
                    )
                  p.ms-3 Después de comer, me lavé las manos.
      .col-lg-5: img(src='@/assets/curso/temas/19.png', alt='')
    .row.justify-content-center.mb-5
      .col-lg-5: img(src='@/assets/curso/temas/20.svg', alt='')
      .col-lg-7
        AcordionA.mb-5(tipo="b" clase-tarjeta="tarjeta tarjeta-3")
          div(titulo='5. After that / Después de eso')
            .tarjeta.bg-white.p-4
              p <em>It shows what’s next after another event. </em>
                span.text-gray / Muestra lo que sigue después de otro evento.
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/21.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="We went to the park. After that, we cooked the meat.  "
                    :audio="require('@/assets/audios/tema2/5.mp3')"
                    )
                  p.ms-3 Fuimos al parque. Después de eso, cocinamos la carne.
          div(titulo='6. Before / Antes ')
            .tarjeta.bg-white.p-4
              p <em>It shows what occurred at a previous time. </em>
                span.text-gray / Muestra lo que ocurrió en un momento anterior. 
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/22.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="Before cleaning, I organized the whole house. "
                    :audio="require('@/assets/audios/tema2/6.mp3')"
                    )
                  p.ms-3 Antes de limpiar, organicé toda la casa.
          div(titulo='7. Before  that / Antes de eso')
            .tarjeta.bg-white.p-4
              p <em>It shows what occurred earlier than another event. </em>
                span.text-gray / Muestra lo que ocurrió en un momento anterior a otro acontecimiento.
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/23.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="I called my brother. Before that, I had to look for his phone number. "
                    :audio="require('@/assets/audios/tema2/7.mp3')"
                    )
                  p.ms-3 Llamé a mi hermano. Antes de eso, tuve que buscar su número de teléfono.
          div(titulo='8. Finally / Finalmente')
            .tarjeta.bg-white.p-4
              p <em>It shows something that happens last in a process. </em>
                span.text-gray / Muestra algo que ocurre en último lugar en un proceso.
              p.text-center.fst-italic.fw-bold For example: 
              .row.justify-content-center.mb-5
                .col-lg-2: img(src='@/assets/curso/temas/24.svg', alt='')
                .col-lg-5
                  TarjetaAudio.color-primario.bg-white.mb-3(
                    texto="Finally, I started my trip to New York.  "
                    :audio="require('@/assets/audios/tema2/8.mp3')"
                    )
                  p.ms-3 Finalmente, inicié mi viaje a Nueva York.
    Dialogo.color-acento-contenido(:dialogo="dialogo")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Completa la conversación
      template(#descripcion-actividad)
      
</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    ocultarEsp: true,
    dialogo: {
      personajes: [
        {
          nombre: 'Tom',
          img: require('@/assets/curso/temas/tom.svg'),
        },
        {
          nombre: 'Maria',
          img: require('@/assets/curso/temas/maria.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Tom',
          textoIng: 'Maria, how did you spend your weekend?',
          textoEsp: 'Pendiente traduccion',
          audio: require('@/assets/audios/a2/1.mp3'),
        },
        {
          personaje: 'Maria',
          textoIng:
            'Well, I went to my aunt’s house, but it rained ***  I entered the house.',
          textoEsp: '',
          audio: require('@/assets/audios/a2/2.wav'),
          palabra: 'before',
        },
        {
          personaje: 'Tom',
          textoIng: 'No! really?',
          textoEsp: '',
          audio: require('@/assets/audios/a2/3.mp3'),
        },
        {
          personaje: 'Maria',
          textoIng:
            'Yes. *** , it got really cold and I didn’t have clothes to change there.',
          textoEsp: '',
          audio: require('@/assets/audios/a2/4.wav'),
          palabra: 'After that',
        },
        {
          personaje: 'Tom',
          textoIng: 'No way! What did you do then?',
          textoEsp: '',
          audio: require('@/assets/audios/a2/5.mp3'),
        },
        {
          personaje: 'Maria',
          textoIng:
            'First, I drank a cup of hot tea, then I bought some medicine, and *** I went to bed.',
          textoEsp: '',
          audio: require('@/assets/audios/a2/6.wav'),
          palabra: 'finally',
        },
        {
          personaje: 'Tom',
          textoIng: 'So, did you get sick?',
          textoEsp: '',
          audio: require('@/assets/audios/a2/7.mp3'),
        },
        {
          personaje: 'Maria',
          textoIng: 'Not really, but I don’t feel that good.',
          textoEsp: '',
          audio: require('@/assets/audios/a2/8.wav'),
        },
      ],
    },
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

<style lang="sass">
.tarjeta-3
  background-color: #a6bbff
</style>
