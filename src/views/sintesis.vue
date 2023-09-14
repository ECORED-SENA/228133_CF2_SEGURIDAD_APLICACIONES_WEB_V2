<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    p.mb-5 En el siguiente recurso se podrá evidenciar un resumen de este componente formativo:

    .row.justify-content-center
      .col-lg-11.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="En esta imagen se representa el resumen del componente formativo, fundamentos y aplicaciones de riesgos de seguridad orientada a aplicaciones web a través de auditorías en aplicaciones web. Se pueden detectar diferentes riesgos. En las aplicaciones como las amenazan o las vulnerabilidades para generar un plan de mejora y finalmente, obtener un informe.")
      .col-auto
        a.anexo.mb-5(:href="obtenerLink('/downloads/sintesis.pdf')" target="_blank")
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
