<template lang="pug">
  .curso-main-container.pb-3
    BannerInterno(icono="far fa-question-circle" titulo="Actividad didáctica")
    .container.tarjeta.tarjeta--blanca.p-4.p-md-5
  
      #Actividad                
        <Actividad :cuestionario="cuestionario"/>
  
  </template>

<script>
import Actividad from 'ecored-pkg-fliz/plugin/components/actividad/Actividad.vue'
export default {
  name: 'ActividadDidactica',
  components: {
    Actividad,
  },
  data: () => ({
    cuestionario: {
      tema: 'Generalidades de la carne y sus derivados',
      titulo: 'Cuestionario',
      introduccion:
        '<b>Objetivo:</b> Evaluar y reforzar el conocimiento adquirido sobre los efectos de la temperatura en la producción panelera.',
      barajarPreguntas: false,
      titulo_aprobado: '¡BUEN TRABAJO!',
      titulo_reprobado: 'VUELVA A INTENTARLO',
      preguntas: [
        {
          id: 1,
          texto:
            'La temperatura no juega un papel importante en el control del proceso de producción de panela.',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 2,
          texto:
            'La relación entre temperatura, concentración y pureza de las soluciones de azúcar es una herramienta de control eficaz para la industria panelera ',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: false,
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
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 3,
          texto:
            'A medida que aumenta la concentración de una solución (grados Brix), el punto de ebullición disminuye.',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 4,
          texto:
            'Colombia es uno de los mayores consumidores de panela en el mundo ',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: false,
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
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 5,
          texto:
            'En la cadena productiva de la panela se han identificado cuatro eslabones. ',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 6,
          texto:
            'La temperatura es una variable que no influye en el tratamiento de jugos azucarados. ',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 7,
          texto:
            'La combustión es el proceso donde el combustible reacciona con el nitrógeno del aire. ',
          imagen: require('@/assets/actividad/imagen3.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 8,
          texto:
            'En las hornillas paneleras se emplea principalmente bagazo de caña como combustible.',
          imagen: require('@/assets/actividad/imagen4.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 9,
          texto:
            'El bagazo es el residuo fibroso que queda después de moler la caña de azúcar. ',
          imagen: require('@/assets/actividad/imagen1.png'),
          barajarRespuestas: true,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: false,
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
        {
          id: 10,
          texto:
            'El contenido de humedad del bagazo en molinos de bajo rendimiento es menor que en molinos de alto rendimiento.',
          imagen: require('@/assets/actividad/imagen2.png'),
          barajarRespuestas: false,
          opciones: [
            {
              id: 'a',
              texto: 'Verdadero',
              esCorrecta: false,
            },
            {
              id: 'b',
              texto: 'Falso',
              esCorrecta: true,
            },
            {
              id: 11,
              texto:
                'La cantidad de bagazo disponible no depende de la eficiencia del ingenio en la extracción del jugo de caña.',
              imagen: require('@/assets/actividad/imagen3.png'),
              barajarRespuestas: false,
              opciones: [
                {
                  id: 'a',
                  texto: 'Verdadero',
                  esCorrecta: false,
                },
                {
                  id: 'b',
                  texto: 'Falso',
                  esCorrecta: true,
                },
              ],
              mensaje_correcto:
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 12,
              texto:
                'El poder calorífico es la cantidad de calor producida al quemar una unidad de peso del combustible.',
              imagen: require('@/assets/actividad/imagen4.png'),
              barajarRespuestas: false,
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
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 13,
              texto:
                'El carbón se compone esencialmente de carbono, hidrógeno, oxígeno y pequeñas cantidades de nitrógeno y azufre.',
              imagen: require('@/assets/actividad/imagen1.png'),
              barajarRespuestas: false,
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
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 14,
              texto:
                'La combustión es un proceso de reducción en el que se libera energía.',
              imagen: require('@/assets/actividad/imagen2.png'),
              barajarRespuestas: false,
              opciones: [
                {
                  id: 'a',
                  texto: 'Verdadero',
                  esCorrecta: false,
                },
                {
                  id: 'b',
                  texto: 'Falso',
                  esCorrecta: true,
                },
              ],
              mensaje_correcto:
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 15,
              texto:
                'El aire seco está compuesto principalmente por oxígeno y dióxido de carbono. ',
              imagen: require('@/assets/actividad/imagen3.png'),
              barajarRespuestas: false,
              opciones: [
                {
                  id: 'a',
                  texto: 'Verdadero',
                  esCorrecta: false,
                },
                {
                  id: 'b',
                  texto: 'Falso',
                  esCorrecta: true,
                },
              ],
              mensaje_correcto:
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 16,
              texto:
                'Para lograr una combustión completa, se requiere un exceso de suministro de aire. ',
              imagen: require('@/assets/actividad/imagen4.png'),
              barajarRespuestas: false,
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
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 17,
              texto:
                'Un exceso de aire en la combustión siempre mejora la eficiencia del proceso ',
              imagen: require('@/assets/actividad/imagen1.png'),
              barajarRespuestas: false,
              opciones: [
                {
                  id: 'a',
                  texto: 'Verdadero',
                  esCorrecta: false,
                },
                {
                  id: 'b',
                  texto: 'Falso',
                  esCorrecta: true,
                },
              ],
              mensaje_correcto:
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 18,
              texto:
                'La cantidad de CO2 producida al quemar bagazo seco es constante. ',
              imagen: require('@/assets/actividad/imagen2.png'),
              barajarRespuestas: false,
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
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 19,
              texto:
                'La falta de automatización en los procesos paneleros puede generar una inadecuada dosificación de insumos. ',
              imagen: require('@/assets/actividad/imagen3.png'),
              barajarRespuestas: false,
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
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
            {
              id: 20,
              texto:
                'La falta de automatización en los procesos paneleros puede generar una inadecuada dosificación de insumos. ',
              imagen: require('@/assets/actividad/imagen4.png'),
              barajarRespuestas: false,
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
                'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
              mensaje_incorrecto:
                'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
            },
          ],
          mensaje_correcto:
            'Excelente trabajo. Tiene un claro entendimiento sobre los efectos de la temperatura en la producción panelera. ',
          mensaje_incorrecto:
            'Respuesta incorrecta, revise nuevamente el contenido del componente formativo. ',
        },
      ],
      mensaje_final_aprobado:
        '¡Excelente! Lo felicito, ha superado la actividad y demuestra sólidos conocimientos sobre el componente formativo.',
      mensaje_final_reprobado:
        'No ha superado la actividad. Le recomendamos volver a revisar el componente formativo e intentar nuevamente la actividad didáctica.',
    },
  }),
}
</script>
