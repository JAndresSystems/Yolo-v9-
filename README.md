<p align="center">
  <h1>Yolo-v9-</h1>
  <p>Detección satelital de incendios con YOLOv9 para una respuesta rápida y efectiva.</p>
  <p align="center">
    <img src="https://img.shields.io/github/workflow/status/YOUR_USERNAME/Yolo-v9-/build?style=for-the-badge" alt="Estado de Construcción">
    <img src="https://img.shields.io/github/license/YOUR_USERNAME/Yolo-v9-?style=for-the-badge" alt="Licencia">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge" alt="Pull Requests Welcome">
    <img src="https://img.shields.io/github/stars/YOUR_USERNAME/Yolo-v9-?style=for-the-badge" alt="Estrellas">
  </p>
</p>

---

## 🌟 El Porqué Estratégico

> La detección temprana de incendios es crucial para mitigar desastres ambientales, proteger infraestructuras y, lo más importante, salvaguardar vidas. Los métodos tradicionales de monitoreo a menudo son lentos, costosos o limitados en su alcance, lo que permite que los pequeños focos de incendio se conviertan rápidamente en catástrofes incontrolables. Esta ineficiencia se traduce en pérdidas económicas masivas y daños ecológicos irreversibles.

Este proyecto aborda directamente estos desafíos aprovechando la vanguardia de la inteligencia artificial con **YOLOv9**. Ofrecemos una solución robusta y eficiente para la detección satelital de focos de incendio. Al procesar imágenes de satélite con un modelo de detección de objetos de última generación, identificamos rápidamente las amenazas, permitiendo una respuesta ágil y la contención efectiva del fuego antes de que escale, transformando la capacidad de respuesta ante emergencias.

## ✨ Características Clave

*   🚀 **Detección Ultrarrápida**: Identifica focos de incendio en segundos, permitiendo una respuesta inmediata y reduciendo el tiempo crítico de acción.
*   🛰️ **Análisis Satelital Preciso**: Utiliza imágenes de satélite para una cobertura geográfica extensa y una detección de alta fidelidad, superando las limitaciones terrestres.
*   🧠 **Modelo YOLOv9 Optimizado**: Emplea el último modelo de YOLO, conocido por su precisión y eficiencia, para una identificación de incendios de vanguardia.
*   📈 **Interfaz Sencilla de Pruebas**: Permite la carga intuitiva de imágenes para realizar pruebas y visualizar los resultados de detección sin complicaciones.
*   💡 **Resultados Visuales Claros**: Genera imágenes procesadas que resaltan los focos de incendio detectados con cuadros delimitadores, facilitando una interpretación rápida.
*   🌐 **Despliegue Flexible**: Diseñado para ser adaptable a diversos entornos de monitoreo y análisis, desde sistemas de alerta temprana hasta plataformas de investigación.

## 🏗️ Arquitectura Técnica

El proyecto se basa en una arquitectura concisa y potente, centrada en la eficiencia de YOLOv9 para el procesamiento de imágenes.

### Pila Tecnológica

| Tecnología | Propósito                                | Beneficio Clave                                    |
| :--------- | :--------------------------------------- | :------------------------------------------------- |
| `Python`   | Lenguaje de programación principal       | Flexibilidad, amplio ecosistema para ML y visión |
| `YOLOv9`   | Modelo de Detección de Objetos           | Alta precisión y velocidad en la identificación    |
| `Flask`    | Microframework Web (para `app.py`)       | Permite una API o interfaz web ligera y rápida     |
| `OpenCV`   | Procesamiento de Imágenes                | Manipulación y visualización de datos de imagen    |
| `Pillow`   | Biblioteca de Procesamiento de Imágenes  | Utilizada para operaciones básicas de imagen       |

### Estructura del Directorio

```
.
├── 📄 Comoejecutar.txt
├── 📄 app.py
├── 📄 best.pt
├── 📄 processed_image.jpg
├── 📄 resized_image.jpg
└── 📁 static/
```

## 🚀 Configuración Operacional

Sigue estos pasos para poner en marcha el proyecto en tu entorno local.

### Prerrequisitos

Asegúrate de tener instalado lo siguiente:

*   **Python 3.8+**
*   **pip** (Administrador de paquetes de Python)

### Instalación

1.  **Clonar el repositorio**:

    ```bash
    git clone https://github.com/YOUR_USERNAME/Yolo-v9-.git
    cd Yolo-v9-
    ```

2.  **Crear y activar un entorno virtual** (opcional pero recomendado):

    ```bash
    python -m venv venv
    # En Linux/macOS:
    source venv/bin/activate
    # En Windows:
    .\venv\Scripts\activate
    ```

3.  **Instalar las dependencias necesarias**:

    ```bash
    pip install ultralytics flask opencv-python pillow
    ```

4.  **Ejecutar la aplicación**:
    Consulta el archivo `Comoejecutar.txt` para instrucciones específicas sobre cómo iniciar la aplicación y realizar pruebas. Generalmente, para una aplicación Flask:

    ```bash
    python app.py
    ```

    Luego, abre tu navegador web y navega a la dirección indicada por la aplicación (típicamente `http://127.0.0.1:5000`).

## 🤝 Contribuciones

¡Nos encantaría recibir tus contribuciones para mejorar este proyecto! Si deseas aportar, por favor sigue estos pasos:

1.  **Haz un Fork** del repositorio.
2.  **Crea una nueva rama** para tu funcionalidad (`git checkout -b feature/AmazingFeature`).
3.  **Realiza tus cambios** y haz commit (`git commit -m 'Add some AmazingFeature'`).
4.  **Sube tus cambios** a la rama (`git push origin feature/AmazingFeature`).
5.  **Abre un Pull Request** explicando tus cambios y por qué deberían ser incluidos.

Asegúrate de mantener un código limpio, bien documentado y de seguir las convenciones existentes.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo `LICENSE` en la raíz del repositorio para más detalles sobre los términos y condiciones.

**Resumen de Permisos:**

*   ✅ Uso comercial
*   ✅ Modificación
*   ✅ Distribución
*   ✅ Uso privado

**Limitaciones:**

*   🚫 Responsabilidad: El software se proporciona "tal cual", sin garantía de ningún tipo.

**Condiciones:**

*   ⚠️ Incluir la nota de copyright y la nota de licencia en todas las copias o porciones sustanciales del software.
