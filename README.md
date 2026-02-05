# 📦 Frigilux SGE - Portal de Documentación Legal

[![Astro](https://img.shields.io/badge/Astro-BC52EE?style=for-the-badge&logo=astro&logoColor=white)](https://astro.build/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://vercel.com/)

Este repositorio contiene el portal oficial de **Términos y Condiciones**, **Políticas de Privacidad** y **Preguntas Frecuentes (FAQ)** de Frigilux App SGE Venezuela.

## 🔗 Enlaces del Proyecto
🚀 **Sitio en Vivo:** [app.friginet.xyz](https://app.friginet.xyz)  
🏢 **Corporativo:** [Frigilux Venezuela](https://frigilux.com)

---

## 📸 Capturas de Pantalla

| Vista de Inicio (Desktop) | Interfaz Móvil (Dark Mode) |
| :--- | :--- |
| ![Preview 1](https://placehold.co/600x400/003366/FFF?text=SGE+Portal+Desktop) | ![Preview 2](https://placehold.co/300x500/111/FFF?text=SGE+Portal+Mobile) |

---

## 🛠️ Stack Tecnológico

* **Framework:** [Astro 5.0+](https://astro.build/) para un rendimiento estático ultrarrápido.
* **Estilos:** [Tailwind CSS](https://tailwindcss.com/) con sistema de diseño personalizado.
* **Componentes:** Arquitectura basada en islas para interactividad mínima y eficiente.
* **Despliegue:** CI/CD automatizado a través de **Vercel**.
* **Iconografía:** Iconos optimizados de Lucide/Tabler.

---

## 📂 Estructura del Proyecto

```text
/
├── public/             # Activos estáticos (Logo corporativo, capturas)
├── src/
│   ├── constants/      # Configuración centralizada (Emails de soporte, textos legales)
│   ├── layouts/        # Estructura Base (Header con Menú Hamburger, Footer dinámico)
│   ├── pages/
│   │   ├── index.astro       # Landing de bienvenida y acceso rápido
│   │   ├── privacy.astro     # Política de Privacidad (Marco legal venezolano)
│   │   ├── terms.astro       # T&C para colaboradores y usuarios
│   │   └── faqs.astro        # Sistema de acordeones interactivos
│   └── styles/         # Tailwinds y animaciones personalizadas (Fade-in, Orbs)
└── tailwind.config.mjs # Branding: Colores primarios y secundarios de Frigilux