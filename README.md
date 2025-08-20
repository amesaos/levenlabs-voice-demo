# ElevenLabs Voice AI Demo Landing Page

Una landing page moderna y responsive que integra el widget conversacional de ElevenLabs para permitir interacciones de voz con IA.

## 🚀 Demo en Vivo

Una vez desplegado en GitHub Pages, tu sitio estará disponible en: `https://tu-usuario.github.io/elevenlabs-widget`

## 📁 Estructura del Proyecto

```
elevenlabs-widget/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
└── README.md          # Documentación
```

## 🛠️ Cómo Desplegar en GitHub Pages

### Paso 1: Crear Repositorio en GitHub
1. Ve a [GitHub](https://github.com) e inicia sesión
2. Clic en "New repository" (botón verde)
3. Nombre del repositorio: `elevenlabs-widget` (o el nombre que prefieras)
4. Marca como **Public**
5. NO inicialices con README (ya tienes uno)
6. Clic en "Create repository"

### Paso 2: Subir los Archivos
Desde tu terminal, en la carpeta del proyecto:

```bash
git init
git add .
git commit -m "Initial commit: ElevenLabs landing page"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/elevenlabs-widget.git
git push -u origin main
```

### Paso 3: Activar GitHub Pages
1. En tu repositorio de GitHub, ve a **Settings**
2. Scroll hacia abajo hasta **Pages** (en el menú lateral)
3. En "Source", selecciona **Deploy from a branch**
4. Selecciona **main** branch
5. Selecciona **/ (root)**
6. Clic en **Save**

### Paso 4: Acceder a tu Sitio
En unos minutos, tu sitio estará disponible en:
`https://TU-USUARIO.github.io/elevenlabs-widget`

## 🎨 Características

- **Diseño Responsive**: Se adapta a móviles, tablets y desktop
- **Widget ElevenLabs Integrado**: Conversación de voz con IA
- **Diseño Moderno**: Gradientes, glassmorphism y animaciones
- **Carga Rápida**: CSS vanilla optimizado
- **SEO Friendly**: Meta tags apropiados

## 🔧 Personalización

### Cambiar el Agent ID
En `index.html`, línea 31, reemplaza el `agent-id`:
```html
<elevenlabs-convai agent-id="TU_NUEVO_AGENT_ID"></elevenlabs-convai>
```

### Modificar Textos
Edita los textos en `index.html`:
- Título principal (línea 12)
- Subtítulo (línea 13)  
- Descripción (líneas 14-18)

### Cambiar Colores
En `styles.css`, modifica el gradiente de fondo (línea 13):
```css
background: linear-gradient(135deg, #TU_COLOR1 0%, #TU_COLOR2 100%);
```

## 📱 Compatibilidad

- ✅ Chrome, Firefox, Safari, Edge (últimas versiones)
- ✅ iOS Safari, Chrome Mobile
- ✅ Responsive design para todos los tamaños de pantalla

## 🆘 Solución de Problemas

**El widget no aparece:**
- Verifica que el `agent-id` sea correcto
- Asegúrate de que el agente esté activo en ElevenLabs

**GitHub Pages no funciona:**
- Espera 5-10 minutos después de activarlo
- Verifica que el repositorio sea público
- Comprueba que `index.html` esté en la raíz del proyecto

## 📄 Licencia

Este proyecto es de código abierto. Úsalo libremente para tus propios proyectos.