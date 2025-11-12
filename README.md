# 🎵 AYDS25-SongInfo

<div align="center">
  <h3>🎶 Aplicación Android para información de canciones 🎶</h3>
  <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android"/>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Room-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Room"/>
</div>

## 📖 Descripción
AYDS25-SongInfo es una aplicación Android desarrollada en Kotlin que permite buscar y obtener información detallada sobre canciones. La aplicación utiliza arquitectura modular con el patrón Observer para la comunicación entre componentes.

## ✨ Características
- Búsqueda de información de canciones
- Integración con APIs externas para obtener datos musicales
- Almacenamiento local con Room Database
- Carga de imágenes con Picasso
- Arquitectura modular con patrón Observer
- Interfaz de usuario moderna con Material Design

## 🛠️ Tecnologías Utilizadas
- **🎯 Lenguaje:** Kotlin
- **📱 Framework:** Android SDK
- **💾 Base de datos:** Room Database
- **🌐 Networking:** Retrofit + Gson
- **🖼️ Imágenes:** Picasso
- **🏗️ Arquitectura:** Observer Pattern
- **🧪 Testing:** JUnit, MockK

## Estructura del Proyecto
```
AYDS25-SongInfo/
├── app/                    # Módulo principal de la aplicación
│   └── src/
│       ├── main/
│       │   └── java/ayds/songinfo/
│       │       ├── home/           # Pantalla principal
│       │       ├── moredetails/    # Detalles de canciones
│       │       └── utils/          # Utilidades
│       └── test/                   # Tests unitarios
└── observer/               # Módulo del patrón Observer
```

## 📋 Requisitos del Sistema
- **📱 Android API Level:** Mínimo 26 (Android 8.0)
- **🎯 Target SDK:** 34
- **☕ Java Version:** 1.8

## 🚀 Instalación y Configuración
1. Clona el repositorio
2. Abre el proyecto en Android Studio
3. Sincroniza las dependencias de Gradle
4. Conecta un dispositivo Android o inicia un emulador
5. Ejecuta la aplicación

## 🔨 Compilación
```bash
./gradlew build
```

## 🧪 Ejecución de Tests
```bash
./gradlew test
```

## 🏛️ Arquitectura
El proyecto utiliza una arquitectura modular basada en el patrón Observer:
- **Módulo App:** Contiene la lógica principal de la aplicación
- **Módulo Observer:** Implementa el patrón Observer para la comunicación entre componentes

## Dependencias Principales
- AndroidX Core KTX
- AndroidX AppCompat
- Material Design Components
- Retrofit para llamadas HTTP
- Room Database para persistencia
- Picasso para carga de imágenes
- MockK para testing

## Contribución
Este proyecto forma parte del curso AYDS (Análisis y Diseño de Sistemas) 2025. Para contribuir:
1. Crear un fork del repositorio
2. Crear una rama para la nueva funcionalidad
3. Realizar los cambios
4. Enviar un pull request

## Licencia
Este proyecto es para fines educativos como parte del curso AYDS 2025.