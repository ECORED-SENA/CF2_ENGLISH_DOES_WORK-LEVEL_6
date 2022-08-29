<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    .row.justify-content-center.mb-5
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p.fst-italic In order to build complex sentences and narrate our experiences, the things that we have lived or that we have been doing in our free time, we must be able to fully handle the grammatical structures of the perfect tenses (present perfect and present perfect continuous) and differentiate their uses from the tenses like, for example, the simple past. We must also learn which discourse markers will help us organize these narratives and how to use them correctly, and, of course, useful vocabulary to be able to express them appropriately. Based on this, we welcome you to the study of this training component and, to begin, you are invited to explore the video presented below:
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p 
              span.r-5 Para poder construir oraciones complejas y narrar nuestras experiencias, las cosas que hemos vivido o que hemos estado realizando en nuestro tiempo libre, debemos poder manejar a cabalidad las estructuras gramaticales de los tiempos perfectos (presente perfecto y presente perfecto continuo) y diferenciar sus usos de los de tiempos como, por ejemplo, el pasado simple. También debemos aprender cuáles marcadores del discurso nos van a ayudar a organizar estas narrativas y cómo usarlos correctamente, y por supuesto, vocabulario útil para poder expresarlas de forma apropiada. Partiendo de lo anterior, le damos la bienvenida al estudio de este componente formativo y, para comenzar, se le invita a explorar el video que se presenta a continuación:

          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
      .col-lg-5: img(src='@/assets/curso/temas/0.jpg', alt='')
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/KSdzPzOQ2Lc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

      
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    ocultarEsp: true,
  }),
}
</script>

<style lang="sass"></style>
