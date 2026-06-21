# ColabUp

**Conectando ideas, talento y oportunidades.**

ColabUp es una plataforma digital desarrollada por la startup **Crynexia**, orientada a facilitar la colaboración y el desarrollo de proyectos innovadores. Permite que estudiantes, egresados, emprendedores y profesionales puedan compartir ideas, encontrar colaboradores con habilidades complementarias, formar equipos de trabajo y gestionar el progreso de sus iniciativas dentro de un mismo entorno digital.

Este repositorio contiene el **avance de implementación del Landing Page** del proyecto, desarrollado para el curso de IHC y Tecnologías Móviles (UPC).

## Tabla de contenido

- [Información del proyecto](#información-del-proyecto)
- [Autores](#autores)
- [El problema que resolvemos](#el-problema-que-resolvemos)
- [Misión y visión](#misión-y-visión)
- [Segmentos objetivo](#segmentos-objetivo)
- [Diferenciación frente a la competencia](#diferenciación-frente-a-la-competencia)
- [Características principales de la plataforma](#características-principales-de-la-plataforma)
- [Avance del Landing Page](#avance-del-landing-page)
- [Guía de estilo (Style Guidelines)](#guía-de-estilo-style-guidelines)
- [Tecnologías](#tecnologías)
- [Estructura del proyecto](#estructura-del-proyecto)
- [Flujo de trabajo (GitFlow)](#flujo-de-trabajo-gitflow)
- [Cómo visualizar el proyecto](#cómo-visualizar-el-proyecto)

## Información del proyecto

- **Producto:** ColabUp
- **Tagline:** Conectando ideas, talento y oportunidades.
- **Startup:** Crynexia
- **Curso:** IHC y Tecnologías Móviles
- **Docente:** Salazar Ruiz, Kevin Edgar
- **Universidad:** Universidad Peruana de Ciencias Aplicadas (UPC)
- **Año:** 2026

## Autores

| Integrante | Código | Carrera |
|---|---|---|
| Torres Garcia, Fabrizio | u202421331 | Ing. de Sistemas de Información |
| Arias Dextre, Fabrizio | u202420862 | Ing. de Software |
| Zevallos Arones, Jose | u202421686 | Ing. de Sistemas de Información |
| Domenack Angeles, Miguel | u202322404 | Ing. de Software |
| Calderon Tarazona, Joan Stuar | U202421469 | Ing. de Sistemas de Información |
| Aujtukai Petsain, Heren Rod Reyzo | U20221E181 | Ing. de Sistemas de Información |

## El problema que resolvemos

Muchos estudiantes, egresados y emprendedores cuentan con ideas o proyectos innovadores, pero no logran llevarlos a cabo por la falta de conexión con personas que posean habilidades complementarias, experiencia en otras áreas, o por la ausencia de una herramienta que les permita organizar el trabajo en equipo. Esta dificultad se concentra principalmente en entornos académicos, comunidades de emprendedores y espacios de innovación.

Esto se traduce en:

- Estudiantes y egresados que no encuentran prácticas o empleos alineados a su perfil a tiempo.
- Emprendedores que no logran identificar socios o colaboradores con habilidades complementarias.
- Equipos que pierden seguimiento de sus interacciones, tareas y avances por falta de organización.

ColabUp busca reducir estas dificultades conectando personas, recomendando oportunidades y colaboradores, y centralizando la gestión de proyectos colaborativos en un mismo entorno digital.

## Misión y visión

- **Misión:** desarrollar una plataforma digital que facilite la creación, colaboración y gestión de proyectos innovadores, permitiendo que emprendedores, estudiantes y profesionales transformen sus ideas en soluciones reales mediante herramientas tecnológicas.
- **Visión:** ser reconocida para el año 2030, a nivel nacional e internacional, como una plataforma innovadora que impulsa el desarrollo de proyectos tecnológicos y fomenta la colaboración entre emprendedores, estudiantes y profesionales.

## Segmentos objetivo

**1. Estudiantes y egresados**
Personas que residan en Perú, estudiantes universitarios o egresados recientes, entre 18 y 30 años, de ambos géneros, con acceso a internet y dispositivos digitales. Se encuentran en búsqueda de prácticas preprofesionales, empleo o primeras experiencias laborales, con un ingreso variable o en formación (aprox. S/0 a S/2500 mensuales). Buscan oportunidades alineadas a sus habilidades, así como mejorar su empleabilidad y conectarse con profesionales o proyectos relevantes.

**2. Emprendedores y networking**
Hombres y mujeres residentes en Perú, entre 20 y 40 años, interesados en desarrollar proyectos, emprendimientos o iniciativas innovadoras. Incluye profesionales, freelancers o personas con ideas de negocio que buscan colaboradores, socios estratégicos o ampliar su red de contactos. Buscan plataformas digitales que les permitan conectar con personas afines, formar equipos de trabajo y desarrollar proyectos de manera colaborativa.

## Diferenciación frente a la competencia

Se analizaron como principales competidores **LinkedIn**, **Indeed** y **Meetup**. Estas plataformas resuelven parcialmente el problema (networking general, búsqueda de empleo o eventos presenciales), pero ninguna está enfocada específicamente en:

- La formación de equipos para proyectos o emprendimientos concretos.
- Estudiantes y egresados sin trayectoria laboral consolidada.
- La gestión integral de un proyecto colaborativo (tareas, roles, avances) dentro de la misma plataforma donde se hizo el match.

ColabUp se diferencia mediante **recomendaciones inteligentes** de oportunidades y colaboradores, y un enfoque centrado en la **colaboración en proyectos**, no solo en el networking o la búsqueda de empleo de forma aislada.

## Características principales de la plataforma

- **Networking profesional:** conexión entre estudiantes, egresados, emprendedores y profesionales de distintas áreas.
- **Recomendaciones inteligentes:** sugerencia de oportunidades, proyectos y colaboradores según habilidades e intereses del usuario.
- **Perfiles profesionales:** habilidades, experiencia, portafolio (ej. enlace a GitHub) y biografía para facilitar la formación de equipos multidisciplinarios.
- **Gestión de proyectos colaborativos:** publicación de ideas, definición de roles requeridos, tablero kanban (To Do / Doing / Done) y asignación de tareas.
- **Búsqueda y filtros avanzados:** por palabras clave, área de especialización, modalidad (full-time/part-time) y nivel de experiencia.
- **Comunicación y notificaciones:** chat por proyecto, avisos de nuevas postulaciones, recordatorios de deadlines y resúmenes semanales por correo.
- **Seguridad y privacidad:** verificación con correo institucional, control de visibilidad de datos de contacto y términos legales claros.

## Avance del Landing Page

La implementación actual del Landing Page (`public/index.html`) cubre las siguientes secciones, alineadas a las User Stories de la plataforma pública (US01–US10 del Product Backlog):

| Sección | Contenido | User Story relacionada |
|---|---|---|
| Hero / Inicio | Mensaje de valor claro sobre qué es ColabUp | US01 |
| Misión y visión | Misión y visión de Crynexia | US02 |
| Beneficios | Beneficios de usar la plataforma | US04 |
| Cómo funciona | Pasos para empezar a usar ColabUp | US01 |
| Explorar | Vista previa de oportunidades/proyectos | US04 |
| Testimonios / Casos de éxito | Validación social de la propuesta | US07 |
| Nosotros | Equipo de Crynexia | US03 |
| Proyectos destacados | Ejemplos de proyectos en la plataforma | US04 |
| Métricas | Indicadores de impacto de la comunidad | US04 |
| Partners | Aliados y comunidades asociadas | US06 |
| Beneficios prácticos / Ayuda / FAQ | Resolución de dudas frecuentes | US05 |
| Seguridad | Manejo de datos personales y legal | US09 |
| Contacto | Formulario de contacto y newsletter | US05, US06 |
| Navegación | Menú superior fijo (sticky) y diseño responsive | US08, US10 |

## Guía de estilo (Style Guidelines)

- **Tipografía principal:** Plus Jakarta Sans (títulos y encabezados).
- **Tipografía secundaria:** Inter (texto descriptivo y contenido extenso).
- **Colores principales:** Azul oscuro `#1E3A5F` (profesionalismo y confianza), Celeste `#4DA8DA` (innovación y tecnología).
- **Colores secundarios:** Verde `#6FCF97` (crecimiento y oportunidades), Naranja `#F2994A` (creatividad y energía).
- **Neutros:** Fondo claro `#F8F9FB`, Texto oscuro `#2C2C2C`, Gris neutro `#E0E0E0`.
- **Espaciado:** sistema basado en múltiplos de 8 px; bordes redondeados entre 6 y 8 px.
- **Botones:** primario (azul oscuro, texto blanco), secundario (borde celeste, fondo blanco), con estados normal/hover/deshabilitado.
- **Responsive:** una columna en móvil (≤768 px), dos a tres columnas en escritorio (≥1025 px), con menú hamburguesa en dispositivos móviles.

## Tecnologías

- HTML5, CSS3 y JavaScript (sin frameworks de CSS)
- [Google Fonts](https://fonts.google.com/) — Plus Jakarta Sans, Inter
- [Font Awesome](https://fontawesome.com/)

## Estructura del proyecto

```
public/
├── index.html              # Landing Page
├── favicon.ico
└── assets/
    ├── styles/              # Archivos .css
    │   └── styles.css
    ├── images/              # Imágenes (logo, etc.)
    │   └── logo.png
    └── scripts/             # Archivos .js
        └── main.js
```

## Flujo de trabajo (GitFlow)

El proyecto sigue el modelo **GitFlow**:

- `main` → versión estable/publicable.
- `develop` → rama de integración del desarrollo.
- `feature/nombre-de-la-funcionalidad` → ramas creadas a partir de `develop` para cada nueva funcionalidad.

## Cómo visualizar el proyecto

Abrir el archivo `public/index.html` directamente en el navegador, o servirlo con una extensión tipo *Live Server*.
