# estudios-sociales
Temas de práctica para tercer grado
# 🌊 Nuestras Costas - Costa Rica

Juego educativo para niños de tercer grado

## 🎯 Descripción del Proyecto

**"Nuestras Costas"** es un juego educativo interactivo diseñado para estudiantes de tercer grado de primaria en la materia de **Estudios Sociales**. El juego tiene como objetivo reforzar el aprendizaje sobre las características geográficas de las costas de Costa Rica, incluyendo aspectos del Océano Pacífico y el Mar Caribe.

### 🌟 Características Principales

- ✅ **Aprendizaje Lúdico**: Aprende mientras juegas y te diviertes
- 🎯 **Retroalimentación Inmediata**: Recibe explicaciones detalladas en cada respuesta
- 📊 **Sistema de Puntaje**: Motiva al estudiante con puntuación en tiempo real
- 🎨 **Interfaz Amigable**: Diseño colorido y atractivo para niños
- 📱 **Responsive**: Funciona en computadoras, tablets y teléfonos móviles
- 🔄 **Reinicio Rápido**: Permite repetir el juego para practicar

## 📚 Módulos del Proyecto

El proyecto está estructurado en **cinco módulos** que trabajan de manera integrada para ofrecer una experiencia educativa completa:

### 1. 🗂️ Módulo de Datos (Affirmations)

**Ubicación**: `statements` array en el código JavaScript

**Función**: Contiene las 10 afirmaciones educativas sobre las costas de Costa Rica, cada una con su valor de verdad (Verdadero/Falso).

**Ejemplos de contenido**:
- ✅ "Las costas de Costa Rica están en el océano Pacífico y en el mar Caribe." → **Verdadero**
- ❌ "La costa del Pacífico mide aproximadamente 212 km." → **Falso**
- ✅ "La costa del Caribe se extiende desde punta Castilla hasta el río Sixaola." → **Verdadero**

### 2. 🎮 Módulo de Lógica del Juego (Game Engine)

**Ubicación**: Funciones JavaScript principales (`initGame`, `renderDeck`, `setupDropZones`)

**Función**: Gestiona el flujo completo del juego incluyendo:
- Mezcla aleatoria de las afirmaciones
- Control del estado del juego (carta actual, puntaje, finalización)
- Gestión del drag & drop
- Validación de respuestas

### 3. 🖼️ Módulo de Interfaz (UI Module)

**Ubicación**: Elementos HTML y CSS de la interfaz

**Función**: Proporciona la experiencia visual del juego con:
- **Columna "Verdadero"**: Zona de destino para respuestas correctas
- **Columna "Falso"**: Zona de destino para respuestas incorrectas
- **Mazo Central**: Muestra la afirmación actual a evaluar
- **Área de Puntaje**: Muestra la puntuación en tiempo real
- **Botón de Reinicio**: Permite comenzar de nuevo

### 4. 📢 Módulo de Retroalimentación (Feedback Module)

**Ubicación**: Sistema de modales y funciones `showFeedbackModal`, `showFinalModal`

**Función**: Brinda retroalimentación educativa al estudiante:
- ✅ **Respuestas Correctas**: Mensaje de felicitación y confirmación
- ❌ **Respuestas Incorrectas**: Explicación detallada del error
- 🏁 **Final del Juego**: Resumen del puntaje y mensaje motivador

**Características especiales**:
- Explicaciones personalizadas para cada afirmación falsa
- Mensajes motivadores según el puntaje obtenido
- Diseño claro y amigable para niños

### 5. 🎨 Módulo de Estilos (Styling Module)

**Ubicación**: CSS integrado en el archivo HTML

**Función**: Define la identidad visual del juego:
- **Paleta de colores**: Azules marinos, amarillos cálidos y verdes
- **Efectos visuales**: Sombras, gradientes, transparencias
- **Adaptabilidad**: Diseño responsive para diferentes dispositivos
- **Accesibilidad**: Fuentes grandes y legibles, botones grandes para facilitar el uso

## 🎮 Cómo Jugar

1. **Lee la afirmación**: En el mazo central aparece una afirmación sobre las costas de Costa Rica
2. **Decide tu respuesta**: Piensa si la afirmación es Verdadera o Falsa
3. **Arrastra la tarjeta**: Toma la tarjeta y arrástrala hacia la columna que corresponda
4. **Recibe retroalimentación**: Aparecerá un modal con la respuesta correcta y una explicación
5. **Continúa**: Después de cada respuesta, aparecerá una nueva afirmación
6. **Completa el juego**: Al terminar las 10 afirmaciones, verás tu puntaje final

## 🛠️ Tecnologías Utilizadas

| Tecnología | Uso |
|------------|-----|
| **HTML5** | Estructura del juego |
| **CSS3** | Estilos y diseño visual |
| **JavaScript** | Lógica del juego, drag & drop, interactividad |
| **W3.CSS** | Sistema de modales para retroalimentación |
| **Drag & Drop API** | Interacción de arrastrar y soltar |

## 📋 Requisitos del Sistema

- 🌐 Navegador web moderno (Chrome, Firefox, Safari, Edge)
- 📱 Conexión a internet (para cargar W3.CSS desde CDN)
- 💻 Dispositivo con capacidad de arrastrar (mouse o pantalla táctil)

## 🚀 Instalación y Uso

### Opción 1: Usar directamente desde GitHub Pages