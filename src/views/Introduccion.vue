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
            p.fst-italic IIn order to build complex sentences and narrate our experiences, the things that we have lived or that we have been doing in our free time, we must be able to fully handle the grammatical structures of the perfect tenses (present perfect and present perfect continuous) and differentiate their uses from the tenses like, for example, the simple past. We must also learn which discourse markers will help us organize these narratives and how to use them correctly, and, of course, useful vocabulary to be able to express them appropriately. Based on this, we welcome you to the study of this training component and, to begin, you are invited to explore the video presented below:
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp}")
            p 
              span.r-5 Traduccion no presente

          a.boton-traduccion(@click='ocultarEsp = !ocultarEsp') Ver traducción
      .col-lg-5: img(src='@/assets/curso/temas/0.jpg', alt='')
    figure
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/2L91WMqw96A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

      
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
