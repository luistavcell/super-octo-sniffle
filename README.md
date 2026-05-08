# 📊 Fruver Fresh - Sistema de Facturación y Gestión

**Fruver Fresh** es una aplicación web diseñada para optimizar la operación de negocios de venta de frutas y verduras (fruvers). Permite gestionar ventas, clientes, inventarios y ofrece integración visual para periféricos como balanzas digitales e impresoras térmicas.

## 🚀 Características Principales

*   **Autenticación de Usuarios:** Sistema de inicio de sesión seguro para el personal administrativo.
*   **Dashboard en Tiempo Real:** Visualización rápida de facturas generadas, total de ventas del día, cantidad de clientes y productos registrados.
*   **Módulo de Facturación:**
    *   Creación de facturas con cálculo automático de totales e impuestos.
    *   Agregado rápido de productos populares.
    *   Sugerencias dinámicas desde la base de datos de la bodega.
    *   Aplicación de descuentos porcentuales.
*   **Gestión de Clientes (CRM):** Registro y administración de hasta 2000 clientes con datos de contacto y NIT.
*   **Bodega e Inventario:**
    *   Control de precios por Kilo y Libra.
    *   Exportación de inventario completo a formato **PDF**.
*   **Historial de Ventas:** Registro detallado de todas las transacciones realizadas.
*   **Integración de Hardware:**
    *   Interfaz para configuración de balanzas digitales mediante puerto serial.
    *   Configuración de impresoras térmicas y vista previa de tickets.

## 🛠️ Tecnologías Utilizadas

*   **Frontend:** HTML5, CSS3 (Diseño responsivo y moderno).
*   **Lógica:** JavaScript Vanilla (ES6+).
*   **Persistencia:** `localStorage` y `sessionStorage` para datos locales.
*   **Librerías Externas:**
    *   jsPDF: Generación de documentos PDF.
    *   jsPDF-AutoTable: Tablas automáticas en los reportes PDF.

## 💻 Instalación y Uso

1.  Clona o descarga este repositorio.
2.  Abre el archivo `index.html` en cualquier navegador web moderno.
3.  **Credenciales de acceso predeterminadas:**
    *   **Usuario:** `admin`
    *   **Contraseña:** `1234`

## 📂 Estructura del Proyecto

```text
fruver/
├── index.html          # Estructura principal y pantallas del SPA
├── manifest.json       # Configuración para PWA
├── src/
│   ├── styles.css      # Estilos visuales
│   └── app.js          # Lógica de negocio y manejo del DOM
└── README.md           # Documentación del proyecto
```

## ⚖️ Licencia

Este proyecto es de uso privado para **Fruver Fresh**.

---
*Desarrollado para optimizar el campo y el comercio local.*