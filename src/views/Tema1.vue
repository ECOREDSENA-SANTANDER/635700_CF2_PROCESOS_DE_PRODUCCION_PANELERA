<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
      .titulo-principal.color-acento-contenido
        .titulo-principal__numero
          span 1
        h1 Combustión utilizados en las hornillas
      
      .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos="fade-down")
        .bloque-texto-g__img(data-aos='fade-right')(
          :style="{'background-image': `url(${require('@/assets/curso/temas/T1/img-1.png')})`}"
        )
        .bloque-texto-g__texto.p-4.py-lg-5
          p.mb-0 La combustión es el proceso por el cual el combustible reacciona con el oxígeno contenido en el aire para liberar energía interna. Luego, se presentan las propiedades y proceso de combustión del combustible utilizado en el quemador.
      
      h3.mb-5 Combustible para quemadores de clarificación y quemadores evaporativos
      
      .row.justify-content-around.align-items-center.mb-4
        .col-8.col-md-4.col-lg-2(data-aos='fade-right')
          img(src='@/assets/curso/temas/T1/img-2.svg')
        .col-sm-12.col-md-12.col-lg-10(data-aos='fade-left')
          .row.justify-content-between.align-items-center
            p Para la concentración de los jugos en las hornillas paneleras, se emplea, como combustible, el bagazo de caña; sin embargo, en algunos casos, para suplir el déficit de bagazo, se hace necesario agregar otros combustibles adicionales como la guadua, la leña, el carbón mineral, el caucho proveniente de llantas usadas, el ACPM, la cascarilla de café o arroz. (Durán, s.f.).
            p El bagazo se presenta como combustible tanto para el clarificador como para el quemador evaporativo, y también, se realiza un análisis de este para determinar la cantidad de calor disponible. 
                
      TabsC.color-acento-contenido.mb-5(data-aos='fade-down')
        .py-3.py-md-4(titulo="Bagazo")
          .row.align-items-center.justify-content-around
            .col-12.col-md-6.col-lg-4.mb-3.mb-lg-0
              img(data-aos='fade-right')(src='@/assets/curso/temas/T1/img-3.png')
            .col-sm-12.col-md-12.col-lg-7
              p Es el residuo fibroso que queda de la caña de azúcar después de haber sido molida para extraer el jugo. Se guarda en una choza llamada bagacera cerca al trapiche y al quemador.
              p En los pequeños ingenios azucareros, este almacenamiento se acumula en pilas individuales de 2-3 metros de altura, lo que requiere un uso juicioso, tanto de la superficie disponible en la bagacera, como del flujo de aire que promueve el secado. Así que lo secamos durante 8-20 días para su posterior uso en el horno. En el trapiche grande, hay una gran bagacera contigua al lugar. En estas, el bagazo se almacena en montones formados por la descarga de canastos recolectados del molino. (Vallejo, Peña & Mora, 1995).         
        .py-3.py-md-4(titulo="Composición física")
          .row.align-items-center.justify-content-around
            .col-12.col-md-6.col-lg-4.mb-3.mb-lg-0
              img(data-aos='fade-right')(src='@/assets/curso/temas/T1/img-4.png')
            .col-sm-12.col-md-12.col-lg-7
              p A pesar de la variedad de plantas de trituración y de las máquinas utilizadas para ellas, la composición física del bagazo varía dentro de límites muy estrechos. En términos de exotermia, la característica más importante del bagazo es su contenido de humedad. 
              p El contenido de humedad del bagazo, en molinos de bajo rendimiento, es de alrededor del 50 % y en molinos de buen rendimiento, alrededor del 40 %. Los valores más comunes para el contenido de humedad varían entre 42 % y 48 % y, en todos los casos, no se considera incorrecto asumir un contenido de humedad del 45 %. (Hugot, 1982, p. 617).
              p Además del agua, el bagazo contiene:
              .col-sm.mb-5.mb-sm-0
                ol.lista-ol--cuadro.fa-lista
                  li 
                    .lista-ol--cuadro__vineta.fcp
                      span.fw-bold a.
                    | Un material insoluble, principalmente celulosa, que forma las fibras de bagazo. El contenido de fibra en la industria panelera es del 35 %.
                  li 
                    .lista-ol--cuadro__vineta.fcp
                      span.fw-bold b.
                    | Sustancia que se disuelve en agua (jugo de frutas) y está compuesta de azúcares e impurezas. Estas sustancias ocurren a una tasa de 5 - 10 %.  
        .py-3.py-md-4(titulo="Cantidad de Bagazo")
          .row.align-items-center.justify-content-around
            .col-12.col-md-6.col-lg-4.mb-3.mb-lg-0
              figure
                img(data-aos='fade-right')(src='@/assets/curso/temas/T1/img-5.png')
            .col-sm-12.col-md-12.col-lg-7
              p La cantidad de bagazo disponible en un ingenio panelero depende del tipo y calidad de la caña de azúcar y de la eficiencia del ingenio en la extracción del jugo de caña. Generalmente, la cantidad de bagazo está entre el 25 % y el 45 % del peso de la caña molida. 250 y 450 KG por tonelada de caña de azúcar procesada.
              p El peso de bagazo recuperado es inversamente proporcional a la eficiencia de extracción del molino. Es decir, cuanto más jugo se extrae, menos bagazo se recupera, pero como resultado, el bagazo también tiene menor contenido de humedad, lo que facilita la combustión.          
        .py-3.py-md-4(titulo="Composición química")
          .row.align-items-center.justify-content-around
            .col-12.col-md-6.col-lg-4.mb-3.mb-lg-0
              figure
                img(data-aos='fade-right')(src='@/assets/curso/temas/T1/img-6.png')
            .col-sm-12.col-md-12.col-lg-7
              p La composición química promedio de la fibra seca de bagazo es:
              p.mb-0 #[b C:] 47 %
              p.mb-0 #[b H:] 6,5 %
              p.mb-0 #[b O:] 44 %
              p.mb-4 #[b Ɛ:] 2,5 %
              p Donde Ɛ. es el contenido de cenizas  
        .py-3.py-md-4(titulo="Valor calorífico")
          .row.align-items-center.justify-content-around
            .col-12.col-md-6.col-lg-4.mb-3.mb-lg-0
              figure
                img(data-aos='fade-right')(src='@/assets/curso/temas/T1/img-7.png')
            .col-sm-12.col-md-12.col-lg-7
              p El poder calorífico (CV) es la cantidad de calor que se puede producir al quemar una unidad de peso del combustible en cuestión. Hay dos tipos de poder calorífico: alto poder calorífico y bajo poder calorífico.              
              .tarjeta.color-secundario.p-3
                .row.justify-content-around.align-items-center
                  .col
                    .row.justify-content-between.align-items-center
                      .col.mb-3.mb-sm-0
                        p.mb-0 Para ampliar la información relacionada con los valores caloríficos del bagazo de la caña, consulte el archivo Anexo 1_Valor calorífico del bagazo.pdf, que se encuentra en la carpeta Anexos, para ampliar la información
                      .col-sm-auto
                        a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")
                          span Descargar
                          i.fas.fa-file-download
              
      h3.mb-4 Combustible utilizado en las hornillas de concentración
  
      p Combustible sólido de color negro o negro parduzco, producido por la descomposición de la vegetación vieja, por ausencia de aire, bajo las influencias bioquímicas, humedad, presión y calor. Se compone esencialmente de carbono, hidrógeno, oxígeno y pequeñas cantidades de nitrógeno y azufre.
      
      .tarjeta.color-secundario.p-4.mb-5(data-aos="fade")
        .row.justify-content-around.align-items-center
          .col-3.col-sm-2.col-lg-1.mb-2.mb-lg-0
            img(src='@/assets/curso/temas/T1/img-8.svg', alt='')
          .col
            .row.justify-content-between.align-items-center
              .col.mb-3.mb-sm-0
                p.mb-3.mb-lg-0 Consulte el archivo Anexo 2_Infografía_generalidades_sobre_el_carbón.pdf que se encuentra en la carpeta Anexos, para ampliar la información.
              .col-sm-auto
                a.boton.color-acento-botones.texto-blanco(:href="obtenerLink('/downloads/Anexo_2.pdf')" target="_blank")
                  span.texto-blanco Descargar
                  i.fas.fa-file-download



      h3.mb-4 Combustión
  
      .bloque-texto-g.color-acento-contenido.p-3.p-sm-4.p-md-5.mb-5(data-aos='fade-down')
        .bloque-texto-g__img(
          :style="{'background-image': `url(${require('@/assets/curso/temas/T1/img-9.png')})`}"
        )
        .bloque-texto-g__texto.p-4.py-lg-5
          p.mb-0 La combustión es una reacción química que se produce entre las moléculas de oxígeno y un material oxidable, por lo tanto, es un proceso de oxidación rápido en el que se libera energía en forma de calor.
        
      p.mb-4 A continuación, se presentan algunos componentes, reacciones, propiedades de la combustión y cómo esta se da con el bagazo de la caña.
    
      .tarjeta.bg-t1.p-4(data-aos="fade-down")
        PasosB.color-secundario
          .row.justify-content-center(titulo="")
            .col-sm-12.col-md-12.col-lg-5.mb-4.mb-md-0
              h3.mb-3 Composición del aire 
              p El aire es una mezcla de gases que se forman en la atmósfera; la composición del aire seco es la siguiente:          
            .col-sm-12.col-md-12.col-lg-6
              .tabla-a.tabla-t1
                table  
                  caption Nota. Tomado de Hugot (1974). 
                  thead  
                    tr  
                      th Elementos  
                      th % en peso  
                      th % en volumen  
                  tbody  
                    tr  
                      td Oxígeno  
                      td 23,15  
                      td 20,84  
                    tr  
                      td Nitrógeno y gases inertes  
                      td 76,85  
                      td 79,16  
          .row.justify-content-center(titulo="")
            .col-sm-12.col-md-12.col-lg-5.mb-4.mb-md-0
              h3.mb-3 Reacciones de la combustión
              p Los elementos combustibles del bagazo son el carbono y el hidrógeno; además de estos elementos, también está presente en el carbón una pequeña cantidad de azufre. Cuando estos reaccionan con el oxígeno, producen:  
            .col-sm-12.col-md-12.col-lg-6
              .tabla-a.tabla-t1
                table  
                  thead  
                    tr  
                      th Elementos combustibles  
                      th Resultado de la combustión  
                  tbody
                    tr  
                      td C + O#[sub 2] 
                      td CO#[sub 2]  
                    tr  
                      td 12 g + 32 g  
                      td 44 g  
                    tr  
                      td 1 + 2,67  
                      td 3,67  
                    tr  
                      td H#[sub 2] + O  
                      td H#[sub 2]O  
                    tr  
                      td 2 g + 16 g  
                      td 18 g  
                    tr  
                      td 1 + 8  
                      td 9  
                    tr  
                      td S + O#[sub 2] 
                      td SO#[sub 2]  
                    tr  
                      td 32 g + 32 g  
                      td 64 g  
                    tr  
                      td 1 + 1  
                      td 2              
          .row.justify-content-center(titulo="")
            .col-sm-12.col-md-12.col-lg-4.mb-4.mb-md-0
              h3.mb-3 Caracterización de los productos gaseosos de la combustión
              p La tabla muestra los principales componentes de los gases de combustión y sus principales propiedades.          
            .col-sm-12.col-md-12.col-lg-8
              .tarjeta.bg-white.p-3
                .tabla-a.tabla-t1
                  table  
                    caption Nota. Tomado de Hugot (1974). 
                    thead  
                      tr  
                        th(rowspan="2") Elemento  
                        th(rowspan="2") Peso Molecular  
                        th(rowspan="2") Constante R  
                        th(rowspan="2") p.e. en kg/m² a 0° / 760  
                        th(rowspan="2") v.e. en m³/kg a 0° / 760  
                        th(colspan="2") Calor específico medio a baja presión constante para el intervalo:  
                      tr  
                        th 0° - 100° 
                        th 0° - 1000° 
                    tbody  
                      tr  
                        td CO#[sub 2]  
                        td 44  
                        td 19,28  
                        td 1,963  
                        td 0,509  
                        td 0,21  
                        td 0,28  
                      tr  
                        td H#[sub 2]  
                        td 18  
                        td 47,11  
                        td 0,804  
                        td 1,244  
                        td 0,48  
                        td 0,62  
                      tr  
                        td N#[sub 2]  
                        td 28  
                        td 30,20  
                        td 1,252  
                        td 0,800  
                        td 0,74  
                        td 0,87  
                      tr  
                        td O#[sub 2]  
                        td 32  
                        td 26,50  
                        td 1,428  
                        td 0,700  
                        td 0,21  
                        td 0,28  
                      tr  
                        td CO  
                        td 28  
                        td 30,29  
                        td 1,251  
                        td 0,800  
                        td 0,24  
                        td 0,29  
                      tr  
                        td AIRE  
                        td 29  
                        td 29,27  
                        td 1,293  
                        td 0,773  
                        td 0,24  
                        td 0,30  
          .row.justify-content-center.align-items-center(titulo="")
            .col-sm-12.col-md-12.col-lg-6.mb-4.mb-md-0
              h3.mb-3 Combustión de bagazo seco sin exceso de aire
              p.mb-3 Para calcular la cantidad de oxígeno necesaria para la combustión se tiene en cuenta la composición química del bagazo y el porcentaje obtenido por las reacciones anteriores.
              p.mb-0 #[b Ejemplo:]
              p.mb-0 C = 0,470 kg×2,67 = 1,250 Kg O#[sub 2] H#[sub 2] = 0,065 kg ×8 = 0,520 Kg O#[sub 2]  
              p.mb-3 Total  = 1770 Kg O#[sub 2]
              p.mb-0 #[b El bagazo contiene] 0,440 Kg O#[sub 2]  
              p.mb-4 El aire debe ser proporcional, es decir, es igual a 1,330 Kg O#[sub 2]
              .bga-1.mb-4.p-3
                p.mb-0 #[b El cálculo del nitrógeno se hace de la siguiente manera:]
                p.mb-0 1,330 (Kg O#[sub 2])(Kg CO)×(76,85 Kg N#[sub 2])/(23,15 Kg O#[sub 2]) = 4,420 (Kg N#[sub 2])/(Kg CO)
                p.mb-0 La masa total del aire necesario por Kg de combustible es igual a 5,750 Kg  
              .bga-1.mb-4.p-3
                p.mb-0 #[b La cantidad de agua formada equivale a:]
                p.mb-0 0,065 + 0,520 = 0,585 Kg H#[sub 2]O
                p.mb-0 Pacheco , A. N. U. A. R. (2016). 
            .col-12.col-md-6.col-lg-5
              img(src='@/assets/curso/temas/T1/img-14.png', alt='')  
          .row.justify-content-center.align-items-center(titulo="")
            .col-sm-12.col-md-12.col-lg-6.mb-4.mb-md-0
              h3.mb-3 Combustión de bagazo húmedo sin exceso de aire
              p.mb-5 Dado que el bagazo utilizado durante la combustión tiene un contenido de agua, para calcular la masa de aire teórica, o requerida por kilogramo de bagazo, se puede usar la siguiente fórmula:
              .bga-1.mb-4.p-3
                p.mb-0 #[b m#[sup 1]=5,75 (I-w)[Kg]]
              p.mb-2 #[b Donde:]
              p.mb-1 #[b m#[sup 1] = ] Masa de aire teórico empleado por Kg de bagazo
              p #[b w = ] Humedad del bagazo con relación a la unidad          
            .col-12.col-md-6.col-lg-5
              img(src='@/assets/curso/temas/T1/img-15.png', alt='')          
          .row.justify-content-center.align-items-center(titulo="")
            .col-sm-12.col-md-12.col-lg-6.mb-4.mb-md-0
              h3.mb-3 Combustión de carbón sin exceso de aire.
              p.mb-4 Para calcular la cantidad de oxígeno necesaria para la combustión, se debe tener en cuenta la composición química del carbón y las proporciones especificadas en la reacción anterior.
              p.mb-1 #[b Ejemplo]
              p.mb-0 C = 0,685 Kg * 2,67   = 1, 829 Kg O#[sub 2]
              p.mb-0 H#[sub 2] = 0,040 Kg * 8  	=  0,320 Kg O#[sub 2]
              p.mb-2 S   = 0,009 Kg * 1  	=  0,009 Kg O#[sub 2]
              p.mb-1 #[b Total] = 2,158 Kg O#[sub 2]
              p.mb-0 El carbón contiene 0,076 Kg O#[sub 2]
              p.mb-4 El aire debe proporcionar   = 2,082 Kg O#[sub 2]
              .bga-1.mb-4.p-3
                p.mb-1 #[b Para calcular el nitrógeno ]
                p.mb-0 2,082 (Kg O#[sub 2])/(Kg CO) * (76,85 Kg N#[sub 2])/(23,15 Kg O#[sub 2]) = 6,915 (Kg N#[sub 2])/(Kg CO)
                p.mb-0 Masa total del aire necesario por Kg de combustible = 8,997 Kg.          
            .col-12.col-md-6.col-lg-5
              img(src='@/assets/curso/temas/T1/img-16.png', alt='')  
          .row.justify-content-center.align-items-center(titulo="")
            .col-sm-12.col-md-12.col-lg-6.mb-4.mb-md-0
              h3.mb- Combustión con exceso de aire
              p.mb-4 En la práctica, no es posible suministrar solo la cantidad de aire teóricamente necesaria para quemar el combustible. Lograr una combustión completa, sin dejar residuos, sin quemar y convertir todo el carbono en CO#[sub 2] requiere un exceso de suministro de aire. De hecho, cuando parte del carbono se quema para formar solo CO, se pierde una cantidad significativa de calor.
              p.mb-2 Calcule la cantidad real de aire consumido por kilogramo de combustible húmedo usando la siguiente fórmula:
              p.mb-4 Ma#[sup r]  = mgh - m#[sub ∞]
              .bga-1.mb-4.p-3
                p.mb-2 #[b Donde:]
                p.mb-1 #[b Ma#[sup r] = ]masa del aire empleado por Kg de combustibles
                p.mb-1 #[b mgh = ]masa de los productos gaseosos de la combustión, en Kg
                p.mb-0 #[b m#[sub ∞] = ]masa del combustible empleada, en Kg
            .col-12.col-md-6.col-lg-5
              img(src='@/assets/curso/temas/T1/img-17.png', alt='')              
          .row.justify-content-center(titulo="")
            .col-sm-12.col-md-12.col-lg-5.mb-4.mb-md-0
              h3.mb-3 Exceso de aire 
              p.mb-4 La relación entre el aire suministrado a la combustión y el aire teóricamente necesario para quemar 1 kg de combustible. Para quemadores, se recomienda que el exceso de aire esté en el rango de 1.4 a 1.6 (CIMPA, 1992, p.61). Un exceso mayor enfría los gases de combustión, un exceso menor puede provocar una mala combustión.
              .bga-1.mb-4.p-3
                p.mb-1 #[b Para su cálculo se utiliza la siguiente fórmula:]
                p.mb-0 m=(mar)/mat
              p Donde m es igual al exceso de aire.
            .col-12.col-md-6.col-lg-6
              img(src='@/assets/curso/temas/T1/img-18.png', alt='')  
          .row.justify-content-center(titulo="")
            .col-sm-12.col-md-12.col-lg-5.mb-4.mb-md-0
              h3.mb-3 Contenido de CO#[sub 2] en los gases de salida
              p.mb-4 Dado que, el contenido de carbono del bagazo es constante (47 %), la cantidad de CO#[sub 2] que se produce al quemar 1 kilogramo de bagazo seco también es constante. Cuando se usa la cantidad de aire requerida teóricamente, el contenido de CO#[sub 2] en los gases de escape se maximiza, mientras que, con el exceso de aire, la cantidad de CO#[sub 2] en un volumen de aire dado aumenta al aumentar el exceso de aire y permanece constante. El porcentaje de CO#[sub 2] disminuye al aumentar el exceso de aire.
              p.mb-1 #[b El aire extra es lo mismo a :] m =  ( 0,196)/ɻ   
              p.mb-1 #[b Donde:]
              p.mb-1 #[b m]= (Masa del aire empleado)/ (Masa del aire estrictamente necesario) 
              p.mb-1 ɻ = Contenido de CO#[sub 2] de los gases secos con relación a la unidad.  
              p.mb-1 En la práctica se ha encontrado que las mejores condiciones para quemar bagazo en quemadores son cuando el exceso de aire varía entre 40 % y 60 % del aire teórico.
              p.mb-1 #[b La tabla muestra algunos valores correlativos entre ɻ y m.]                                      
            .col-sm-12.col-md-12.col-lg-6
              p.mb-4 Correlación entre el contenido CO#[sub 2] de los gases de escape y el exceso de aire.
              .tarjeta.bg-white.p-1
                .tabla-a.tabla-peq.est-t1
                  table  
                    caption Nota. Tomado de Hugot (1974).
                    thead  
                      tr  
                        th y  
                        th 0,06  
                        th 0,07  
                        th 0,08  
                        th 0,09  
                        th 0,10  
                        th 0,11  
                        th 0,12  
                        th 0,13  
                        th 0,14  
                        th 0,15  
                        th 0,16  
                        th 0,17  
                    tbody  
                      tr  
                        td m  
                        td 3,27  
                        td 2,80  
                        td 2,45  
                        td 2,18  
                        td 1,96  
                        td 1,78  
                        td 1,63  
                        td 1,51  
                        td 1,40  
                        td 1,30  
                        td 1,22  
                        td 1,15 


      Separador
  
      #t_1_1.titulo-segundo.color-acento-contenido.mb-5(data-aos="fade-right")
        h2 1.1.	Procesos unitarios


      .row.justify-content-center(data-aos='fade')
        .col-12.col-lg-4.col-md-6.mb-3.mb-lg-0.pe-lg-0
          img(src="@/assets/curso/temas/T1/img-20.png")  
        .col-sm-12.col-lg-8.col-md-12.ps-lg-0
          .tarjeta--gris.h-100.p-3.px-lg-4
            p El Estado colombiano llevará a cabo investigación y desarrollo para modelar matemáticamente los procesos energéticos involucrados en la producción de panela y evaluará alternativas para mejorar procesos claves como la extracción (molienda), evaporación y concentración (punteo) del jugo de caña de azúcar en la producción de la panela.
            p Como se puede observar en el diagrama de flujo del proceso de transformación de caña en panela, los procesos unitarios del procesamiento de la caña de azúcar para obtención de panela son:
            .col-sm.mb-5.mb-sm-0
              ol.lista-ol--cuadro.fa-lista
                li 
                  .lista-ol--cuadro__vineta.fcp
                    span 1.
                  | Disposición de la caña de azúcar en la zona de molinos.
                li 
                  .lista-ol--cuadro__vineta.fcp
                    span 2.
                  | Extracción de los jugos utilizando molinos (molienda).
                li 
                  .lista-ol--cuadro__vineta.fcp
                    span 3.
                  | Decantación y clarificación de los jugos.
                li 
                  .lista-ol--cuadro__vineta.fcp
                    span 4.
                  | Evaporación y concentración para obtención de las mieles (jarabe).
                li 
                  .lista-ol--cuadro__vineta.fcp
                    span 5.
                  | Cristalización.
                
      .row.justify-content-center.mt-5.mb-5(data-aos="fade-down")
        .col-12.col-md-12.col-lg-6
          .titulo-sexto.color-acento-contenido
            p.mb-0 #[b Figura 1.] #[br] #[i Diagrama de flujo del proceso de transformación de caña de panela] 
          figure
            img(src='@/assets/curso/temas/T1/4.svg', alt='La imagen ilustra un diagrama de flujo del proceso de transformación de la caña de azúcar en panela. Este diagrama permite identificar puntos de mejora y tomar decisiones para aumentar la productividad. ')
      
      p Aunque el Estado colombiano ha tratado de tecnificar las pequeñas empresas productoras de panela, no se ha logrado acceder a recursos para la reconversión tecnológica de sus hornillas y pailas, gracias a esto, en las unidades de producción de panela, se presentan eventos no deseables:
      
      .row.justify-content-center.t1-tarj.mb-5(data-aos="fade-down")
        .col-lg-6
          .tarjeta-avatar-b.mb-5
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/temas/T1/img-22.svg', alt='')
            .tarjeta
              .p-4
                p.mb-0 Contaminación del aire con gases de combustión y cenizas.
          hr
        .col-lg-6
          .tarjeta-avatar-b.mb-5
            .tarjeta-avatar-b__img
              img(src='@/assets/curso/temas/T1/img-23.svg', alt='')
            .tarjeta
              .p-4
                p.mb-0 Agotamiento de recursos naturales, principalmente madera, para alimentar las hornillas paneleras.
          hr  
        .col-lg-6
          .tarjeta-avatar-b.mb-5
            .tarjeta-avatar-b__img
              figure
                img(src='@/assets/curso/temas/T1/img-24.svg', alt='')
            .tarjeta
              .p-4
                p.mb-0 Contaminación de fuentes de agua con el vertimiento de cachaza y lodo de caña.
          hr  
        .col-lg-6
          .tarjeta-avatar-b.mb-5
            .tarjeta-avatar-b__img
              figure
                img(src='@/assets/curso/temas/T1/img-25.svg', alt='')
            .tarjeta
              .p-4
                p.mb-0 Emisiones atmosféricas como resultado del uso de motores Diésel en los molinos de caña.
          hr  
      
      .row.justify-content-center.align-items-center
        .col-lg-9.col-md-12.col-sm-12 
          .row
            .col-md-12.mb-4.mb-md-0
              .tarjeta.tarjeta-amarillo.p-4.mb-4
                p.mb-0 Debe tenerse en cuenta, que la falta de automatización y control en procesos y operaciones unitarias, genera una inadecuada dosificación de insumos, como el bagazo – suministrado a la cámara de combustión - y las sustancias clarificantes – sobre los jugos. La falta de automatización y de control dificulta la trazabilidad interna de la panela.  
          .row
            .col-md-12.mb-4.mb-md-0
              .tarjeta.tarjeta-amarillo.p-4.mb-4
                p.mb-0 Al no integrarse los procesos unitarios se propicia pérdidas energéticas, pérdida de calor por transferencia a las paredes de la cámara de combustión, la no captura de calor residual al interior del ducto de gases y pérdida de temperatura de los gases expulsados por la chimenea. Se estimó que la pérdida de calor alcanza el 41 %.          
        .col-lg-3.d-none.d-lg-block
          img(src='@/assets/curso/temas/T1/img-26.png')
  
  </template>

<script>
export default {
  name: 'Tema1',
  components: {},
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
