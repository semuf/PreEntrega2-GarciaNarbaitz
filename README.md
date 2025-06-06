# PreEntrega3-GarciaNarbaitz

## Campamento Aventura – Sitio Web

Proyecto web desarrollado como parte de la **tercera entrega** del curso de Desarrollo Web.

---

## Objetivo

Aplicar una estructura web responsive y escalable utilizando:
- HTML semántico
- SASS como preprocesador
- Bootstrap y Flexbox/Grid para maquetado
- Buenas prácticas de control de versiones con Git y GitHub

Se buscó lograr un sitio visualmente atractivo, funcional en desktop y mobile, con código optimizado y ordenado mediante arquitectura SCSS.

---

## Tecnologías utilizadas

- HTML5
- SASS / SCSS
- CSS personalizado
- Bootstrap 
- Google Fonts
- Git & GitHub

---

## Estructura del sitio

El sitio incluye las siguientes secciones:

- **Inicio**: presentación del campamento con imagen de portada tipo hero y botón de llamado a la acción.
- **Nosotros**: quiénes somos, sobre fondo hero común.
- **Actividades**: tarjetas con info destacada de cada actividad.
- **Galería**: imágenes con efecto hover responsivo.
- **Contacto**: formulario + mapa (o indicación de ubicación).

---

Sitio en línea disponible en:

https://semuf.github.io/PreEntrega2-GarciaNarbaitz/

## Organización SCSS

```plaintext
scss/
├── base/           → resets y tipografías
├── layout/         → header, footer, hero
├── components/     → botones, galería
├── pages/          → estilos específicos por página
├── utils/          → variables y mixins
└── main.scss       → archivo principal que importa todo
