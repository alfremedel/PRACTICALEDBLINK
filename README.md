# LectorNoticias - Aplicación Móvil en Android

Aplicación móvil desarrollada en **Android** (Java) que consume una API remota para mostrar una lista dinámica de publicaciones o noticias utilizando componentes modernos de la interfaz de usuario como `RecyclerView` y adaptadores personalizados.

## 🚀 Tecnologías Utilizadas

* **Lenguaje:** Java
* **Entorno de Desarrollo:** Android Studio
* **Componentes UI:** `RecyclerView`, `CardView`, Activity, Layouts XML
* **Consumo de Red / API:** Conexión HTTP para extraer datos en formato JSON (`org.json`)
* **Control de Versiones:** Git & GitHub / Docker

---

## 📱 Estructura Principal del Proyecto

* `app/src/main/java/mx/edu/tesoem/istd/tsdmh/lectornoticias/`: Paquete principal del código fuente.
  * `MainActivity.java`: Actividad principal encargada de inicializar la interfaz y realizar la petición de datos remotos.
  * `Noticias.java`: Clase modelo que estructura los atributos de cada noticia.
  * `NoticiasAdapter.java`: Adaptador personalizado para enlazar los datos con los elementos visuales del `RecyclerView`.
* `app/src/main/res/layout/`: Diseños de las interfaces de usuario (actividades e ítems individuales).
* `AndroidManifest.xml`: Configuración general de la aplicación y permisos de internet.

---

## ⚙️ Configuración y Ejecución

1. Clonar el repositorio:
   ```bash
   git clone [https://github.com/tu-usuario/LectorNoticias.git](https://github.com/tu-usuario/LectorNoticias.git)
