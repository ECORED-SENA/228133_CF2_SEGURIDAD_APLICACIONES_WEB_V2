<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Organización y protocolos de seguridad y privacidad

      
    .row.justify-content-center.mb-5(data-aos="fade-down") 
      .col-lg-10
        .bloque-texto-g.p-3.p-sm-4.p-md-5.bg-2
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema5/img-1.jpg')})`}")
          .bloque-texto-g__texto.p-4
            p.mb-0 Gracias a internet el mundo vive interconectado; así, el protocolo TCP/IP se encarga de que cada ordenador, dispositivo móvil y servicio web disponible a través de internet cuente con una dirección IP exclusiva como 92.183.215.3. Así, el sistema DNS “indica”, con ayuda del servidor de nombres, esta dirección en un dominio como, por ejemplo, www.example.org, que al ojo humano le resulta más sencillo de leer. Este proceso también se denomina resolución de nombres.
    
    p.mb-4(data-aos="fade") A continuación, se podrán conocer algunos de estos protocolos de seguridad y privacidad: 

    .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade") 
      p.mb-0 #[b Tabla 1.] Dominios
    .tabla-a.color-acento-contenido.mb-5(data-aos="fade-down") 
      table
        thead
          tr.bg-3
            th Protocolo
            th Subdominio
            th Nombre del dominio
            th Extensión
            th Descripción
        tbody
          tr.text-center.bg-4
            td https://
            td www
            td example
            td org
            td.text-start Organización sin ánimo de lucro.
          tr.text-center
            td https://
            td www
            td example
            td co
            td.text-start Dirección de dominio Colombia.
          tr.text-center.bg-4
            td https://
            td www
            td example
            td blog
            td.text-start Dirección de blog.
          tr.text-center
            td https://
            td example
            td co
            td uk
            td.text-start Dominio de tercer o cuarto nivel.
          tr.text-center.bg-4
            td https://
            td en
            td example
            td org
            td.text-start Dirección para proyecto web.

    p.mb-4(data-aos="fade") Así como la tabla de los dominios, se deben tener en cuenta los protocolos de aplicaciones oficiales de internet que se pueden usar.

    .d-flex.flex-wrap.align-items-center
      .col-12.col-lg-6.px-3(data-aos="fade-right")
        .d-flex.align-items-center.mb-3.w-100.bg-5
          img(src="@/assets/curso/temas/tema5/img-2.svg" style="max-width: 190px")
          .p-3.mb-0
            h5 #[em Domain Name Protocol]
            p.mb-0 (Protocolo de nombres de dominio).
        .d-flex.align-items-center.mb-3.w-100.bg-5
          img(src="@/assets/curso/temas/tema5/img-3.svg" style="max-width: 190px")
          .p-3.mb-0 
            h5 #[em Exterior Gateway Protocol]
            p.mb-0 (Protocolo de pasarela exterior).
      .col-12.col-lg-6.px-3(data-aos="fade-left")
        .d-flex.align-items-center.mb-3.w-100.bg-5
          img(src="@/assets/curso/temas/tema5/img-4.svg" style="max-width: 190px")
          .p-3.mb-0 
            h5 #[em File Transfer Protocol]
            p.mb-0 (Protocolo de transferencia de archivos).
        .d-flex.align-items-center.mb-3.w-100.bg-5
          img(src="@/assets/curso/temas/tema5/img-5.svg" style="max-width: 190px")
          .p-3.mb-0 
            h5 #[em Name/Finger Protocol]
            p.mb-0 (Protocolo de nombres/finger).
        .d-flex.align-items-center.mb-3.w-100.bg-5
          img(src="@/assets/curso/temas/tema5/img-6.svg" style="max-width: 190px")
          .p-3.mb-0 
            h5 #[em Telnet Protocol]
            p.mb-0 (Protocolo Telnet).



</template>

<script>
export default {
  name: 'Tema5',
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
