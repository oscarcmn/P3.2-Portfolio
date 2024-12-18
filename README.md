# P3.2-Portfolio

**Nombre del autor**: Óscar Carmena Martín  
**Nombre de la asignatura**: DIW  
**Título de la práctica**: P3.2-Portfolio  
**Fecha de entrega**: 14-12-2024

---

## Índice
- [P3.2-Portfolio](#p32-portfolio)
  - [Índice](#índice)
  - [1. Introducción](#1-introducción)
  - [2. Diseño y Decisiones](#2-diseño-y-decisiones)
    - [2.1 Versión de Ordenador](#21-versión-de-ordenador)
    - [2.2 Versión de Tablet](#22-versión-de-tablet)
    - [2.3 Versión de Móvil](#23-versión-de-móvil)
  - [3. Conclusiones](#3-conclusiones)

---

## 1. Introducción
El presente documento describe las decisiones de diseño tomadas en el desarrollo de una página web que sirve como mi portfolio y es adaptativa. La página web está estructurada para proporcionar información profesional sobre mi, incluyendo mis soft skills, conocimientos, estudios, proyectos destacados y enlaces a redes sociales. Se implementaron tres versiones principales: ordenador, tablet y móvil, garantizando así la accesibilidad en diferentes dispositivos.

---

## 2. Diseño y Decisiones

### 2.1 Versión de Ordenador

**Estructura y Decisiones**:
- **Header**: Ubicada en la parte superior, con un logo y botones alineados horizontalmente y fácilmente accesibles.
- **"Sobre mí"**: Se presenta un bloque centrado con texto descriptivo, lo que facilita la lectura.
- **Sección de Conocimientos**: Diseñada en un contenedor oscuro que resalta las categorías (*FrontEnd*, *BackEnd* y *Bases de Datos*), con texto blanco para garantizar el contraste.
- **Sección de estudios**: Una lista que mantiene los colores de la pagina con una animacion al scrollear.
- **Proyectos**: Presentados en tarjetas alineadas horizontalmente. Cada tarjeta tiene una imagen de vista previa, título y descripción, acompañada de un botón "Más en GitHub".Incluye una animacion al scrollear.
- **Seccion "¿Donde encontrarme?**: Contiene enlaces a redes sociales (GitHub, LinkedIn e Instagram) con iconos.

**Aspectos Visuales**:
- Paleta de colores equilibrada (blanco, azul(varias tonalidades) y negro).
- Margen generoso entre secciones para mejorar la organización visual.

---

### 2.2 Versión de Tablet

**Estructura y Decisiones**:
- **Header**: Sigue en la parte superior, pero se reduce el espaciado horizontal para adaptarse al menor ancho.
- **Seccion "sobre mi"**: El icono pasa a estar arriba y se prioriza el texto centrado, ajustando el tamaño de fuente para una mejor legibilidad en pantallas pequeñas.
- **Sección de Conocimientos**: Se mantiene el diseño de la tabla, pero con menor ancho.
- **Proyectos**: Las tarjetas de proyectos pasan a apilarse en dos columnas, facilitando la lectura sin sacrificar el diseño.
- **Sección de estudios**: El tamaño se mantiene y sigue en el centro.
- **Seccion "¿Donde encontrarme?**: Igual que en desktop pero mas pequeño

**Aspectos Visuales**:
- Adaptación del tamaño de fuentes y margenes para evitar el desbordamiento de contenido.

---

### 2.3 Versión de Móvil

**Estructura y Decisiones**:
- **Header**: Gracias al flex-wrap se alinean unos debajo de otros reduciendo el espacio que ocupan.
- **Seccion "sobre mi"**: Se prioriza el texto centrado, ajustando el tamaño de fuente para una mejor legibilidad en pantallas pequeñas.
- **Sección de Conocimientos**: Se mantiene el diseño de la tabla, pero con menor ancho.
- **Sección de estudios**: El tamaño decrece y ocupa casi todo el ancho del dispositivo.
- **Proyectos**: Las tarjetas se muestran en una sola columna, ocupando el ancho del dispositivo.
- **Seccion "¿Donde encontrarme?**: Igual que en desktop pero mas pequeño

**Aspectos Visuales**:
- Optimización de espacios y reducción de margen entre elementos.

---

## 3. Conclusiones
La página web desarrollada demuestra un diseño adaptativo eficiente que garantiza una buena experiencia de usuario en diferentes dispositivos. Se implementaron buenas prácticas de diseño, como el uso de contrastes visuales, fuentes legibles y organización jerárquica de información. Cada versión (ordenador, tablet y móvil) fue diseñada considerando las limitaciones de tamaño.

---

**Enlace a la pagina**: https://oscarcmn.github.io/P3.2-Portfolio/

---