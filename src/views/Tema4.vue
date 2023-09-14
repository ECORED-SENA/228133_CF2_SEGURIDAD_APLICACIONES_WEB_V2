<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Informe o políticas de sistema de gestión de seguridad de la información o afines
      
    .row.align-items-center.mb-5.bg-t4
      .col-lg-6.order-2.order-lg-1.ms-auto.px-lg-4.py-4.align-items-center(data-aos="fade-right")
        p En la gestión de información, cuando se generan informes o documentos sobre los hallazgos y vulnerabilidades detectadas, estos deben contener un completo diligenciamiento con la compilación de datos recolectados por el técnico en seguridad de aplicaciones web. 
        p.mb-4 El informe de auditoría sirve para verificar los cumplimientos de planes, estrategias y programas, los informes son necesarios para el monitoreo y toma de decisiones; este debe contener los siguientes ítems como resultados:
        .tarjeta.color-acento-contenido.px-3.py-3.py-lg-2.bg-cta 
          .row.justify-content-around.align-items-center
            .col-3.col-lg-2
              img.px-lg-2.px-2(src="@/assets/curso/temas/tema1/interes.svg" alt="")
            .col-9.ps-lg-1
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Modelo informe de auditoría
                .col-sm-auto
                  a.boton.color-acento-botones.texto-negro.px-4(:href="obtenerLink('downloads/auditoria_PDF.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
      
      .col-lg-5.col-9.order-1.order-lg-2.mb-4.mb-lg-0.mx-auto(data-aos="fade-left")
        img.mx-auto(src="@/assets/curso/temas/tema4/img-1.svg")





</template>

<script>
export default {
  name: 'Tema4',
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
