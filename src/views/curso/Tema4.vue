<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'4. Novedades de nómina'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema4/1.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Dentro de la gestión de la nómina, es importante considerar las novedades de nómina, que incluyen diferentes situaciones o eventos que afectan el salario de los trabajadores, como las horas extras, recargos, licencias, entre otros. 
    
        .bg-color-1.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema4/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Estas novedades no solo están relacionadas con el tiempo trabajado, sino también con el cumplimiento de derechos laborales que deben ser remunerados o compensados, de acuerdo con las leyes vigentes. La correcta gestión y registro de estas novedades es esencial para garantizar que tanto los empleados como los empleadores cumplan con las normativas laborales, evitando conflictos legales y asegurando una correcta compensación de los trabajadores.
        p(data-aos="fade-left") Las novedades de nómina deben tener un tratamiento adecuado para que las empresas cumplan con sus responsabilidades laborales y proporcionen un ambiente justo y equilibrado para sus empleados. 

    .bg-full-width.bg-color-3
      div.p-4(data-aos="fade-left")
        p.mb-0 A lo largo de este tema, se explicarán algunas de las principales novedades que pueden ocurrir dentro de la nómina <b>algunas ya fueron explicadas en la Unidad 1</b>, tales como vacaciones y cesantías, para revisar dar completitud es necesario que revise de nuevo esta primera unidad. 
    
    .bg-full-width.bg-color-2.mb-lg-5
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-8.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Novedades de nómina
            p.mb-4(data-aos="fade-right") La gestión de la nómina es un proceso fundamental en la administración de personal, ya que garantiza el cumplimiento de las obligaciones laborales y la correcta remuneración de los trabajadores. En el PDF <b>Novedades de nómina</b>, se presentan los principales aspectos que pueden impactar el cálculo salarial, incluyendo el pago de horas extras, recargos nocturnos, compensación por trabajo en días festivos y dominicales, así como licencias e incapacidades. Además, se abordan las implicaciones legales y los procedimientos necesarios para asegurar la equidad y transparencia en la administración de los salarios.
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Novedades de nómina.
    
          .col-lg-4
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema4/3.png', alt='')
    
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


    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.gerencie.com/nomina.html" target="_blank" rel="noopener noreferrer") Novedades de nómina (2025). 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.mintrabajo.gov.co/web/guest/inicio" target="_blank" rel="noopener noreferrer") Ministerio de Trabajo. (2025, enero 27). Mi calculadora laboral. Ministerio de Trabajo

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/8isFu39G98k?si=lL38WrroAGWWMR9m" target="_blank" rel="noopener noreferrer") CYM Asesorías y Servicios Integrales. (2022, 29 de abril). Quien paga las incapacidades laborales del trabajador? [Video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema4',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              'El balance general es un estado financiero que solo se utiliza para calcular el monto de los salarios de los trabajadores.',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Verdadero',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Falso ',
                esCorrecta: true,
              },
            ],
            mensaje_correcto:
              'El balance general refleja la situación económica y financiera de una empresa, mostrando sus activos, pasivos y patrimonio. No está destinado exclusivamente a la elaboración de salarios.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              'El ciclo contable tiene como objetivo principal la organización, registro y análisis de todas las transacciones financieras de una empresa para determinar su rentabilidad.',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Verdadero ',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Falso',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              'El ciclo contable cubre el proceso completo de registrar las transacciones financieras, desde su inicio hasta la elaboración de los estados financieros, lo que incluye la determinación de rentabilidad.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              'La administración de salarios tiene como fin establecer una compensación equitativa entre los empleados, tomando en cuenta sus responsabilidades y el valor del puesto en el mercado.',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Verdadero ',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Falso',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              'La administración de salarios busca garantizar una compensación justa y competitiva, tomando en cuenta factores como el valor del puesto, las responsabilidades y la situación del mercado laboral.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              'En un reporte de nómina, las deducciones como los aportes a la seguridad social se suman a los devengos, para obtener el salario neto del trabajador.',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Verdadero',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Falso ',
                esCorrecta: true,
              },
            ],
            mensaje_correcto:
              'Las deducciones se restan de los devengos para calcular el salario neto del trabajador. No se suman a los devengos.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              'Las licencias por calamidad doméstica son remuneradas, pero solo si el trabajador presenta los documentos que certifiquen la situación.',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Verdadero',
                esCorrecta: true,
              },
              {
                id: 'b',
                texto: 'Falso',
                esCorrecta: false,
              },
            ],
            mensaje_correcto:
              'Según la normativa, las licencias por calamidad doméstica pueden ser remuneradas, siempre y cuando el trabajador entregue los soportes que demuestren la situación que causó la ausencia.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
