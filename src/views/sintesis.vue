<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .row.justify-content-center.mb-5
      .col-lg-4: img(src='@/assets/curso/temas/00.jpg', alt='')
      .col-lg-8 
        p 
          span.r-4.fst-italic.fw-normal Up to this point, we have been able to appreciate everything that has to do with the present perfect and present perfect continuous tenses, how they are used and structured, their differences with other verb tenses that we learned previously (such as the simple past), and other grammar elements and vocabulary that complement this topic. For this reason, you are invited to appreciate the following conceptual scheme that summarizes the subject matter:
          br
          br
          span.text-gray Hasta este punto, hemos podido apreciar todo lo que tiene que ver con los tiempos presente perfecto y presente perfecto continuo, cómo se usan y se estructuran, sus diferencias con otros tiempos verbales que aprendimos anteriormente, como por ejemplo el pasado simple, y demás elementos gramaticales y vocabulario que complementan este tema. Por ello, se invita a que aprecie el siguiente esquema conceptual que resume la temática tratada:
    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="alt")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
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
