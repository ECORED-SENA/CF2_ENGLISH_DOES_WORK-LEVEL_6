<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 <em>Present perfect continuous</em> (Presente perfecto continuo)
    .row.justify-content-center.mb-5
      .col-lg-5: img(src='@/assets/curso/temas/25.svg')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p.fst-italic The present perfect continuous is a tense used to refer to an unspecified time between ‘before now’ and ‘now’, so it shows duration and importance in the present time. The speaker is talking about an action or activity that started but perhaps did not finish in that period of time.
              br
              br
              |The present perfect continuous is formed by using the present tense of the verb have + the past participle of be + the present participle of the main verb.
              br
              br
              |Next, we will see some cases in which the present perfect continuous tense is used:
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp1}")
            p 
              span.r-5 El presente perfecto continuo es un tiempo verbal que se usa para referirse a un tiempo no especificado entre 'antes de ahora' y 'ahora', por lo que muestra duración e importancia en el tiempo presente. El emisor está hablando de una acción o actividad que comenzó, pero quizás no terminó en ese periodo de tiempo.
                br
                br
                |El presente perfecto continuo se forma usando el tiempo presente del verbo #[i have +] el participio pasado de #[i be +] el participio presente del verbo principal.
                br
                br
                |A continuación, veremos casos en los que se usa el tiempo presente perfecto continuo:


          a.boton-traduccion(@click='ocultarEsp1 = !ocultarEsp1') Ver traducción
    .bg-card.p-4.mb-5
      .row.justify-content-center.align-items-end.mb-5
        .col-lg-3
          img(src='@/assets/curso/temas/26.png', alt='')
        .col-lg-9
          .tarjeta.bg-white.p-4
            SlyderA(tipo='b')
              div
                p.fw-bold.text-center Past activities that recently ended / Actividades pasadas que acabaron recientemente
                .contenedor-traductor.mb-5
                  .contenedor-traductor__eng
                    p.fst-italic We use the present perfect continuous tense to talk about a finished action or activity in the recent past. When we use the present perfect continuous tense, we focus on the activity, but we don’t give a specific time. Even though the activity is finished, we can see the result in the present:
                  .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp2}")
                    p 
                      span.r-5 Usamos el presente perfecto continuo para hablar de una acción o actividad finalizada en el pasado reciente. Cuando usamos el presente perfecto continuo nos enfocamos en la actividad, pero no damos un tiempo específico. Aunque la actividad está terminada, podemos ver el resultado en el presente: 
                  a.boton-traduccion(@click='ocultarEsp2 = !ocultarEsp2') Ver traducción
                p.text-center <em>For example</em> / Por ejemplo: 
                .row.justify-content-center
                  .col-lg-2: img(src='@/assets/curso/temas/41.svg', alt='')
                  .col-lg-5
                    TarjetaAudio.color-primario.bg-white.mb-3(
                      texto="It has been raining."
                      :audio="require('@/assets/audios/tema3/1.mp3')"
                      )
                    p.ms-3 Ha estado lloviendo.
              div
                p.fw-bold.text-center Actions not finished or in progress / Acciones no finalizadas o en curso
                .contenedor-traductor.mb-5
                  .contenedor-traductor__eng
                    p.fst-italic We use the present perfect continuous tense for a single activity that began at a point in the past and is still continuing:
                  .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp3}")
                    p 
                      span.r-5 Usamos el tiempo presente perfecto continuo para una sola actividad que comenzó en un punto en el pasado y aún continúa: 
                  a.boton-traduccion(@click='ocultarEsp3 = !ocultarEsp3') Ver traducción
                p.text-center <em>For example</em> / Por ejemplo: 
                .row.justify-content-center
                  .col-lg-2: img(src='@/assets/curso/temas/42.svg', alt='')
                  .col-lg-5
                    TarjetaAudio.color-primario.bg-white.mb-3(
                      texto="I have been reading this book. (I’m still reading it.)"
                      :audio="require('@/assets/audios/tema3/2.mp3')"
                      )
                    p.ms-3 He estado leyendo este libro. (Todavía lo estoy leyendo).
              div
                p.fw-bold.text-center Repeated events in progress / Eventos repetidos en curso
                .contenedor-traductor.mb-5
                  .contenedor-traductor__eng
                    p.fst-italic We use the present perfect continuous tense to talk about repeated activities which started at a particular time in the past and are still continuing up until now:
                  .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp4}")
                    p 
                      span.r-5 Usamos el presente perfecto continuo para hablar de actividades repetidas que comenzaron en un momento particular en el pasado y continúan hasta ahora: 
                  a.boton-traduccion(@click='ocultarEsp4 = !ocultarEsp4') Ver traducción
                p.text-center <em>For example</em> / Por ejemplo: 
                .row.justify-content-center
                  .col-lg-2: img(src='@/assets/curso/temas/43.svg', alt='')
                  .col-lg-5
                    TarjetaAudio.color-primario.bg-white.mb-3(
                      texto="He’s been playing football on and off for five years. "
                      :audio="require('@/assets/audios/tema3/3.mp3')"
                      )
                    p.ms-3 Ha estado jugando al fútbol de forma intermitente durante cinco años.
              div
                p.fw-bold.text-center How long …? / ¿Cuánto tiempo …?
                .contenedor-traductor.mb-5
                  .contenedor-traductor__eng
                    p.fst-italic We often use the present perfect continuous tense to ask and answer questions about the duration of an action or activity. We use the question “How long …+ present perfect continuous”:
                  .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp5}")
                    p 
                      span.r-5 A menudo, usamos el presente perfecto continuo para hacer y responder preguntas sobre la duración de una acción o actividad. Usamos la pregunta "¿Cuánto tiempo…+ presente perfecto continuo":
                  a.boton-traduccion(@click='ocultarEsp5 = !ocultarEsp5') Ver traducción
                p.text-center <em>For example</em> / Por ejemplo: 
                .row.justify-content-center
                  .col-lg-2: img(src='@/assets/curso/temas/44.svg', alt='')
                  .col-lg-7
                    TarjetaAudio.color-primario.bg-white.mb-3(
                      texto="A: How long have you been studying English?<br>B: About a year. (I have been studying English for about a year.)"
                      :audio="require('@/assets/audios/tema3/4.mp3')"
                      )
                    p.ms-3 <b>A:</b> ¿Cuánto tiempo has estado estudiando inglés?
                      br
                      |<b>B:</b> Como un año. (He estado estudiando inglés durante aproximadamente un año.)
    #t_3_1.titulo-segundo.color-primario(data-aos='fade-right')
      h2 3.1  <em>Verbs ending in “-ing”</em> (Verbos con terminación “-ing”)
    .row.justify-content-center.mb-5
      .col-lg-5: img(src='@/assets/curso/temas/27.jpg')
      .col-lg-7.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p.fst-italic To use the continuous tenses (also called progressive), we need to use the main verbs in a verbal pattern called “present participle”, a pattern that is characterized by the fact that the verb always ends in “-ing”.
              br
              br
              |To write a verb ending in “-ing”, we need to know the correct spelling, that is why the rules for correctly writing verbs ending in “-ing” are listed below:
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp6}")
            p 
              span.r-5 Para usar los tiempos continuos (también llamados progresivos), se necesita usar los verbos principales en un patrón verbal llamado "participio presente", patrón que se caracteriza porque siempre el verbo termina en "-ing".
                br
                br
                |Para escribir un verbo terminado en "-ing", se necesita saber la ortografía correcta, es por eso que a continuación están enunciadas las reglas para escribir correctamente verbos terminados en "-ing":
          a.boton-traduccion(@click='ocultarEsp6 = !ocultarEsp6') Ver traducción
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/tsaNgMHca2k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    Separador
    #t_3_2.titulo-segundo.color-primario(data-aos='fade-right')
      h2 3.2  <em>Affirmative, negative and interrogative structures</em> (Estructuras afirmativas, negativas e interrogativas)
    .tarjeta.rounded-0.p-1(style='background-color: #f0f4ff').mb-5
      .row.justify-content-center.align-items-center
        .col-lg-8
          p
            span.r-4.fw-normal.fst-italic For the present perfect continuous tense, the verb <b>"to have"</b> is used as an auxiliary, conjugated in the present simple (have / has), together with the past participle of the verb “to be” <b>(been)</b>. Let's see how to use the auxiliaries for the present perfect continuous tense with each subject pronoun:
            br
            br
            span.text-gray Para el tiempo presente perfecto continuo, se usa como auxiliar el verbo <b>"to have"</b>, conjugado en presente simple (have/has), junto con el participio pasado del verbo <em>"to be"</em> <b>(been)</b>. Veamos cómo usar los auxiliares del tiempo presente perfecto continuo con cada pronombre de sujeto:
        .col-lg-3: img(src='@/assets/curso/temas/28.svg', alt='')
    p.text-center
      span.r-4.fst-italic Verb “to have” in present simple + BEEN
    .titulo-sexto.color-primario(data-aos='fade-right')
      h5 Tabla 2
      span Auxiliaries for the present perfect continuous tense
    .tarjeta.rounded-0.color-acento-contenido.p-3
      h3.text-center.mb-0 Singular
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-3.mb-lg-0.mb-3.h-100
        .tarjeta.rounded-0.p-4(style='background-color: #e1e8ff; border: 2px solid #6b8dfc').h-100
          img.m-auto.mb-2(src='@/assets/curso/temas/29.svg', alt='' style='width: 85px')
          h4.text-center
            span.r-3 1st person
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto="I have been"
            :audio="require('@/assets/audios/tema3/5.wav')"
            )
      .col-lg-3.mb-lg-0.mb-3.h-100
        .tarjeta.rounded-0.p-4(style='background-color: #e1e8ff; border: 2px solid #6b8dfc').h-100
          img.m-auto.mb-2(src='@/assets/curso/temas/29.svg', alt='' style='width: 85px')
          h4.text-center
            span.r-3 2st person
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto="You have been"
            :audio="require('@/assets/audios/tema3/6.wav')"
            )
      .col-lg-6
        .tarjeta.rounded-0.p-4(style='background-color: #e1e8ff; border: 2px solid #6b8dfc').h-100
          img.m-auto.mb-2(src='@/assets/curso/temas/29.svg', alt='' style='width: 85px')
          h4.text-center
            span.r-3 3st person
          .row.justify-content-center
            .col-lg-4
              TarjetaAudio.color-primario.bg-white.mb-3(
                texto="He has been"
                :audio="require('@/assets/audios/tema3/7.wav')"
                )
            .col-lg-4
              TarjetaAudio.color-primario.bg-white.mb-3(
                texto="She has been"
                :audio="require('@/assets/audios/tema3/8.wav')"
                )
            .col-lg-4
              TarjetaAudio.color-primario.bg-white.mb-3(
                texto="It has been"
                :audio="require('@/assets/audios/tema3/9.wav')"
                )
    .row.justify-content-center
      .col-lg-9
        .tarjeta.rounded-0.color-acento-botones.p-3
          h3.text-center.mb-0 Plural
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-3.mb-lg-0.mb-3
        .tarjeta.rounded-0.p-4(style='background-color: #d5d6f0; border: 2px solid #6b8dfc').h-100
          img.m-auto.mb-2(src='@/assets/curso/temas/30.svg', alt='' style='width: 85px')
          h4.text-center
            span.r-4 1st person
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto="We have been"
            :audio="require('@/assets/audios/tema3/10.wav')"
            )
      .col-lg-3.mb-lg-0.mb-3
        .tarjeta.rounded-0.p-4(style='background-color: #d5d6f0; border: 2px solid #6b8dfc').h-100
          img.m-auto.mb-2(src='@/assets/curso/temas/30.svg', alt='' style='width: 85px')
          h4.text-center
            span.r-4 2st person
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto="You have been"
            :audio="require('@/assets/audios/tema3/11.wav')"
            )
      .col-lg-3.mb-lg-0.mb-3
        .tarjeta.rounded-0.p-4(style='background-color: #d5d6f0; border: 2px solid #6b8dfc').h-100
          img.m-auto.mb-2(src='@/assets/curso/temas/30.svg', alt='' style='width: 85px')
          h4.text-center
            span.r-4 3st person
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto="They have been"
            :audio="require('@/assets/audios/tema3/12.wav')"
            )
    .row.justify-content-center.mb-5
      .col-lg-3: img(src='@/assets/curso/temas/31.svg')
      .col-lg-9.mb-lg-0.mb-3
        .contenedor-traductor
          .contenedor-traductor__eng
            p.fst-italic Something that should be highlighted when structuring sentences in the present perfect continuous is that “subject + have been / has been + main verb ending in -ing” is used at the beginning of the sentence. Basically, if you already know how to structure sentences in the “simple” present perfect tense, structuring the present perfect continuous is going to be very simple since it is practically the same, but with the verb “to be” always in the form of a past participle (been) and, after this, the main verb in the form of a present participle (ending in “-ing”).
              br
              br
              |We are going to see how these verbs interact with the rest of the words in the sentences in the past progressive.
          .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp1}")
            p 
              span.r-5 Algo que hay que resaltar a la hora de estructurar oraciones en presente perfecto continuo es que se usa “sujeto + #[i have been / has been] + verbo principal terminado en #[i -ing”] al comienzo de la oración. Básicamente, si ya se sabe cómo estructurar oraciones en el tiempo presente perfecto, estructurar el presente perfecto continuo va a ser muy sencillo, porque es prácticamente lo mismo, pero con el verbo #[i "to be"] siempre en forma de participio pasado #[i (been)] y, después de este, el verbo principal en forma de participio presente (terminado en #[i “-ing”)].
                br  
                br  
                |Veamos cómo estos verbos interactúan con el resto de las palabras en las oraciones en pasado progresivo:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta-4")
      div(titulo="Affirmative / Afirmativa").p-5
        .tarjeta.bg-white.p-4
          p.text-center
            span.r-4 Affirmative / Afirmativa
          img.mb-4(src='@/assets/curso/temas/32.svg', alt='')
          .row.justify-content-center.mb-3
            .col-lg-6.mb-lg-0.mb-3: img(src='@/assets/curso/temas/33.svg', alt='')
            .col-lg-6
              p 
                span.text-gray Yo he estado <b>jugando</b> al tenis recientemente.
                  br
                  |Tú has estado <b>escuchando</b> música todo el día.
                  br
                  |Él ha estado <b>trabajando</b> aquí desde el año pasado.
                  br
                  |Ella ha estado <b>estudiando</b> para sus exámenes.
                  br
                  |(Eso) Ha estado <b>comiendo</b> mucho últimamente.
                  br
                  br
                  |Nosotros hemos estado <b>viendo</b> Netflix por seis horas.
                  br
                  |Ustedes han estado <b>escribiendo</b> sus ensayos toda la tarde.
                  br
                  |Ellos han estado <b>haciendo</b> ejercicio desde el bachillerato.
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto=""
            :audio="require('@/assets/audios/tema3/13.mp3')"
            )
      div(titulo="Negative / Negativa")
        .tarjeta.bg-white.p-4
          p.text-center
            span.r-4 Negative / Negativa
          img.mb-4(src='@/assets/curso/temas/34.svg', alt='')
          .row.justify-content-center.mb-3
            .col-lg-6.mb-lg-0.mb-3: img(src='@/assets/curso/temas/35.svg', alt='')
            .col-lg-6
              p 
                span.text-gray Yo no he estado <b>jugando</b> al tenis recientemente.
                  br
                  |Tú no has estado <b>escuchando</b> música todo el día.
                  br
                  |Él no ha estado <b>trabajando</b> aquí desde el año pasado.
                  br
                  |Ella no ha estado <b>estudiando</b> para sus exámenes.
                  br
                  |(Eso) No ha estado <b>comiendo</b> mucho últimamente.
                  br
                  br
                  |Nosotros no hemos estado <b>viendo</b> Netflix por seis horas.
                  br
                  |Ustedes no han estado <b>escribiendo</b> sus ensayos toda la tarde.
                  br
                  |Ellos no han estado <b>haciendo</b> ejercicio desde el bachillerato.
          TarjetaAudio.color-primario.bg-white.mb-3(
              texto=""
              :audio="require('@/assets/audios/tema3/14.mp3')"
              )
      div(titulo="“Yes” or “No” Questions / Preguntas de “Sí” y “No”")
        .tarjeta.bg-white.p-4
          p.text-center
            span.r-4 “Yes” or “No” Questions / Preguntas de “Sí” y “No”
          img.mb-4(src='@/assets/curso/temas/36.svg', alt='')
          .row.justify-content-center.mb-3
            .col-lg-6.mb-lg-0.mb-3: img(src='@/assets/curso/temas/37.svg', alt='')
            .col-lg-6
              p 
                span.text-gray ¿Yo he estado <b>jugando</b> al tenis recientemente?
                  br
                  |¿Tú has estado <b>escuchando</b> música todo el día?
                  br
                  |¿Él ha estado <b>trabajando</b> aquí desde el año pasado?
                  br
                  |¿Ella ha estado <b>estudiando</b> para sus exámenes?
                  br
                  |¿(Eso) Ha estado <b>comiendo</b> mucho últimamente?
                  br
                  br
                  |¿Nosotros hemos estado <b>viendo</b> Netflix por seis horas?
                  br
                  |¿Ustedes han estado <b>escribiendo</b> sus ensayos?
                  br
                  |¿Ellos han estado <b>haciendo</b> ejercicio desde el bachillerato?
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto=""
            :audio="require('@/assets/audios/tema3/15.mp3')"
            )
      div(titulo="Information Questions / Preguntas de información")
        .tarjeta.bg-white.p-4
          p.text-center
            span.r-4 Information Questions / Preguntas de información
          img.mb-4(src='@/assets/curso/temas/38.svg', alt='')
          .row.justify-content-center.mb-3
            .col-lg-6.mb-lg-0.mb-3: img(src='@/assets/curso/temas/39.svg', alt='')
            .col-lg-6
              p 
                span.text-gray ¿Yo <b>por qué</b> he estado <b>jugando</b> al tenis?
                  br
                  |¿Tú <b>dónde</b> has estado <b>escuchando</b> música?
                  br
                  |¿Él por <b>cuánto</b> tiempo ha estado <b>trabajando</b> aquí?
                  br
                  |¿Ella <b>cómo</b> ha estado <b>estudiando</b> para sus exámenes?
                  br
                  |¿(Eso) cuánto ha estado <b>comiendo</b>?
                  br
                  br
                  |¿Nosotros <b>qué</b> hemos estado <b>viendo</b> últimamente?
                  br
                  |¿Ustedes <b>dónde</b> han estado <b>escribiendo</b> sus ensayos?
                  br
                  |¿Ellos <b>por qué</b> han estado <b>haciendo</b> ejercicio?
          TarjetaAudio.color-primario.bg-white.mb-3(
            texto=""
            :audio="require('@/assets/audios/tema3/16.mp3')"
            )
    .bg-card
      .row.justify-content-center.px-4
        .col-lg-4.py-5
          img.m-auto.mb-4(src='@/assets/curso/temas/numero1.svg', alt='' style='width:50px')
          .contenedor-traductor
            .contenedor-traductor__eng
              p.fst-italic In the Spanish language, the structure of affirmative sentences and questions is generally the same, the only thing that changes is the intonation in which they are pronounced; but in English, sentence structure and word order does change and you should be very aware of it.
            .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp7}")
              p 
                span.r-5 En el idioma español, generalmente, la estructura de las oraciones afirmativas y las preguntas es la misma, lo único que cambia es la entonación con la que se pronuncian; pero en inglés, la estructura de la oración y el orden de las palabras sí cambia y se debe estar muy consciente de ello.

            a.boton-traduccion(@click='ocultarEsp7 = !ocultarEsp7') Ver traducción
        .col-lg-4: img(src='@/assets/curso/temas/40.png', alt='')
        .col-lg-4.py-5
          img.m-auto.mb-4(src='@/assets/curso/temas/numero2.svg', alt='' style='width:50px')
          .contenedor-traductor
            .contenedor-traductor__eng
              p.fst-italic Both “have not been” and its contraction “haven’t been” are correct, the same with “has not been” and its contraction “hasn’t been”. But keep in mind that for formal contexts it is not recommended to use contractions.
            .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp8}")
              p 
                span.r-5 Tanto #[i "have not been"] como su contracción #[i "haven't been"] son correctos, lo mismo con #[i "has not been"] y su contracción #[i "hasn't been".] Pero hay que tener en cuenta que para contextos formales no se recomienda usar contracciones.

            a.boton-traduccion(@click='ocultarEsp8 = !ocultarEsp8') Ver traducción
    .card.rounded-0(style='background-color: #a6bbff').p-5.mb-4
      .row.justify-content-center.mb-3
        .col-lg-8
          .d-flex 
            img.m-auto(src='@/assets/curso/temas/numero3.svg', alt='' style='width:50px')
            .contenedor-traductor
              .contenedor-traductor__eng
                p.fst-italic When we talk about interrogative sentences, we have closed questions (“yes” or “no” questions) and open questions (information questions).
              .contenedor-traductor__esp(:class="{ mostrar: ocultarEsp9}")
                p 
                  span.r-5 Cuando hablamos de oraciones interrogativas, tenemos preguntas cerradas (preguntas de "sí" o "no") y preguntas abiertas (preguntas informativas).

              a.boton-traduccion(@click='ocultarEsp9 = !ocultarEsp9') Ver traducción
    Dialogo.color-acento-contenido(:dialogo="dialogo")
      template(#nombre-actividad) Arrastrar y Soltar
      template(#titulo-actividad) Completa la conversación
      template(#descripcion-actividad)        
        
</template>

<script>
export default {
  name: 'Tema3',
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
          nombre: 'Oscar',
          img: require('@/assets/curso/temas/oscar.svg'),
        },
        {
          nombre: 'Manuel',
          img: require('@/assets/curso/temas/manuel.svg'),
        },
      ],
      dialogo: [
        {
          personaje: 'Oscar',
          textoIng: 'Manuel! It’s been a long time!',
          textoEsp: '',
          audio: require('@/assets/audios/a3/1.mp3'),
        },
        {
          personaje: 'Manuel',
          textoIng: 'Hi! Yes, I know! I *** abroad',
          textoEsp: '',
          audio: require('@/assets/audios/a3/2.mp3'),
          palabra: 'have been living',
        },
        {
          personaje: 'Oscar',
          textoIng: 'That’s amazing! I didn’t know that.',
          textoEsp: '',
          audio: require('@/assets/audios/a3/3.mp3'),
        },
        {
          personaje: 'Manuel',
          textoIng:
            'Sorry, I didn’t tell anyone because I wasn’t sure about that.',
          textoEsp: '',
          audio: require('@/assets/audios/a3/4.mp3'),
        },
        {
          personaje: 'Oscar',
          textoIng: 'And where ***?',
          textoEsp: '',
          audio: require('@/assets/audios/a3/5.mp3'),
          palabra: 'have you been living',
        },
        {
          personaje: 'Manuel',
          textoIng: '*** in England.',
          textoEsp: '',
          audio: require('@/assets/audios/a3/6.mp3'),
          palabra: 'I have been living',
        },
        {
          personaje: 'Oscar',
          textoIng: 'That’s amazing! *** about moving to Scotland.',
          textoEsp: '',
          audio: require('@/assets/audios/a3/7.mp3'),
          palabra: 'I have been thinking',
        },
        {
          personaje: 'Manuel',
          textoIng:
            'It is a great idea! Go ahead and do it! You won’t regret it.',
          textoEsp: '',
          audio: require('@/assets/audios/a3/8.mp3'),
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
</style>
