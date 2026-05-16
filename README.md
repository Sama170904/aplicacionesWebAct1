BioMech Lab

Optimización biomecánica y fortalecimiento del tejido conectivo.

BioMech Lab es una plataforma web estática dedicada a la gestión inteligente de la carga física y el rendimiento deportivo. Diseñada para atletas que buscan superar estancamientos y prevenir lesiones, la web permite explorar soluciones técnicas y protocolos basados en la ciencia para fortalecer tendones y ligamentos, alejándose del enfoque convencional de solo estética para priorizar la longevidad articular.

Tabla de contenidos

Vista general

Características

Estructura del proyecto

Tecnologías utilizadas

Secciones de la página

Zonas Críticas Disponibles

Síntomas y Dolores Catalogados

Cómo usar

Contacto

Vista general

BioMech Lab es una herramienta de consulta biomecánica que organiza el entrenamiento desde dos ejes fundamentales:

Por Anatomía (Core Biomecánico) — exploración a través de un modelo 3D interactivo que permite visualizar la relación mecánica entre músculos y tejido conectivo.

Por Sintomatología (Selector de Dolor) — filtrado inteligente de protocolos correctivos basados en la molestia específica del usuario.

Características

Explorador Corporal Interactivo con nodos de selección anatómica.

Selector dinámico de síntomas para filtrado rápido de información técnica.

Biblioteca integrada de videos correctivos (Isometría, Movilidad y Estabilidad).

Calculadora de carga específica para protocolos de fortalecimiento de tendones.

Diseño técnico estilo "Dark Mode" de alto rendimiento.

Arquitectura ligera — cero frameworks JavaScript y máxima velocidad de carga.

Interfaz completamente responsive para uso en dispositivos móviles dentro del gimnasio.

Estructura del proyecto

biomechlab/
└── index.html          Página única (Single Page Application) con HTML, CSS y JS integrados.


Nota: Al ser un sitio estático de un solo archivo, no requiere de servidores dedicados, procesos de compilación ni instalación de módulos. Basta con abrir el archivo en cualquier navegador.

Tecnologías utilizadas

HTML5 — marcado semántico enfocado en la jerarquía de datos técnicos.

CSS3 — variables globales, sistema de Grid y Flexbox, y filtros de desenfoque modernos (backdrop-filter).

JavaScript Vanilla — lógica de filtrado de síntomas, manejo de modales de video y algoritmos de la calculadora de carga.

Google Fonts — tipografías de alta legibilidad para entornos técnicos y deportivos.

Secciones de la página

Hero / Explorador 3D

Sección principal con el Interactive Body Explorer. Permite al usuario rotar e interactuar con el modelo anatómico para identificar zonas de dolor y abrir paneles de detalle.

Selector de Dolor (Beneficios)

Sistema de pestañas donde el usuario elige su síntoma (ej. "Dolor al agacharse"). La app filtra automáticamente el contenido científico relevante y las soluciones sugeridas.

El Core Biomecánico

Ficha técnica de la articulación seleccionada que incluye:

Descripción de la patología o molestia.

Estadísticas visuales de estrés articular vs. resiliencia.

Mapa de articulaciones adyacentes vinculadas mecánicamente.

Video-Librería de Corrección

Módulo visual con videos explicativos de ejercicios clave como Isometría de Rodilla, Movilidad de Cadera y Estabilidad de Core.

Calculadora Tool

Herramienta funcional para calcular porcentajes de carga y protocolos de recuperación activa basados en el peso máximo (1RM) ingresado por el usuario.

Zonas Críticas Disponibles

Cada zona activa un panel de control con videos y guías específicas:

🦵 Rodilla (Patelar) — Tendón distal · Cuádriceps · Meniscos (Protocolos isométricos)

🏃 Cadera — Glúteo medio · Psoas · Piramidal (Movilidad activa)

🧘 Core (Lumbar) — Transverso · Multífidos · Erectores (Estabilidad central)

🦾 Hombro — Manguito rotador · Supraespinoso · Deltoides (Centrado articular)

🦶 Tobillo — Tendón de Aquiles · Sóleo · Fascia (Cargas excéntricas)

📐 Codo — Epicóndilo lateral · Tendón común (Fricción y carga)

Síntomas y Dolores Catalogados

Asociación de molestias comunes con su correspondiente protocolo en la app:

Icono

Síntoma

Zona Asociada

Objetivo

🛑

Dolor profundo al agacharse

Tendón Patelar

Carga isométrica

⚠️

Rigidez al hacer sentadillas

Articulación de Cadera

Movilidad funcional

📉

Molestia lumbar al cargar peso

Estabilidad de Core

Anti-rotación/Anti-extensión

⚡

Pinzamiento al levantar el brazo

Manguito Rotador

Fortalecimiento específico

Cómo usar

Descargar el archivo index.html.

Abrir directamente en el navegador (no requiere servidor local).

Seleccionar una articulación en el modelo 3D o usar el buscador de síntomas.

Seguir la guía visual de los videos y usar la calculadora para ajustar las cargas de entrenamiento.

Contacto

¿Sugerencias biomecánicas o reporte de errores técnicos?

✉ rolando.samaniego@uees.edu.ec

© 2026 BioMech Lab — Plataforma de Optimización Biomecánica
