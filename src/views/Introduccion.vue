<template lang="pug">
.curso-main-container.introduccion
  BannerInterno(subTitulo="Introducción")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5

    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/intro/1.png", data-aos="zoom-in")
      .col-lg-7
        .bg-color-1.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/intro/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 “Capacidad en la definición de la compensación salarial a los trabajadores, de acuerdo con el perfil, las responsabilidades, y las actividades realizadas”, es una unidad que permite determinar las bases para la respectiva remuneración del empleado, de acuerdo con sus horarios y actividades laborales. 
        p(data-aos="fade-left") En este contexto, esta unidad se enfoca en cómo definir y administrar la compensación salarial, teniendo en cuenta aspectos necesarios en el perfil de los empleados, sus responsabilidades y las actividades que desempeñan dentro de la empresa.
    
    .bg-full-width-2.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        .row.justify-content-center.align-items-stretch.mb-5
          .col-lg-4.mb-4(data-aos="zoom-in-up")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/intro/3.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Tema 1
                p.mb-0 Inicia con el estudio del balance de prueba y su relación con el ciclo contable, permitiendo comprender la administración de salarios desde una perspectiva contable y financiera.
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/intro/4.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Tema 2
                p.mb-0 Explora conceptos y principios que rigen la administración de salarios, así como los objetivos que se deben cumplir al establecer una compensación salarial adecuada.
          .col-lg-4.mb-4(data-aos="zoom-in-down")
            .custom-image-card-2.h-100
              img.custom-image-card__image(src="@/assets/curso/intro/5.png" alt="")
              .custom-image-card__text.p-4
                h5.mb-2.text-center Temas 3 y 4
                p.mb-0 Profundizan en el proceso de elaboración de la nómina, para tener precisión en la remuneración de los trabajadores, y las novedades que pueden surgir, como horas extras y recargos nocturnos.
    
    .bg-full-width-2.bg-h85
      .px-md-5.pb-md-3
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-9(data-aos="fade-left").mb-3.mb-lg-0
                p Gracias a la estructura de los temas interrelacionados se proporcionan los conocimientos necesarios para que los estudiantes logren un entendimiento profundo de estos procesos.
                p.mb-0 Es necesario la participación constante a través de actividades y lecturas, dado que esto les permitirá adquirir conocimientos teóricos, y ponerlos en práctica en situaciones reales. 
              .col-lg-3(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/intro/6.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .bg-full-width.bg-color-2
      div.text-center.p-4(data-aos="fade-left")
        h5.mb-0 ¡Con una participación comprometida se logrará cumplir con éxito los objetivos propuestos!

</template>
