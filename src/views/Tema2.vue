<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1(data-aos="fade-right") Aspectos diferenciales del acompañamiento psicosocial en familias con personas en situación de discapacidad

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8(data-aos="fade-left")
        p El programa Mi familia atiende a familias con niños, niñas o adolescentes en situación de discapacidad desde una perspectiva inclusiva, lo cual permite a las PcD y a sus familias gozar de sus derechos y hacer presencia en los entornos y espacios en igualdad de condiciones que el resto de la población. 
        p Asimismo, la perspectiva inclusiva implica la incorporación de ajustes o adecuaciones al diseño del programa y a su modelo de atención que tengan en cuenta los intereses y las necesidades particulares de estas familias, con el propósito de contribuir al cierre de las brechas que enfrentan. 
        p.text-bold Los aspectos diferenciales del programa Mi familia para la atención a familias con personas en situación de discapacidad, en especial si se trata de niños, niñas o adolescentes son:
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-right")
        figure
          img.img-t.m-auto(src='@/assets/curso/tema2/img01.png')

    .row.g-2.mb-5
      .col-lg-3.col-sm-6.mb-4.mb-lg-0.mb-sm-0(data-aos="fade-left")
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img02.svg')})`}")
            .tarjeta-flip__contenido.p-4.flex-center-text
              .row.justify-content-center
                .col-lg-12.mb-4
                  .bg_10.p-2
                    h4.text-center.m-0 Meta de atención
                p.text-center Una meta específica en cada vigencia para la atención de familias con NNAcD.

      .col-lg-3.col-sm-6(data-aos="fade-right")
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img03.svg')})`}")
            .tarjeta-flip__contenido.p-4.flex-center-text
              .row.justify-content-center
                .col-lg-12.mb-4.align-self-center
                  .bg_10.p-2
                    h4.text-center.m-0 Ciclo básico
                p.text-center Que se ofrece a las familias con integrantes en situación de discapacidad incluye, además de las temáticas que aplican a todas las familias, el cuidado del cuidador y la participación de la persona en situación de discapacidad en las dinámicas familiares.

      .col-lg-3.col-sm-6.mb-4.mb-lg-0.mb-sm-0(data-aos="fade-left")
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .indicador--hover(v-if="indicadorTarjetaFlip")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img04.svg')})`}")
            .tarjeta-flip__contenido.p-4.flex-center-text
              .row.justify-content-center
                .col-lg-12.mb-4
                  .bg_10.p-2
                    h4.text-center.m-0 Encuentros inclusivos
                p.text-center Las familias con integrantes en situación de discapacidad participan con el resto de las familias beneficiarias en encuentros familiares o comunitarios inclusivos.

      .col-lg-3.col-sm-6(data-aos="fade-right")
        .tarjeta.tarjeta-flip.color-primario(@mouseover="indicadorTarjetaFlip = false")
          .tarjeta-flip__contenedor
            .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/tema2/img05.svg')})`}")
            .tarjeta-flip__contenido.p-4.flex-center-text
              .row.justify-content-center
                .col-lg-12.mb-4.align-self-center
                  .bg_10.p-2
                    h4.text-center.m-0 Encuentros especializados
                p.text-center Se desarrollan espacios de encuentros especializados para las familias con integrantes en situación de discapacidad, beneficiarias de la modalidad y donde se abordan asuntos de interés particular para estas familias.

    p Estos ajustes en el modelo de atención que se detallarán en apartados posteriores se soportan en dos conceptos propuestos por la Convención y que también han sido adoptados en el marco normativo y de la política de Colombia, <b>la eliminación de barreras y los ajustes razonables,</b> cuyos principales elementos se presentan a continuación.

    Separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 2.1 La eliminación de barreras y los ajustes razonables para la atención inclusiva de las PcD y sus familias

    .bg_11.mb-4
      .row.justify-content-center
        .col-xxl-11.col-xl-11.col-lg-10(data-aos="fade-left")
          p El reconocimiento de las personas en situación de discapacidad como sujetos de derechos, independiente de sus condiciones biológicas representa un gran avance; sin embargo, para avanzar en equidad y en la superación de las brechas que enfrenta esta población es preciso reconocer que las personas en situación de discapacidad y sus familias han sido segregadas y discriminadas, limitando las posibilidades con las que cuentan para lograr su pleno desarrollo.
        .col-xxl-1.col-xl-1.col-lg-2(data-aos="fade-right")
          figure
            img.img-t.m-auto.mb-4(src='@/assets/curso/tema2/img06.svg')

    .row.justify-content-center.mb-5(data-aos="zoom-in-down")
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img07.png')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Es necesario recordar que la Convención reconoce que la discapacidad se hace evidente en la interacción de las personas con el entorno. En este sentido, hay entornos y espacios más o menos incapacitantes en la medida que facilitan o entorpecen la participación de los individuos. A esas características de los espacios, las instituciones y de las personas que dificultan o impiden la participación de las PcD se les conoce como <b>barreras</b>.

    p Serrano (2013) (citado en Unicef & ICBF, 2020), precisa que las barreras son factores que obstaculizan la participación y el desarrollo de los individuos. Las barreras presentes en el entorno físico, en la tecnología y en las actitudes de las personas frente a la discapacidad afectan el funcionamiento de los órganos y estructuras corporales e impiden el desarrollo de las actividades cotidianas de las PcD. <b>El documento referenciado presenta tres tipos de barreras:</b>

    .row.justify-content-center
      .col-lg-10
        ImagenInfografica.color-acento-botones.mb-5.t_img-info2.m_card-imginf2.c_card-imginf2.t_img-infografica2(data-aos="fade-down-right")
          template(v-slot:imagen)
            figure(data-aos="zoom-in-up")
              img(src='@/assets/curso/tema2/img08.svg', alt='')

          .tarjeta.color2.p-4.t_tar-imginfo(x="74.5%" y="33.3%" numero="+")
            .h5.mb-3 Barreras actitudinales
            p Se encuentran en las personas,  en las instituciones y se manifiestan a través de conductas, palabras, frases, sentimientos, preconcepciones, estigmas, que impiden u obstaculizan el acceso en condiciones de igualdad de las personas en situación de discapacidad a los espacios y servicios sociales.
          
          .tarjeta.color2.p-4(x="33.7%" y="40%" numero="+")
            .h5.mb-3 Barreras comunicativas
            p Obstáculos que impiden o dificultan el acceso a la información, a la consulta, al conocimiento y en general, el desarrollo en condiciones de igualdad del proceso comunicativo de las personas en situación de discapacidad a través de cualquier medio o modo de comunicación, incluidas las dificultades en la interacción comunicativa de las personas.

          .tarjeta.color2.p-4(x="11%" y="54.6%" numero="+")
            .h5.mb-3 Barreras físicas
            p Obstáculos materiales, tangibles o construidos que impiden o dificultan el acceso y el uso de espacios, objetos y servicios de carácter público y privado, en condiciones de igualdad, por parte de las personas en situación de discapacidad.

    p Las barreras a la participación de las personas en situación de discapacidad pueden estar presentes en todos los entornos donde transcurren sus vidas. Desde la perspectiva ecosistémica, presentada en el componente formativo «Acompañamiento psicosocial familiar», las barreras pueden estar presentes en todos los sistemas donde las PcD participan directamente o en aquellos en donde no participan o no hacen presencia; pero donde se toman decisiones que tienen efectos en sus vidas. En este sentido, las barreras a la participación se pueden encontrar en la familia, en la casa o domicilio que habita la PcD, en el barrio, la comunidad, el espacio público, en las políticas, en las prácticas institucionales, etc. 
    p.mb-5 El proceso de eliminar o reducir las barreras para avanzar en la inclusión de las PcD se ha denominado <b>‘ajustes’</b>. La Convención sobre los derechos de las PcD les ha puesto la característica de ‘razonables’ para considerar que estos ajustes no impliquen una carga desmedida para la comunidad o la familia.

    .row.justify-content-center.align-items-center.mb-5
      .col-xxl-5.col-xl-5.col-lg-6.mb-4.mb-xxl-0.mb-xl-0(data-aos="fade-right")
        .bloque-texto-d.color-acento-contenido.p-2
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            p Así, los ‘ajustes razonables’ hacen referencia a las modificaciones y las adaptaciones, que no impongan una carga desproporcionada o indebida, de todo aquello que impide o limite la participación de las personas con discapacidad en las actividades familiares, sociales y colectivas de la sociedad que habitan.
            i.fas.fa-quote-right
          .bloque-texto-d__autor 
            .h5.mb-0 (Unicef & ICBF, 2020).
      .col-xxl-3.col-xl-3.col-lg-4(data-aos="fade-left")
        figure
          img.img-t.m-auto(src='@/assets/curso/tema2/img09.svg')

    Separador

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 2.2	Elementos para el abordaje de la discapacidad desde el rol del profesional de acompañamiento familiar

    .bg_12.mb-4
      .row.justify-content-center
        .col-xxl-11.col-xl-11.col-lg-10(data-aos="fade-left")
          p El componente «Estructuración del acompañamiento psicosocial familiar» presenta un apartado que contiene las orientaciones sobre el rol del Profesional de acompañamiento familiar, las cuales aplican también para el trabajo con familias con personas en situación de discapacidad. A esas orientaciones se suman las que se presentan a continuación, relacionadas con aspectos de especial atención cuando se participa en procesos de fortalecimiento con familias con PcD.
        .col-xxl-1.col-xl-1.col-lg-2(data-aos="fade-right")
          figure
            img.img-t.m-auto.mb-4(src='@/assets/curso/tema2/img10.svg')

    TabsA.color-acento-contenido.mb-5
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Reconocimiento de derechos")
        h4 Reconocimiento de derechos
        .row
          .col-lg-12
            p Incorporar una visión sobre la discapacidad que reconozca a las PcD como sujetos de derechos que pueden participar plenamente en la vida familiar, social y comunitaria, superando las miradas de la discapacidad como un error, una falla o una enfermedad, asumiéndola como parte de la diversidad humana. Es importante que el PAF tenga siempre presente que las capacidades de una persona no definen a qué derechos pueden o no acceder.        
      
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Contacto")
        h4 Contacto
        .row
          .col-lg-12
            p Referirse siempre a la persona con discapacidad por su nombre y no por su diagnóstico o con diminutivos que pueden transmitir o consolidar una visión desde la incapacidad y la dependencia.
      
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Perspectiva integral")
        h4 Perspectiva integral
        .row
          .col-lg-12
            p Identificar a la PcD desde una perspectiva integral, teniendo en cuenta su contexto, su historia y no limitándose a reconocerla a partir de un diagnóstico. Esto implica promover conversaciones sobre cómo se han construido las relaciones al interior de la familia y con su entorno más cercano para motivar la transformación de prácticas y costumbres que limitan el pleno desarrollo de la PcD, teniendo cuidado de no juzgar o cuestionar las decisiones de las familias.
            p El reconocimiento de la PcD desde una perspectiva integral y no solo desde el diagnóstico de su discapacidad permite trascender la idea que quienes comparten un diagnóstico tienen la misma personalidad, las mismas preferencias y las mismas habilidades. Esta idea, que asume el diagnóstico como un pronóstico de lo que será o no será la vida de una persona, ha permitido que se consoliden estereotipos que niegan el papel del contexto social y cultural en el desarrollo de las personas.

      .tarjeta.color-acento-contenido--borde.p-4(titulo="Autorreferenciación")
        h4 Autorreferenciación
        .row
          .col-lg-12
            p En el trabajo con familias con PcD podría suceder que el PAF adopte miradas compasivas como resultado de sus propias ideas y experiencias sobre la discapacidad. El PAF debe estar atento a estas miradas con las familias con PcD, puesto que pueden entorpecer el proceso de fortalecimiento y consolidación de la autonomía de la familia. Las miradas compasivas podrían estar presentes cuando el PAF se excede en mecanismos sobreprotectores, evita el establecimiento de compromisos por parte de las familias, lleva regalos o les permite saltar las normas o los acuerdos establecidos en el acompañamiento.
            p Una forma de avanzar es observar su cotidianidad, sus momentos de encuentro, las manifestaciones de afecto, sus preocupaciones y la forma como viven sus conflictos, para reconocer que la realidad de las familias de niños y niñas con discapacidad es parecida a la de las demás familias de su contexto y que tienen más elementos en común de los que parecen.
      
      .tarjeta.color-acento-contenido--borde.p-4(titulo="Normalizar")
        h4 Normalizar
        .row
          .col-lg-12
            p Otra mirada que puede aparecer cuando se trabaja con familias con personas con discapacidad y que parece ser la opuesta a la mirada compasiva es la mirada normalizadora, esta no reconoce la necesidad de incorporar ajustes razonables soportada en un aparente sentido de igualdad que desconoce la diversidad.  
    
    Separador

    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 2.3 Abordaje de la discapacidad en la caracterización y el diagnóstico

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8(data-aos="fade-right") 
        p La aplicación de los instrumentos como la ficha de caracterización sociofamiliar, el genograma, el ecomapa e instrumentos de medición de habilidades facilita el proceso de caracterización y diagnóstico de la familia y, por parte del PAF, la comprensión de la realidad de las mismas, para así proponer cursos de acción adecuados para el acompañamiento, a la vez que promueve en las familias el reconocimiento de su propia realidad e historia y la apropiación de su proceso de transformación.
        p El proceso de caracterización y diagnóstico del programa Mi familia incorpora aspectos diferenciales para las familias con PcD. Dentro de estos, el más importante es el relacionado con la caracterización de la discapacidad en la ficha sociofamiliar.           
      .col-lg-4.mb-4.mb-lg-0(data-aos="fade-left")
        figure
          img.img-t.m-auto(src='@/assets/curso/tema2/img11.png')

    .row.justify-content-center.mb-4
      .col-lg-10
        .bg_13.p-4
          .row.justify-content-center.align-items-center
            .col-lg-4
              figure(data-aos="zoom-in-up")
                img.img-t.m-auto(src='@/assets/curso/tema2/img12.svg', alt='')
            .col-lg-8.mb-4.mb-lg-0
              p.m-0.mt-4 En el desarrollo de este proceso es probable que el PAF requiera realizar ajustes razonables para garantizar la participación y la expresión de las opiniones por parte de las PcD, por ejemplo, si hay un adolescente con discapacidad visual en la familia se debe ajustar el mecanismo para diligenciar el instrumento de Disciplina positiva, cambiando el diligenciamiento autónomo por un diligenciamiento donde el PAF lee las frases o preguntas así como las opciones de respuesta para que el adolescente pueda manifestar sus preferencias y, que sus percepciones y opiniones queden recogidas en la caracterización y diagnóstico de la familia.

    p.mb-5 En los apartados que siguen se presentan los aspectos a resaltar, relacionados con el abordaje de la discapacidad en los instrumentos de caracterización y diagnóstico que contempla el programa Mi familia. 

    .row.mb-4.mb-lg-5
      .col-lg-2.col-md-4.col-7
        .bg_14.p-2
          p.m-0.text-white.text-bold.text-center Ficha sociofamiliar

    p.mb-5 Esta ficha tiene cuatro  apartados, dos  de los cuales recogen información a nivel de individuos, el dedicado a recoger la información del jefe del grupo familiar y el dedicado a los demás integrantes. En el diligenciamiento de estos apartados y cuando se esté recogiendo información correspondiente a una PcD se debe procurar que se encuentre presente y las preguntas se le realicen directamente. <b>El siguiente recurso del ICBF (2020) presenta el apartado de caracterización de las personas en situación de discapacidad y en qué consiste el diligenciamiento de cada campo.</b> 

    .bg_03.p-2.py-5.mb-5
      .row.justify-content-center
        .col-lg-12
          ImagenInfografica.color-acento-botones.t_img-info2.m_card-imginf2.c_card-imginf2
            template(v-slot:imagen)
              figure
                img(src='@/assets/curso/tema2/img13.svg', alt='')

            .tarjeta.color2.p-4.t_tar-imginfo(x="0.7%" y="7.3%" numero="+")
              .h5.mb-3 ¿El beneficiario presenta discapacidad?
              p El primer campo de este grupo de preguntas sirve como filtro inicial. La opción sí se elige cuando el informante presenta el certificado de discapacidad emitido por una Entidad Promotora de Salud (EPS) del régimen contributivo o subsidiado, una administradora del régimen especial de excepción o una Institución Prestadora de Servicios de Salud (IPS). Asimismo, se debe elegir la opción sí cuando, sin tener el certificado, la persona se autorreconoce en situación de discapacidad. 
              p Cuando una persona se autorreconoce en situación de  discapacidad y no tiene el certificado de discapacidad, el profesional de acompañamiento familiar debe orientarlo sobre las gestiones necesarias para obtenerlo.
            
            .tarjeta.color2.p-4(x="1.7%" y="44%" numero="+")
              .h5.mb-3 ¿La discapacidad está certificada?
              p El sistema de salud de Colombia ha dispuesto mecanismos para certificar la discapacidad; en este sentido, la discapacidad está certificada cuando la PcD cuenta con el certificado de discapacidad emitido por una EPS del régimen contributivo o subsidiado, una administradora del régimen especial de excepción o una IPS, como se mencionó anteriormente.

            .tarjeta.color2.p-4(x="40.5%" y="17%" numero="+")
              .h5.mb-3 Entidad que certifica la discapacidad
              p En este caso se mencionan las opciones al informante y se espera su respuesta. Se puede orientar al informante siguiendo lo establecido en la Guía para el registro de las variables de discapacidad en los sistemas de información del ICBF (2019) en el siguiente sentido: 
              ul.lista-ul
                li 
                  i.fas.fa-check-circle
                  | Se debe escoger la opción EPS Resolución 583 cuando la PcD cuente con el certificado generado por una EPS, en cumplimiento de lo estipulado en la Resolución 583 de 2018.
                li 
                  i.fas.fa-check-circle
                  | Se debe escoger la opción EPS cuando la PcD cuente con un certificado emitido por una EPS del régimen contributivo o subsidiado de manera previa a la Resolución 583 de 2018.
                li 
                  i.fas.fa-check-circle
                  | Se debe escoger la opción IPS cuando la PcD cuente con un certificado emitido por una entidad de esa naturaleza; se debe escoger la opción Medicina Legal cuando la PcD cuente con un certificado emitido por el Instituto Nacional de Medicina Legal y Ciencias Forenses INMLCF.
                li 
                  i.fas.fa-check-circle
                  | Se debe escoger la opción Junta de Calificación de Invalidez cuando la PcD cuente con un certificado emitido por una Junta Regional o Nacional de Calificación de Invalidez, las cuales califican la pérdida de capacidad laboral, el estado de invalidez y determinan su origen, en casos de accidentes y enfermedades de origen común o profesional, entre otras.

            .tarjeta.color2.p-4(x="53%" y="44%" numero="+")
              .h5.mb-3 ¿Está inscrito en el registro para la localización y caracterización de personas en situación de discapacidad?
              p Debe escoger la opción sí cuando la PcD cuenta con el certificado emitido por la EPS en cumplimiento a lo estipulado en la Resolución 583 de 2018 o manifiesta estar inscrito en el Registro de Localización y Caracterización de Personas con Discapacidad (RLCPD). Siguiendo las orientaciones de ICBF (2019), en caso de que la PcD no esté registrada, el profesional de acompañamiento familiar debe registrar la opción no y orientar a la PcD para gestionar el RLCPD, a través de la expedición del certificado de discapacidad. Una vez obtenido el certificado deberá actualizar el RLCPD de la PcD en las herramientas de recolección de información del ICBF.

            .tarjeta.color2.p-4(x="98.4%" y="19%" numero="+")
              .h5.mb-3 Cinco situaciones
              p Se presentan cinco situaciones, que se deben marcar en caso de que se presenten en la PcD, siguiendo las siguientes indicaciones. 
              ul.lista-ul
                li 
                  i.fas.fa-check-circle
                  p.m-0 <b>El beneficiario requiere la ayuda de otra persona.</b> Se debe marcar cuando la PcD requiere la ayuda de otra persona para realizar actividades básicas de la vida diaria como cuidado personal, aseo personal, control de esfínteres, comer y beber, vestirse, cambiar y mantener diversas posturas corporales, levantarse, acostarse y permanecer de pie, y desplazarse dentro del hogar. En caso de que la PcD esté necesitando un apoyo transitorio para este tipo de actividades no se debe marcar esta situación. 
                li 
                  i.fas.fa-check-circle
                  p.m-0 <b>El beneficiario requiere ayuda técnica/producto de apoyo.</b> Se debe marcar cuando la PcD, su médico tratante o su acompañante, manifiesten que la persona requiere algún producto o tecnología de apoyo para el desarrollo de sus actividades básicas de la vida diaria.
                li 
                  i.fas.fa-check-circle
                  p.m-0 <b>El beneficiario cuenta con la ayuda técnica/producto de apoyo.</b> Se debe marcar cuando la PcD cuenta con un producto de apoyo o ayuda técnica, cuando esta o su acompañante informan que dispone de ayuda técnica o cuando es evidente que la persona la está usando.
                li 
                  i.fas.fa-check-circle
                  p.m-0 <b>El beneficiario requiere terapia y/o rehabilitación.</b> Se debe marcar cuando la PcD o su acompañante informan que un médico tratante le ordenó terapia y/o rehabilitación.
                li 
                  i.fas.fa-check-circle
                  p.m-0 <b>El beneficiario recibe atención en terapia y/o rehabilitación.</b> Se debe marcar cuando la PcD o su acompañante informan que recibe atención en terapia y/o rehabilitación.

            .tarjeta.color2.p-4(x="1.7%" y="75%" numero="+")
              .h5.mb-3 ¿Tiene proceso de interdicción?
              | Se debe escoger la opción sí cuando la PcD o su acompañante informan que la PcD tiene un proceso de interdicción declarada por una autoridad judicial. Se presentan listadas las once categorías de discapacidad que contiene la ficha sociofamiliar, las cuales no son excluyentes, es decir, una persona puede presentar una o varias de estas categorías. Las categorías incluidas son las que dispone la Resolución 583 de 2018 más otras que aparecen en los certificados de discapacidad anteriores a la mencionada Resolución y que todavía son válidos. Marque las categorías siguiendo las siguientes orientaciones, retomadas de ICBF (2019). 

            .tarjeta.color2.p-4(x="71%" y="54%" numero="+")
              .h5.mb-3 Nivel de dificultad de desempeño %
              | El último campo referente a la discapacidad incluye seis subcampos no excluyentes, en donde se debe consignar un valor en porcentaje. Esta información solo se debe diligenciar si la PcD cuenta con la certificación emitida por la EPS, en el marco de la Resolución 583 de 2018 y tiene 6 o más años y se debe transcribir tal como aparece en dicha certificación.  

    p.text-bold.mb-5 Una vez comprendido cada apartado, es tiempo de reconocer los tipos de discapacidad presentados en la ficha anterior.

    SlyderA(tipo="b").bg_15.p-5.mb-5
      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Discapacidad psicosocial (mental)
          p Resulta de la interacción entre las personas con alteraciones en el pensamiento, percepciones, emociones, sentimientos, comportamientos y relaciones y, las barreras del entorno que evitan su participación plena y efectiva en la sociedad.                                     
        .col-lg-7(data-aos="fade-right") 
          figure
            img.img-t.mx-auto(src='@/assets/curso/tema2/img14.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Discapacidad intelectual
          p Se refiere a aquellas personas que presentan deficiencias en las capacidades mentales generales, como el razonamiento, la resolución de problemas, la planificación, el pensamiento abstracto, el juicio, el aprendizaje académico y el aprendizaje de la experiencia. En estos casos, los individuos no alcanzan los estándares de independencia personal y de responsabilidad social en uno o más aspectos de la vida cotidiana, incluidos la comunicación, la participación social, el funcionamiento académico u ocupacional y la independencia personal en la casa o en la comunidad (American Psychiatric Association, 2014, citado por la Resolución 583 de 2018).                 
        .col-lg-7
          figure.mb-4
            img.img-t.mx-auto(src='@/assets/curso/tema2/img15.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5
          h4 Discapacidad visual
          p Incluye a aquellas personas que presentan deficiencias para percibir la luz, la forma, el tamaño o el color de los objetos. Se incluye a las personas ciegas y a las personas con baja visión, es decir, quienes a pesar de usar gafas o lentes de contacto o haberse practicado una cirugía tienen dificultades para distinguir formas, colores, rostros, objetos en la calle, ver en la noche, ver de lejos o de cerca por ambos ojos. Estas personas presentan diferentes grados de dificultad en la ejecución de actividades de cuidado personal, del hogar o del trabajo, entre otras (Resolución 583 de 2018).
        .col-lg-7
          figure.mb-4
            img.img-t.mx-auto(src='@/assets/curso/tema2/img16.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Discapacidad auditiva
          p Se encuentran personas que presentan en forma permanente deficiencias en las funciones sensoriales relacionadas con la percepción de los sonidos y la discriminación de su localización, tono, volumen y calidad. Como consecuencia, presentan diferentes grados de dificultad en la recepción y producción de mensajes verbales y, por tanto, para la comunicación oral. Se incluye en esta categoría a las personas sordas y a las personas con hipoacusia, esto es, aquellas que debido a una deficiencia en la capacidad auditiva presentan dificultades en la discriminación de sonidos, palabras, frases, conversación e incluso sonidos con mayor intensidad que la voz conversacional, según el grado de pérdida auditiva (Resolución 583 de 2018).                                 
        .col-lg-7(data-aos="fade-right") 
          figure
            img.img-t.mx-auto(src='@/assets/curso/tema2/img17.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Sordoceguera
          p Es una discapacidad única que resulta de la combinación de una deficiencia visual y una deficiencia auditiva, que genera en las personas que la presentan, problemas de comunicación, orientación, movilidad y acceso a la información. Algunas personas sordociegas son sordas y ciegas totales, mientras que otras conservan restos auditivos y/o restos visuales (Resolución 583 de 2018).        
        .col-lg-7
          figure.mb-4
            img.img-t.mx-auto(src='@/assets/curso/tema2/img18.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5
          h4 Discapacidad física
          p Personas que presentan en forma permanente deficiencias corporales funcionales a nivel músculo esquelético; neurológico; tegumentario de origen congénito o adquirido; pérdida o ausencia de alguna parte de su cuerpo o presencia de desórdenes del movimiento corporal. Estas personas pueden presentar en el desarrollo de sus actividades cotidianas, diferentes grados de dificultad funcional para el movimiento corporal y su relación en los diversos entornos al caminar, desplazarse, cambiar o mantener posiciones del cuerpo, llevar, manipular o transportar objetos y realizar actividades de cuidado personal o del hogar, interactuar con otros sujetos, entre otras (Resolución 583 de 2018).
        .col-lg-7
          figure.mb-4
            img.img-t.mx-auto(src='@/assets/curso/tema2/img19.png', alt='AvatarTop')
      
      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Discapacidad múltiple
          p Hace referencia a la presencia de dos o más deficiencias asociadas, de orden físico, sensorial, mental o intelectual, las cuales afectan significativamente el nivel de desarrollo, las posibilidades funcionales, la comunicación, la interacción social y el aprendizaje, por lo que requieren para su atención de apoyos generalizados y permanentes. Las particularidades de la discapacidad múltiple no están dadas por la sumatoria de los diferentes tipos de deficiencia, sino por la interacción que se presenta entre ellos. A través de dicha interacción se determina el nivel de desarrollo, las posibilidades funcionales de la comunicación y de la interacción social (Resolución 583 de 2018).                                    
        .col-lg-7(data-aos="fade-right") 
          figure
            img.img-t.mx-auto(src='@/assets/curso/tema2/img20.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Sensorial, gusto, olfato, tacto
          p Se ubican aquellas personas que, por las deficiencias en alguno de los sentidos del gusto, olfato o tacto, podrían de forma permanente presentar en el desarrollo de sus actividades cotidianas diferentes grados de dificultad en el aprendizaje, el cuidado personal, del hogar o del trabajo.              
        .col-lg-7
          figure.mb-4
            img.img-t.mx-auto(src='@/assets/curso/tema2/img21.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5
          h4 Piel, pelo y uñas
          p Personas que pueden presentar alteraciones en funciones de protección de la piel, pigmentación, calidad de la piel, de aislamiento de la piel, formación de callosidades, endurecimiento; funciones reparadoras de la piel en referencia a formación de costras, cicatrización, magulladuras y formación de queloides; funciones relacionadas con el sudor, funciones glandulares de la piel y olor corporal; sensaciones relacionadas con la piel tales como picor, sensación de quemazón o de hormigueo, sensación de pinchazos y de algo que se arrastra sobre la piel y, funciones de protección, pigmentación y la apariencia del pelo y las uñas. 
          p En esta categoría se ubican personas que presentan algún grado de dificultad en el desarrollo de sus actividades cotidianas o que experimentan en algunas ocasiones por su aspecto físico restricción en la participación social.
        .col-lg-7
          figure.mb-4
            img.img-t.mx-auto(src='@/assets/curso/tema2/img22.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Sistémica
          p Personas que presentan en forma permanente alteraciones severas en los sistemas cardiovascular, hematológico, inmunológico, respiratorio, digestivo, metabólico, endocrino, genitourinario y reproductor, entre otros. Estas personas presentan diferentes grados de dificultad en el desarrollo de sus actividades de la vida diaria.                                   
        .col-lg-7(data-aos="fade-right") 
          figure
            img.img-t.mx-auto(src='@/assets/curso/tema2/img23.png', alt='AvatarTop')

      .row.justify-content-center
        .col-lg-5.mb-4.mb-lg-0
          h4 Voz y habla
          p Personas que presentan en forma permanente alteraciones en el tono de la voz, la vocalización, la velocidad del habla, la producción de sonidos inadecuados para el hablante en términos de su edad o desarrollo físico; al igual que las que presentan dificultades graves o importantes para articular palabra (mudez, tartamudez). En este grupo se encuentran personas que podrían presentar en el desarrollo de sus actividades cotidianas diferentes grados de dificultad en la emisión de mensajes verbales.        
        .col-lg-7
          figure.mb-4
            img.img-t.mx-auto(src='@/assets/curso/tema2/img24.png', alt='AvatarTop')

    .row.mb-4.mb-lg-5
      .col-lg-2.col-xl-3.col-xxl-2.col-md-4.col-7
        .bg_14.p-2.px-4
          p.m-0.text-white.text-bold Genograma y ecomapa

    p.mb-5 Estos dos instrumentos no tienen aspectos diferenciales cuando se aplican a familias con PcD;sin embargo, es importante que se realice con especial cuidado el diligenciamiento de la información para las PcD, graficando, por ejemplo, el tipo de relación que tiene la PcD con cada uno de los integrantes de la familia y de esta forma tener elementos que permitan comprender el nivel de participación de la PcD en las dinámicas familiares y el involucramiento de cada uno de los integrantes de la familia en el cuidado de la PcD, en caso de ser necesario. 

    .row.justify-content-center.mb-5.color_bloque-texto3(data-aos="zoom-in-down")
      .col-lg-8
        .bloque-texto-g.color-secundario.p-3.p-sm-4.p-md-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/tema2/img26.png')})`}"
          )
          .bloque-texto-g__texto.p-5
            p.mb-0 El ecomapa adquiere especial relevancia en la atención de las familias con PcD, teniendo en cuenta las barreras de acceso que enfrentan ante los servicios y los espacios sociales y comunitarios. 

    p.mb-5 De igual manera, es preciso trabajar sobre las redes de apoyo formales e informales de estas familias, en especial cuando enfrentan una carga importante de cuidado, por ejemplo, cuando la PcD requiere apoyo y acompañamiento permanente para realizar sus actividades cotidianas y una única persona de la familia se encarga de brindárselo. 

    .row.mb-4.mb-lg-5
      .col-lg-4.col-md-8.col-12
        .bg_14.p-2
          p.m-0.ms-2.text-white.text-bold Instrumentos de medición de habilidades

    .bg_12-1
      .row.justify-content-center
        .col-xxl-11.col-xl-11.col-lg-10(data-aos="fade-left")
          p Estos dos instrumentos, al igual que el genograma y el ecomapa, no tienen aspectos diferenciales cuando se aplican a las familias con PcD; sin embargo, es preciso que en su diligenciamiento se incluyan, de ser necesario, ajustes razonables cuando se vayan a aplicar a una PcD. 
          p Los instrumentos siempre se deberán aplicar a las PcD si cumplen las condiciones establecidas en los mismos, relacionadas con la edad o con el rol que cumplen en la familia. En estos casos, el PAF deberá ajustar el proceso de recolección siempre que no represente una carga desproporcionada o indebida, como lo establece la definición de ajuste razonable.
        .col-xxl-1.col-xl-1.col-lg-2(data-aos="fade-right")
          figure
            img.img-t.m-auto.mb-4(src='@/assets/curso/tema2/img10.svg') 

    .bg_16.p-2.py-5
      .row.align-items-center
        .col-lg-4(data-aos="fade-right")
          figure
            img.img-t.m-auto(src='@/assets/curso/tema2/img27.svg') 
        .col-lg-8(data-aos="fade-left")
          p Por ejemplo, puede cambiar el proceso de diligenciamiento autónomo por uno donde el PAF lee las preguntas y las opciones de respuesta a la PcD para que ella pueda seleccionar la respuesta que mejor describa su opinión o percepción, apoyarse en un intérprete de la familia o de la comunidad, etc. 
          p Si el PAF tiene dudas al respecto puede conversar con su Unidad de acompañamiento familiar o su Unidad de asistencia técnica, para seleccionar una opción que maximice la posibilidad de participación por parte de las PcD.  

    Separador

    #t_2_4.titulo-segundo.color-acento-contenido(data-aos="zoom-out-right")
      h2 2.4 Acompañamiento desde un enfoque inclusivo y diferencial de la discapacidad

    p.mb-5 En este apartado se precisan los elementos relacionados con el enfoque diferencial e inclusivo de la discapacidad en las formas de intervención que contempla el programa Mi familia, es decir, en las visitas y en los encuentros. 

    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")(data-aos="fade-down-right")
      .row(titulo="Ciclo básico")
        .col-lg-7.mb-4.mb-lg-0.ms-lg-5
          p Para el caso de las familias con PcD se adicionan dos sesiones al ciclo básico. Una relacionada con el autocuidado y cuidado del otro, la cual profundiza en el cuidado al cuidador y autocuidado de personas con discapacidad, cuyas orientaciones se encuentran en la cartilla metodológica ‘Para cuidarte, primero me cuido: autocuidado PcD’ y otra; relacionada con la participación en familia que profundiza en la participación de las personas en situación de discapacidad en la vida familiar, para la cual se dispone de la cartilla metodológica ‘Todos hacemos parte’. 
          p Estas dos sesiones se concentran en aspectos relacionados con la vivencia de la discapacidad en la vida familiar; sin embargo, esto no significa que en las demás sesiones del ciclo básico no se aborde el tema, recuerde que uno de los propósitos de la modalidad es promover la participación de todos los integrantes de la familia en las sesiones de acompañamiento e incorporar y abordar en ellas sus intereses, necesidades y particularidades.
        .col-lg-4
          figure
            img.img-t.m-auto(src='@/assets/curso/tema2/img28.png', alt='Texto que describa la imagen')

      .row(titulo="Encuentros inclusivos")
        .col-lg-7.mb-4.mb-lg-0.ms-lg-5
          p En estos encuentros se debe promover el reconocimiento y la valoración de las PcD, así como la eliminación de las barreras de acceso y de participación que se encuentran en los entornos comunitarios. 
          p Las familias y las personas con experiencias de vida no cercanas a la discapacidad pueden no ser conscientes de las barreras que impiden el goce pleno de los derechos por parte de las PcD. Asimismo, la comunidad cercana a una familia con PcD puede convertirse en parte de su red de apoyo si tiene una visión positiva de la diversidad y reconocen a las PcD como sujetos con derecho a participar plenamente y en condiciones de igualdad de la vida social y comunitaria. 
          p El programa Mi familia incluye como una de las opciones para los encuentros inclusivos, la cartilla metodológica ‘Conocer y reconocer la discapacidad’ que busca promover reflexiones sobre la participación de las personas con discapacidad en la vida social y comunitaria.
        .col-lg-4
          figure
            img.img-t.m-auto(src='@/assets/curso/tema2/img29.png', alt='Texto que describa la imagen')
    
      .row(titulo="Encuentros especializados")
        .col-lg-7.mb-4.mb-lg-0.ms-lg-5
          p En estos encuentros participan las familias con PcD beneficiarias del programa. En la modalidad urbana son dos encuentros de este tipo, mientras que en la modalidad rural hay un único encuentro especializado. 
          p Para el desarrollo de estos, el programa cuenta con las cartillas ‘Cuidar a los que cuidan’ y ‘Capacidad de agencia de las familias: familias con niños, niñas y adolescentes con discapacidad’. La primera de ellas permite abordar de manera grupal estrategias para aliviar el impacto emocional y físico de las personas que cuidan a niños, niñas o adolescentes en situación de discapacidad. La segunda, por su parte, propone reflexiones comunitarias para el fortalecimiento de la independencia y autonomía de las familias con personas en situación de discapacidad. 
          p De igual manera, las Unidades de acompañamiento familiar pueden proponer ajustes a estas orientaciones para el desarrollo de los encuentros especializados, retomando elementos de ambas cartillas o proponiendo otros que sean de interés para las familias invitadas a participar y que estén relacionados con la garantía de los derechos de las personas en situación de discapacidad y sus familias.
        .col-lg-4
          figure
            img.img-t.m-auto(src='@/assets/curso/tema2/img30.png', alt='Texto que describa la imagen')


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
