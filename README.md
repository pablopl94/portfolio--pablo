# 👨🏻‍💻 Portfolio Pablo Prieto López - Desarrollador Full Stack Junior

<div align="center">
<a href="https://linkedin.com/in/pablopl94">
<img src="./public/yo.webp" alt="Pablo Prieto López" width="150" height="150" style="border-radius: 50%;">
</a>
<p></p>
</div>

<div align="center">

![Astro Badge](https://img.shields.io/badge/Astro-FF3E00?logo=astro&logoColor=fff&style=flat)
![Tailwind CSS Badge](https://img.shields.io/badge/Tailwind%20CSS-06B6D4?logo=tailwindcss&logoColor=fff&style=flat)
![TypeScript Badge](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat)
![Spring Boot Badge](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=fff&style=flat)
![Angular Badge](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=fff&style=flat)
![Java Badge](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white&style=flat)

</div>

## 🚀 Sobre el Proyecto

Portfolio personal desarrollado con tecnologías modernas que muestra mi experiencia como **Desarrollador Full Stack Junior** con más de 4 meses de experiencia profesional y 2 años de experiencia emprendedora.

### 🎯 Especialización
- **Backend**: Java, Spring Boot, Spring MVC, Spring Security, .NET Core
- **Frontend**: Angular, TypeScript, HTML5, CSS3, JavaScript
- **Bases de Datos**: MySQL, SQL Server, Oracle
- **Herramientas**: Git, Postman, Swagger, Azure, n8n

## 🔧 Tecnologías Utilizadas

- **Framework**: [Astro](https://astro.build/) - Framework web moderno para contenido estático
- **Estilos**: [Tailwind CSS](https://tailwindcss.com/) - Framework de CSS utilitario
- **Tipografía**: [Onest Font](https://onest.dev/) - Fuente variable moderna
- **Optimización**: Generación de sitemap y robots.txt automática
- **Despliegue**: Preparado para despliegue estático

## 🌟 Características

- ✨ **Diseño Responsivo**: Optimizado para todos los dispositivos
- 🌙 **Modo Oscuro**: Cambio automático según preferencias del usuario
- 🚀 **Rendimiento Optimizado**: Carga rápida y experiencia fluida
- 📱 **Progressive Web App**: Instalable en dispositivos móviles
- 🎨 **Interfaz Moderna**: Diseño limpio y profesional
- 📊 **Secciones Organizadas**: Experiencia, proyectos y información personal

## 📂 Estructura de Proyectos

### Backend
- **AppEventos**: Sistema de gestión de eventos con Spring Boot MVC
- **AppCajero**: Simulador de cajero automático con Spring Boot

### Frontend
- **QuizzDAW**: Aplicación de tests educativos con HTML, CSS y JavaScript

### Full Stack
- **EasyFit**: Aplicación de fitness con Angular y Spring Boot
- **FullJob**: Plataforma de búsqueda de empleo

## 💼 Experiencia Profesional

### Euro Kaizen SL (Marzo 2025 - Junio 2025)
**Desarrollador Backend**
- Actualización de ERP de .NET Core 3.1 a .NET 8
- Implementación de herramientas de IA para optimizar desarrollo
- Desarrollo de workflows automatizados con n8n
- Reducción del tiempo de desarrollo en 4 semanas

### Formación Académica
**Grado Superior en Desarrollo de Aplicaciones Web** - UNIR (2023-2025)

### Experiencia Emprendedora
**TheSoleJungle** - Ecommerce propio (2020-2022)
- Gestión completa de negocio online
- Desarrollo y mantenimiento de sitio web
- Marketing digital y redes sociales

## 🚀 Instalación y Configuración

### Prerrequisitos

- [Node.js](https://nodejs.org/) (versión 18 o superior)
- [pnpm](https://pnpm.io/) (recomendado) o npm

### Instalación

```bash
# Clonar el repositorio
git clone https://github.com/pablopl94/portfolio.dev.git

# Navegar al directorio
cd portfolio.dev

# Instalar dependencias
pnpm install
```

### Comandos Disponibles

```bash
# Desarrollo
pnpm dev          # Inicia el servidor de desarrollo
pnpm start        # Alias para pnpm dev

# Producción
pnpm build        # Construye el proyecto para producción
pnpm preview      # Previsualiza la build de producción

# Otros
pnpm astro        # Ejecuta comandos de Astro CLI
```

## 📁 Estructura del Proyecto

```
porfolio.dev/
├── public/
│   ├── favicon.svg
│   ├── yo.webp
│   ├── PabloPrietoLopez_CV.pdf
│   ├── icons/
│   └── projects/
│       ├── backend/
│       ├── frontend/
│       └── fullstack/
├── src/
│   ├── components/
│   │   ├── AboutMe.astro
│   │   ├── Experience.astro
│   │   ├── Hero.astro
│   │   ├── Projects.astro
│   │   └── icons/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
├── astro.config.mjs
├── tailwind.config.mjs
└── package.json
```

## 🎨 Personalización

### Modificar Información Personal

1. **Datos personales**: Editar `src/components/Hero.astro`
2. **Experiencia laboral**: Actualizar `src/components/Experience.astro`
3. **Proyectos**: Modificar `src/components/Projects.astro`
4. **Sobre mí**: Cambiar `src/components/AboutMe.astro`

### Añadir Nuevos Proyectos

```javascript
// En src/components/Projects.astro
const NUEVO_PROYECTO = {
  title: "Nombre del Proyecto",
  description: "Descripción del proyecto",
  github: "https://github.com/usuario/repositorio",
  images: ["/projects/carpeta/imagen.webp"],
  tags: [TAGS.TECNOLOGIA]
};
```

### Personalizar Estilos

Los estilos se gestionan con Tailwind CSS. Puedes:
- Modificar `tailwind.config.mjs` para personalizar el tema
- Añadir nuevas clases en los componentes Astro
- Personalizar el modo oscuro en cada componente

## 🌐 Despliegue

### Netlify (Recomendado)

1. Conecta tu repositorio con Netlify
2. Configura el comando de build: `pnpm build`
3. Directorio de publicación: `dist`

### Vercel

1. Importa el proyecto en Vercel
2. Selecciona Astro como framework
3. Despliega automáticamente

### GitHub Pages

```bash
# Instalar adaptador para GitHub Pages
pnpm add @astrojs/github-pages

# Configurar en astro.config.mjs
import { defineConfig } from 'astro/config'
import githubPages from '@astrojs/github-pages'

export default defineConfig({
  integrations: [githubPages()],
  site: 'https://tu-usuario.github.io/portfolio.dev'
})
```

## 📈 Optimizaciones Incluidas

- ⚡ **Renderizado Estático**: Generación estática para máximo rendimiento
- 🖼️ **Optimización de Imágenes**: Formato WebP para menor peso
- 🎯 **SEO Optimizado**: Meta tags, sitemap y robots.txt
- 📱 **Diseño Responsivo**: Adaptado a todos los dispositivos
- 🌙 **Modo Oscuro**: Cambio automático según preferencias
- 🚀 **Core Web Vitals**: Optimizado para métricas de Google

## 🤝 Contribuciones

Si encuentras algún bug o tienes sugerencias de mejora:

1. Fork el proyecto
2. Crea una branch para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la branch (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.

## 📞 Contacto

**Pablo Prieto López**

- 💼 [LinkedIn](https://linkedin.com/in/pablopl94)
- 🐙 [GitHub](https://github.com/pablopl94)
- 📧 Email: [Disponible en CV](./public/PabloPrietoLopez_CV.pdf)
- 🌐 Portfolio: [En línea próximamente]

---

<div align="center">

**¿Te gusta mi trabajo? ¡No dudes en contactarme para nuevas oportunidades!**

⭐ **Disponible para trabajar** ⭐

</div>
