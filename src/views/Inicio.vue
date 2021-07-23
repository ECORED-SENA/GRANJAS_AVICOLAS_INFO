<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.svg')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Gestión de granjas avícolas
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Gestión de granjas avícolas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 722203
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3984 Horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración en meses: 
                p.banner-principal__datos__item__texto 27 Meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto a distancia

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/QDXsJQaCJoE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p El programa Tecnólogo en gestión de granjas avícolas incluye las necesidades sentidas del sector productivo avícola por su crecimiento permanente y sus exigencias de evolución tecnológica obligan al sector a contar con personal calificado en las diferentes áreas de producción.
      br
      br
      |El SENA oferta este programa que incluye las temáticas de bioseguridad, proceso de producción, bienestar animal, trazabilidad, planes operativos estandarizados de sanitización, control de planes de impacto ambiental, manejo administrativo, entre otros.
      br
      br
      |Generando mayores oportunidades de productividad, competitividad, empleabilidad y emprendimiento, apuntando al desarrollo del campo como motor de la economía rural


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p La industria avícola colombiana es una de las principales actividades pecuarias que impactan en gran medida la economía del país debido a su crecimiento continuo, el cual en los últimos 4 años ha marcado un promedio del 5.4%, además de la generación anual de más de 550 mil empleos, lo que ha permitido aportar alrededor del 9.7% al PIB agrícola, el 6% al PIB Agropecuario y el 21% al PIB del subsector pecuario; lo que la consolida como el aportante de casi la quinta parte del valor agregado de la producción pecuaria nacional. Adicionalmente, cifras reportadas por el DANE (2019) tasan la avicultura colombiana en 18.1 billones de pesos en producción de pollo y huevo, lo que ha hecho que el sector avícola sea, tal vez, el de mayor valor de los sectores agropecuarios.
      br
      br
      |Al impacto en la economía se une la dimensión del sector, con más de 845 millones de aves encasetadas y más de 2.5 millones de toneladas de pollo y huevo producidas en 571 mil granjas entre pequeñas, medianas y grandes, distribuidas en 400 municipios de 1.100 que tiene el país, donde a nivel departamental la mayor representatividad se tiene en Santander, Cundinamarca y la región del Tolima y Huila; y la última, la zona suroccidental, que incluye el departamento del Valle y el norte del departamento del Cauca. En esas tres zonas está el 75% de la avicultura y el otro 25% está repartido aproximadamente del 10% a 12% en Antioquia y el restante en lo que se conoce como el Eje Cafetero y la Costa Atlántica.
      br
      br
      |En este sentido, el programa Tecnólogo en gestión de granjas avícolas  se requiere para brindar al sector la posibilidad de incorporar personal con altas calidades laborales y profesionales, con alta capacidad de decisión que le permita desempeñarse en procesos productivos dinámicos que contribuyan al desarrollo sectorial, dadas las oportunidades potenciales y existentes de desempeño que se han evidenciado para esta ocupación. El programa está dirigido a personas relacionadas con actividades de producción avícola, vinculadas o no con empresas formales del sector, o que hagan parte del entorno familiar de pequeños o medianos productores avícolas, ya sea en la producción de pollo de engorde o de aves de postura. De igual forma, a emprendedores de negocios avícolas que busquen consolidar el desempeño de su unidad productiva, bajo criterios de calidad, inocuidad, sostenibilidad y competitividad.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias a desarrollar 
    ul.lista-ul
        li 
          i.fas.fa-angle-right
          | Implementar condiciones bioseguras según sistema de producción pecuaria y normativa sanitaria.
        li 
          i.fas.fa-angle-right
          | Levantar aves según guía técnica y normativa.
        li 
          i.fas.fa-angle-right
          | Acopiar huevos de acuerdo con parámetros técnicos y de bioseguridad.
        li 
          i.fas.fa-angle-right
          | Seleccionar huevos según parámetros y métodos técnicos.
        li 
          i.fas.fa-angle-right
          | Planear producción de acuerdo con sistema productivo y métodos técnicos. 
        li 
          i.fas.fa-angle-right
          |Coordinar producción de especie pecuaria según procedimiento técnico y normativa. 
        li 
          i.fas.fa-angle-right
          | Gestionar el manejo de residuos sólidos según especificaciones técnicas y normativa.
        li 
          i.fas.fa-angle-right
          | Registrar información de acuerdo con normativa y procedimiento técnico.
        li 
          i.fas.fa-angle-right
          | Calcular costos de operación de acuerdo con métodos.
        li 
          i.fas.fa-angle-right
          | Formular el plan según objetivos y metodologías.
        li 
          i.fas.fa-angle-right
          | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
        li 
          i.fas.fa-angle-right
          | Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.
        li 
          i.fas.fa-angle-right
          | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
        li 
          i.fas.fa-angle-right
          | Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de Referencia para las Lenguas.
        li 
          i.fas.fa-angle-right
          | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
        li 
          i.fas.fa-angle-right
          | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.
        li 
          i.fas.fa-angle-right
          | Ética para la construcción de una cultura de paz - Enrique Low Murtra- Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
        li 
          i.fas.fa-angle-right
          | Protección para la salud y el medio ambiente - Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
        li 
          i.fas.fa-angle-right
          | Orientar investigación formativa según referentes técnicos.
        li 
          i.fas.fa-angle-right
          | Ejercer los derechos fundamentales del trabajo de acuerdo al reconocimiento de la dignidad.
        li 
          i.fas.fa-angle-right
          | Aplicar en la resolución de problemas reales del sector productivo, los conocimientos, habilidades y destrezas pertinentes a las competencias del programa de formación asumiendo estrategias y metodologías de autogestión.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso 

    p El nivel de competencias a demostrar en el proceso de ingreso por tipo de certificación:
    ul.lista-ul
        li 
          i.fas.fa-check
          | Nivel académico: media académica
        li 
          i.fas.fa-check
          | Curso: grado 11
        li 
          i.fas.fa-check
          |Formación para el trabajo y el desarrollo humano: no
        li 
          i.fas.fa-check
          |Número de horas: no aplica   
        li 
          i.fas.fa-check
          |Requiere certificación académica: si
        li 
          i.fas.fa-check
          |Requiere experiencia laboral: no
        li 
          i.fas.fa-check
          |Edad mínima definida en la ley: 15 años
        li 
          i.fas.fa-check
          | Requisitos adicionales: presentar certificado prueba de Estado de la educación media
        li 
          i.fas.fa-check
          |Restricciones de ingreso soportadas en la legislación vigente: no existe legislación que establezca restricciones de ingreso a nivel de discapacidad física o cognitiva.
        li 
          i.fas.fa-check
          |Aspectos actitudinales, motivacionales y de interés: los aspirantes al programa de formación deben contar con capacidad de análisis, reflexión, creatividad e innovación en la búsqueda de soluciones a problemas reales, actitud de liderazgo, capacidad de adaptación a nuevas situaciones, determinación y perseverancia, dominio del propio idioma, facilidad para el manejo de relaciones interpersonales y el trabajo en equipo, análisis y síntesis de lecturas, adaptación al trabajo al aire libre en el medio rural y urbano.  
        li 
          i.fas.fa-check
          |El aspirante debe demostrar interés por el sector agropecuario, tolerancia, disponibilidad al cambio, a la colaboración y al diálogo; respeto por la vida, la biodiversidad y su conservación; así como honestidad, compromiso y responsabilidad.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso 
    p El tecnólogo en gestión  de granjas  avícolas  está en  capacidad de contribuir al desarrollo social y tecnológico del sector como persona idónea en la implementación de actividades relacionadas con la coordinación,  supervisión y control de procesos productivos en granjas avícolas; administración de recursos de  producción; e  información y comercialización de productos y subproductos avícolas;  actividades  enmarcadas en la normatividad y  preservación  del medio ambiente, con  honestidad, responsabilidad, sentido de pertenencia  y capacidad de liderar trabajo en equipo.
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica

    p Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportada en la utilización de las tecnologías de la información y la comunicación integradas en ambientes virtuales de aprendizaje, que, en todo caso, recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      |Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    ul.lista-ul
        li 
          i.fas.fa-angle-right
          |El instructor - Tutor
        li 
          i.fas.fa-angle-right
          |El entorno
        li 
          i.fas.fa-angle-right
          |Las TIC
        li 
          i.fas.fa-angle-right
          |El trabajo colaborativo










  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
