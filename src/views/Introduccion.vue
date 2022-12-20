<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p En este componente formativo se recorrerá el tercer escenario del curso para profundizar sobre el enfoque diferencial e inclusivo del acompañamiento psicosocial del programa Mi familia. En el siguiente video se explica de manera genérica las temáticas a profundizar.

    figure
    .video.mb-5
      iframe(width="560" height="315" src="https://www.youtube.com/embed/U1rc8XF0UaU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    .bg_color1.p-4
      .row.align-items-center
        .col-lg-1.mb-4.mb-lg-0(data-aos="fade-right")
          img.img-t.m-auto(src='@/assets/curso/introduccion/img01.svg')
        .col-lg-10(data-aos="fade-left")
          p.m-0 <b>Objetivo:</b> identificar los elementos inclusivos y diferenciales del programa Mi familia para la atención a familias con niños, niñas y adolescentes u otros integrantes en situación de discapacidad.
    
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
