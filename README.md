# Prueba-Tecnica-Dentsu
Evaluar tu capacidad para traducir un diseño de Figma en una página web funcional, responsive y optimizada para motores de búsqueda (SEO), prestando atención a la calidad del código, la estructura del proyecto y la claridad en la comunicación escrita (a través de comentarios, nombres de archivos y contenido SEO).

## 📌 Descripción General
Este proyecto es una adaptación basada en un diseño de Figma.  
Se buscó mantener una estructura **responsiva** para móvil, tablet y escritorio, asegurando la correcta visualización en distintos dispositivos.

## ✏️ Decisiones de Diseño o Implementación
- **Responsive Adaptativo:** Algunos tamaños de letra e imágenes se ajustaron progresivamente mediante `media queries`, para garantizar una mejor experiencia en tablets movil, tablets y escritorio.
movil: (< 768px)
Tablet: (768px - 1024px)
Escritorio: (> 1024px)

- **Menú hamburguesa:** Se ajustó el comportamiento para que, en móvil, al abrirse el menú despliegue el contenido hacia abajo y no se sobreponga a la imagen principal.
- **Secciones de iconos:** Se diseñó una grilla que muestra 4 iconos por fila en móvil, 6 en tablet y 12 en escritorio.
- **Cambio dinámico de imágenes:** Se implementó una función JavaScript sencilla para que los botones puedan cambiar imágenes al hacer clic.
- **Archivo `robots.txt` y `sitemap.xml`:** Incluidos en la raíz del proyecto para SEO básico.

## 🛠️ Tecnologías Utilizadas
- **HTML5**
- **CSS3** (Puro, sin frameworks como Bootstrap)
- **JavaScript** (solo para funciones ligeras de interacción)

No se utilizó ninguna librería externa para mantener el código lo más puro posible.

## 👀 Instrucciones para Visualizar el Proyecto
1. Descargar o clonar el repositorio.
2. Abrir el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Firefox, Edge, Safari).
3. Asegurarse que la estructura de carpetas se mantenga (por ejemplo, imágenes dentro de `/assets`).
4. Para una mejor experiencia de prueba, usar herramientas de desarrollador (`Ctrl+Shift+I`) y probar el diseño en distintos tamaños de pantalla.
