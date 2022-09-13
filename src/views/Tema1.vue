<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1(data-aos='fade-right') <em>Present perfect vs past simple</em> (Presente perfecto vs pasado simple)
    .row.justify-content-center.mb-5
      .col-lg-5: img(src='@/assets/curso/temas/1.svg')(data-aos='fade-right')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor(data-aos='fade-right')
          .contenedor-traductor__eng
            p.fst-italic The present perfect and the past simple are topics that tend to be confused with each other due to their similarities, especially the possibility of narrating past events with both verb tenses, which causes them to be used equivocally in some cases.
              br
              br
              | To solve this, we are going to see the differences between them and their uses:
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p 
              span.r-5 El presente perfecto y el pasado simple son temas que tienden a confundirse debido a sus similitudes, sobre todo, la posibilidad de narrar eventos pasados con ambos tiempos verbales genera que se usen de manera equívoca en algunos casos.
                br
                br
                |Para solucionar esto, vamos a ver las diferencias que hay entre ellos y sus usos:


          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
    .row.justify-content-center.mb-5(data-aos='fade-right')
      .col-lg-6.h-100 
        .tarjeta-titulo-up(style='background-color: #FFF0F1').p-4.mb-3
          .tarjeta-titulo-up__titulo
            .tarjeta.rounded-0.d-inline-block.p-3(style='background-color: #FC5F65')
              p.text-center.fw-bold.mb-0 <em>Simple past</em> / Pasado simple
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
        img.mb-3(src='@/assets/curso/temas/2.svg', alt='')(data-aos='fade-right')  
        .tarjeta.rounded-0.p-3(style='background-color: #FFDFE0')(data-aos='fade-right')
          .tarjeta.bg-white.p-4
            SlyderA(tipo='b')
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.py-4
                    span 1
                  | <em>The past simple talks about actions and events in the past that are now finished.</em> 
                  span.text-gray / El pasado simple habla acerca de acciones y eventos en el pasado que ya terminaron.
                  br
                  br
                  | <em>For example: </em> / Por ejemplo: 
                img.mb-3.m-auto(src='@/assets/curso/temas/3.svg', alt='' style='width: 287px')
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="She phoned me two hours ago.  <span class='r-5 fw-normal fst-normal'>/ Ella me llamó hace dos horas.</span>"
                  :audio="require('@/assets/audios/tema1/1.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="He didn’t play golf yesterday. <span class='r-5 fw-normal fst-normal'> / Él no jugó golf ayer. </span>"
                  :audio="require('@/assets/audios/tema1/2.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="Shakespeare wrote many plays. <span class='r-5 fw-normal fst-normal'>/ Shakespeare escribió muchas obras de teatro.</span>"
                  :audio="require('@/assets/audios/tema1/3.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="He worked there for six years.(He doesn’t work there anymore.) <span class='r-5 fw-normal fst-normal'> / Él trabajó ahí durante seis años. (Él ya no trabaja ahí.)</span>"
                  :audio="require('@/assets/audios/tema1/4.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.py-4
                    span 2
                  | <em>To indicate that something happened at a specific time in the past </em>  
                  span.text-gray / Para indicar que algo sucedió en un momento específico en el pasado.
                  br
                  br
                  | <em>For example: </em> / Por ejemplo: 
                img.mb-3.m-auto(src='@/assets/curso/temas/4.svg', alt='' )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="I bought a new car last week. <span class='r-5 fw-normal fst-normal'>/ Yo compré un coche nuevo la semana pasada. </span>"
                  :audio="require('@/assets/audios/tema1/5.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="He learned to ride a bike two months ago. <span class='r-5 fw-normal fst-normal'>/ Él aprendió a andar en bicicleta hace dos meses.</span>"
                  :audio="require('@/assets/audios/tema1/6.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="The new school year began yesterday. <span class='r-5 fw-normal fst-normal'>/ El nuevo año escolar comenzó ayer. </span>"
                  :audio="require('@/assets/audios/tema1/7.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="The plane to New York departed ten minutes ago. <span class='r-5 fw-normal fst-normal'>/ El avión a Nueva York partió hace diez minutos. </span>"
                  :audio="require('@/assets/audios/tema1/8.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.py-4
                    span 3
                  | <em>We use the past simple for a state in the past in a period which is finished. </em> 
                  span.text-gray / Usamos el pasado simple para un estado en el pasado en un periodo que ha terminado.
                  br
                  br
                  | <em>For example: </em> / Por ejemplo: 
                img.mb-3.m-auto(src='@/assets/curso/temas/5.svg', alt='' )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="I was in the hospital for three days.  <span class='r-5 fw-normal fst-normal'>/ Yo estuve en el hospital durante tres días. </span>"
                  :audio="require('@/assets/audios/tema1/9.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="She lived in London for two years. (She doesn’t live in London now.) <span class='r-5 fw-normal fst-normal'>/ Ella vivió en Londres durante dos años. (Ella no vive en Londres ahora.) </span>"
                  :audio="require('@/assets/audios/tema1/10.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.py-4
                    span 4
                  | <em>We use the past simple with “today”, “this morning”, “this week”, etc., when these periods are finished at the time of speaking. </em> 
                  span.text-gray / Usamos el pasado simple con “today”, “this morning”, “this week”, etc., cuando estos periodos ya se han terminado al momento de hablar.
                img.mb-3.m-auto(src='@/assets/curso/temas/c3.svg', alt='' style='width: 287px')
                p <em>For example: </em> / Por ejemplo: 
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="I didn’t shave today. (The day has passed. It means he will not shave today.) <span class='r-5 fw-normal fst-normal'> / No me afeité hoy. (El día ha pasado. Significa que no se afeitará hoy.)</span>"
                  :audio="require('@/assets/audios/tema1/11.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="She wrote three prescriptions this morning. (The morning is over.) <span class='r-5 fw-normal fst-normal'>/ Ella escribió tres recetas médicas esta mañana. (La mañana ha terminado.) </span>"
                  :audio="require('@/assets/audios/tema1/12.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.py-4
                    span 5
                  | <em>The past simple is used to give the details. </em> 
                  span.text-gray / El pasado simple se usa para dar los detalles.
                  br
                  br
                  | <em>For example: </em> / Por ejemplo:
                img.mb-3.m-auto(src='@/assets/curso/temas/7.svg', alt='' )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="The US space shuttle Atlantis landed in Florida this morning. <span class='r-5 fw-normal fst-normal'>/ El transbordador espacial estadounidense Atlantis aterrizó en Florida esta mañana. </span>"
                  :audio="require('@/assets/audios/tema1/13.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="Denver won by the comfortable score of 24 -  10. <span class='r-5 fw-normal fst-normal'>/ Denver ganó por la cómoda puntuación de 24 - 10. </span>"
                  :audio="require('@/assets/audios/tema1/14.wav')"
                  )
      .col-lg-6 
        .tarjeta-titulo-up(style='background-color: #e1e8ff').p-4.mb-3
          .tarjeta-titulo-up__titulo
            .tarjeta.rounded-0.d-inline-block.p-3(style='background-color: #6b8dfc')
              p.text-center.fw-bold.mb-0.text-white <em>Present perfect</em> / Presente perfecto
          .tarjeta-titulo-up__contenido
            p 
              span.r-3.fst-italic.fw-normal It usually talks about an activity that started in the past but it’s not finished (it is connected to the present.)
              | Por lo general, habla de una actividad que comenzó en el pasado, pero no ha terminado (está conectado con el presente).

              br
              br
              span.r-3.fst-italic.fw-normal Clue words: 
              | / Palabras clave:
              br
              |<em><b>“Ever / Never” “Since”  “So far” “Yet”</b></em>
              br
              br
              span.r-3.fst-italic.fw-normal Cases in which the present perfect is used: 
              |  / Casos en los que se usa el presente perfecto:
        img.mb-3(src='@/assets/curso/temas/8.svg', alt='')(data-aos='fade-right')  
        .tarjeta.rounded-0.p-3(style='background-color: #a6bbff')(data-aos='fade-right')
          .tarjeta.bg-white.p-4
            SlyderA(tipo='b')
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.azul.py-4
                    span 1
                  | <em>The present perfect shows relation between past time and present time. </em> 
                  span.text-gray  / El presente perfecto muestra una relación entre el tiempo pasado y el tiempo presente.

                  br
                  br
                  | <em>For example: </em> / Por ejemplo: 

                img.mb-3.m-auto(src='@/assets/curso/temas/9.svg', alt='' style='width: 287px')
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="She has phoned me four times so far. <span class='r-5 fw-normal fst-normal'> /  Ella me ha llamado cuatro veces hasta ahora.</span>"
                  :audio="require('@/assets/audios/tema1/15.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="He has never played golf before. <span class='r-5 fw-normal fst-normal'>/ Él nunca ha jugado golf antes.</span>"
                  :audio="require('@/assets/audios/tema1/16.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="My sister has written many books. (She still writes books.) <span class='r-5 fw-normal fst-normal'>/ Mi hermana ha escrito muchos libros. (Ella todavía escribe libros.) </span>"
                  :audio="require('@/assets/audios/tema1/17.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="He has worked there for six years. (He still works there.) <span class='r-5 fw-normal fst-normal'> / Él ha trabajado ahí durante seis años. (Él todavía trabaja ahí.)</span>"
                  :audio="require('@/assets/audios/tema1/18.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.azul.py-4
                    span 2
                  | <em>To talk about something that happened in the past, but we don’t specify when it has happened (because we don’t know or it is not important.) </em> 
                  span.text-gray / Para hablar de algo que sucedió en el pasado, pero no especificamos cuándo sucedió (porque no sabemos o no es importante).
                img.mb-3.m-auto(src='@/assets/curso/temas/10.svg', alt='' )
                p  <em>For example: </em> / Por ejemplo: 
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="I have bought a new car. <span class='r-5 fw-normal fst-normal'> / Yo he comprado un nuevo auto.</span>"
                  :audio="require('@/assets/audios/tema1/19.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="He has already learned to ride a bike. <span class='r-5 fw-normal fst-normal'> / Él ya ha aprendido a andar en bicicleta.</span>"
                  :audio="require('@/assets/audios/tema1/20.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="The new school year has just begun. <span class='r-5 fw-normal fst-normal'> / El nuevo año escolar acaba de comenzar. (El nuevo año escolar ha acabado de comenzar.)</span>"
                  :audio="require('@/assets/audios/tema1/21.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="The plane to New York has already departed. <span class='r-5 fw-normal fst-normal'> / El avión a Nueva York ya ha partido.</span>"
                  :audio="require('@/assets/audios/tema1/22.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.azul.py-4
                    span 3
                  | <em>We use the present perfect for a state which has gone on up to the present. </em> 
                  span.text-gray / Usamos el presente perfecto para un estado que ha continuado hasta el presente.
                  br
                  br
                  | <em>For example: </em> / Por ejemplo: 

                img.mb-3.m-auto(src='@/assets/curso/temas/11.svg', alt='' )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="I have been in the hospital for three days. (I am still in the hospital.) <span class='r-5 fw-normal fst-normal'>/ Yo he estado en el hospital durante tres días. (Todavía estoy en el hospital.) </span>"
                  :audio="require('@/assets/audios/tema1/23.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="She has lived in London for two years. (She still lives in London.)  <span class='r-5 fw-normal fst-normal'>/ Ella ha vivido en Londres desde hace dos años. (Todavía vive en Londres.) </span>"
                  :audio="require('@/assets/audios/tema1/24.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.azul.py-4
                    span 4
                  | <em>We use the present perfect with “today”, “this morning”, “this week”, etc., when these periods are not finished at the time of speaking.</em> 
                  span.text-gray / Usamos el presente perfecto con “today”, “this morning”, “this week”, etc., cuando estos periodos no se han terminado al momento de hablar.
                img.mb-3.m-auto(src='@/assets/curso/temas/12.svg', alt='' style='width: 287px')
                p <em>For example: </em> / Por ejemplo: 

                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="I haven’t shaved today. (The day is not finished. He may shave later or may not)  <span class='r-5 fw-normal fst-normal'>/ Yo no me he afeitado hoy. (El día no ha terminado. Puede que luego se afeite o puede que no.)</span>"
                  :audio="require('@/assets/audios/tema1/25.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="She has written three prescriptions this morning. (It is still morning.) <span class='r-5 fw-normal fst-normal'> / Ella ha escrito tres recetas esta mañana. (Todavía es de mañana.)</span>"
                  :audio="require('@/assets/audios/tema1/26.wav')"
                  )
              div
                ol.lista-ol--cuadro
                  li
                  .lista-ol--cuadro__vineta.azul.py-4
                    span 5
                  | <em>The present perfect is used to give new information (a general summary.) </em> 
                  span.text-gray / El presente perfecto se usa para dar nueva información (un resumen general).
                  br
                  br
                  | <em>For example: </em> / Por ejemplo: 

                img.mb-3.m-auto(src='@/assets/curso/temas/13.svg', alt='' )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="The US space shuttle Atlantis has returned safely to earth. <span class='r-5 fw-normal fst-normal'>/ El transbordador espacial estadounidense Atlantis ha regresado sano y salvo a la Tierra.</span>"
                  :audio="require('@/assets/audios/tema1/27.wav')"
                  )
                TarjetaAudio.color-primario.bg-white.mb-3(
                  texto="Denver Broncos have won the Super Bowl 2016. <span class='r-5 fw-normal fst-normal'>/ Los Broncos de Denver han ganado el Super Bowl 2016.</span>"
                  :audio="require('@/assets/audios/tema1/28.wav')"
                  )
    Dialogo.color-acento-contenido(:dialogo="dialogo")(data-aos='zoom-in')
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Completa la conversación
      template(#descripcion-actividad)
    .titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 Actividad didáctica 
    .row.mb-5.justify-content-center.align-items-center.align-items-lg-stretch
      .col-6.col-md-4.col-lg-3.mb-4.mb-md-0
        .tarjeta.h-100.d-flex.align-items-center.p-4
          figure
            img(src="@/assets/template/completar-espacios.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 #[i Present perfect and past simple] / Presente perfecto y pasado simple
        p.mb-4 Diferenciar las estructuras y los usos de los tiempos pasado simple y presente perfecto.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Completar los espacios
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/a1/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    ocultarEsp: true,
    dialogo: {
      personajes: [
        {
          nombre: 'Ana',
          img: require('@/assets/curso/temas/ana.svg'),
        },
        {
          nombre: 'Luisa',
          img: require('@/assets/curso/temas/luisa.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Ana',
          textoIng: 'Hi! How ***?',
          textoEsp: 'Pendiente traduccion',
          audio: require('@/assets/audios/a1/1.wav'),
          palabra: 'have you been',
        },
        {
          personaje: 'Luisa',
          textoIng: 'Hey! Awesome! How about you?',
          textoEsp: '',
          audio: require('@/assets/audios/a1/2.wav'),
        },
        {
          personaje: 'Ana',
          textoIng: 'I’m great! *** from my trip yesterday',
          textoEsp: '',
          audio: require('@/assets/audios/a1/3.wav'),
          palabra: 'I arrived',
        },
        {
          personaje: 'Luisa',
          textoIng: 'Really? Where did you go?',
          textoEsp: '',
          audio: require('@/assets/audios/a1/4.wav'),
        },
        {
          personaje: 'Ana',
          textoIng:
            '*** to Italy. I have been there many times, but I love it.',
          textoEsp: '',
          audio: require('@/assets/audios/a1/5.wav'),
          palabra: 'I went',
        },
        {
          personaje: 'Luisa',
          textoIng:
            'Wow! *** there for the first time 2 years ago and I loved it too.',
          textoEsp: '',
          audio: require('@/assets/audios/a1/6.wav'),
          palabra: 'I traveled',
        },
        {
          personaje: 'Ana',
          textoIng: 'Sure! Have you already planned your next trip?',
          textoEsp: '',
          audio: require('@/assets/audios/a1/7.wav'),
        },
        {
          personaje: 'Luisa',
          textoIng: 'I haven’t, but *** many options this time.',
          textoEsp: '',
          audio: require('@/assets/audios/a1/8.wav'),
          palabra: 'I have seen',
        },
      ],
    },
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
  span
    font-weight: bold
.lista-ol--cuadro__vineta.azul
  background-color: $color-acento-contenido
  span
    font-weight: bold
    color: #12263f

span.text-gray
  color: #777777
</style>
