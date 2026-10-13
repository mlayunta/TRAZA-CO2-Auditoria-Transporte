# 🚛 TRAZA//CO₂ - Optimizador de Rutas de Transporte Sostenible

**Sistemas de Trazabilidad de Carbono y Auditoría Logística 5.0**

---

### 👨‍💻 Autoría y Propiedad Intelectual
* **Desarrollador y Autor:** Miguel Ángel Layunta López
* **Dominio Técnico:** Logística de Transporte, Cadena de Frío, Trazabilidad ESG y Conducción Eficiente.

---

## 📌 Descripción del Proyecto

**TRAZA//CO₂** es una Aplicación Web Progresiva (PWA) diseñada para auditar, planificar y optimizar rutas de transporte de mercancías. Orientada a la **Logística 5.0**, la herramienta permite reducir la huella de carbono operacional mediante la secuenciación inteligente de paradas (algoritmo de vecino más cercano) e integra modelos de consumo ajustados tanto para carga seca como para la **cadena de frío alimentaria**.

La plataforma está estructurada en módulos por roles para conectar las necesidades de la dirección logística, los chóferes en cabina y los auditores ambientales.

---

## 🛠️ Características Principales

* **🧭 Planificación y Optimización Multi-Parada:**
  * Configuración personalizada de punto de origen y múltiples destinos.
  * Cálculo dinámico de secuencia óptima, kilometraje total y estimación de consumo energético a velocidad crucero eficiente.
* **❄️ Integración de Cadena de Frío (Transporte Frigorífico):**
  * Modelo de sobrecoste energético por equipo de frío autónomo (+25% en factor de emisión).
  * Guía y tabla de referencia técnica de temperaturas obligatorias por categoría alimentaria (carnes, pescado, lácteos, frutas y congelados).
* **🚛 Control de Flota y Conductor:**
  * Registro de chófer, matrícula de tractora y remolque.
  * Módulo de asistencia en cabina con lista de chequeo (*checklist*) y bitácora de incidencias/averías.
* **📊 Auditoría Visual e Informes PDF:**
  * Gráficas interactivas mediante Chart.js para comparativa de emisiones e indicadores de reducción de kilometraje.
  * Generación y exportación de informes oficiales en formato **PDF** con un solo clic.
* **📱 Soporte PWA (Progressive Web App):**
  * Instalable en dispositivos móviles Android/iOS y ordenadores de escritorio sin requerir descargas en tiendas de aplicaciones.

---

## 📐 Estructura del Repositorio

```text
TRAZA-CO2-Optimizador-de-rutas/
├── index.html         # Interfaz principal, lógica de cálculo y visualización gráfica
├── manifest.json      # Configuración de instalación PWA e identidad visual
├── sw.js              # Service Worker para gestión de cachés y soporte offline
├── README.md          # Documentación del proyecto
└── icons/
    └── icon.png       # Logotipo e icono vectorial oficial de la aplicación
