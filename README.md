# Manuales para implementación de C-Agent

Este repositorio contiene los manuales de creación y configuración de los recursos en Azure necesarios para la implementación de C-Agent, organizados por **versiones** y con una estructura común que facilita su mantenimiento, reutilización de recursos y evolución en el tiempo.

Cada versión del manual se encuentra aislada en su propia carpeta, mientras que las imágenes se gestionan de forma centralizada para evitar duplicaciones innecesarias.

## 📁 Estructura de carpetas

La estructura del repositorio es la siguiente:


```
/
├── Imagenes/
│   ├── Global/
│   └── Specific/
│       └── v20/
├── v20/
│   └── C-Agent-v20.md
└── README.md

```

### 📂 Carpeta `Imagenes/`

Contiene todas las imágenes utilizadas en los manuales.

- **`Imagenes/Global/`**  
  Imágenes comunes que se utilizan en todas las versiones del manual  
  (por ejemplo: arquitectura general, diagramas reutilizables, logos).

- **`Imagenes/Specific/v20/`**  
  Imágenes específicas de la versión `v20`, relacionadas únicamente con cambios, pantallas o configuraciones propias de esa versión.

### 📂 Carpetas de versión (`vXX/`)

Cada carpeta de versión contiene la documentación correspondiente a una versión específica del manual.

Ejemplo:
- **`v20/`**: Manual correspondiente a la versión 20.

Dentro de cada carpeta de versión se encuentra el archivo Markdown con el manual completo de esa versión.

## 📝 Convención de versiones

- Cada versión tiene su propia carpeta (`v20`, `v21`, `v22`, etc.).
- Las imágenes específicas de una versión deben colocarse en `Imagenes/Specific/vXX/`.
- Las imágenes compartidas entre versiones deben colocarse en `Imagenes/Global/`.

De esta forma, se evita la duplicación innecesaria de recursos y se mantiene una estructura limpia y escalable.