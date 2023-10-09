<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Identificación de riesgos

    p(data-aos="fade") Se invita a ampliar el conocimiento sobre los riesgos informáticos, a través del siguiente video:
    
    figure.mb-5(data-aos="fade-down")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/-5OkRKCWfyg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Riesgos informáticos

    p.mb-4(data-aos="fade") Dentro de los métodos de identificación de riesgos, la organización debe clasificar los tipos de riesgos en altos, medios y bajos; en este caso, en las aplicaciones web se revisan varios factores como, el lenguaje de programación y la arquitectura del <em>software</em> para poder empezar a analizar y trabajar sobre las posibles amenazas o vulnerabilidades. 

    .color-acento-contenido.py-3.px-5.mb-5.bg-cta2(style="margin-left: -3rem; margin-right: -3rem;" data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-auto.px-lg-2(src="@/assets/curso/temas/tema1/interes.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0.text-white
              h3.mb-1 Guía de gestión de riesgos MinTIC
              p.mb-0 Conozca la guía de gestión de riesgos del Ministerio de Tecnologías de la información y las comunicaciones (MinTIC) de Colombia.
            .col-sm-auto
              a.boton.color-acento-botones.texto-negro.px-4(href="https://www.mintic.gov.co/gestionti/615/articles-5482_G7_Gestion_Riesgos.pdf" target="_blank")
                span Ir al enlace

    p.mb-5(data-aos="fade") En el siguiente recurso se podrán conocer las técnicas de #[em hacking] utilizadas por los ciberdelincuentes:

    .col-lg-10.mx-auto.mb-5
      .titulo-sexto.color-acento-contenido.mb-0(data-aos="fade") 
        p.mb-0 #[b Figura 2.] Técnicas de #[em hacking] utilizadas por los ciberdelincuentes
      img.mb-4(src="@/assets/curso/temas/tema2/img-1.jpg" data-aos="fade-down" alt="La figura muestra las técnicas de hacking utilizadas por ciberdelincuentes. En primer lugar, se encuentran los vectores de ataque. En segundo lugar, las debilidades de seguridad; en tercer lugar, los controles de seguridad; en cuarto lugar, los impactos técnicos; y en quinto lugar, los impactos en el negocio.")
      p.px-4.py-3.bg-8.tarjeta(data-aos="fade-down") El pirata informático mediante vectores de ataque, utiliza técnicas de #[em hacking] e ingeniería social, revisa y analiza las debilidades de seguridad de la aplicación o sistema de información, revisa los controles de seguridad con que cuenta la herramienta o la infraestructura y los impactos, buscando el objetivo final: afectar el negocio de la organización.

    .color-acento-contenido.py-3.px-5.mb-5.bg-cta2(style="margin-left: -3rem; margin-right: -3rem;" data-aos="fade-down")
      .row.justify-content-around.align-items-center
        .col-3.col-sm-2.col-lg-1
          img.mx-auto.px-2(src="@/assets/curso/temas/tema1/interes.svg")
        .col
          .row.justify-content-between.align-items-center
            .col.mb-3.mb-sm-0.text-white
              h3.mb-1 Norma ISO 27005
              p.mb-0 La prevención de los riesgos se origina del análisis de las amenazas y vulnerabilidades que se detectan en la organización. La norma ISO 27005 contiene recomendaciones y normas que se deben llevar a cabo o tener en cuenta en los proyectos de aplicaciones web y que sirve de control ante futuras amenazas o riesgos informáticos.
            .col-sm-auto
              a.boton.color-acento-botones.texto-negro.px-4(href="https://gmas2.envigado.gov.co/gmas/downloadFile.public?repositorioArchivo=000000001071&ruta=/documentacion/0000001359/0000000107" target="_blank")
                span Ir al enlace

    .row.align-items-center.mb-5
      .col-lg-8.order-2.order-lg-1(data-aos="fade-right")
        p El comercio electrónico que en Colombia está reglamentado a través de la Ley 527 de 1999 ha sido uno de los factores que ha llevado a las empresas a tener un crecimiento económico, pues dentro de la transformación digital una de las líneas de medición es la venta por medio de canales digitales o aplicaciones web.
        p Pero también existen diferentes factores de ataques en los que está la suplantación que es muy común en este tipo de aplicaciones web donde un pirata informático podrá alterar el contenido de una <em>cookie</em> y redireccionarlo a un servidor diferente. 
      .col-lg-4.col-9.mb-4.mb-lg-0.order-1.order-lg-2(data-aos="fade-left")
        img(src="@/assets/curso/temas/tema2/img-2.svg")
    
    .d-flex.mb-5.bg-9.w-fit(data-aos="fade")
      h5.px-4.py-2.mb-0 Metodología o estándar para identificar riesgos en aplicaciones web
    
    .row.align-items-center.mb-5
      .col-lg-4.col-7.mb-4.mb-lg-0(data-aos="fade-right")
        img.mx-auto(src="@/assets/curso/temas/tema2/img-3.jpg")
      .col-lg-8(data-aos="fade-left")
        p Una metodología para identificar riesgos en aplicaciones web, podría ser a través de una matriz de riesgo de seguridad de la información, esta herramienta permite analizar o dar valor a los riesgos. 
        p.mb-4 La matriz de riesgos 3 X 3 permite clasificar y valorar las diferentes vulnerabilidades comunes según la metodología OWASP dentro de las aplicaciones de sitios web de la siguiente manera:
        .tarjeta.color-acento-contenido.px-3.py-2.bg-cta
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img.px-2.px-lg-4(src="@/assets/curso/temas/tema1/interes.svg")
            .col.col-lg-10
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0
                  p.mb-0 Matriz Riesgos
                .col-sm-auto
                  a.boton.color-acento-botones.texto-negro(:href="obtenerLink('downloads/matrizRiesgos_pdf.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    p.mb-5(data-aos="fade") Con la metodología <em>Open Web Application Security Project</em> (OWASP) se pueden aplicar técnicas de evaluación, tipos de controles frente a los riesgos, aplicar métodos de medición de controles y localizar vulnerabilidades.

    .titulo-sexto.color-acento-contenido.mb-0(data-aos="fade") 
      p.mb-0 #[b Figura 3.] Vulnerabilidades
    img.mb-4(src="@/assets/curso/temas/tema2/img-4.jpg" data-aos="fade-down" alt="En esta figura se pueden identificar las diferentes vulnerabilidades que se pueden presentar. Entre ellas están las redirecciones y reenvíos no válidos, las fallas en las restricciones de acceso a URL, el almacenamiento criptográfico inseguro, la configuración defectuosa de ciberseguridad, la falsificación de sitios cruzados, las referencias inseguras y directas a objetos, la pérdida de autenticación, la secuencia de comandos XSS y la inyección.")

    p.mb-5(data-aos="fade") Las diferentes acciones que se tomen ayudarían a jerarquizar el impacto, es importante que las aplicaciones en sitios web se corran en dominios aptos y seguros para la protección de la información de los usuarios.

    .d-flex.mb-5.bg-9.w-fit(data-aos="fade")
      h5.px-4.py-2.mb-0 Modelo OSI en la capa 7
    
    p.mb-4(data-aos="fade") El modelo OSI en la capa 7 nivel de aplicación, presenta los siguientes protocolos:

    .row.justify-content-center(data-aos="fade-down")
      .col-md-10.col-lg-6
        .titulo-sexto.color-acento-contenido.mb-0 
          p.mb-0 #[b Figura 4.] Protocolos capa aplicación
        img.mx-auto(src="@/assets/curso/temas/tema2/img-5.jpg" alt="En esta figura se pueden evidenciar los protocolos para la aplicación en la capa 7 del modelo OSI, que es el nivel de aplicación. Estos son: HTTP, POP3, IMAP, SMTP, FTP y DNS.")
  
    
    Separador

    .titulo-segundo.color-acento-contenido
      h2#t_2_1 2.1	Análisis de riesgos
    
    p.mb-4(data-aos="fade") En la identificación de riesgos se debe tener presente que:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-10.mx-auto
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5.mb-4(style="background-color: #FFF4D6 !important;")
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img-6.jpg')})`}")
          .bloque-texto-g__texto.p-4
            p.mb-0 
              span.fw-bold.bg-1 La inseguridad
              |  se enuncia en procesos de la composición de los resultados de un suceso y, 
              span.fw-bold.bg-1 la probabilidad de ocurrencia
              |  está asociada a las fuentes de riesgos, comportamiento humano (interno y externo), comercio, economía y mercado, circunstancias políticas, tecnología, eventos naturales y, finalmente, organizacionales.
        
        p.mb-0(data-aos="fade") Dentro de la gestión del riesgo de seguridad de la información se debe proteger la empresa ante las posibles consecuencias como pérdidas de confidencialidad, integridad, disponibilidad… también se tienen otras como no-repudio, autenticidad, o confiabilidad de los activos, el incumplimiento de la legislación, pérdidas financieras, impacto de orden público, impactos de orden internacional. 
    
    p.mb-5(data-aos="fade") A continuación, se invita a conocer el ciclo PHVA, según la #[em Guía de gestión de riesgos de seguridad de la información], presentada por el Icontec:

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-md-10.col-lg-7
        .titulo-sexto.color-acento-contenido.mb-0
          p.mb-0 #[b Figura 5.] Ciclo PHVA
        img.mx-auto(src="@/assets/curso/temas/tema2/img-7.svg" alt="La figura representa el ciclo PHVA. En primer lugar, tenemos Planificar, que incluye establecer el contexto, evaluar el riesgo, planificar el tratamiento y aceptar los riesgos. En segundo lugar, está Hacer, donde se implementa el plan de tratamiento de riesgos. En tercer lugar, tenemos Verificar, que consiste en monitorear y revisar continuamente los riesgos. Finalmente, en Actuar, se busca mantener y mejorar el proceso de gestión del riesgo.")
        figcaption.mt-3 Nota. Adaptado de Organización Internacional de Normalización. (2015).

    p(data-aos="fade") En las políticas lo primero será determinar el tratamiento que se le dará a cada uno de los riesgos identificados en la aplicación, donde se puede tomar la decisión de aceptarlos, transferirlos o ejercer controles apropiados según el nivel de riesgo. Posteriormente, habrá que determinar qué controles se pueden ejercer, una vez determinada la causa que los origina. 
    p.mb-4(data-aos="fade") De acuerdo con lo anterior, los controles pueden ser de tipo:

    .row.justify-content-center.mb-4(data-aos="fade-down")
      .col-md-6.col-lg-4.px-md-3.position-relative.mb-3.mb-lg-0
        .tarjeta-hover-color(data-aos="fade-right")
          .header-img.p-3.p-lg-5
            img.mx-auto(src="@/assets/curso/temas/tema2/img-8.svg" style="max-width: 105px;")
            h4(style="display: block; border-radius: 50px; background-color: white;") Controles preventivos
          .body-text.p-4
            p.mb-0 Estos se anticipan a los eventos no deseados antes de que sucedan. 
      .col-md-6.col-lg-4.px-md-3.mb-3.mb-lg-0
        .tarjeta-hover-color(data-aos="fade")
          .header-img.p-3.p-lg-5
            img.mx-auto(src="@/assets/curso/temas/tema2/img-9.svg" style="max-width: 105px;")
            h4(style="display: block; border-radius: 50px; background-color: white;") Controles detectivos
          .body-text.p-4
            p.mb-0 Permiten identificar eventos en el momento en el que se presentan. 
      .col-md-6.col-lg-4.px-md-3.mb-3.mb-lg-0
        .tarjeta-hover-color(data-aos="fade-left")
          .header-img.p-3.p-lg-5
            img.mx-auto(src="@/assets/curso/temas/tema2/img-10.svg" style="max-width: 105px;")
            h4(style="display: block; border-radius: 50px; background-color: white;") Controles correctivos
          .body-text.p-4
            p.mb-0 Se caracterizan por la toma de acciones para prevenir eventos no deseados.

    p(data-aos="fade") Los anteriores controles buscan mitigar los riesgos de mayor impacto y la posibilidad de ocurrencia. Luego, se buscará integrar estos controles a las políticas y procedimientos empresariales para configurar un sistema de control denominado 
      span.fw-bold.bg-1 sistema de gestión de seguridad de la información.


    Separador

    .titulo-segundo.color-acento-contenido
      h2#t_2_2 2.2	Herramientas de valoración de riesgos

    .d-flex.flex-wrap.mb-5
      .col-lg-4.col-8.mb-4.m-lg-auto(data-aos="fade-right")
        img.mx-auto(src="@/assets/curso/temas/tema2/img-11.jpg")
      .col-lg-8.ps-lg-4(data-aos="fade-left")
        p La valoración del riesgo asegura que para que el sistema logre los efectos previstos, con las mismas herramientas, se pueden prevenir o reducir efectos indeseados, logrando la mejora progresiva, integrando e implementando acciones en sus procesos.
        p Se puede encontrar también empresas en el mundo que ofrecen una gran cantidad de herramientas para la valoración del riesgo como:
        
        .row.align-items-center.justify-content-around.bg-10.py-2(data-aos="fade-down")
          .col-lg-3.col-4.mb-4.mb-lg-0
            img(src="@/assets/curso/temas/tema2/img-12.svg")
          .col-lg-7.mb-4.mb-lg-0
            ul.lista-ul--color.fa-ul.mb-0
              li
                i.fas.fa-check 
                h5.mb-0 SpiraPlan de Inflectra Corp.
              li
                i.fas.fa-check 
                h5.mb-0 Rastreados a 1.
              li
                i.fas.fa-check 
                h5.mb-0 IsoMetriz y otras.
    
    p.mb-4(data-aos="fade") Un informe de valoración de riesgos debe contener:

    .row.justify-content-center.align-items-stretch(data-aos="fade-down")
      .col-12.col-md-6.col-lg-4.px-md-3.d-flex.content-tj-hover
        .tarjeta-hover-up.p-4.p-lg-5(@mouseover="mostrarIndicador2 = false")
          .indicador--hover(v-if="mostrarIndicador2")
          img.mb-4(src="@/assets/curso/temas/tema2/img-13.svg" style="max-width: 82px;")
          p.mb-0 Todas las vulnerabilidades y amenazas detectadas.
      .col-12.col-md-6.col-lg-4.px-md-3.d-flex.content-tj-hover
        .tarjeta-hover-up.p-4.p-lg-5
          img.mb-4(src="@/assets/curso/temas/tema2/img-14.svg" style="max-width: 82px;")
          p.mb-0 La matriz de riesgo aplicada. 
      .col-12.col-md-6.col-lg-4.px-md-3.d-flex.content-tj-hover
        .tarjeta-hover-up.p-4.p-lg-5
          img.mb-4(src="@/assets/curso/temas/tema2/img-15.svg" style="max-width: 82px;")
          p.mb-0 La información con los métodos y técnicas utilizados.     






</template>

<script>
export default {
  name: 'Tema2',
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
