<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1(data-aos='fade-right') <em>We have been enjoying our free time a lot</em> (Hemos estado disfrutando mucho de nuestro tiempo libre)
    .row.justify-content-center.mb-5(data-aos='fade-right')
      .col-lg-7.mb-lg-0.mb-3
        p
          span.r-4.fst-italic.fw-normal When talking about leisure activities or free time activities, it is important to take into account all of those activities that we do in order to have fun. It is not about all of those obligations that we have in our daily life. 
          br
          br
          span.text-gray Cuando se habla de actividades de ocio o actividades de tiempo libre, es importante tener en cuenta todas aquellas actividades que realizamos para divertirnos. No se trata de todas esas obligaciones que tenemos en nuestra vida diaria.

      .col-lg-5: img(src='@/assets/curso/temas/45.svg')
    .margin-n.p-5(style='background-color: #d5d6f0').mb-5(data-aos='zoom-in')
      p.text-center Observe y escuche vocabulario de algunas actividades de ocio o actividades de tiempo libre:
      .tarjeta.bg-white.p-4.position-relative
        .img-1: img(src='@/assets/curso/temas/adorno1.svg', alt='')
        .img-2: img(src='@/assets/curso/temas/adorno2.svg', alt='')
        SlyderF.mb-5(columnas="col-lg-6 col-xl-4").slyder-100
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/46.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Dance</b></em>
                br
                br
                span.text-gray Bailar
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/1.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic I danced at a party yesterday. 
                  br 
                  | Yo bailé en una fiesta ayer.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/47.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Sing</b></em>
                br
                br
                span.text-gray Cantar
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/2.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic My brother has been singing for years.
                  br 
                  | Mi hermano ha estado cantando por años.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/48.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Go shopping</b></em>
                br
                br
                span.text-gray Ir de compras
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/3.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic We have gone shopping twice this month. 
                  br 
                  | Nosotros hemos ido de compras dos veces este mes.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/49.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Eat out</b></em>
                br
                br
                span.text-gray Salir a comer
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/4.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic I haven’t eaten out with my brother this year. 
                  br 
                  | No he salido a comer con mi hermano este año.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/50.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Sleep late</b></em>
                br
                br
                span.text-gray Dormir hasta tarde
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/5.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic I haven’t slept late in months. 
                  br 
                  | No he dormido hasta tarde en meses.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/51.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Fish</b></em>
                br
                br
                span.text-gray Pescar
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/6.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic My father has been fishing for hours. 
                  br 
                  | Mi papá ha estado pescando por horas. 
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/52.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Check social networks</b></em>
                br
                br
                span.text-gray Revisar redes sociales 
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/7.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic Sara has been checking her social networks for an hour.  
                  br 
                  | Sara ha estado revisando sus redes sociales por una hora.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/53.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Go sightseeing</b></em>
                br
                br
                span.text-gray  Ir a turistear
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/8.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic My family has gone sightseeing in Europe.
                  br 
                  | Mi familia ha ido a turistear en Europa.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/54.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Paint</b></em>
                br
                br
                span.text-gray Pintar
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/9.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic The artist has been painting that picture for years. 
                  br 
                  | El artista ha estado pintando esa pintura por años.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/55.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Do yoga</b></em>
                br
                br
                span.text-gray Hacer yoga
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/10.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic My mother has been doing yoga since 2017.
                  br 
                  | Mi mamá ha estado haciendo yoga desde 2017. 
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/56.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Chill</b></em>
                br
                br
                span.text-gray Relajarse
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/11.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic I have been chilling for 2 hours. 
                  br 
                  | Yo he estado relajándome por 2 horas.
          .tarjeta.color-primario.p-4.h-100.hbg--4.h-100.hbg--3.h-100.h-100
            .row.justify-content-center.mb-3
              .col-6
                img(src='@/assets/curso/temas/57.svg' alt='AvatarTop')
            .tarjeta.bg-white.p-2
              p.text-center <em><b>Tell stories </b></em>
                br
                br
                span.text-gray Contar historias
              .tarjeta.color-primario--borde.border-1.p-3.d-flex.flex-column.justify-content-center
                Audio.color-primario.d-block(:audio="require('@/assets/audios/tema4/12.mp3')").m-auto.mb-2
                p.text-center
                  span.r-1.fst-italic My teacher has been telling stories the whole class. 
                  br 
                  | Mi profesor ha estado contando historias toda la clase.


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
            img(src="@/assets/template/arrastrar.svg", alt="Texto que describa la imagen")
      .col-12.col-md-8.col-lg-9
        .titulo-segundo
          h2 #[i Vocabulary trivia game] / Juego de preguntas de vocabulario
        p.mb-4 Reforzar conocimientos acerca del vocabulario útil para hablar de actividades de ocio.
        .tarjeta.actividad.p-3
          .row.justify-content-around.align-items-center            
            .col-sm.mb-3.mb-sm-0
              p.fw-bold.mb-0 Arrastrar y soltar
            .col-auto
              a.boton.boton--b(:href="obtenerLink('/actividades/a4/story.html')" target="_blank")
                span Realizar
                i.fas.fa-puzzle-piece       
        
</template>

<script>
export default {
  name: 'Tema4',
  data: () => ({
    ocultarEsp1: true,
    ocultarEsp2: true,
    ocultarEsp3: true,
    ocultarEsp4: true,
    ocultarEsp5: true,
    ocultarEsp6: true,
    ocultarEsp7: true,
    ocultarEsp8: true,
    ocultarEsp9: true,
    dialogo: {
      personajes: [
        {
          nombre: 'Sandra',
          img: require('@/assets/curso/temas/sandra.svg'),
        },
        {
          nombre: 'David',
          img: require('@/assets/curso/temas/david.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Sandra',
          textoIng:
            'Hey David, did you practice many sports when you were a child?',
          textoEsp: 'Pendiente traduccion',
          audio: require('@/assets/audios/a4/1.wav'),
        },
        {
          personaje: 'David',
          textoIng:
            'Sure! My parents have been registering me to try new activities.',
          textoEsp: '',
          audio: require('@/assets/audios/a4/2.mp3'),
        },
        {
          personaje: 'Sandra',
          textoIng: 'What sports have you practiced?',
          textoEsp: '',
          audio: require('@/assets/audios/a4/3.wav'),
        },
        {
          personaje: 'David',
          textoIng:
            'Well, I have played ***, volleyball, football, and of course basketball. ',
          textoEsp: '',
          audio: require('@/assets/audios/a4/4.mp3'),
          palabra: 'tennis',
        },
        {
          personaje: 'Sandra',
          textoIng: 'Wow! Have you ever tried any other activities?',
          textoEsp: '',
          audio: require('@/assets/audios/a4/5.wav'),
        },
        {
          personaje: 'David',
          textoIng:
            'Yes! I have done yoga, I have gone camping, I have *** and played chess. ',
          textoEsp: '',
          audio: require('@/assets/audios/a4/6.mp3'),
          palabra: 'fished',
        },
        {
          personaje: 'Sandra',
          textoIng: 'I have always loved fishing! Have you been *** recently?',
          textoEsp: '',
          audio: require('@/assets/audios/a4/7.wav'),
          palabra: 'fishing',
        },
        {
          personaje: 'David',
          textoIng:
            'Not really, but three months ago something incredible happened, I got a small shark, it was terrifying!',
          textoEsp: '',
          audio: require('@/assets/audios/a4/8.mp3'),
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
.bg-card
  background-image: url(../assets/curso/temas/bg-card.svg)
  background-repeat: repeat
  background-size: cover
.tarjeta-4
  background-color: #a6bbff
.bg-card
  background-image: url(../assets/curso/temas/bg-card-1.svg)
  background-repeat: repeat
  background-size: cover
  background-position: center
.img-1
  position: absolute
  width: 75px
  top: 0
  right: 0
  transform: translate(30%,-30%)

.img-2
  position: absolute
  width: 83px
  bottom: 0
  left: 0
  transform: translate(-30%,30%)
</style>
