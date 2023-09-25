<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Introducción a la ciberseguridad
      
    .row.mb-5.bg-gradient
      .col-lg-7.order-2.order-xl-1.pe-xl-4(data-aos="fade-right")
        p.position-relative(style="z-index: 1;") La ciberseguridad, también conocida como seguridad informática o seguridad digital, es el área relacionada con la informática y telemática en la protección de la infraestructura computacional, ya sea una máquina o el parque computacional de una organización 
        p.position-relative(style="z-index: 1;") La ciberseguridad se emplea en todo tipo de empresas públicas y privadas siendo aplicada en proyectos como: #[em home office] o teletrabajo, videoconferencias; cuando se habla de ciberseguridad abarca muchas líneas o áreas una de ellas es la seguridad en aplicaciones web y parte de las generalidades que en Colombia están enmarcadas en el Conpes 3701 de 2011 desarrollado por los Ministerios de Interior y de Justicia, Relaciones Exteriores, Defensa Nacional, Tecnologías de la Información y las Comunicaciones, Departamento Administrativo de Seguridad, Departamento Nacional de Planeación-DJSG-DIFP-DIES-OI, Fiscalía General, y que busca impulsar lineamientos de política en ciberseguridad y ciberdefensa orientados a desarrollar una estrategia nacional que contrarreste el incremento de las amenazas informáticas que afectan significativamente; por lo que se crea el grupo de respuesta a emergencias cibernéticas de Colombia colCERT.
      .col-lg-5.col-10.order-1.order-xl-2.mb-4.mb-xl-0(data-aos="fade-left")
        img.position-relative.mx-auto(src="@/assets/curso/temas/tema1/img-1.png" style="z-index: 1;")

    .color-acento-contenido.py-3.px-5.mb-5.bg-cta2(style="margin-left: -3rem; margin-right: -3rem;" data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-auto.px-2(src="@/assets/curso/temas/tema1/interes.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0.text-white
              h3.mb-1 CONPES
              p.mb-0 Para una mayor apropiación del tema, se invita a conocer el documento de lineamientos de política para ciberseguridad y ciberdefensa del Conpes 3701 de 2011.
            .col-sm-auto
              a.boton.color-acento-botones.texto-negro.px-4(href="https://tic.bogota.gov.co/sites/default/files/marco-legal/CONPES%203701%20DE%202011.pdf" target="_blank")
                span Ir al enlace

    p.mb-4(data-aos="fade") Dentro de las figuras de ciberseguridad de una organización se encuentra al gerente o CEO, el departamento de Tecnología e Información (TI), el personal de seguridad informática o de la información y el departamento legal o jurídico, todos ellos desempeñan un rol importante en la actuación frente a un caso de un incidente informático o la protección de datos. 

    .row.align-items-center.mb-5
      .col-md-1.mb-4.mb-md-0(data-aos="fade-right")
        img(src="@/assets/curso/temas/tema1/img-2.svg" style="max-width: 85px")
      .col-md-11(data-aos="fade-left")
        p La seguridad en aplicaciones web se considera como una rama de la ciberseguridad donde la misma busca preservar la integridad, confidencialidad y disponibilidad de la información.
        p.mb-0 Hoy en día, las empresas que están a la vanguardia de la transformación digital y en plena cuarta Revolución Industrial deben blindarse y proteger sus aplicaciones web, pero sobre todo el activo más importante dentro de una organización: la información que ingresa día a día y se puede verse afectada por diversas técnicas de #[em hacking] y los ataques informáticos que en Colombia y el mundo van en gran aumento. 
    
    .titulo-sexto.color-acento-contenido.mb-0(data-aos="fade") 
      p.mb-0 #[b Figura 1.] Ciberseguridad
    .row.justify-content-center 
      .col-lg-6.col-md-10
        img.mb-5.d-none.d-md-block(src="@/assets/curso/temas/tema1/fig1.png" data-aos="fade-down" alt="La figura representa los elementos de la ciberseguridad, en la que se incluyen la gestión de vulnerabilidades, el hacking ético, la crítica ortográfica, la protección de datos, la seguridad en la nube y la seguridad en aplicaciones web.")

    p.mb-4(data-aos="fade") Es importante tener en cuenta que dentro de la ciberseguridad los principios de seguridad son la confidencialidad, integridad y disponibilidad.

    .row.align-items-end.border-t-r.bg-6.mb-5
      .col-lg-6.p-3.pt-5.p-xl-4(data-aos="fade-right")
        .tarjeta-avatar-b.mb-4
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/icon-1.svg' alt='')
          .d-flex.align-items-center.tarjeta.tarjeta--azul.tarj-t1
            .p-4.py-3
              p.mb-0 La confidencialidad previene la divulgación de datos personales delicados cumpliendo con la normatividad legal del <em>habeas data</em>.
        .tarjeta-avatar-b.mb-4
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/icon-2.svg' alt='')
          .d-flex.align-items-center.tarjeta.tarjeta--azul.tarj-t1
            .p-4.py-3
              p.mb-0 La integridad garantiza la seguridad del contenido. 
        .tarjeta-avatar-b
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema1/icon-3.svg' alt='')
          .d-flex.align-items-center.tarjeta.tarjeta--azul.tarj-t1
            .p-4.py-3
              p.mb-0 La disponibilidad mantiene los datos siempre disponibles para los usuarios autorizados en la organización. 
      .col-lg-6(data-aos="fade-left")
        img(src="@/assets/curso/temas/tema1/img-5.svg")
    

    p(data-aos="fade") Con lo anterior, se puede afirmar que la ciberseguridad son las técnicas de procedimiento y uso de herramientas que se implementan con el único objetivo de proteger y blindar la información que se genera en computadores, dispositivos móviles, herramientas API, servidores, redes, información en la nube y sistemas electrónicos. Si una organización cuenta con personal capacitado en el área de la ciberseguridad y herramientas, sabrá detectar a tiempo los riesgos informáticos y afrontar con facilidad una vulnerabilidad o ataque informático. 




</template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
