# 🇪🇨 Selección Ecuatoriana de Fútbol — App Móvil

Aplicación móvil básica desarrollada con **React Native + Expo Go** es una práctica de entorno de desarrollo móvil.

## 📱 Pantallas

### Splash Screen
- Animación de entrada (fade + spring scale)
- Colores de la bandera ecuatoriana (amarillo, azul, rojo)
- Logo FEF con bandera
- Redirección automática a Home tras 3 segundos

### Home Screen
- Header con identificación de La Tri
- Grid de estadísticas del equipo
- Historial de Mundiales FIFA
- Lista de jugadores destacados (con Alert al presionar)
- Información general del equipo

## 🛠 Tecnologías

- React Native
- Expo SDK 50
- React Navigation (Native Stack)
- Animated API (React Native)

## 🚀 Instalación y ejecución

```bash
# Clonar el repositorio
git clone https://github.com/TU_USUARIO/seleccion-ecuador.git
cd seleccion-ecuador

# Instalar dependencias
npm install

# Iniciar el servidor de desarrollo
npx expo start
```

Escanea el código QR con la app **Expo Go** en tu dispositivo.

## 📁 Estructura del proyecto

```
seleccion-ecuador/
├── App.js                  # Punto de entrada, configuración de navegación
├── app.json                # Configuración de Expo
├── babel.config.js         # Configuración de Babel
├── package.json            # Dependencias
├── assets/                 # Recursos estáticos (íconos, imágenes)
└── screens/
    ├── SplashScreen.js     # Pantalla de bienvenida animada
    └── HomeScreen.js       # Pantalla principal con info del equipo
```

## 👨‍💻 Autor

Senior Over junto ocn Claude y con React Native y Expo.
