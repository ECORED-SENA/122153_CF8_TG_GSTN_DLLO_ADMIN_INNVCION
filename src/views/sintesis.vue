<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
            
    p El siguiente mapa integra los criterios y especificidades de los conocimientos expuestos en el presente componente formativo:

    .row.justify-content-center
        .col-lg-10.mb-5
          figure
            img(src="@/assets/curso/temas/sintesis.svg", alt="Generalidades de los eventos empresariales: Trazabilidad del servicio: se registra e identifica la ubicación y trayectoria del servicio, a través del ciclo de servicio. Evento: acontecimiento planeado y organizado que convoca y reúne una cantidad determinada de personas en un mismo lugar y al mismo tiempo. Tipos de eventos: sociales, familiares, deportivos, culturales, empresariales, entre otros. Evento empresarial: acción concreta alineada con actividades de la empresa convocante y su estrategia de marketing que reúne personas afines al sector en que opera o de sectores relacionados. Protocolos de organización: determinan cómo actuar según el tipo de evento, la entidad que lo ofrece y el mensaje que se quiere transmitir a las personas invitadas. Convocatoria: Acción de invitar a un grupo de personas a asistir a un acto o lugar. Comité de eventos: conjunto de personas encargadas de velar por la realización exitosa de un evento. Logística de eventos: permite ofrecer bienes y servicios adecuados, en el momento justo, en el lugar idóneo y en condiciones deseadas.")
    .row.justify-content-center
      .col-lg-3
        a.anexo.mb-4(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
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
