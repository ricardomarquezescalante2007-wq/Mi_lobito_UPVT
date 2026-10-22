# 🐺 Lobito UPVT

Aplicación web y móvil oficial para la comunidad universitaria de la UPVT (Universidad Politécnica del Valle de Toluca). Esta plataforma busca centralizar servicios, información académica y herramientas útiles para estudiantes y docentes en una interfaz rápida, intuitiva y accesible. 🚀

---

## 📌 Tabla de contenidos

* [📱 Sobre el proyecto](#-sobre-el-proyecto)
* [🛠️ Tecnologías utilizadas](#️-tecnologías-utilizadas)
* [⚡ Características principales](#-características-principales)
* [📂 Estructura del proyecto](#-estructura-del-proyecto)
* [📋 Requisitos previos](#-requisitos-previos)
* [💻 Comandos para crear e inicializar el repositorio](#-comandos-para-crear-e-inicializar-el-repositorio)
* [⚙️ Instalación y configuración](#-instalación-y-configuración)
* [🔄 Comandos diarios de trabajo con Git](#-comandos-diarios-de-trabajo-con-git)
* [🌳 Flujo de trabajo con SourceTree](#-flujo-de-trabajo-con-sourcetree)
* [📦 Despliegue y compilación](#-despliegue-y-compilación)
* [📐 Convenciones de código](#-convenciones-de-código)
* [🤝 Contribución](#-contribución)
* [📄 Licencia y contacto](#-licencia-y-contacto)

---

## 📱 Sobre el proyecto

Lobito UPVT nace para solucionar la dispersión de información y mejorar la experiencia digital de la comunidad universitaria. La aplicación aprovecha el rendimiento de Ionic 8 para ofrecer una experiencia nativa en dispositivos móviles y un comportamiento fluido en navegadores web. 🎓

---

## 🛠️ Tecnologías utilizadas

* 🔵 **Ionic 8:** Framework UI para el desarrollo de componentes híbridos y multiplataforma.
* 🔷 **TypeScript (TS):** Superset de JavaScript que añade tipado estático para un código más robusto.
* 🌐 **HTML5 & CSS3 & JavaScript:** Fundamentos web para la estructura, lógica y estilos visuales personalizados.
* 🌳 **SourceTree & Git:** Cliente gráfico y sistema de control de versiones para la gestión del repositorio.
* 🟢 **Node.js & npm:** Entorno de ejecución y gestor de paquetes del proyecto.

---

## ⚡ Características principales

* 📱 **Interfaz adaptable:** Diseño *responsive* optimizado para celulares, tabletas y computadoras.
* 🌙 **Modo oscuro / claro:** Soporte nativo para temas visuales según la preferencia del usuario.
* 🚀 **Navegación fluida:** Uso de rutas optimizadas y componentes nativos de Ionic.
* 🧩 **Arquitectura modular:** Código limpio y desacoplado para facilitar el mantenimiento a largo plazo.

---

## 📂 Estructura del proyecto

```text
lobito-upvt/
├── 📁 src/
│   ├── 📁 app/
│   │   ├── 📁 components/     # Componentes reutilizables
│   │   ├── 📁 pages/          # Vistas principales de la app
│   │   ├── 📁 services/       # Lógica de negocio y consumo de APIs
│   │   ├── 📁 guards/         # Protección de rutas y autenticación
│   │   └── 📄 app.module.ts   # Módulo principal
│   ├── 📁 assets/             # Imágenes, íconos y archivos estáticos
│   └── 📁 theme/              # Estilos globales y variables de CSS
├── ⚙️ ionic.config.json       # Configuración del CLI de Ionic
├── ⚙️ tsconfig.json           # Configuración del compilador de TypeScript
└── 📄 package.json            # Dependencias y scripts del proyecto
