# 📡 HelioAndes - Plataforma de Servicios

Aplicación web Single Page Application (SPA) desarrollada con **React** que simula el portal de una empresa de telecomunicaciones/servicios. El proyecto demuestra la capacidad de crear interfaces complejas separando la vista pública (Landing) del área privada (Dashboard).

## 🛠️ Stack Tecnológico
* **Core:** React.js (Hooks, Props, State).
* **Estilos:** CSS3 Modular con variables y diseño responsivo.
* **Enrutamiento:** React Router (Navegación sin recarga).
* **Datos:** Simulación de Backend mediante archivos JSON locales y Mockoon.

## ✨ Características Principales

### 1. Arquitectura de Layouts 📐
El sistema implementa múltiples layouts para diferenciar contextos:
* **Landing Layout:** Navbar corporativo, Hero section, Testimonios y Footer.
* **Dashboard Layout:** Sidebar lateral colapsable, Topbar de usuario y área de contenido dinámico.

### 2. Gestión de Planes y Servicios 📋
* Visualización de listados de planes (PlanList) y detalles específicos (PlanDetail).
* Catálogo de servicios con fichas técnicas simuladas.
* Carga dinámica de datos desde `helio-andes.json`.

### 3. Herramientas Integradas 🧮
* **Calculadora Integral:** Módulo lógico documentado para estimación de costos/servicios.
* **Descarga de Recursos:** Acceso directo a archivos estáticos como el catálogo PDF.

## 🚀 Cómo ejecutarlo
1.  Clonar el repositorio.
2.  Instalar dependencias:
    ```bash
    npm install
    ```
3.  Correr el servidor de desarrollo:
    ```bash
    npm start
    ```
4.  Abrir [http://localhost:3000](http://localhost:3000) en el navegador.

## 📂 Estructura del Proyecto
```text
src/
├── components/      # Átomos y moléculas (Botones, Cards, Sections)
├── data/           # Fuente de verdad (Mock Data JSON)
├── layouts/        # Plantillas base (Dashboard vs Landing)
├── pages/          # Vistas principales (Rutas)
└── styles/         # Hojas de estilo globales y específicas
