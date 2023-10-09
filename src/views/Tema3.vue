<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Auditoría infraestructura tecnológica

    .row.align-items-center.mb-5
      .col-lg-8.order-2.order-lg-1(data-aos="fade-right")
        p Las auditorías informáticas internas o externas siempre son recomendadas para prevenir pérdidas o fugas de información y económicas en todos los aspectos (sanciones, ventas, ingresos, clientes, entre otros) para la organización; por ello, en cualquier infraestructura tecnológica estas auditorías se deben realizar al #[em hardware] por los requerimientos técnicos de la aplicación, en este caso, y el #[em software] para el análisis de vulnerabilidades o actualizaciones a los componentes de este garantizando la seguridad y confianza en las aplicaciones web. 
        p Se deben tener en cuenta los aspectos técnicos de la aplicación; sin embargo, se han elegido cuatro tipos de auditorías en aplicaciones web, a saber:
      .col-lg-4.col-9.order-1.order-lg-2.mb-4.mb-lg-0(data-aos="fade-left")
        img.mx-auto(src="@/assets/curso/temas/tema3/img-1.jpg")

    .row.align-items-center.mb-5
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        .titulo-sexto.color-acento-contenido.mb-3(data-aos="fade") 
          p.mb-0 #[b Figura 6.] Tipos de auditorías en aplicaciones web
        img.mx-auto(src='@/assets/curso/temas/tema3/img-4.svg' alt="La figura representa los diferentes tipos de auditorías en aplicaciones web. Entre ellas se encuentran la auditoría SEO, la auditoría de seguridad, la auditoría de usabilidad y accesibilidad, y las auditorías de rendimiento.")
      .col-lg-8(data-aos="fade-left")
        TabsA.color-acento-contenido
          .tarjeta.bg-7.p-4(titulo="Auditoría SEO")
            h4 Auditoría SEO
            p.mb-0 En este tipo de auditoría se revisa el posicionamiento o la indexación que se analiza frente a la búsqueda, se estudian los enlaces, el contenido, <em>marketing</em> digital frente al posicionamiento en las redes sociales y el análisis de comparaciones con las posibles competencias.          
          .tarjeta.bg-7.p-4(titulo="Auditoría de seguridad")
            h4 Auditoría de seguridad
            p En este tipo de auditoría se revisa el estado del servidor, el sistema operativo y que los mismos se encuentren en buenas condiciones de <em>hardware</em> y con sus actualizaciones al día. Se analizan las posibles vulnerabilidades informáticas detectadas existentes y analizar que no se tengan fugas de información y se cumpla con la Ley de Protección de Datos.
          .tarjeta.bg-7.p-4(titulo="Auditoría de usabilidad y accesibilidad")
            h4 Auditoría de usabilidad y accesibilidad
            p Es una de las auditorías más complejas, ya que en la misma se ayuda a detectar el mal funcionamiento, la conectividad y tiempos de respuesta de la aplicación.
            p Además, se suelen utilizar herramientas de seguimiento que generan mapas de calor en conectividad y pruebas de <em>testing</em> desde varios dispositivos al tiempo. 
          .tarjeta.bg-7.p-4(titulo="Auditoría de rendimiento")
            h4 Auditoría de rendimiento
            p En esta auditoría se enfoca en analizar y estudiar la velocidad de conectividad de cargas en la aplicación web, se puede recomendar cambiar a mejores servidores donde se aloja el proyecto. 

    .row.align-items-center.mb-5
      .col-lg-8.order-2.order-lg-1(data-aos="fade-right")
        p Dentro de los métodos de administración más complejos están las auditorías forenses, ya que estas tienen el objetivo de recolectar toda la evidencia digital y pruebas que permitan comprobar si existen o no fraudes, o delitos en una empresa, conforme a los protocolos nacionales e internacionales para mantener la integridad de la misma y su posterior cadena de custodia de la información; desde el punto normativo en Colombia se deben cumplir con los requisitos de los artículos 5°, 6° y 7° de la Ley 527 de 1999.
        .tarjeta.color-acento-contenido.px-3.py-3.py-lg-2.bg-cta 
          .row.justify-content-around.align-items-center
            .col-3.col-lg-2
              img.px-lg-4.px-2(src="@/assets/curso/temas/tema1/interes.svg" alt="")
            .col-9.ps-lg-1
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  h5.mb-0 Ley 527 de 1999
                .col-sm-auto
                  a.boton.color-acento-botones.texto-negro.px-4(href="https://www.mindeporte.gov.co/recursos_user/2019/Juridica/Normograma/Leyes/Ley-527-de-1999.pdf" target="_blank")
                    span Ir al enlace
      .col-lg-4.mx-auto.mb-4.mb-lg-0.order-1.order-lg-2(data-aos="fade-left")
        img(src="@/assets/curso/temas/tema3/img-2.svg")
    
    
    .row.align-items-center
      .col-lg-3.col-9.mb-4.mb-lg-0(data-aos="fade-right")
        img.mx-auto(src="@/assets/curso/temas/tema3/img-3.svg")
      .col-lg-9.ps-lg-4(data-aos="fade-left")
        p Dentro de la distribución de dominios en la auditoría informática está la planeación y organización donde es establece el cronograma y las diferentes estrategias de análisis o métodos para usar en la misma, seguidamente está la adquisición e implementación como establecer los diferentes correctivos y dar soluciones a los inconvenientes encontrados en la misma, además, se recomienda el servicio y soporte frente a los controles de aplicación sin dejar a un lado el monitoreo con el que toda organización debe evaluar frecuentemente la calidad, integridad y confidencialidad. 
        p En cada auditoría se deben cumplir con los protocolos de seguridad informática, ya que hay que ceñirse a las reglas o normas donde se garantiza la confidencialidad, integridad y disponibilidad de toda la información.






</template>

<script>
export default {
  name: 'Tema3',
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
