
# PeopleCount 👥

**Estado del Proyecto:** 🚧 En Desarrollo Activo

Sistema de conteo y análisis de flujo peatonal en espacios públicos utilizando cámaras de seguridad (CCTV). El objetivo es procesar video en tiempo real o grabado para contar personas y estudiar patrones de movimiento.

## 📋 Descripción

**PeopleCount** es un sistema de software basado en visión por computador y aprendizaje profundo que:

* Detecta y cuenta personas que transitan en zonas específicas.
* Determina la dirección del movimiento (ej. norte-sur, izquierda-derecha).
* Calcula métricas temporales sobre el flujo peatonal por hora, día o periodos personalizados.
* Presenta un dashboard con estadísticas y gráficos de actividad por zonas.

El producto final integrará video en vivo (o grabado) con conteo superpuesto y un panel de datos interactivo.

## 🛠️ Stack Tecnológico Previsto

* **Lenguaje:** Python
* **Librerías:** OpenCV, PyTorch/TensorFlow, MediaPipe/Dlib
* **Modelos:** YOLO (detección), DeepSORT/SORT (seguimiento), base de datos para métricas temporales.

## ⚙️ Instalación y Uso (Pendiente)

El código y las instrucciones de instalación se documentarán conforme avance el desarrollo. Se prevé el uso de entornos virtuales y dependencias listadas en un archivo `requirements.txt`.

## 📅 Próximos Pasos (Cronograma 13 semanas)

* **Semana 1-2:** Investigación y definición técnica (papers, repositorios, elección de herramientas).
* **Semana 3-4:** Configuración del entorno y recolección de datos de prueba.
* **Semana 5-6:** Implementación del conteo básico de personas con YOLOv5 (mínimo 15 FPS).
* **Semana 7-8:** Seguimiento y cálculo de dirección de movimiento (DeepSORT/SORT).
* **Semana 9-10:** Almacenamiento y agregación de datos (por hora, día, dirección).
* **Semana 11:** Desarrollo del dashboard de visualización con filtros y gráficos.
* **Semana 12:** Integración de video en vivo con métricas y superposición de datos.
* **Semana 13:** Pruebas, documentación y presentación del prototipo.

## 👥 Equipo

* Adrian Yebid Rincón
* Alirio Hernando Martínez Barreto
* Diego Fernando Vesga Ocampo
* Julian Garzón Jiménez
* Pablo Felipe Sandoval Menjura




*Este README se actualizará conforme el proyecto avance.*

