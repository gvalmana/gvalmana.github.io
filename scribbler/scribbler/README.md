# CV Web - Gustavo Valmaña Villalonga

CV personal en formato web desarrollado con la plantilla Scribbler, optimizado para GitHub Pages.

## 🚀 Características

- ✅ Diseño moderno y responsivo
- ✅ Totalmente adaptable a dispositivos móviles
- ✅ Secciones organizadas: Perfil, Experiencia, Habilidades, Formación
- ✅ Enlaces a redes sociales integrados
- ✅ Optimizado para GitHub Pages
- ✅ SEO optimizado con meta tags

## 📋 Contenido

El CV incluye las siguientes secciones:

1. **Hero Section**: Presentación principal con terminal interactiva
2. **Sobre mí**: Perfil profesional y datos de contacto
3. **Competencias Técnicas**: Habilidades organizadas por categorías
4. **Redes Sociales**: Enlaces a GitHub, LinkedIn, YouTube, Twitter, Facebook y Twitch
5. **Experiencia Laboral**: Historial profesional detallado
6. **Formación Académica**: Títulos y estudios universitarios
7. **Cursos y Certificaciones**: Formación complementaria
8. **Habilidades Profesionales**: Soft skills y conocimientos específicos
9. **Referencias**: Contactos profesionales

## 🌐 Publicar en GitHub Pages

### Opción 1: Repositorio nuevo

1. **Crear un nuevo repositorio en GitHub**

   ```bash
   # En tu terminal, navega al directorio
   cd /home/sysadmin/Documentos/TRABAJO/PERSONALES/CV-WEB/scribbler/scribbler

   # Inicializa el repositorio
   git init

   # Agrega todos los archivos
   git add .

   # Haz el primer commit
   git commit -m "Initial commit: CV personal"

   # Crea el repositorio en GitHub y conecta el remoto
   git remote add origin https://github.com/gvalmana/tu-repositorio.git

   # Sube los cambios
   git branch -M main
   git push -u origin main
   ```

2. **Configurar GitHub Pages**
   - Ve a la configuración de tu repositorio en GitHub
   - Navega a la sección "Pages" en el menú lateral
   - En "Source", selecciona la rama `main` y la carpeta `/ (root)`
   - Haz clic en "Save"
   - Tu sitio estará disponible en: `https://gvalmana.github.io/tu-repositorio/`

### Opción 2: Repositorio de usuario (Recomendado)

Para tener una URL más limpia como `https://gvalmana.github.io/`:

1. **Crear repositorio con nombre especial**

   - Crea un repositorio llamado exactamente: `gvalmana.github.io`
   - Este será tu sitio personal

2. **Subir los archivos**

   ```bash
   cd /home/sysadmin/Documentos/TRABAJO/PERSONALES/CV-WEB/scribbler/scribbler

   git init
   git add .
   git commit -m "Initial commit: CV personal"
   git remote add origin https://github.com/gvalmana/gvalmana.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. **Acceder al sitio**
   - Automáticamente estará disponible en: `https://gvalmana.github.io/`
   - No necesitas configurar nada adicional

## 📝 Estructura de archivos

```
scribbler/
├── index.html              # Página principal del CV
├── scribbler-global.css    # Estilos globales
├── scribbler-landing.css   # Estilos específicos de la landing
├── scribbler.js           # JavaScript para interactividad
├── logo.svg               # Logo (opcional)
└── README.md              # Este archivo
```

## 🎨 Personalización

### Modificar colores

Edita el archivo `scribbler-global.css` en las variables CSS:

```css
:root {
  --primary-color: #432e30;
  --accent-color: #fe6a6b;
  /* ... otros colores ... */
}
```

### Actualizar contenido

Edita el archivo `index.html` para modificar:

- Información personal
- Experiencia laboral
- Habilidades
- Formación académica
- Enlaces a redes sociales

### Añadir favicon

1. Crea o descarga un favicon (archivo `.ico` o `.png`)
2. Colócalo en el directorio raíz
3. Agrega en el `<head>` de `index.html`:

```html
<link rel="icon" type="image/png" href="favicon.png" />
```

## 🔧 Desarrollo local

Para visualizar el sitio localmente:

```bash
# Opción 1: Servidor Python simple
cd /home/sysadmin/Documentos/TRABAJO/PERSONALES/CV-WEB/scribbler/scribbler
python3 -m http.server 8000

# Opción 2: Servidor Node.js
npx http-server -p 8000

# Abre en el navegador: http://localhost:8000
```

## 📱 Responsive Design

El sitio está optimizado para diferentes dispositivos:

- 📱 Móviles (< 600px)
- 📱 Tablets (600px - 750px)
- 💻 Desktop (> 750px)

## 🔍 SEO y Meta Tags

El sitio incluye:

- Meta descripción optimizada
- Keywords relevantes
- Open Graph tags (opcional, puedes añadirlos)
- Título descriptivo

## 📄 Licencia

Este CV es personal y privado. La plantilla Scribbler es de uso libre.

## 👤 Contacto

**Gustavo Valmaña Villalonga**

- 📧 Email: (agrega tu email si lo deseas)
- 📱 Teléfono: +52 934 100 1693
- 🔗 LinkedIn: [Ver perfil](https://www.linkedin.com/in/gustavo-valma%C3%B1a-villalonga-9a5b95119/)
- 🐙 GitHub: [gvalmana](https://github.com/gvalmana)

---

**Última actualización:** Octubre 2024
