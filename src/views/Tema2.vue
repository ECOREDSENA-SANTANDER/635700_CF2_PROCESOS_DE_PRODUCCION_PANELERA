<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 2
        h1 Procesos de transferencia de calor en la hornilla panelera 
  
      .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos='fade-down')
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/T2/img-1.png')})`}")
        .bloque-texto-g__texto.p-4.py-lg-5
          p.mb-0 La panela es un edulcorante altamente nutritivo que se elabora concentrando todos los sólidos solubles en agua y en el jugo de caña de azúcar. La panela se diferencia de la azúcar refinada en que contiene, además de sacarosa, glucosa y fructosa, una presencia importante de minerales, grasas, compuestos proteicos y vitaminas, desde el punto de vista nutricional.
      
      p.mb-4 #[b A continuación, se presentan las fases del proceso de producción de panela.]
  
      LineaTiempoC.color-acento-botones.t2.fondo(text-small).p-5(data-aos='fade-down')
        .row.justify-content-around.align-items-center(titulo="Extracción de la materia prima")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-2.png', alt='')            
          .col-lg-8.col-md-12.col-sm-12
            h4 Extracción de la materia prima
            p El corte y transporte de las cañas de azúcar es muy importante, ya que, es la etapa previa al inicio del proceso productivo de panela y al mismo tiempo, es necesario cortar las cañas en el punto óptimo de madurez para garantizar la excelente calidad de la panela.
            p La caña de azúcar está madura cuando la concentración de azúcar en la base y el final del tallo es similar. El tiempo de maduración de la caña de azúcar desde el momento de la siembra o entre cortes depende de la variedad, las condiciones climáticas y, sobre todo, la altitud del campo de cultivo.           
        .row.justify-content-around.align-items-center(titulo="Recepción de la materia prima")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-3.png', alt='')            
          .col-lg-8.col-md-12.col-sm-12
            h4 Recepción de la materia prima
            p Esta etapa se denomina preparación de caña, y consiste en almacenar suficiente caña para permitir el funcionamiento continuo del quemador. Se recomienda cubrir el área con un piso de cemento (en el techo) para evitar que el lodo se pegue a la caña, lo que puede afectar la calidad de la panela. 
            p Un dato útil es que 1 tonelada de tubería ocupa un área de aproximadamente 2 m#[sup 3], o 1 m#[sup 2] x 2 m de alto.
        .row.justify-content-around.align-items-center(titulo="Molienda")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-4.png', alt='')
          .col-lg-8.col-md-12.col-sm-12
            h4 Molienda
            p Esta es la primera parte del proceso donde la caña de azúcar se pasa entre los rodillos o martillos de un molino para obtener el jugo de caña de azúcar y un residuo sólido llamado bagazo verde que contiene 50 – 60 % de humedad. 
            p La industria panelera utiliza un proceso de extracción en seco. Es decir, el proceso de trituración se realiza sin añadir agua.  
        .row.justify-content-around.align-items-center(titulo="Prelimpieza")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-5.png', alt='')                  
          .col-lg-8.col-md-12.col-sm-12
            h4 Prelimpieza
            p El jugo crudo obtenido durante el proceso de molienda, o guarapo, es un pre-prensado, elemento compuesto principalmente por bagazo, caña de azúcar, tierra, sobrantes de materia en suspensión, que tiene la función de retener las impurezas dispersas en el jugo, pasar por el limpiador, sustancias, lodos y sustancias precursoras del color. 
            p Los prelimpiadores funcionan separando las impurezas del jugo debido a las diferencias de densidad. La separación en frío, antes del inicio del proceso, evita que los precursores de colorantes se liberen en el jugo por exposición al calor, afectando negativamente la presentación de los azúcares orgánicos. Este proceso se repite hasta que el jugo esté completamente limpio, garantizando mejores productos.  
        .row.justify-content-around.align-items-center(titulo="Almacenamiento de los jugos")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-6.png', alt='')                  
          .col-lg-8.col-md-12.col-sm-12
            h4 Almacenamiento de los jugos
            p.mb-4 Consiste en recolectar el jugo pre lavado en tanques de almacenamiento o colectores de acero inoxidable. El paso del jugo almacenado al clarificador es por gravedad, por lo que es importante que el colector quede arriba del clarificador.  
        .row.justify-content-around.align-items-center(titulo="Clarificación")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-7.png', alt='')                  
          .col-lg-8.col-md-12.col-sm-12
            h4 Clarificación
            p La etapa de clarificación se realiza, tradicionalmente, precalentando el calor generado en los quemadores en combinación sin evaporación y alcalinizando el jugo de caña de azúcar mediante la adición de aditivos básicos a base de corteza vegetal como el guásimo, cadillo, etc. 
            p En algunos lugares se utiliza la ceniza de la cascarilla del café. La clarificación se realiza por flotación. En esta etapa, la cachaza se elimina en forma de burbujas que se forman en la superficie del jugo, lo que garantiza un producto más puro y claro.
            p La literatura sugiere aumentar la temperatura del jugo en el rango de 1.5 - 2.5 °C / min. Esto permite que los contaminantes floculan debido al efecto combinado de la temperatura, el tiempo de clarificación y el floculante o aglutinante. Es importante tener en cuenta que el tiempo de residencia del jugo en la sartén después de la clarificación debe ser de 1,5 a 2 horas.
            p Uno de los factores más importantes a controlar al hacer panela es la acidez del jugo. Para medir este factor se utiliza el pH (0 - 7 soluciones ácidas y 7-14 soluciones básicas). El objetivo es trabajar a un pH neutro (7) que no destruya los azúcares reductores presentes y evite la descomposición o inversión de la sacarosa en azúcares reductores (glucosa y fructosa).  
        .row.justify-content-around.align-items-center(titulo="Evaporación y concentración")
          .col-lg-3.col-md-6.col-12.mb-4.lg-00
            img(src='@/assets/curso/temas/T2/img-8.png', alt='')            
          .col-lg-8.col-md-12.col-sm-12
            h4 Evaporación y concentración
            p Al final de la refinación del jugo de caña de azúcar, el contenido de agua se evapora. Esto aumenta la concentración de azúcar hasta que alcanza un nivel de sólidos solubles de alrededor de 70 ° Brix, llamado miel.
            p Este proceso se realiza en platos metálicos en módulos de paneles pequeños o en filas de 3 - 4 pailas en módulos grandes. Las pailas aumentan la eficiencia energética, reduce el tiempo de residencia, aumenta la producción y los ingresos de los productores.
            p En la etapa de concentración, el jugo ya evaporado se concentra evaporando más agua. La diferencia en esta etapa es que se usa menos jugo y que la sacarosa se remueve constantemente para evitar que se queme y se pegue a las paredes de la olla.  
        .row.justify-content-around.align-items-center(titulo="Punteo")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-9.png', alt='')                    
          .col-lg-8.col-md-12.col-sm-12
            h4 Punteo
            p Esta parte del proceso consiste en la evaporación casi completa del agua. Con ello se consigue la mayor concentración de sólidos alcanzando valores superiores a los 90 ° Brix.
            p Un indicador técnico es el punto de ebullición de la miel, que debe llegar a unos 127 °C para la panela granular. Esta temperatura puede variar hasta 2 °C dependiendo de la altitud y la pureza de la miel.
            p Sin equipo de control, el módulo panelero se basa en la observación de propiedades específicas como la viscosidad y la adhesión de la miel.  
        .row.justify-content-around.align-items-center(titulo="Cristalización y enfriamiento")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-10.png', alt='')                    
          .col-lg-8.col-md-12.col-sm-12
            h4 Cristalización y enfriamiento
            p En esta etapa se bate la miel y cuando llega al punto de panela se retira del fogón y se remueve con un batidor de acero inoxidable en un recipiente llamado cazo. 
            p Una vez encontrado el punto, se deja enfriar, batiéndolo por 20 minutos, logrando su enfriamiento y acto seguido se transfiere a las gabelas que pueden ser de 1 libra o de 1 kilo.
            p Al pasar 20 minutos, ya la panela se ha cristalizado, desarman las gabelas y la panela ya se encuentra lista para ser empacada, sin antes dejar enfriar.  
        .row.justify-content-around.align-items-center(titulo="Tamizado")
          .col-lg-3.col-md-6.col-12.mb-4.lg-0
            img(src='@/assets/curso/temas/T2/img-11.png', alt='')                    
          .col-lg-8.col-md-12.col-sm-12
            h4 Tamizado
            p El único caso en que es necesario este paso es en la producción de panela granulada, proceso que consiste en tamizar la panela después de la molienda para obtener un granulado uniforme. 
            p El residuo del tamiz se procesa nuevamente y se envía a evaporación.
  
  
      Separador
  
      #t_2_1.titulo-segundo.color-acento-contenido.mb-5(data-aos="fade-right")
        h2 2.1.	Hornilla panelera
  
      p.mb-54 El horno para hacer panela, comúnmente llamado quemador #[b panelero], es un subsistema, dispositivo o equipo en un ingenio azucarero que remueve la mayoría de las impurezas y evapora el agua del jugo de la caña de azúcar para concentrar los sólidos solubles, principalmente azúcar, hasta "punto de la panela". La energía utilizada para calentar el jugo y evaporar el agua proviene del bagazo que se produce al triturar la caña de azúcar.
      
      .row.justify-content-around.align-items-center.mb-5(data-aos="fade-down")
        .col-lg-10
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 2] #[br] #[i Diagrama en perspectiva de un trapiche panelero]
          figure
            img.mb-3(src='@/assets/curso/temas/T2/fig2.svg', alt='La imagen ilustra en perspectiva el diagrama de un trapiche panelero y los diferentes pasos que se surten en la transformación de la caña en panela.')
            figcaption Nota. Adaptada de Programa de procesos Agroindustriales. CORPOICA- C.I. Tibaitatá (2011).
  
      p.mb-5 La mayoría de los ingenios azucareros trabajan con un sistema de “evaporación abierta y fuego directo”. Está abierto porque el evaporador (olla) está en contacto directo con los gases de combustión, por lo que el jugo hierve a la presión atmosférica local y tiene llama abierta.
      
      p.mb-4 #[b A continuación, se presentan las partes que componen una hornilla panelera.]
  
      ImagenInfografica.color-acento-botones.mb-5(data-aos="fade-down")
        template(v-slot:imagen)
          figure
            img(src='@/assets/curso/temas/T2/infog.svg', alt='')              
        .tarjeta.tarjeta-amarillo.p-3.p-md-4(x="10%" y="62%" numero="1")
          .h5.mb-2 Cámara de combustión
          p Una cavidad en la parte delantera del quemador donde se quema bagazo u otro combustible.
          img.px-md-4.px-5(src='@/assets/curso/temas/T2/img-14.svg', alt='')  
        .tarjeta.tarjeta-amarillo.p-3.p-md-4(x="3%" y="100%" numero="2")
          .h5.mb-2 Cenicero
          p El cenicero es el compartimento o espacio justo debajo de la parrilla. 
          img.px-md-4.px-5(src='@/assets/curso/temas/T2/img-15.svg', alt='')  
        .tarjeta.tarjeta-amarillo.p-3.p-md-4(x="7%" y="83%" numero="3")
          .h5.mb-2 Puerta de alimentación
          p Una abertura para que el panelero inserte el bagazo y encienda fuego. 
          img.px-md-4.px-5(src='@/assets/curso/temas/T2/img-16.svg', alt='')  
        .tarjeta.tarjeta-amarillo.p-3.p-md-4(x="36%" y="96%" numero="4")
          .h5.mb-2 Parrilla
          p La parrilla consiste en una serie de placas de hierro fundido colocadas horizontalmente una detrás de la otra. 
          img.px-md-4.px-5(src='@/assets/curso/temas/T2/img-17.svg', alt='')  
        .tarjeta.tarjeta-amarillo.p-3.p-md-4(x="49%" y="93%" numero="5")
          .h5.mb-2 Ducto de gases
          p También recibe su nombre de gasoductos, carreteras, barcos, etc.  
          img.px-md-4.px-5(src='@/assets/curso/temas/T2/img-18.svg', alt='')  
        .tarjeta.tarjeta-amarillo.p-3.p-md-4(x="78%" y="27%" numero="6")
          .h5.mb-2 Chimenea
          p Se trata de un conducto de ladrillo o chapa que se encuentra al final del quemador.  
          img.px-md-4.px-5(src='@/assets/curso/temas/T2/img-19.svg', alt='')  
        .tarjeta.tarjeta-amarillo.p-3.p-md-4(x="50%" y="47%" numero="7")
          .h5.mb-2 Pailas
          p Una paila es un recipiente metálico (a veces llamado charola, cacerola o evaporador).  
          img.px-md-4.px-5(src='@/assets/curso/temas/T2/img-20.svg', alt='')
      figcaption.mb-5 Nota. Adaptada de Programa de procesos Agroindustriales. CORPOICA- C.I. Tibaitatá (2011).
  
      ol.lista-ol--cuadro.mb-4.t2(data-aos="fade-right")
        li
          .lista-ol--cuadro__vineta.fcc
            span 
          span.mb-0.t-nar #[b Tipos de cámaras de combustión]
      
      .row.justify-content-center.mb-5.t2
        .col-lg-9.col-md-12.col-sm-12(data-aos="fade-right")
          TabsA.color-secundario.mb-5
            .tarjeta.color-acordeones.p-4(titulo="Plana")
              p En las cámaras convencionales, la superficie de la parrilla es demasiado grande, lo que permite que el aire falso enfríe el gas, lo que resulta en bajas temperaturas de combustión (850 °C, humedad del bagazo de 30 °C). Además, la superficie relativamente fría de la olla está directamente en la cámara, lo que termina en una combustión incompleta y un alto porcentaje de CO (6-7 %).                            
            .tarjeta.color-acordeones.p-4(titulo="Plana-Cimpa")  
              p Esta cámara es un diseño mejorado de la cámara tradicional, donde el bagazo se quema lejos de la primera bandeja y alcanza una alta temperatura de combustión de casi 950 °C. Este tipo de cámara se caracteriza por la combustión de bagazo con una humedad inferior al 30 % (base húmeda, b.h.) y un exceso de aire de casi el 60 %.
              p Las dimensiones de la cámara dependen de la energía requerida para el proceso y la geometría de la parrilla estándar. En general son más largas que anchas y las dimensiones son la velocidad del gas (3-5 m/s debajo de la primera cubeta y 7-10 m/s debajo de la última cubeta) y el máximo medio La 4ª o 5ª cubeta dada la longitud de la llama del bagazo alcanzando los 6 metros.              
            .tarjeta.color-acordeones.p-4(titulo="Ward-CIMPA")
              p Este tipo de cámara tiene un diseño especial que aumenta la combustión y la eficiencia del proceso. Esto se debe a una mejor estabilidad en términos de temperatura y potencia a lo largo del tiempo. Este tipo de cámara puede alcanzar temperaturas cercanas a los 1200 °C y, cuando se le suministra un 60 % de exceso de aire y una humedad promedio de 40 bagazo, produce un 3 % en volumen de monóxido de carbono y un 14 % en volumen de dióxido de carbono. 
              p También cuenta con dos características especiales. Primero, hay lámparas que precalientan y secan el bagazo antes de quemarlo. 
              p.mb-0 En esta tolva, la humedad contenida en el bagazo se evapora de las paredes de la cámara bajo la acción de la energía radiante. Esta característica permite la introducción de bagazo con un contenido de humedad de casi 45 % (b.h.). En segundo lugar, el aire necesario para la combustión se suministra en dos corrientes. Uno es el aire primario que fluye a través de la parrilla (un total de 70 litros de aire) y el 30 % restante se alimenta como aire secundario a la cámara por encima de la combustión de los volátiles en el lecho de bagazo (Gordillo & García, 1992).        
        .col-lg-3.d-none.d-lg-block(data-aos="fade-left")
          img(src='@/assets/curso/temas/T2/img-26.png')
    
      ol.lista-ol--cuadro.mb-4.t2(data-aos="fade-right")
        li
          .lista-ol--cuadro__vineta.fcc
            span 
          span.mb-0.t-nar #[b Tipos de pailas]
  
      .row.justify-content-center
        .col-lg-4.col-md-5.col-8(data-aos='fade-right')
          img(src='@/assets/curso/temas/T2/img-23.png')
        .col-lg-8.col-md-12.col-sm-12(data-aos='fade-left')
          AcordionA(tipo="a" clase-tarjeta="faa")
            .row.justify-content-center(titulo="Paila semicilíndrica")
              .col-md-11
                p Se utiliza una cubeta semicilíndrica cuando el paso del jugo se realiza manualmente. Tiene la ventaja de poder reducir el ancho del quemador con la misma superficie de transferencia de calor que una olla plana. Están en la zona más caliente del quemador.                
            .row.justify-content-center(titulo="Paila semiesférica ")
              .col-md-11
                p La cuba hemisférica se utiliza cuando el paso del jugo se hace de forma manual y en la parte final de evaporación y concentración. También se usa cuando la relación entre la superficie de transferencia de calor y el volumen de la olla es baja y la transferencia manual de jugo no requiere mucho esfuerzo.              
            .row.justify-content-center(titulo="Pailas planas y aleteadas")
              .col-md-11
                p Son más eficientes en términos de transferencia de calor que las sartenes planas. Esto se debe a que el área de superficie adicional proporcionada por las nervaduras aumenta el área expuesta al líquido, aumentando así el flujo de calor por convección de los gases de combustión a la caña. 
                p Esto permite longitudes de quemador más cortas para la salida de calor requerida. Tenga en cuenta que se deben realizar cálculos para determinar las dimensiones y el número de las nervaduras para lograr un rendimiento óptimo. Suelen colocarse en la zona fría del quemador y requieren una mayor área de transferencia para asegurar el flujo de calor requerido.  
            .row.justify-content-center(titulo="Pailas pilotubulares pirotubulares")
              .col-md-11
                p Al igual que con las bandejas acanaladas, el uso de revestimientos se limita a la primera parte de la etapa de evaporación. Esto se debe a que es más eficiente en la zona fría de la cámara de combustión donde el mecanismo dominante de transferencia de calor es la convección. Debido a la alta relación entre el área de transferencia de calor y el volumen, la longitud de la bandeja se puede reducir en comparación con las bandejas planas y con aletas planas con el mismo flujo de calor y tiempo de residencia.
      
      
      Separador
      #t_2_2.titulo-segundo.color-acento-contenido.mb-5
        h2 2.2.	Seguridad y salud en el trabajo
  
      .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos='fade-down')
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/T2/img-24.png')})`}"
        )
        .bloque-texto-g__texto.p-4.py-lg-5
          p.mb-0 Los temas de seguridad y salud en el trabajo han cobrado mucha importancia en Colombia, esto se debe a que a lo largo de los años  progresivamente se han hecho cumplir leyes, normas y reglamentos que son más que beneficiosos para la empresa y sus empleados. Es deber de los empresarios velar por el cumplimiento de esta normativa, por la seguridad y salud de los trabajadores y evitar riesgos y peligros que tengan efectos sobre la salud.
      
      .tarjeta.color-secundario.p-3.mb-5(data-aos='fade-down')
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-1
            img(src="@/assets/curso/temas/T2/img-25.svg")
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                h3.texto-negro.mb-1 Profundice en el estudio de este tema
                p.texto-negro.mb-0  Consulte el archivo Anexo 3_ Seguridad y salud en el trabajo.pdf que se encuentra en la carpeta Anexos, para ampliar la información.   
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Anexo_3.pdf')" target="_blank")
                  span Descargar
                  i.fas.fa-file-download
  
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
