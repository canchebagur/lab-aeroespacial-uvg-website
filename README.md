# Sitio Web del Laboratorio Aeroespacial UVG

[![Hugo](https://img.shields.io/badge/Hugo-0.110+-blue.svg)](https://gohugo.io)
[![HugoBlox](https://img.shields.io/badge/HugoBlox-Latest-green.svg)](https://hugoblox.com)

Sitio web oficial del **Laboratorio Aeroespacial de la Universidad del Valle de Guatemala**, construido con HugoBlox (anteriormente Wowchemy) y Hugo.

## 🚀 Acerca del Laboratorio

El Laboratorio Aeroespacial de la UVG es un espacio de investigación y desarrollo dedicado a la tecnología espacial, nanosatélites y sistemas embebidos. Este sitio web presenta nuestros proyectos, equipo de trabajo, publicaciones y actividades.

## 📋 Características del Sitio

- **Página de inicio** con información destacada del laboratorio
- **Proyectos** de investigación y desarrollo
- **Equipo** con perfiles de investigadores y colaboradores
- **Publicaciones** académicas y técnicas
- **Blog** con noticias y actualizaciones
- **Formulario de contacto** integrado
- **Responsive** y optimizado para dispositivos móviles

## 🛠️ Tecnologías Utilizadas

- [Hugo](https://gohugo.io/) - Generador de sitios estáticos
- [HugoBlox](https://hugoblox.com) - Framework y constructor de páginas
- [Formspree](https://formspree.io) - Gestión de formularios de contacto

## 📦 Instalación y Desarrollo Local

### Requisitos previos
- Hugo Extended v0.110.0 o superior
- Go 1.19 o superior (opcional)

### Pasos de instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu-usuario/laboratorio-aeroespacial-uvg.git
cd laboratorio-aeroespacial-uvg
```

2. Instala las dependencias de Hugo:
```bash
hugo mod get -u
```

3. Inicia el servidor de desarrollo:
```bash
hugo server
```

4. Abre tu navegador en `http://localhost:1313`

## 📝 Estructura del Proyecto
```
.
├── content/           # Contenido del sitio (páginas, posts, proyectos)
│   ├── authors/      # Perfiles de miembros del equipo
│   ├── project/      # Proyectos del laboratorio
│   ├── publication/  # Publicaciones académicas
│   └── post/         # Blog y noticias
├── assets/           # Recursos (CSS, JS, imágenes)
├── config/           # Archivos de configuración
└── static/           # Archivos estáticos
```

## ✏️ Cómo Actualizar Contenido

### Agregar un nuevo miembro del equipo
1. Crea una carpeta en `content/authors/nombre-apellido/`
2. Agrega el archivo `_index.md` con la información del miembro
3. Incluye una foto de perfil `avatar.jpg`

### Agregar un nuevo proyecto
1. Crea una carpeta en `content/project/nombre-proyecto/`
2. Agrega el archivo `index.md` con los detalles del proyecto
3. Incluye imágenes relevantes en la misma carpeta

### Publicar una noticia
1. Crea un archivo en `content/post/titulo-noticia/index.md`
2. Agrega las imágenes en la misma carpeta
3. Actualiza el front matter con título, fecha y resumen

## 🚀 Despliegue

El sitio puede desplegarse en múltiples plataformas:

- **GitHub Pages**: Usa GitHub Actions para despliegue automático
- **Vercel**: Conecta el repositorio para despliegue continuo
- **Netlify**: Similar a Vercel, con configuración automática

### Construcción para producción
```bash
hugo --minify
```

Los archivos generados estarán en la carpeta `public/`.

## 👥 Equipo

Este sitio es mantenido por el equipo del Laboratorio Aeroespacial de la UVG.

**Coordinador**: MSc. José Bagur  
**Contacto**: satelite@uvg.edu.gt

## 📄 Licencia

Copyright © 2025 Universidad del Valle de Guatemala. Todos los derechos reservados.

## 🔗 Enlaces Útiles

- [Sitio web de la UVG](https://www.uvg.edu.gt)
- [Documentación de HugoBlox](https://docs.hugoblox.com/)
- [Comunidad de Hugo](https://discourse.gohugo.io)

## 📞 Contacto

Para preguntas o sugerencias sobre el sitio web:
- **Email**: satelite@uvg.edu.gt
- **Teléfono**: +502 2507-1500 Ext. 21284
- **Ubicación**: CIT-115A, Campus Central de la UVG

---

Desarrollado con ❤️ desde Guatemala por el equipo del Laboratorio Aeroespacial UVG
