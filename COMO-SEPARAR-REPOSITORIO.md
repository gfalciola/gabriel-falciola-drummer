# Cómo Separar el Perfil de Baterista en un Repositorio Independiente

## 🎯 Objetivo
Crear un repositorio completamente separado para tu perfil de baterista, independiente del currículum profesional.

## 📋 Pasos para crear el repositorio separado

### 1. Crear el nuevo repositorio en GitHub
1. Ve a [GitHub](https://github.com)
2. Crea un nuevo repositorio llamado `gabriel-falciola-drummer`
3. **NO** inicialices con README (ya tienes uno)
4. **NO** agregues .gitignore (ya tienes uno)

### 2. Preparar los archivos localmente
Los archivos ya están organizados en el directorio `drummer-profile/`:
```
drummer-profile/
├── index.html          # Página principal
├── README.md           # Documentación
├── profile.jpg         # Foto de perfil
├── .gitignore          # Configuración de Git
├── audio/              # Samples de audio (vacío por ahora)
├── images/             # Imágenes adicionales (vacío por ahora)
└── videos/             # Videos locales (vacío por ahora)
```

### 3. Inicializar Git en el directorio del baterista
```bash
cd drummer-profile
git init
git add .
git commit -m "Initial commit: Gabriel Falciola - Drummer Profile"
```

### 4. Conectar con el repositorio remoto
```bash
git remote add origin https://github.com/TU-USUARIO/gabriel-falciola-drummer.git
git branch -M main
git push -u origin main
```

### 5. Activar GitHub Pages
1. Ve a Settings > Pages en tu nuevo repositorio
2. Selecciona "Deploy from a branch"
3. Selecciona la rama "main" y carpeta "/ (root)"
4. Tu sitio estará en: `https://tu-usuario.github.io/gabriel-falciola-drummer/`

## 🔄 Resultado Final

### Repositorio Principal (Sistema/IT)
- **Nombre**: `gabriel-falciola-resume`
- **URL**: `https://tu-usuario.github.io/gabriel-falciola-resume/`
- **Contenido**: Currículum profesional IT/Management

### Repositorio Baterista
- **Nombre**: `gabriel-falciola-drummer`
- **URL**: `https://tu-usuario.github.io/gabriel-falciola-drummer/`
- **Contenido**: Perfil musical completo

## 🧹 Limpieza del repositorio original
Una vez que hayas creado el repositorio separado del baterista, puedes eliminar el directorio `drummer-profile/` del repositorio original:

```bash
cd ..  # Regresar al directorio del currículum
rm -rf drummer-profile/
git add .
git commit -m "Remove drummer profile - moved to separate repository"
git push
```

## 🎵 Próximos pasos para el perfil de baterista
1. Agregar samples de audio en `audio/`
2. Subir más fotos en `images/`
3. Agregar más videos de YouTube
4. Actualizar links de redes sociales
5. Agregar más información sobre equipamiento

## 📝 Notas importantes
- Los dos repositorios serán completamente independientes
- Cada uno tendrá su propia URL de GitHub Pages
- Puedes mantener estilos y enfoques diferentes
- Las actualizaciones se hacen por separado
- Mejor organización para diferentes audiencias 