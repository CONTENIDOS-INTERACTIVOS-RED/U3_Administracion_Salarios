<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Administración de salarios'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        p(data-aos="fade-left") La administración de salarios es un área fundamental dentro de la gestión de recursos humanos, que abarca una serie de normas y procedimientos para establecer y mantener una estructura salarial justa y equitativa en la organización. 
        p.mb-5(data-aos="fade-left") Se enfoca en la remuneración de los trabajadores en función de sus funciones, responsabilidades, el mercado laboral y las políticas internas. Dado que las organizaciones están compuestas por puestos de diferentes niveles jerárquicos y sectores de actividad, la administración de salarios involucra a toda la estructura de la empresa y tiene un impacto directo en todos sus niveles y funciones. 
    
        .bg-color-5.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 La justicia salarial no solo responde a las necesidades del trabajador, sino también a la viabilidad económica de la empresa, buscando siempre un equilibrio entre ambos elementos (Ramírez & Tejada Betancourt, 2019).

    #t_2_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.1] Historia y evolución de la administración de salarios
    
    .row.mb-5
      .col-lg-5
        figure
          img(src="@/assets/curso/tema2/3.png", data-aos="zoom-in")
      .col-lg-7.mb-3.mb-lg-0
        p(data-aos="fade-left") La historia de la administración de salarios está marcada por el constante cambio de las necesidades y estructuras de las organizaciones. En sus inicios, los sistemas salariales eran rudimentarios, basados únicamente en la negociación individual entre empleador y empleado. 
        p.mb-5(data-aos="fade-left") A medida que las empresas crecían y se diversificaban, se hizo necesario establecer criterios objetivos para la remuneración, impulsando la creación de políticas salariales estructuradas.
    
    .bg-full-width-2.bg-color-1
      .px-md-5.pb-md-3
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
                p En el siglo XX, con la Revolución Industrial y la expansión de las grandes corporaciones, las organizaciones comenzaron a establecer jerarquías salariales basadas en el valor de los puestos, la competencia en el mercado y las condiciones económicas. 
                p.mb-0 Desde mediados del siglo XX, la preocupación por la equidad salarial, los sindicatos y la regulación gubernamental marcaron una transformación clave, orientada a garantizar salarios justos para los trabajadores y a reducir las brechas salariales. 
              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema2/4.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .bg-full-width.bg-color-7.mb-5
      .px-4.px-md-5.py-4
        p.mb-0 Hoy en día, la administración de salarios se maneja mediante metodologías modernas que buscan establecer estructuras salariales claras, transparentes y competitivas, basadas en la evaluación de puestos, la comparación con el mercado y el establecimiento de sistemas de incentivos, bonos y prestaciones adicionales (Ramírez & Tejada Betancourt, 2019).

    #t_2_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.2] Conceptos básicos de la administración de salarios
    
    p.mb-4 La administración de salarios implica no solo determinar el salario base de los empleados, sino también gestionar las diferentes formas de compensación, como los beneficios adicionales, bonos y premios. Algunos conceptos claves incluyen:

    TabsC.color-acento-contenido.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Valoración de puestos" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Valoración de puestos
            p Proceso que establece la importancia relativa de cada puesto dentro de la organización. Esta valoración se realiza a través de metodologías como el análisis de las competencias y responsabilidades de cada puesto en comparación con otros dentro de la organización.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/5.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Equidad interna" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Equidad interna
            p Hace referencia a la igualdad de remuneración entre empleados que ocupan puestos de similar valor y responsabilidad dentro de la organización.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/6.png', alt='')
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Equidad externa" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Equidad externa
            p Relacionado con la competitividad de los salarios en el mercado. Las empresas comparan sus salarios con los ofrecidos por otras organizaciones para atraer y retener talento.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/7.png', alt='')
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Estructura salarial" :icon="require('@/assets/bullets/2.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Estructura salarial
            p Sistema organizado y jerarquizado que define las escalas salariales, según los diferentes niveles y tipos de puestos dentro de la empresa.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema2/8.png', alt='')


    #t_2_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.3] Objetivo de la administración de salarios
    
    p El principal objetivo de la administración de salarios es asegurar que los empleados reciban una compensación adecuada, justa y competitiva, teniendo en cuenta tanto el mercado como el desempeño individual. Además, busca motivar a los trabajadores a través de un sistema de recompensas que les incentive a mejorar su rendimiento y alcanzar los objetivos organizacionales. 
    p.mb-4 Los objetivos de la administración de salarios, incluyen:

    .row.justify-content-center.align-items-stretch.mb-4
      .col-lg-6
        .bg-color-4.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Garantizar la competitividad salarial
              p.mb-0 Asegurar que los salarios de la empresa estén alineados con el mercado para atraer y retener talento.

      .col-lg-6
        .bg-color-4.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Mantener la equidad interna
              p.mb-0 Evitar disparidades salariales injustificadas entre empleados con roles similares.

    .row.justify-content-center.align-items-stretch.mb-5
      .col-lg-6
        .bg-color-4.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Fomentar el desempeño
              p.mb-0 A través de incrementos salariales y bonificaciones por logros específicos.
      .col-lg-6
        .bg-color-4.p-4(data-aos="fade-left").h-100
          .row.align-items-center
            .col-lg-auto
              img(src="@/assets/curso/tema2/9.svg", style="max-width: 90px").mx-auto
            .col-lg
              h5.mb-2 Cumplimiento legal
              p.mb-0 Asegurar que la empresa cumpla con las normativas salariales y laborales vigentes en su jurisdicción.


    #t_2_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 2.4] Factores que pueden influir en la administración de salarios
    
    p La administración de salarios no depende únicamente de los criterios internos de la empresa, sino que está influenciada por diversos factores externos e internos que pueden variar de un mercado a otro. 
    p.mb-4 Entre los factores más relevantes se incluyen:

    .bg-full-width.bg-fondo-slider
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/10.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Condiciones del mercado laboral
              p La oferta y demanda de talento en un sector o región específica impactan directamente en los salarios que una empresa debe ofrecer para atraer y retener empleados calificados.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/11.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Legislación laboral
              p Las leyes y regulaciones sobre salarios mínimos, beneficios laborales, seguridad social, entre otros, establecen un marco legal que las empresas deben cumplir.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/12.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Cultura organizacional
              p La política interna de la empresa también influye en la administración de salarios. Algunas empresas optan por ofrecer salarios más altos a cambio de un entorno de trabajo más flexible, mientras que otras priorizan un salario estable en función de la experiencia y desempeño.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema2/13.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Rendimiento individual y colectivo
              p El desempeño de los empleados, tanto individual como en equipo, es un factor clave en la determinación de incrementos salariales y otros beneficios.
         

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.gov.co/ " target="_blank" rel="noopener noreferrer") De trabajo, M. (2020). Derechos de los trabajadores domésticos: Ministerio de Trabajo. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://actualicese.com/ " target="_blank" rel="noopener noreferrer") Actualícese. (2025, Febrero 5). ABC de la nómina. Actualícese.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href=" https://youtu.be/08ZbnME1gQw?si=-ZGxO5fPEB4Q1aDo" target="_blank" rel="noopener noreferrer") CYM Asesorías y servicios integrales. (2024, 1 de marzo). Aportes a la seguridad social en Colombia. [Video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
