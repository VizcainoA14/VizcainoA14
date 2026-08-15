<h1 align="center">Hola, soy Adrián Vizcaíno 👋</h1>

<p align="center">
  <b>Ingeniero de Sistemas y Computación</b> · Desarrollo de Software &amp; Ciencia de Datos<br>
  Cartagena de Indias, Colombia 🇨🇴
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/adrian-david-vizcaino-del-rio-886891298/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:vizcainoadrian2003@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://lumaweb.vercel.app/es">
    <img src="https://img.shields.io/badge/LUMA-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="LUMA">
  </a>
</p>

---

### Sobre mí

Construyo software donde se cruzan el desarrollo web y el análisis de datos. Trabajo actualmente como **desarrollador de software en Fundasaberes**, automatizando procesos internos, y vengo del **Semillero de Astronomía y Ciencia de Datos de la UTB**, donde fui coautor de dos publicaciones científicas.

Me muevo cómodo tanto escribiendo un pipeline de procesamiento de imágenes en Python como levantando una interfaz en Next.js para que esos datos se puedan leer. Lo que me interesa: convertir datos crudos en algo que la gente pueda usar para decidir.

---

### 📄 Publicaciones

| Año | Publicación | Venue |
|:---|:---|:---|
| 2024 | **LUMA: Empowering Solar Research Through Open-Source Web Observatories and Image Analysis Tool** | IEEE ENO-CANCOA · [10.1109/ENO-CANCOA61307.2024.10751134](https://doi.org/10.1109/ENO-CANCOA61307.2024.10751134) |
| 2025 | **From Console to Dashboard: A Demonstration of Real-Time Visualization for Social Simulation with WellProdSim** | Springer LNCS · [10.1007/978-3-032-07638-0_35](https://doi.org/10.1007/978-3-032-07638-0_35) |

---

### 🚀 Proyectos destacados

#### ☀️ [LUMA — Observatorio solar open source](https://lumaweb.vercel.app/es)
Aplicación web que traduce imágenes del Sol en indicadores numéricos y gráficos de actividad solar.

- **Frontend:** Next.js 14, Tailwind CSS, Radix UI, Tremor, Recharts, Framer Motion, GSAP, soporte multilenguaje con `next-intl`, desplegado en Vercel.
- **Datos:** Prisma sobre una base con **6 instrumentos** (`eit171`, `eit195`, `eit284`, `eit304`, `hmiigr`, `hmimag`).
- **Pipeline ([Ejecutable-luma](https://github.com/VizcainoA14/Ejecutable-luma)):** scraping del archivo público de **SOHO/NASA**, extracción de **16 descriptores por imagen** — entropía, dimensión fractal por *box-counting*, matriz de co-ocurrencia (GLCM), descriptores de Tamura, wavelets y gradientes Sobel — con procesamiento paralelo (`ThreadPoolExecutor` / `ProcessPoolExecutor` + Numba) y carga incremental a base de datos vía SQLAlchemy.

#### 🌾 [WellProdSim — Simulación social con agentes BDI](https://github.com/VizcainoA14/wpsSimulator)
Simulador que estima productividad y bienestar de familias campesinas mediante agentes **BDI** con razonamiento emocional, arquitectura orientada a eventos y alta concurrencia. Java + Maven sobre el framework **BESA**. Mi aporte: visualización en tiempo real del estado de la simulación (base del paper de 2025).

#### 🛒 [Ecommerce System Prototype](https://github.com/VizcainoA14/AS-EcommerceCompany) · [demo](https://as-ecommercecompany.onrender.com/)
Tienda en línea construida en equipo como proyecto final de Arquitectura de Software, con énfasis en patrones arquitectónicos y Scrum. **React 18**, autenticación con **Auth0**, pagos con **Stripe**, React Router y Axios contra una API en FastAPI.

#### 📊 [Dashboard estadístico en R](https://github.com/VizcainoA14/Dashboard-proyecto)
Análisis exploratorio e inferencial de tecnologías y lenguajes de programación entre **1960 y 2023**. `flexdashboard` + `tidyverse` + `plotly` + `DT`: pruebas de normalidad, intervalos de confianza al 90/95/99 %, pruebas chi-cuadrado de independencia y análisis bivariado.

#### 🌡️ [Procesamiento numérico](https://github.com/VizcainoA14/Procesamiento-numerico)
Proyecto en Jupyter sobre una base de datos de temperatura, aplicando métodos numéricos y análisis de datos.

---

### 🛠️ Stack técnico

**Lenguajes**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

**Web**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**Datos y análisis**

![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white)

**Herramientas**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

---

### 🎓 Formación

- **Ingeniería de Sistemas y Computación** — Universidad Tecnológica de Bolívar (2021 – 2026)
- **Bootcamp de Inteligencia Artificial** — Talento Tech, UTB / MinTIC (2024)
- **Diplomado en Habilidades de Investigación** — UTB (2024)
- **Misión TIC 2022** — Universidad del Norte / MinTIC (2021)

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=VizcainoA14&show_icons=true&hide_border=true&theme=default&hide=issues" alt="Estadísticas de GitHub" height="150">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=VizcainoA14&layout=compact&hide_border=true&theme=default&langs_count=6" alt="Lenguajes más usados" height="150">
</p>

<p align="center">
  <i>¿Hablamos? <a href="mailto:vizcainoadrian2003@gmail.com">vizcainoadrian2003@gmail.com</a></i>
</p>
