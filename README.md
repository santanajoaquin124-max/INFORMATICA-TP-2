# INFORMATICA-TP-2
# Herramientas de Desarrollo Web y el Impacto de la IA (2021–2026)

## 1. Tema del proyecto

El proyecto analiza la evolución de las herramientas de desarrollo web en Front End y Back End entre 2021 y 2026, y el impacto de la Inteligencia Artificial en el flujo de trabajo de desarrollo. El material de base describe el paso de las aplicaciones de página única (SPA) hacia arquitecturas híbridas, la adopción de entornos Serverless y Edge, y la consolidación de la IA como asistente de desarrollo.

## 2. Objetivo

Reunir datos cuantitativos y una explicación textual sobre la evolución de los frameworks, los entornos de ejecución y las herramientas de IA, y presentarlos en un sitio web que sintetice los resultados del análisis.

## 3. Relación con la carrera

El proyecto se vincula con la Tecnicatura en Marketing Digital porque el documento de base trata sobre las herramientas con las que se construyen los sitios web, que son el soporte de la presencia digital. El propio documento menciona que el renderizado híbrido se estandarizó para optimizar el SEO y los Core Web Vitals, y que la IA permite al desarrollador enfocarse en la experiencia de usuario final. Son temas que conectan la tecnología web con el posicionamiento y la experiencia de usuario.

## 4. Archivos analizados

### Excel 1

**Archivo:** `Datos_Frontend_Backend_2021_2025.xlsx`

Contiene datos de uso de tecnologías web provenientes de las encuestas de desarrolladores de Stack Overflow. Sus hojas son:

- **Datos_Frontend:** porcentaje de uso de React, Angular, Vue.js, AngularJS y Svelte en cada año de 2021 a 2025.
- **Analisis_Frontend:** cálculos con fórmulas a partir de esos datos: uso en 2021 y 2025, cambio en puntos porcentuales, promedio, máximo del período, año del máximo y ranking 2025.
- **Backend_Runtimes_2025:** uso en 2025 de Node.js, Next.js, Express, NestJS, Astro, Nuxt.js y Deno, con su categoría (runtime, meta-framework o framework backend), ranking y diferencia respecto del líder.
- **Fuentes:** origen y notas de cada hoja.

### Excel 2

**Archivo:** `Datos_IA_en_Desarrollo_2023_2026.xlsx`

Contiene datos sobre el uso de la IA entre desarrolladores. Sus hojas son:

- **Adopcion_IA:** porcentaje de desarrolladores que usa o planea usar IA, que la usa actualmente, que confía en la precisión de sus resultados y que tiene un sentimiento favorable hacia ella, para 2023, 2024 y 2025.
- **Agentes_y_Modelos:** uso de agentes de IA (2025 y un sondeo de abril de 2026), resultados reportados por quienes los usan, la frustración por respuestas "casi correctas" y el uso de los modelos GPT de OpenAI, Claude Sonnet y Gemini Flash.
- **Analisis_IA:** ocho indicadores calculados con fórmulas, como el crecimiento del uso, la brecha entre uso y confianza y el salto en el uso de agentes.
- **Fuentes:** origen y notas de cada hoja.

### Word

**Archivo:** `Herramientas_Frontend_Backend_IA_2021_2026.docx`

Es el documento textual del proyecto. Incluye un resumen ejecutivo y tres secciones:

1. **Evolución del desarrollo Front End (2021–2025):** frameworks híbridos (Next.js, Remix, Nuxt 3, SvelteKit), herramientas de build (Vite, Turbopack, Rolldown, Rspack), Tailwind CSS, las novedades de CSS nativo y el rol de TypeScript.
2. **Tendencias en el desarrollo Back End:** runtimes (Node.js, Bun, Deno), frameworks (NestJS, Fastify, FastAPI, Rust y Go), ORMs (Prisma, Drizzle) y bases de datos, incluidas las vectoriales.
3. **El impacto transformador de la IA:** una tabla con cuatro categorías de herramientas (asistentes de código en IDE, generación de interfaces, agentes de desarrollo e infraestructura para RAG), con ejemplos y su impacto en el flujo de trabajo.

Cierra con una conclusión clave: el rol del desarrollador no fue reemplazado sino elevado. Este documento aporta el contexto y las explicaciones sobre los cambios y la evolución, mientras que los Excel aportan las cifras.

## 5. Análisis realizado

Los datos de los Excel se analizaron mediante fórmulas y se interpretaron junto con el Word.

**Front End (2021–2025)**

- React pasó de 40,1 % a 44,7 % de uso (+4,6 p. p.) y lidera el ranking 2025.
- Angular bajó de 23,0 % a 18,2 % (−4,8 p. p.) y quedó segundo.
- Vue.js bajó de 19,0 % a 17,6 % (−1,4 p. p.) y quedó tercero.
- AngularJS bajó de 11,5 % a 7,2 % (−4,3 p. p.).
- Svelte subió de 2,8 % a 7,2 % (+4,5 p. p.) y empata con AngularJS en el cuarto lugar de 2025.

**Back End (2025)**

- Node.js lidera con 48,7 %, seguido por Next.js (20,8 %), Express (19,9 %), NestJS (6,7 %), Astro (4,5 %), Nuxt.js (4,0 %) y Deno (4,0 %).

**IA en el desarrollo (2023–2025)**

- Quienes usan o planean usar IA pasaron de 70 % a 84 %.
- El uso actual pasó de 44 % a 79 %, un aumento de 35 p. p. (1,8 veces).
- La confianza en la precisión bajó de alrededor de 40 % a 29 %, y la brecha entre uso y confianza en 2025 es de 50 p. p.
- El sentimiento favorable bajó de 72,0 % a 59,7 % entre 2024 y 2025.
- El uso de agentes pasó de 31 % (2025) a 59 % (sondeo de abril de 2026), un salto de 28 p. p.
- En 2025, el 52 % no usaba agentes o se quedaba en herramientas simples y el 38 % no planeaba adoptarlos. Entre quienes los usan, el 69 % mejoró su productividad, el 70 % redujo el tiempo de sus tareas y el 38 % mejoró la calidad del código.
- El 66 % señaló como frustración las respuestas "casi correctas" de la IA.
- Modelos más usados en 2025: GPT de OpenAI (81 %), Claude Sonnet (43 %) y Gemini Flash (35 %).

**Limitaciones indicadas en los archivos**

- Los datos de 2021, 2022 y 2024 del primer Excel provienen de recopilaciones públicas de los resultados de Stack Overflow y conviene contrastarlos con las páginas oficiales.
- La confianza de 2023 es aproximada, y el sentimiento favorable de 2023 quedó vacío porque solo se publicó como "más de 70 %".

## 6. Desarrollo del sitio web

[COMPLETAR: describir el sitio a partir del archivo HTML. Indicar las secciones que contiene, cómo presenta los datos de los Excel (tablas, gráficos u otros elementos) y cómo incorpora el contenido del Word. Incluir solo lo que figure en el HTML.]

## 7. Herramientas utilizadas

- **Claude:** se utilizó para generar los dos archivos Excel a partir de los datos de las encuestas de Stack Overflow.
- **Netlify:** se utilizó para publicar el sitio web (ver sección 8).
- **GitHub:** se utilizó para alojar el proyecto y su documentación (ver sección 9).
- **Microsoft Excel y Microsoft Word:** formatos de los archivos de datos y del documento textual.

## 8. Publicación

El sitio web fue publicado mediante Netlify.

**Enlace del sitio:** [COMPLETAR: URL de Netlify]

## 9. Repositorio

El proyecto y su documentación se encuentran en GitHub.

**Enlace del repositorio:** [COMPLETAR: URL del repositorio]

## 10. Fuentes

Las fuentes de los datos están indicadas en la hoja "Fuentes" de cada Excel:

- Stack Overflow Developer Survey, ediciones 2021 a 2025: <https://survey.stackoverflow.co/2023/> y <https://survey.stackoverflow.co/2025/>.
- Stack Overflow Blog, "Getting ready for 2026 results: A look back on Developer Survey findings" (30/09/2026): <https://stackoverflow.blog/2026/09/30/getting-ready-for-2026-results-a-look-back-on-developer-survey-findings>.
- Stack Overflow Blog, "Developers remain willing but reluctant to use AI: The 2025 Developer Survey results are here": <https://stackoverflow.blog/2025/12/29/developers-remain-willing-but-reluctant-to-use-ai-the-2025-developer-survey-results-are-here/>.
- Stack Overflow Blog, "Mind the gap: Closing the AI trust gap for developers": <https://stackoverflow.blog/2026/02/18/closing-the-developer-ai-trust-gap/>.
- Recopilación pública de resultados de frameworks front end (gist de tkrotoff): <https://gist.github.com/tkrotoff/b1caa4c3a185629299ec234d2314e190>.
- Resumen de la encuesta 2025 en DEV Community (davidshq): <https://dev.to/davidshq/thoughts-on-stackoverflow-2025-developer-survey-part-1-3d5o>.
- Cobertura de la encuesta 2025: InfoWorld (<https://www.infoworld.com/article/4031673/ai-use-among-software-developers-grows-but-trust-remains-an-issue-stack-overflow-survey.html>) y ShiftMag (<https://shiftmag.dev/stack-overflow-survey-2025-ai-5653/>).
- Documento Word del proyecto: *Herramientas de Desarrollo Web y el Impacto de la IA (2021–2026)*.

## 11. Conclusión

El análisis muestra que, entre 2021 y 2025, React consolidó su liderazgo en Front End, Svelte creció y Angular, Vue.js y AngularJS perdieron participación. En IA, el uso entre desarrolladores creció con fuerza entre 2023 y 2025, y en 2026 el uso de agentes se acercó a duplicarse, aunque la confianza en los resultados bajó. Esto coincide con la conclusión del documento de base: la IA se encarga de tareas repetitivas y el rol del desarrollador se orienta hacia la arquitectura, la seguridad, la lógica de negocio y la experiencia de usuario.
