# FitCalc — Calculadora Fitness

> Calculadora de calorías diarias (TDEE) y porcentaje de grasa corporal con fórmulas validadas científicamente. Interfaz moderna, responsive y sin dependencias externas.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green.svg)

---

## 🚀 Demo en vivo

🔗 **[Ver demo](https://rubenghumanes.github.io/calories-calc/)**

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
git clone https://github.com/rubenghumanes/calories-calc.git
```

2. Abre el archivo en tu navegador:
```bash
# macOS
open calories-calc/index.html

# Linux
xdg-open calories-calc/index.html

# Windows (PowerShell)
start calories-calc/index.html
```

O simplemente arrastra el archivo `index.html` a una ventana del navegador.

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
  <a href="https://github.com/rubenghumanes/calories-calc">⭐ Star este repo si te resulta útil</a>
</p>
