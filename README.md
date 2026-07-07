# FitCalc — Calculadora Fitness

> Calculadora de calorías diarias (TDEE) y porcentaje de grasa corporal con fórmulas validadas científicamente. Interfaz moderna, responsive y sin dependencias externas.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 🚀 Demo en vivo

🔗 **[Ver demo](https://TU_USUARIO.github.io/fitcalc)** *(sustituye por tu URL real tras el despliegue)*

---

## 📸 Vista previa

| Calculadora de calorías | % Grasa corporal | Documentación |
|:---:|:---:|:---:|
| TDEE con Mifflin-St Jeor y Katch-McArdle | Fórmula de la Marina (US Navy) | Consejos, fórmulas y referencias |

---

## ✨ Características

- **Calculadora de calorías (TDEE)**
  - Fórmula de **Mifflin-St Jeor** (población general)
  - Fórmula de **Katch-McArdle** (modo avanzado con % de grasa)
  - Objetivos: mantenimiento, pérdida suave/fuerte, ganancia muscular
  - Análisis automático del resultado con recomendaciones

- **Calculadora de % de grasa corporal**
  - **Fórmula de la Marina** (US Navy) — modo avanzado con circunferencias
  - **Estimación por BMI** — modo básico sin cinta métrica
  - Clasificación automática (Esencial → Obeso)
  - Recomendaciones personalizadas por edad y sexo

- **Documentación completa**
  - Consejos prácticos de estilo de vida
  - Consecuencias de cada nivel de grasa
  - Rangos por edad y sexo
  - Fórmulas detalladas con explicaciones
  - Distribución de macronutrientes
  - Hidratación y electrolitos
  - Referencias científicas (PubMed, ACE, OMS...)

- **UX/UI**
  - Diseño responsive (móvil, tablet, escritorio)
  - Sidebar con navegación entre secciones
  - Modales con diagramas de cómo medir
  - Animaciones suaves en resultados
  - Sincronización de datos entre calculadoras
  - Navegación directa a secciones de documentación

---

## 🛠️ Tecnologías

| Tecnología | Uso |
|---|---|
| **HTML5** | Estructura semántica |
| **CSS3** | Estilos con variables CSS, Grid, Flexbox, animaciones |
| **Vanilla JavaScript** | Lógica de cálculo, DOM, eventos |
| **Google Fonts (Inter)** | Tipografía moderna |

> Sin frameworks. Sin dependencias. Sin build step. Solo abrir el archivo en un navegador.

---

## 📁 Estructura del proyecto

```
fitcalc/
├── index.html          # Aplicación completa (HTML + CSS + JS)
├── README.md           # Este archivo
└── .github/
    └── workflows/
        └── deploy.yml  # Configuración para GitHub Pages (opcional)
```

> Todo está contenido en un único archivo `index.html` para máxima simplicidad de despliegue.

---

## 🧮 Fórmulas implementadas

| Fórmula | Uso | Precisión |
|---|---|---|
| **Mifflin-St Jeor** | BMR población general | Alta (±10%) |
| **Katch-McArdle** | BMR con % de grasa conocido | Muy alta (cuerpos atípicos) |
| **US Navy** | % grasa con circunferencias | r ≈ 0.90 vs hidrostática |
| **Deurenberg (BMI)** | % grasa estimada sin medidas | Media (±3-5%) |

---

## 🚀 Cómo usar localmente

1. Clona el repositorio:
```bash
git clone https://github.com/TU_USUARIO/fitcalc.git
```

2. Abre el archivo en tu navegador:
```bash
# macOS
open fitcalc/index.html

# Linux
xdg-open fitcalc/index.html

# Windows (PowerShell)
start fitcalc/index.html
```

O simplemente arrastra el archivo `index.html` a una ventana del navegador.

---

## 🌐 Despliegue en GitHub Pages (recomendado)

GitHub Pages permite alojar sitios web estáticos **gratis** directamente desde tu repositorio.

### Paso 1: Crear el repositorio en GitHub

1. Ve a [github.com/new](https://github.com/new)
2. Nombre del repositorio: `fitcalc`
3. Descripción: `Calculadora de calorías y grasa corporal con fórmulas científicas`
4. Visibilidad: **Público** (recomendado para tu portfolio)
5. Marca ✅ "Add a README file"
6. Clic en **Create repository**

### Paso 2: Subir los archivos

**Opción A: Por web (más fácil para principiantes)**

1. En tu repo de GitHub, clic en **"Add file" → "Upload files"**
2. Arrastra `index.html` (y `README.md` si no lo creaste antes)
3. Escribe un mensaje de commit: `feat: añade calculadora fitness completa`
4. Clic en **"Commit changes"**

**Opción B: Por terminal (Git)**

```bash
# 1. Clona el repo vacío que acabas de crear
git clone https://github.com/TU_USUARIO/fitcalc.git
cd fitcalc

# 2. Copia tu index.html aquí (y este README.md)
#    (arrastra los archivos a la carpeta fitcalc/)

# 3. Sube los cambios
git add .
git commit -m "feat: añade calculadora fitness completa"
git push origin main
```

### Paso 3: Activar GitHub Pages

1. En tu repo de GitHub, ve a **Settings** (pestaña arriba a la derecha)
2. En el menú lateral izquierdo, haz clic en **Pages**
3. En "Source", selecciona **Deploy from a branch**
4. Selecciona la rama **`main`** y la carpeta **`/(root)`**
5. Clic en **Save**
6. Espera 1-2 minutos y recarga la página
7. Verás un mensaje verde: `Your site is live at https://TU_USUARIO.github.io/fitcalc`

> 💡 **Tip:** Si no ves la opción "Pages", busca en el menú lateral: **Settings → Code and automation → Pages**

---

## 🔧 Despliegue alternativo (opcional)

| Plataforma | Tipo | Enlace |
|---|---|---|
| **Netlify** | Arrastrar y soltar | [netlify.com](https://netlify.com) |
| **Vercel** | Importar desde GitHub | [vercel.com](https://vercel.com) |
| **Surge.sh** | CLI | `npm install -g surge` |

Para un proyecto estático como este, **GitHub Pages** es más que suficiente y no requiere cuenta adicional.

---

## 📝 Buenas prácticas para tu primer proyecto en GitHub

### Commits descriptivos
Usa prefijos para que tu historial sea profesional:

```
feat:    nueva funcionalidad
fix:     corrección de bug
docs:    cambios en documentación
style:   cambios de formato (espacios, CSS)
refactor: reestructuración de código
```

Ejemplo:
```bash
git commit -m "feat: añade modo avanzado Katch-McArdle"
git commit -m "fix: corrige cálculo de cadera en mujeres"
git commit -m "docs: añade sección de hidratación"
```

### README profesional
- ✅ Incluye demo en vivo
- ✅ Explica qué hace el proyecto
- ✅ Muestra las tecnologías usadas
- ✅ Instrucciones de instalación/uso
- ✅ Screenshots o GIFs (cuando puedas)
- ✅ Licencia (MIT es la más común para proyectos personales)

### Issues y Projects (opcional)
- Usa **Issues** para listar bugs o mejoras futuras
- Usa **Projects** para organizar un roadmap (v1.0, v1.1...)

---

## 📚 Recursos para aprender más

- [GitHub Docs - Pages](https://docs.github.com/es/pages)
- [GitHub Docs - Git básico](https://docs.github.com/es/get-started/quickstart)
- [Markdown Guide](https://www.markdownguide.org/) (para escribir READMEs)
- [GitHub Profile README](https://docs.github.com/es/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme) (para tu portfolio)

---

## ⚠️ Descargo de responsabilidad

Los resultados de esta calculadora son **estimaciones orientativas** basadas en fórmulas científicas validadas. No sustituyen el consejo médico, nutricional o de entrenamiento profesional. Consulta siempre a un especialista antes de realizar cambios significativos en tu dieta o rutina de ejercicio.

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Puedes usarlo, modificarlo y distribuirlo libremente.

```
MIT License

Copyright (c) 2026 TU_NOMBRE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND...
```

---

<p align="center">
  Hecho con 💪 para la comunidad fitness<br>
  <a href="https://github.com/TU_USUARIO/fitcalc">⭐ Star este repo si te resulta útil</a>
</p>
