# Módulo 2 – App de Clima (Frontend)

[Ver repositorio en **GitHub**](https://github.com/SebasIMM/weather-frontend-m2)  
[Ver repositorio en **Netlify**](https://weather-m2.netlify.app/)  


---

## Descripción

Esta es la versión final final. ahora si del frontend de una aplicación de clima. Permite visualizar información climática actual de distintas ciudades y un pronóstico semanal. La aplicación fue desarrollada utilizando:

- **HTML5**
- **Bootstrap 5**
- **JavaScript**
- **Git/GitHub**

---

## Funcionamiento

1. Abrir el proyecto en un editor y ejecutar **Live Server**.
2. La página principal (**Home**) muestra una grilla de **cards** con ciudades, mostrando:
   - Nombre de la ciudad
   - Icono del clima
   - Temperatura
   - Sensación térmica
   - Humedad
   - Viento
   - Última actualización

3. Al hacer clic en **"Ver detalle"** de una ciudad, se abre un **modal** con:
   - Datos ampliados de la ciudad (temperatura, sensación, humedad y viento)
   - Pronóstico semanal (tabla con los 7 días)

---

## Estructura del proyecto

weather-frontend-m2/
│
├─ index.html # Página principal
├─ assets/
│ ├─ js/
│ │ ├─ clima.js # Carga y muestra las cards de ciudades
│ │ └─ detalle.js # Manejo del modal y pronóstico semanal
│ └─ img/ # Iconos de clima y logos
├─ data/
│ ├─ clima.json # Datos de las ciudades
│ └─ detalle.json # Datos del pronóstico semanal
└─ README.md


---

## Tecnologías utilizadas

- HTML5 (header, nav, main, section, article, footer)
- Bootstrap 5 (grid, utilidades, navbar, card, badge, botones)
- JavaScript (fetch, DOM, eventos)
- Font Awesome (iconos)
- Git/GitHub (control de versiones)

---

## Comentarios en el código

- Todos los comentarios como `<!-- hack ==== -->` o `<!-- idea ==== -->` **son parte de la extensión Comment Highlighter**, que utilizo para organizar visualmente las secciones y facilitar la lectura del código.  
- `hack` usada para secciones semanticas del HTML.  
- `idea` usada en plantillas, componentes o elementos reutilizables.

---

## Requisitos para ejecutar

- No se necesita instalación de dependencias.  
- Abrir `index.html` en un navegador moderno.  
- Se recomienda usar **Live Server** para que los archivos JSON se carguen correctamente con `fetch`.

