# Tech Skills Academy 2025
💻 *Laboratorio 2*  
**Nombre:** Brasly Villarebia Morales  
**Carné:** 2023105915  
**Curso:** IC-8057 – Introducción al Desarrollo de Páginas Web

---

## Descripción de la página
Este sitio web ofrece matrícula de cursos en áreas de alta demanda, tales como:

- **Ciberseguridad**  
- **Análisis de datos**  
- **Redes**  

### Proporciona:
- Agenda de cursos  
- Formulario breve para inscripción  
- Información sobre la modalidad de los cursos y la plataforma o lugar donde se impartirán las clases

---

## Estructura semántica
- **`<header>`**: Encabezado principal con el título del sitio.  
- **`<nav>`**: Barra de navegación con enlaces internos a secciones.  
- **`<main>`**: Contenido principal de la página.  
- **`<article>`**: Describe los cursos disponibles.  
- **`<figure>`** + **`<figcaption>`**: Utilizados para la inclusión de imágenes de los cursos.  
- **`<form>`**, **`<label>`**, **`<input>`**, **`<select>`**, **`<option>`**, **`<button>`**: Utilizados para la creación del formulario de inscripción.  
- **`<table>`**, **`<thead>`**, **`<tbody>`**, **`<tr>`**, **`<th>`**, **`<td>`**: Creación de tabla sobre la disponibilidad de horarios por curso.  
- **`<blockquote>`**: Cita destacada del evento.  
- **`<aside>`**: Información lateral sobre profesores y contactos.  
- **`<footer>`**: Pie de página con derechos de autor.  

---

## URL pública de Netlify
[https://techskillsacademycr.netlify.app/](https://techskillsacademycr.netlify.app/)

---

## Validación W3C

### Prueba #1
![Validación W3C](images/WhatsApp_Image_2025-08-15_at_23.17.13_67630d0d.jpg)  

En la primera prueba de W3C se muestran 5 warnings, los cuales se deben a no respetar la estructura de encabezados h2-h6. La página sugiere que, si no son indispensables, se utilice la etiqueta `<div>`.

### Prueba #2
Se corrigen los encabezados agregando la etiqueta `<h2>`, respetando así la jerarquía de títulos en la página web. Con estas modificaciones, en la segunda prueba de W3C no se muestran warnings.

![Validación corregida](images/image.png)

---

## Lighthouse

Mediante la herramienta Lighthouse se evaluarán 4 categorías:

- Performance  
- Accessibility  
- SEO  
- Best practices

### Prueba #1
![Resultados Lighthouse](images/image-1.png)

#### Prueba SEO y Best practices
##### Puntaje:
- **SEO:** 100  
- **Best practices:** 100  

No se encontraron problemas, advertencias ni conflictos entre elementos.

#### Performance
##### Puntaje:
- **Performance:** 99  

El diagnóstico indica un problema en los tamaños de las imágenes, ya que no se especifica el `width` y `height`.

![Problema performance](images/image-2.png)

##### Plan de mejora
Se solucionará mediante la implementación de CSS, ajustando el tamaño de las imágenes según la proporción de la página web.

#### Accessibility
##### Puntaje:
- **Accessibility:** 88  

Este diagnóstico es el más bajo, y se especifican los motivos.

![Problema accesibilidad](images/image-3.png)

##### Plan de mejora
- **Formulario:** Asociar correctamente cada campo con su etiqueta `<label>` para mejorar la accesibilidad.  
- **Botones táctiles:** Aumentar tamaño y separación de los botones del menú para facilitar la navegación en dispositivos móviles.

### Pruebas 2






---

## Accesibilidad aplicada
