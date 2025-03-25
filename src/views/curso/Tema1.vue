<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Balance de prueba y ciclo contable'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    p.mb-4 El ciclo contable es un proceso sistemático que abarca una serie de etapas diseñadas para registrar, clasificar, y preparar la información financiera de una empresa. 

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-4.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Este ciclo comienza con la recopilación de datos sobre las transacciones económicas de la organización y culmina con la preparación de los estados financieros, que reflejan la situación económica y financiera de la entidad. 
        p(data-aos="fade-left") El ciclo contable es esencial para garantizar que las transacciones se registren de manera precisa, y que la información presentada sea fiable para la toma de decisiones tanto internas como externas a la organización.
        p(data-aos="fade-left") Dentro de este ciclo, uno de los pasos iniciales es la elaboración del <b>balance de prueba</b>, un documento que permite verificar que los débitos y créditos registrados en los libros contables estén equilibrados antes de pasar a la fase de ajustes y la preparación de los estados financieros. 

    #t_1_1.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.1] El balance de prueba, definición y objetivos


    p.mb-4 El balance de prueba se construye con base en los saldos de las cuentas del libro mayor y tiene como principal objetivo asegurar que los registros contables sean correctos y completos.


    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema1/3.png", data-aos="zoom-in")
      .col-lg-8.mb-3.mb-lg-0.order-1
        .bg-color-5.p-4.mb-3(data-aos="fade-left")
          p.mb-0 De acuerdo con Vargas Moreno (2020), el balance de prueba es una herramienta fundamental dentro del ciclo contable, dado que permite identificar posibles errores en los registros antes que estos afecten los estados financieros finales.
        p(data-aos="fade-left") Su función es la de garantizar que todos los registros contables sean exactos y que, si se presentan diferencias entre los débitos y créditos, se pueda corregir el problema antes que las cifras se reflejen en los informes financieros.
        p(data-aos="fade-left") La interrelación entre el balance de prueba y el ciclo contable es fundamental, puesto que el balance de prueba actúa como una "revisión de calidad" del trabajo realizado en las etapas previas del ciclo contable. 
    
    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5.py-4
        .row.align-items-center
          .col-lg-auto
            img(src="@/assets/curso/tema1/4.svg", style="max-width: 90px").mx-auto
          .col-lg
            p.mb-0 Solo cuando el balance de prueba está equilibrado, es posible pasar a la siguiente fase del ciclo contable: los ajustes y la preparación de los estados financieros, como el estado de resultados y el balance general. 
    
    h2(data-aos="fade-left") Objetivos 
    p.mb-5 El balance de prueba, tiene varios objetivos los cuales se podrían identificar así:

    .bg-full-width-2.bg-fondo-1
      .px-4.px-md-5.pb-md-3
        div.row.justify-content-center.align-items-stretch.mb-5
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema1/5.svg" alt="" style="width: 90px")
              p.mb-0.text-center Verificar la exactitud de los registros contables, asegurando que no haya errores de transcripción o de cálculo. 
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema1/6.svg" alt="" style="width: 90px")
              p.mb-0.text-center Facilitar los ajustes en las cuentas antes de elaborar los estados financieros, permitiendo corregir posibles errores antes que la información final se presente a los interesados. 
        
          div.col-lg-4.mb-4(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema1/7.svg" alt="" style="width: 90px")
              p.mb-0.text-center Identificar errores de clasificación, como transacciones que se han registrado en cuentas incorrectas, lo que es fundamental para la fiabilidad de los estados financieros.

        p Además, el balance de prueba cumple una función preventiva en la detección de fraudes. Al comparar los saldos de las cuentas, es posible identificar irregularidades que podrían sugerir manipulaciones o errores en el registro de las transacciones, lo que permite tomar medidas correctivas antes que la información sea utilizada por los auditores o para la toma de decisiones.

    #t_1_2.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.2] Estructura y proceso de elaboración

    .row.mb-5
      .col-lg-5.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/8.png", data-aos="zoom-in")
      .col-lg-7
        .bg-color-1.p-4.mb-3(data-aos="fade-left")
          p.mb-0 La estructura del balance de prueba debe ser clara y organizada, de modo que permita a los contadores y auditores verificar fácilmente si los registros contables están equilibrados. Como se mencionó anteriormente, el balance de prueba tiene dos columnas principales: Débitos y Créditos.
        p(data-aos="fade-left") Dentro de estas columnas, es fundamental que las cuentas estén ordenadas, según su naturaleza y clasificación contable. La organización correcta de las cuentas sigue el mismo orden que el libro mayor, y comúnmente se agrupan en categorías como:
    
    .bg-full-width.bg-fondo-slider
      .p-4.p-md-5
        SlyderA(tipo="b").bg-white
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/9.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Activos
              p Cuentas que representan los bienes y derechos de la empresa, como caja, bancos, cuentas por cobrar, inventarios, etc. Las cuentas de activos normalmente tienen saldos de débito.
    
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/10.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Pasivos
              p Cuentas que representan las deudas u obligaciones de la empresa, como cuentas por pagar, préstamos, impuestos por pagar, entre otros. Estas cuentas generalmente tienen saldos de crédito.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/11.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Patrimonio o Capital
              p Representa el valor residual de los activos después de deducir los pasivos. Incluye capital social, utilidades retenidas, etc. Estas cuentas suelen tener saldos de crédito.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/12.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Ingresos
              p Son las cuentas que reflejan los recursos obtenidos por la empresa, como ventas y otros ingresos operativos. Estas cuentas tienen saldos de crédito.
          .row.align-items-center.p-4.p-md-5
            .col-lg-5.order-2
              figure
                img(src="@/assets/curso/tema1/13.png")
            .col-lg-7.order-1.mb-3.mb-lg-0
              h5 Gastos
              p Reflejan los costos asociados con la operación de la empresa, tales como sueldos, alquiler, suministros, entre otros. Las cuentas de gastos generalmente tienen saldos de débito.
    
    .bg-full-width-2.bg-h85-2
      .px-md-5.pb-md-3
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-10(data-aos="fade-left").mb-3.mb-lg-0.order-2
                p Este orden permite a los responsables del registro de la contabilidad a visualizar de los saldos de cada grupo contable y asegurar que las sumas de débitos y créditos sean correctas al final del proceso.

                p.mb-0 La estructura del balance de prueba, bien organizada, asegura la transparencia y fiabilidad de la información financiera.
              .col-lg-2(data-aos="zoom-in").order-1
                img.img-fluid(src='@/assets/curso/tema1/14.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0


    h2(data-aos="fade-left") Proceso de elaboración del balance de prueba
    p El proceso de elaboración del balance de prueba consta de varias etapas que deben seguirse de manera ordenada para asegurar su exactitud y efectividad. 
    p.mb-5 El proceso de elaboración paso a paso, es:

    .row.align-items-center.mb-5
      .col-lg-5.order-1.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/15.png", alt="", data-aos="zoom-in").mb-4.mb-lg-0
      .col-lg-7.order-2.order-lg-1
        LineaTiempoD.color-primario.large(data-aos="fade-left")
          p(numero="1" titulo="Revisión de los libros contables") El primer paso es revisar todos los registros contables de la empresa. Esto incluye asegurar que todas las transacciones se hayan registrado correctamente en el libro diario y que cada transacción haya sido correctamente transferida al libro mayor. La precisión en este paso garantiza que el balance de prueba sea exacto.
          p(numero="2" titulo="Cálculo de los saldos finales") Después de corroborar  que todas las transacciones han sido transferidas al libro mayor, se procede a calcular el saldo de cada cuenta. Para ello, se suman todos los débitos y créditos registrados en cada cuenta. El saldo final de cada cuenta se calcula tomando en cuenta los saldos iniciales y los movimientos registrados durante el periodo. 
          p(numero="3" titulo="Preparación del balance de prueba") Con los saldos de las cuentas ya determinados, se procede a la elaboración del balance de prueba. En este paso, las cuentas se agrupan en las categorías correspondientes y se colocan en las columnas de débitos y créditos. Cada cuenta se coloca en su columna respectiva, dependiendo de si tiene un saldo de débito o de crédito.
          p(numero="4" titulo="Verificación de la igualdad entre débitos y créditos") El siguiente paso es verificar que la suma total de los débitos sea igual a la suma total de los créditos. Esta igualdad es un indicador de que l os registros contables están equilibrados. Si los totales no coinciden, es necesario revisar todas las transacciones registradas, la transferencia al libro mayor y el cálculo de los saldos para encontrar y corregir el error.
          p(numero="5" titulo="Corrección de errores") Si se detecta que los débitos y créditos no están equilibrados, se procede a una revisión detallada. Esto puede implicar la verificación de los registros en los libros contables, la revisión de los cálculos de saldos o la identificación de transacciones mal clasificadas. Cualquier error debe corregirse antes de continuar con el ciclo contable. 
          p(numero="6" titulo="Finalización y ajustes") Una vez que el balance de prueba esté equilibrado, se pueden realizar los ajustes necesarios a las cuentas para reflejar con precisión la situación financiera de la empresa. Estos ajustes pueden incluir la corrección de estimaciones, la actualización de registros de ingresos y gastos, entre otros. Los ajustes se reflejan en el balance de prueba y permiten preparar la información para la elaboración de los estados financieros.
    
    .titulo-figura.mb-4
      h5 Tabla 1.
      span Ejemplo balance de prueba
    
    div.bg-color-3.p-4
      h5.mb-0.text-center Balance de prueba – Empresa XYZ – Nit 1234-4
    .tabla-a.color-acento-botones
      table
        thead
          tr
            th.bg-color-6.text-center(rowspan="2") Código
            th.bg-color-6.text-center(rowspan="2")  Cuenta
            th.bg-color-6.text-center(colspan="2")  Sumas
            th.bg-color-6.text-center(colspan="2")  Saldos
          tr
            th.bg-color-6.text-center Debe
            th.bg-color-6.text-center Haber
            th.bg-color-6.text-center Deudor
            th.bg-color-6.text-center Acreedor
        tbody
          tr.text-center
            td.text-bold 1105
            td Caja
            td 100.000
            td 
            td 100.000
            td 
          tr.text-center
            td.text-bold 1405
            td Inventarios
            td 300.000
            td 
            td 300.000
            td 
          tr.text-center
            td.text-bold 1512
            td Equipo de oficina
            td 1.000.000
            td 
            td 1.000.000
            td 
          tr.text-center
            td.text-bold 2105
            td Bancos
            td 
            td 1.000.000
            td 
            td 1.000.000
          tr.text-center
            td.text-bold 3105
            td Capital social
            td 
            td 400.000
            td 
            td 400.000
          tr
            td.text-bold.text-end(colspan="2") Totales
            td.text-center 1.400.000
            td.text-center 1.400.000
            td.text-center 1.400.000
            td.text-center 1.400.000
        
    
    div.bg-color-1.p-4.mb-5
      .row.align-items-center
        .col-lg-auto
          img(src="@/assets/curso/tema1/16.svg", style="max-width: 90px").mx-auto
        .col-lg
          p.mb-0 Este proceso asegura que la información contable sea confiable, clara y precisa. Un balance de prueba bien elaborado es un indicativo que el ciclo contable se ha seguido correctamente, lo que facilita la preparación de los estados financieros y la toma de decisiones empresariales (Vargas Moreno, 2020).


    #t_1_3.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.3] Ciclo contable y sus etapas

    p.mb-4 El ciclo contable, al ser un proceso secuencial, depende de la precisión de cada uno de sus pasos, y el balance de prueba juega un papel crucial al garantizar la calidad y la integridad de la información contable, útil para la toma de decisiones empresariales y la presentación ante las autoridades fiscales.

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/17.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-5.p-4.mb-3(data-aos="fade-left")
          p.mb-0 El ciclo contable se define como el proceso secuencial que sigue una empresa para registrar todas las transacciones financieras realizadas durante un período, y con ello, elaborar los estados financieros finales que reflejan la salud financiera de la entidad.
        p(data-aos="fade-left") Cada etapa debe ser precisa y es necesaria para garantizar que la información registrada sea confiable, y que los resultados obtenidos sean fieles a la realidad económica de la empresa.
        p(data-aos="fade-left") Primero, conozcamos cada uno de esos pasos:

    .bg-full-width.bg-color-info.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center.mb-5
          .col-lg-8
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema1/18.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="39%" y="7.5%" numero="+")
                h5 1. Asientos de apertura
                p Recolección de datos y análisis de transacciones y Balance General, principio de periodo reportado.
              .bg-color-white.box-shadow.p-3(x="73%" y="13%" numero="+")
                h5 2. Transacciones
                p Creación, análisis y registro de asientos de diario, para cada transacción.
              .bg-color-white.box-shadow.p-3(x="92%" y="39%" numero="+")
                h5 3. Libro diario general
                p Registro cronológico de las entradas en el primer libro de cuentas.
              .bg-color-white.box-shadow.p-3(x="88%" y="73%" numero="+")
                h5 4. Libro mayor general
                p Una vez que una transacción se registra como una entrada de diario, debe contabilizarse en una cuenta en el libro mayor; este proporciona un resumen de todas las actividades por cuentas.
              .bg-color-white.box-shadow.p-3(x="61.5%" y="92%" numero="+")
                h5 5. Balance de aprobación no ajustado
                p Al final del periodo contable (mes, trimestre o año), se calcula un saldo de prueba que es la fuente de todos los estados financieros, y ayuda a identificar errores y realizar ajustes.
              .bg-color-white.box-shadow.p-3(x="29%" y="88%" numero="+")
                h5 6. Ajustes o saldo de prueba ajustada
                p Se realizan entradas de ajuste, relacionadas con ajustes de acumulación, periódicos, de depreciación o amortiguación del libro Diario al libro Mayor.
              .bg-color-white.box-shadow.p-3(x="7%" y="61%" numero="+")
                h5 7. Estados ajustados
                p Después que la empresa realiza todas las entradas de ajuste, se generan todos los estados financieros básicos: Estado de Resultados, Balance General, Estado de Patrimonio, Accionistas y Flujo de Efectivo.
              .bg-color-white.box-shadow.p-3(x="11%" y="29%" numero="+")
                h5 8. Cierre de libros
                p Se cierran los libros de las cuentas de ingresos y gastos y comienza de nuevo el ciclo, sin dejar saldo en dichas cuentas.

    p.mb-4 Y continuemos con las etapas del ciclo contable:

    .row.align-items-start.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/19.png", alt="").mb-4.mb-lg-0
      .col-lg-8.order-lg-1
    
        AcordionA(tipo="b")
          .div(titulo="Identificación y análisis de las transacciones")
            p El primer paso en el ciclo contable es la identificación de las transacciones. En esta fase, se registran todos los hechos económicos que ocurren dentro de la empresa, como compras, ventas, pagos, cobros, entre otros. 
            p Este análisis permite determinar qué cuentas se ven afectadas y cuál es el impacto de la transacción en las finanzas de la empresa (Vargas Moreno, 2020). Las transacciones pueden ser internas o externas, y cada una debe ser cuidadosamente registrada para asegurar la veracidad de los registros contables.
    
          .div(titulo="Registro en el libro diario")
            p Una vez que se identifican y analizan las transacciones, el siguiente paso es registrar cada una en el libro diario. Este libro debe llevar un registro cronológico de todas las transacciones, mostrando las cuentas afectadas, el monto de cada transacción y una breve descripción del hecho.
            p Cada transacción se debe registrar con al menos dos entradas: un débito y un crédito, siguiendo el principio de la partida doble (Vargas Moreno, 2020).

    
          .div(titulo="Transferencia al libro mayor")
            p Tras registrar las transacciones en el libro diario, se procede a trasladarlas al libro mayor. En esta etapa, se clasifica cada transacción, según el tipo de cuenta (por ejemplo, activos, pasivos, patrimonio, ingresos, gastos).
            p En el libro mayor, se agrupan las transacciones, de acuerdo con las cuentas que fueron afectadas, lo que facilita ver el saldo de cada cuenta en particular.

    
          .div(titulo="Elaboración del balance de prueba")
            p Con las cuentas ya registradas en el libro mayor, se realiza el balance de prueba. Este balance es un reporte que agrupa las cuentas y sus respectivos saldos de débito y crédito. 
            p El objetivo es asegurar que la suma de los débitos sea igual a la de los créditos, lo cual es un indicativo que no hay errores matemáticos en los registros. Si los débitos y créditos no coinciden, se deben revisar los registros para detectar posibles errores.
    
    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/20.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="b")
          .div(titulo="Ajustes contables")
            p En algunos casos, es necesario realizar ajustes contables para reflejar correctamente la situación financiera de la empresa. Estos ajustes incluyen operaciones como la amortización de activos, el reconocimiento de ingresos devengados y la corrección de estimaciones.
            p Los ajustes garantizan que los estados financieros presenten una imagen fiel de la situación financiera y del rendimiento de la empresa.

          .div(titulo="Elaboración de los estados financieros")
            p Tras los ajustes, se procede a elaborar los estados financieros, los cuales incluyen el estado de situación financiera (que muestra los activos, pasivos y patrimonio) y el estado de resultados (que muestra los ingresos y gastos). 
            p Estos informes proporcionan una visión clara de la rentabilidad y la solvencia de la empresa. Los estados financieros son indispensables para la toma de decisiones por parte de gerentes, inversionistas, auditores y otros interesados..

    
          .div(titulo="Cierre de libros contables")
            p Finalmente, una vez que se han preparado los estados financieros, se realiza el cierre de libros. En esta etapa, las cuentas de ingresos y gastos se "cierra" a una cuenta de utilidades o pérdidas acumuladas. Esto se hace para preparar los registros para el siguiente período contable. 
            p Tras el cierre, el ciclo contable comienza de nuevo, con el siguiente periodo.

    #t_1_4.titulo-segundo(data-aos="flip-up")
      h2 #[span 1.4] Análisis de los estados financieros

    .bg-full-width.bg-h85-3.mb-3
      .p-4.p-md-5
        p.mb-4 Para el estudio de esta temática, lo invitamos a escuchar el siguiente podcast.
        .row.justify-content-center.align-items-center
          .col-lg-6
            TarjetaAudio.color-acento-botones.bg-color-white.mb-3(
              texto="Fundamentos de la innovación estratégica"
              tiempo
              :audio="require('../../assets/curso/podcast/podcast1.mp3')"
            )
    
    h2(data-aos="fade-left") Técnicas e indicadores para el análisis de los estados financieros
    p.mb-5 Para realizar un análisis adecuado de los estados financieros, se utilizan en su mayoría dos técnicas: el análisis vertical y el análisis horizontal. Ambas permiten evaluar la evolución y la situación financiera de una empresa desde diferentes perspectivas. Conozcamos cada una de ellas:

    TabsC.color-acento-contenido.mb-5
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Análisis vertical" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Análisis vertical
            p El análisis vertical consiste en evaluar cada partida de los estados financieros como un porcentaje de una cifra base. Por ejemplo, en el caso de un balance general, cada cuenta se expresa como un porcentaje del total de activos. Esto permite comparar diferentes partidas dentro del mismo periodo, haciendo más fácil identificar qué tan significativas son ciertas áreas en relación con otras.
            p Esta técnica es útil para entender la proporción de cada elemento dentro de un conjunto, como las proporciones de activos frente a pasivos o los ingresos frente a los gastos.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/21.png', alt='')
    
      .tabs-content.border.px-4.p-md-5.py-3(titulo="Análisis horizontal" :icon="require('@/assets/bullets/1.svg')")
        .row.justify-content-center
          .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
            h4 Análisis horizontal
            p El análisis horizontal, por otro lado, compara los estados financieros de diferentes períodos, permitiendo observar las tendencias a lo largo del tiempo. Esta técnica ayuda a identificar patrones de crecimiento o contracción en la empresa, comparando los resultados actuales con los de años anteriores.
            p El análisis horizontal facilita la identificación de variaciones importantes, ya sea en términos de ingresos, costos o activos, lo que ayuda a prever el futuro financiero de la empresa.
    
          .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema1/22.png', alt='')
    



    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://micrositios.dian.gov.co/sistema-de-facturacion-electronica." target="_blank" rel="noopener noreferrer") ¡Bienvenido al Sistema de Factura Electrónica! (2022, septiembre 6). Sistema de Facturación Electrónica. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://actualicese.com/" target="_blank" rel="noopener noreferrer") Actualícese. (2025, Febrero 5). Balance general. Actualícese.

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://youtu.be/CTbC9H_JRco?si=8p8Y4dZVaEr5fuU_" target="_blank" rel="noopener noreferrer") Mis finanzas U. (2020, 15 de agosto). ¿Cómo se realiza un diagnóstico financiero? ¿Cómo se interpretan los ratios o indicadores? [Video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
