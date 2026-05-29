[README.md](https://github.com/user-attachments/files/28372265/README.md)

# 📱 CalificacionApp

Aplicación Android desarrollada en **Java** con **Android Studio** que convierte una calificación numérica (0–100) a su equivalente en letra (**A, B, C o F**).

---

## 👨‍💻 Desarrollador

| Campo       | Detalle        |
|-------------|----------------|
| Matrícula   | 2021-1754      |
| Lenguaje    | Java           |
| Plataforma  | Android        |
| IDE         | Android Studio |

---

## 📋 Descripción

CalificacionApp es una aplicación móvil sencilla e intuitiva que permite al estudiante ingresar una calificación numérica y obtener de forma inmediata su equivalente en letra, siguiendo la escala académica estándar.

---

## 🎯 Escala de calificaciones

| Rango     | Letra | Significado |
|-----------|-------|-------------|
| 90 – 100  | **A** | Excelente   |
| 80 – 89   | **B** | Muy bien    |
| 70 – 79   | **C** | Aprobado    |
| 0 – 69    | **F** | Reprobado   |

---

## ✨ Funcionalidades

- ✅ Ingreso de calificación numérica con teclado decimal
- ✅ Conversión instantánea a letra al presionar el botón
- ✅ Validación de entradas (vacío, texto, fuera de rango)
- ✅ Código de colores por resultado (verde, azul, naranja, rojo)
- ✅ Tabla de equivalencias visible en pantalla
- ✅ Interfaz personalizada con foto y datos del estudiante

---

## 🛠️ Tecnologías utilizadas

- Java
- Android SDK 34
- AndroidX / AppCompat
- Material Components
- CardView

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/CalificacionApp.git
   ```
2. Abre **Android Studio** y selecciona **"Open"**.
3. Navega hasta la carpeta `CalificacionApp` y haz clic en **OK**.
4. Haz clic en **"Trust Project"** cuando se solicite.
5. Espera a que **Gradle** sincronice las dependencias.
6. Presiona ▶ **Run** (`Shift + F10`) y selecciona un emulador o dispositivo físico.

---

## 📁 Estructura del proyecto

```
CalificacionApp/
├── app/
│   ├── src/
│   │   └── main/
│   │       ├── java/com/example/calificacionapp/
│   │       │   └── MainActivity.java
│   │       ├── res/
│   │       │   ├── drawable/
│   │       │   │   ├── foto_perfil.png
│   │       │   │   ├── button_background.xml
│   │       │   │   ├── circle_border.xml
│   │       │   │   ├── input_background.xml
│   │       │   │   └── result_background.xml
│   │       │   ├── layout/
│   │       │   │   └── activity_main.xml
│   │       │   └── values/
│   │       │       ├── colors.xml
│   │       │       ├── strings.xml
│   │       │       └── themes.xml
│   │       └── AndroidManifest.xml
│   └── build.gradle
├── build.gradle
├── settings.gradle
├── gradle.properties
└── README.md
```

---


## 📄 Licencia

Este proyecto fue desarrollado con fines académicos.
