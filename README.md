# 🗳️ Sistema de Votación sin Backend (Vanilla JavaScript)

Este proyecto es una prueba de concepto y una aplicación web funcional que simula un sistema de votación o encuestas en tiempo real, utilizando únicamente las capacidades del **lado del cliente**. Su principal característica es que **no requiere ningún servidor o base de datos (backend)** para almacenar los resultados, sino que utiliza el almacenamiento local del navegador (`localStorage`).

Es ideal para encuestas rápidas, demostraciones de votación, o como una excelente herramienta de aprendizaje para entender la manipulación de datos en el frontend.

## ✨ Características Principales

* **Persistencia Local:** Los votos y resultados se guardan en el `localStorage` del navegador, persistiendo incluso si el usuario cierra y vuelve a abrir la página.
* **Visualización en Tiempo Real:** Los resultados se actualizan dinámicamente en la interfaz de usuario.
* **Puro Vanilla JS:** Desarrollado con HTML, CSS y JavaScript nativo, sin dependencias de frameworks.

## 🛠️ Tecnologías Utilizadas

* **HTML5:** Estructura de la página de votación y los elementos de visualización.
* **CSS3:** Estilos, incluyendo la representación de las barras de resultados.
* **Vanilla JavaScript:** Toda la lógica de negocio, incluyendo:
    * Manejo de eventos de clic.
    * Uso de `localStorage` para guardar y recuperar votos.
    * Cálculo y renderizado de votación.

## ⚙️ Conceptos Clave en el Código

El funcionamiento del sistema se basa en dos pilares de JavaScript:

1.  **Manipulación del DOM:** Para registrar el evento de votación y actualizar visualmente los resultados.
2.  **`localStorage`:** Se utiliza para simular una base de datos.
    * Guarda un objeto JSON que contiene el conteo de votos para cada opción.

## 🚀 Cómo Empezar

Este proyecto no requiere servidor.

### 1. Clonar el repositorio

```bash
git clone [https://github.com/santiagourdaneta/Sistema-de-votacion-sin-backend-vanilla-JavaScript.git](https://github.com/santiagourdaneta/Sistema-de-votacion-sin-backend-vanilla-JavaScript.git)
cd Sistema-de-votacion-sin-backend-vanilla-JavaScript

2. Ejecutar
Simplemente abre el archivo index.html en tu navegador web.

👥 Autor
Santiago Urdaneta
