# Gabriel Falciola - Perfil de Baterista

Este es tu sitio web profesional como baterista, diseñado para mostrar tu trabajo musical, discografía, videos y samples.

## 🚀 Cómo publicar en GitHub Pages

### 1. Crear el repositorio
1. Ve a [GitHub](https://github.com) y crea un nuevo repositorio
2. Nómbralo como `gabriel-falciola-drummer` o el nombre que prefieras
3. Marca la opción "Add a README file"

### 2. Subir los archivos
1. Sube el archivo `drummer-profile.html` a tu repositorio
2. Sube tu foto de perfil como `profile.jpg`
3. Opcionalmente, puedes renombrar `drummer-profile.html` a `index.html` para que sea la página principal

### 3. Activar GitHub Pages
1. Ve a Settings (Configuración) en tu repositorio
2. Busca la sección "Pages" en el menú lateral
3. En "Source", selecciona "Deploy from a branch"
4. Selecciona la rama "main" y la carpeta "/ (root)"
5. Haz clic en "Save"

### 4. Acceder a tu sitio
Tu sitio estará disponible en: `https://tu-usuario.github.io/nombre-del-repositorio/`

## 🎨 Personalización

### Contenido ya incluido:

#### ✅ **Información Personal Actualizada**
- Biografía con tu trayectoria real desde 1992
- Formación completa (autodidacta, clases con Rubén "Mosca" Bloise, EPM)
- Experiencia en múltiples géneros musicales

#### ✅ **Trayectoria Musical Completa**
- Sección de formación con todos tus estudios
- Todas tus bandas desde Caballo Espíritu hasta Honduras
- Links a sitios web reales de los proyectos

#### ✅ **Discografía Real**
- Honduras con sus dos discos
- Caballo Espíritu como pioneros del grunge argentino
- Marania y otros proyectos con links funcionales

#### ✅ **Video de Honduras**
- Video oficial de YouTube ya integrado
- Placeholders específicos para otros proyectos

#### ✅ **Samples por Género**
- Específicos para cada estilo que has tocado
- Referencias a tus bandas reales

### Próximos pasos de personalización:

#### 1. **Completar Videos**
- Buscar y agregar videos de Caballo Espíritu
- Grabaciones del ensamble de jazz de EPM
- Videos de El Arca tocando Pink Floyd

#### 2. **Agregar Samples de Audio**
- Subir archivos MP3 de cada estilo
- Reemplazar placeholders con elementos `<audio>` reales
- Ejemplo: `<audio controls><source src="audio/grunge-sample.mp3" type="audio/mpeg"></audio>`

#### 3. **Actualizar Links de Redes Sociales**
- YouTube personal
- Instagram musical
- SoundCloud si tienes
- Spotify de tus proyectos

#### 4. **Agregar Más Fotos**
- Foto de perfil actual
- Fotos con las bandas
- Fotos del setup de batería

### Estructura de archivos recomendada:
```
tu-repositorio/
├── index.html (o drummer-profile.html)
├── profile.jpg
├── images/
│   ├── album1.jpg
│   ├── album2.jpg
│   └── live-photo.jpg
├── audio/
│   ├── sample-rock.mp3
│   ├── sample-jazz.mp3
│   └── sample-pop.mp3
└── README.md
```

## 🔧 Funcionalidades incluidas

- **Diseño responsive** - Se adapta a móviles y tablets
- **Navegación suave** - Scroll suave entre secciones
- **Estilo moderno** - Diseño dark con acentos de color
- **Grid layout** - Organización en tarjetas para contenido
- **Optimizado para SEO** - Meta tags apropiados

## 📱 Agregar contenido multimedia

### Para videos de YouTube:
```html
<iframe width="100%" height="200" 
        src="https://www.youtube.com/embed/TU_VIDEO_ID" 
        frameborder="0" allowfullscreen></iframe>
```

### Para archivos de audio:
```html
<audio controls style="width: 100%;">
    <source src="audio/tu-sample.mp3" type="audio/mpeg">
    Tu navegador no soporta audio HTML5.
</audio>
```

### Para links de streaming:
```html
<a href="https://open.spotify.com/album/TU_ALBUM_ID" target="_blank">
    🎵 Escuchar en Spotify
</a>
```

## 🎯 Próximos pasos

1. **Personaliza el contenido** con tu información real
2. **Sube archivos multimedia** (fotos, audio, videos)
3. **Actualiza links** de redes sociales y plataformas
4. **Prueba el sitio** en diferentes dispositivos
5. **Comparte tu URL** con contactos y colaboradores

## 💡 Ideas adicionales

- Agregar una sección de "Equipamiento" con tu setup de batería
- Incluir testimonios de músicos con los que has trabajado
- Agregar un blog/news section para actualizaciones
- Implementar un formulario de contacto funcional
- Integrar con Google Analytics para estadísticas

¡Tu sitio web profesional como baterista está listo para ser personalizado y publicado! 