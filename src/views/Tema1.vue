<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 <em>Present perfect vs past simple</em> (Presente perfecto vs pasado simple)
    .row.justify-content-center.mb-5
      .col-lg-5: img(src='@/assets/curso/temas/1.svg')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p.fst-italic The present perfect and the past simple are topics that tend to be confused with each other due to their similarities, especially the possibility of narrating past events with both verb tenses, which causes them to be used equivocally in some cases.
              br
              br
              | To solve this, we are going to see the differences between them and their uses:
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p 
              span.r-5 Traduccion no presente

          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
    .row.justify-content-center.mb-5
      .col-lg-6 
        .tarjeta-titulo-up(style='background-color: #FFF0F1').p-4.mb-3
          .tarjeta-titulo-up__titulo
            .tarjeta.rounded-0.d-inline-block.p-3(style='background-color: #FC5F65')
              p.text-center.fw-bold.mb-0 Simple past / Pasado simple
          .tarjeta-titulo-up__contenido
            p 
              span.r-3.fst-italic.fw-normal It usually talks about an activity that started and finished in the past (it is not connected to the present). 
              | / Por lo general, habla de una actividad que comenzó y terminó en el pasado (no está conectado con el presente).

              br
              br
              span.r-3.fst-italic.fw-normal Clue words: 
              | / Palabras clave:
              br
              |<em><b>“Last…..” “...ago” “Yesterday”</b></em>
              br
              br
              span.r-3.fst-italic.fw-normal Cases in which the past simple is used: 
              | / Casos en los que se usa el pasado simple:
        img.mb-3(src='@/assets/curso/temas/2.svg', alt='')  
        .tarjeta.rounded-0.p-3(style='background-color: #FFDFE0')
          .tarjeta.bg-white.p-4
            SlyderA(tipo='b')
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.py-4
                    span 1
                  | <em>The past simple talks about actions and events in the past that are now finished.</em> 
                  span.text-gray / El pasado simple habla acerca de acciones y eventos en el pasado que ya terminaron.
                img.mb-3.m-auto(src='@/assets/curso/temas/3.svg', alt='' style='width: 287px')
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="She phoned me two hours ago.  <span class='r-5 fw-normal fst-normal'>/ Ella me llamó hace dos horas.</span>"
                  :audio="require('@/assets/audios/tema1/1.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="<span class='r-5 fw-normal fst-normal'></span>"
                  :audio="require('@/assets/audios/tema1/1.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="<span class='r-5 fw-normal fst-normal'></span>"
                  :audio="require('@/assets/audios/tema1/1.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="<span class='r-5 fw-normal fst-normal'></span>"
                  :audio="require('@/assets/audios/tema1/1.wav')"
                  )


      .col-lg-6 
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    ocultarEsp: true,
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
.tarjeta-titulo-up
  position: relative

  &__titulo
      position: inherit
      width: 100%
      display: flex
      justify-content: center
      left: 0
      top: 0
      transform: translateY(-60%)
.lista-ol--cuadro__vineta
  background-color: $color-primario
span.text-gray
  color: #777777
</style>
