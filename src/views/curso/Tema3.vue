<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Título tema'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-5.tarjeta.p-4(data-aos="fade-left")
          p(data-aos="fade-left") La nómina es uno de los procesos administrativos más importantes dentro de una organización, porque no solo involucra el pago a los trabajadores, sino también la correcta aplicación de las leyes laborales y la gestión de diferentes aspectos como impuestos y beneficios sociales. 
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/1.png", data-aos="zoom-in")
      .col-lg-4.mb-3.mb-lg-0
        .bg-color-4.tarjeta.p-4(data-aos="fade-left")
          p(data-aos="fade-left") Su elaboración es necesaria para garantizar la transparencia y el cumplimiento de las obligaciones tanto de la empresa como de los empleados. En este sentido, la nómina no es solo un registro de salarios, sino un reflejo de las relaciones laborales y las normativas vigentes.
    
        
    #t_3_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.1] Generalidades de la nómina
    
    p.mb-4 La estructura de la nómina se compone principalmente de dos partes: los devengos y las deducciones, las cuales son claves para calcular el pago neto que recibe un trabajador:

    .row.align-items-start.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema3/2.png", alt="").mb-4.mb-lg-0
      .col-lg-8.mb-3.mb-lg-0.order-1
    
        AcordionA(tipo="b")
          .div(titulo="Devengos")
            p Los devengos son las sumas que se le pagan al trabajador por concepto de remuneración por su trabajo. Estos pueden incluir una variedad de conceptos como el salario básico, las horas extras, comisiones, participación en ventas, y cualquier otra remuneración relacionada directamente con los servicios prestados.
            p Dentro de los devengos, también encontramos conceptos no salariales como el auxilio de transporte, prestaciones sociales (como la prima de servicios, cesantías e intereses sobre las cesantías), y cualquier otro pago otorgado por el empleador que, por acuerdo entre las partes, no se considera parte del salario. 
            p Es importante distinguir entre aquellos devengos que constituyen salario y aquellos que no lo constituyen (esto fue explicado en la Unidad 1, si considera puede darle lectura nuevamente), debido a que esto tiene implicaciones en el cálculo de las cargas sociales y fiscales.
    
          .div(titulo="Deducciones")
            p Por otro lado, las deducciones son los montos que deben ser restados de los devengos del trabajador para cumplir con diversas obligaciones legales y acordadas. Las deducciones más comunes incluyen:
            ul.lista-ul--color
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-8
                p.mb-0 <b>Aportes a la seguridad social</b>. Según la legislación laboral, el trabajador debe realizar aportes a la seguridad social, los cuales se calculan sobre un porcentaje de su salario.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-8
                p.mb-0 <b>Descuentos por préstamos o libranza.</b> Estos son descuentos autorizados por el trabajador, generalmente para pagos de préstamos personales u otros compromisos adquiridos.
              li.mb-0.d-flex
                i.far.fa-arrow-alt-circle-right.bg-color-8
                p.mb-0 <b>Embargos.</b> En algunos casos, los trabajadores pueden tener embargos judiciales, que deben ser descontados de su salario, según las órdenes emitidas por los jueces competentes.
    
    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema3/3.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Estas deducciones aseguran el cumplimiento de las obligaciones del trabajador con la seguridad social y otros compromisos legales, y también para garantizar que la nómina se ajuste a las normativas del país.

    #t_3_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.2] Proceso de elaboración de nómina
    
    p.mb-4 La elaboración de la nómina es un proceso que debe llevarse a cabo con precisión y en cumplimiento con la legislación vigente. Este proceso incluye varios pasos, entre los que destacan:


    
    .bg-full-width.bg-fondo-slider.mb-5
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/4.png")
            .col-lg-7
              h5 Recolección de datos
              p Se recopilan los datos de todos los trabajadores, incluyendo las horas trabajadas, los conceptos de devengos (salario básico, horas extras, comisiones, etc.), así como las deducciones aplicables (seguridad social, préstamos, etc.).
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/5.png")
            .col-lg-7
              h5 Cálculo de devengos y deducciones
              p Con base en la información obtenida, se calculan los devengos y deducciones correspondientes a cada trabajador. Este paso debe ser meticuloso, dado que cualquier error puede tener consecuencias legales y financieras.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/6.png")
            .col-lg-7
              h5 Elaboración del recibo de pago
              p Una vez calculado el total a pagar, se procede a elaborar el recibo de pago, que debe detallar claramente todos los devengos, deducciones y el salario neto a recibir por el trabajador.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/7.png")
            .col-lg-7
              h5 Revisión y validación
              p El siguiente paso es revisar y validar la información antes de proceder al pago, asegurándose que se cumplan todas las normativas legales y políticas internas de la empresa.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/8.png")
            .col-lg-7
              h5 Pago
              p Finalmente, se realiza el pago a los empleados, de acuerdo con el monto neto que ha sido calculado.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.mb-3.mb-lg-0
              figure
                img(src="@/assets/curso/tema3/9.png")
            .col-lg-7
              h5 Archivado y reportes
              p Una vez realizada la nómina, se debe archivar adecuadamente la documentación para su posible consulta futura. Además, se generan los reportes correspondientes para las autoridades fiscales y de seguridad social, cumpliendo con las normativas nacionales.
    
    .bg-full-width.bg-color-9.mb-3
        .row.mb-5.justify-content-center
          .col-lg-8
            .bg-color-white.shadow-soft.py-4.px-lg-5.mb-5
              .row.justify-content-around.align-items-center
                .col-md-auto
                  img(src="@/assets/template/xls.svg", style="width: 90px;")
                .col
                  .row.justify-content-between.align-items-center
                    .col.mb-3.mb-sm-0
                      h3.mb-1 Plantilla novedades
                      p Lo invitamos a revisar la plantilla en Excel, la cual puede ser empleada para los ejercicios prácticos.
                    .col-sm-auto
                      a.boton.color-primario.texto-blanco(:href="obtenerLink('/downloads/prueba.pdf')" target="_blank")
                        span Descargar
                        i.fas.fa-arrow-right

    #t_3_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 3.3] Nómina electrónica en Colombia
    
    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema3/10.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") En Colombia, la nómina electrónica ha sido implementada como una medida para mejorar la transparencia y eficiencia en los pagos y en la gestión de las obligaciones laborales. La nómina electrónica consiste en el proceso de registro y pago de los salarios de los trabajadores de manera digital, utilizando sistemas automatizados para generar los recibos de pago y reportar las transacciones correspondientes a las autoridades competentes.
        .bg-color-1.p-4.mb-3(data-aos="fade-left")
          p.mb-0 La Ley 1273 del 2009 y la Resolución 007 del 2011, promovida por la Dirección de Impuestos y Aduanas Nacionales (DIAN), establece la obligatoriedad de la nómina electrónica en el país. Esta medida busca optimizar la recolección de datos y mejorar el control sobre los pagos de seguridad social y demás aportes.
        p.mb-5(data-aos="fade-left") Los principales beneficios de la nómina electrónica incluyen:


    .bg-full-width-2.bg-fondo-2
      .px-4.px-md-5.pb-md-3
        div.row.justify-content-center.align-items-stretch.mb-5
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/11.svg" alt="" style="width: 90px")
              h5.text-center Facilidad en la gestión
              p.mb-0.text-center La automatización de los procesos reduce los errores humanos y facilita la gestión administrativa de los pagos.
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/12.svg" alt="" style="width: 90px")
              h5.text-center Mayor transparencia
              p.mb-0.text-center Al ser un proceso digital, se disminuye la posibilidad de fraudes y se asegura que todas las transacciones sean verificables. 
        
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/13.svg" alt="" style="width: 90px")
              h5.text-center Cumplimiento de la Ley
              p.mb-0.text-center El uso de la nómina electrónica asegura que los empleadores cumplan con sus obligaciones fiscales y de seguridad social..
          div.col-lg-3.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema3/14.svg" alt="" style="width: 90px")
              h5.text-center Ahorro de tiempo y costos
              p.mb-0.text-center El proceso es más rápido y menos costoso, puesto que no requiere el manejo físico de documentos ni el uso de papelería.


    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.gerencie.com/nomina.html" target="_blank" rel="noopener noreferrer") Nómina 2025. (s/f). 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.minjusticia.gov.co/programas-co/LegalApp/Paginas/Que-se-puede-descontar-del-salario-de-un-trabajador.aspx" target="_blank" rel="noopener noreferrer") Ministerio de Justicia. (2025, enero 27). ¿Qué se puede descontar del salario de un trabajador? Ministerio de Justicia. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href=" https://youtu.be/QcHAqxyvJ8k?si=x7vvjA5G4LzICrc2" target="_blank" rel="noopener noreferrer") MaríaCanovirtual. (2021, 15 de enero). Liquidación de horas las extras y recargos. [Video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
export default {
  name: 'Tema3',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
