# Visor de Mapa Básico con ArcGIS y Leaflet

![Visor ArcGIS Leaflet](https://i.imgur.com/n0Wz8Vq.png)

Un visor de mapa interactivo simple creado con HTML, CSS y JavaScript, utilizando la librería [Leaflet.js](https://leafletjs.com/) y los servicios de localización de [ArcGIS](https://developers.arcgis.com/location-services/). Este proyecto demuestra cómo integrar un mapa base de ArcGIS, añadir un buscador de direcciones (geocodificación), cargar un marcador en una ubicación específica al iniciar y mostrar las coordenadas del mouse en tiempo real.

## Características

-   **Mapa Base Vectorial:** Utiliza la capa de mapa base "Navigation" de ArcGIS.
-   **Geobúsqueda:** Incluye un control de búsqueda para encontrar direcciones y lugares en todo el mundo.
-   **Marcador Inicial:** Carga y centra el mapa en una dirección predefinida al iniciar la aplicación.
-   **Display de Coordenadas:** Muestra la latitud y longitud en tiempo real en una esquina del mapa a medida que el usuario mueve el mouse.
-   **Diseño Responsivo:** Simple y funcional en diferentes tamaños de pantalla.

## Tecnologías Utilizadas

-   **HTML5**
-   **CSS3**
-   **JavaScript (ES6+)**
-   [**Leaflet.js**](https://leafletjs.com/) - Una librería de mapas interactivos de código abierto.
-   [**Esri Leaflet**](https://developers.arcgis.com/esri-leaflet/) - Un plugin para conectar Leaflet con los servicios de ArcGIS Location Services.
    -   **Esri Leaflet Geocoder:** Plugin para la búsqueda de direcciones.
    -   **Esri Leaflet Vector:** Plugin para mostrar mapas base vectoriales de ArcGIS.
-   **ArcGIS Location Services:** Para el acceso a los mapas base y al servicio de geocodificación.

## Configuración y Puesta en Marcha

Para ejecutar este proyecto en tu máquina local, sigue estos pasos:

### 1. Prerrequisitos

-   Un navegador web moderno (Chrome, Firefox, Edge, etc.).
-   Un editor de código (como [VS Code](https://code.visualstudio.com/)).
-   Una cuenta de **ArcGIS for Developers** para obtener una API Key. Puedes crear una cuenta gratuita [aquí](https://developers.arcgis.com/sign-up).

### 2. Clonar el Repositorio

Abre una terminal y clona este repositorio en tu máquina local:

```bash
git clone [https://github.com/MilenaGandy/visor-arcgis.git](https://github.com/MilenaGandy/visor-arcgis.git)
cd visor-arcgis