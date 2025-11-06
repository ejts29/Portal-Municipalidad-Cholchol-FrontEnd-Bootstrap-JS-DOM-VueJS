
#  Portal Web Dinámico: Municipalidad de Cholchol (Front-End Avanzado)

> Proyecto de **Desarrollo Front-End** implementado como Evaluación Sumativa U2. Consiste en la modernización del portal web de la Municipalidad de Cholchol.
>
> Este sistema demuestra el dominio del diseño responsivo, la **manipulación avanzada del DOM** y la integración de **librerías y frameworks (Bootstrap, JavaScript, Vue.js)**, cumpliendo rigurosamente con los principios de usabilidad y accesibilidad.

---

##  Habilidades Clave y Criterios de Evaluación

### 1. Arquitectura y Estructura (CE4, CE7)
* **Framework Principal:** Integración completa de **Bootstrap 5** para el diseño responsivo (CE4).
* **Modularidad con Vue.js:** Uso de **Vue.js** para la sección de Noticias y el Formulario de Newsletter, utilizando el patrón de **Componentes Reutilizables** (IL 2.3, CE7).
* **Patrones de Código:** Uso de JavaScript Vanilla (`main.js`) para la lógica de formularios y Vue.js (`vue_app.js`) para el estado de las noticias, separando las responsabilidades de forma clara.

### 2. Interactividad y Validación (CE1, CE2, CE3)
* **Manejo de Eventos (CE1):** Implementación de eventos `load` (para el Modal de Alerta inicial), `submit`, y `input` para validar el formulario en tiempo real (IL 1.1).
* **Validación de Formularios (CE2):** Formulario de Contacto implementado con JavaScript nativo para validar campos obligatorios y el **formato de correo electrónico**, mostrando mensajes de error/éxito dinámicamente (IL 1.2).
* **Manipulación del DOM (CE3):** Uso de JavaScript para mostrar/ocultar el Modal de Alerta y para manejar las clases y atributos `aria-invalid` en tiempo real, demostrando la transformación de objetos HTML (IL 1.3).

### 3. Diseño y Usabilidad (CE5, CE6)
* **Diseño Coherente (CE5):** Aplicación de principios de diseño UI consistentes, utilizando una paleta de colores coherente (azul primario y escala de grises) y una navegación clara.
* **Estética y Legibilidad (CE6):** Integración de principios de diseño visual:
    * **Jerarquía:** Uso de la fuente **'Pacifico'** para títulos, creando una identidad visual atractiva.
    * **Accesibilidad:** Uso de etiquetas semánticas, texto alternativo en imágenes y atributos **ARIA** para mejorar la accesibilidad (IL 1.6).
* **Efectos de Interacción:** Implementación de efectos visuales CSS (ej. `hover` en tarjetas y carruseles) para una experiencia de usuario atractiva.

---

##  Ejecución en Línea (GitHub Pages)

Dado que este proyecto es 100% Front-End, la mejor forma de demostrar su funcionalidad es a través del servicio gratuito **GitHub Pages**.

## Ejecución en Línea con GitHub Pages

Este proyecto es completamente estático (HTML, CSS, JS), lo que permite publicarlo fácilmente mediante el servicio gratuito y profesional **GitHub Pages**.

 Puedes ver el resultado final haciendo clic en el siguiente enlace:

[🔗 Portal Web Dinámico: Municipalidad de Cholchol](https://ejts29.github.io/Portal-Municipalidad-Cholchol-FrontEnd-Bootstrap-JS-DOM-VueJS/)


### Ejecución Local

1.  Clonar el repositorio.
2.  Abrir el archivo **`index.html`** directamente en cualquier navegador.

##  Estructura del Proyecto

```

.
├── assets/
│   ├── imag/                      \# Imágenes del portal (noticias, becas, logos)
│   └── logos/
├── css/
│   └── styles.css                 \# Estilos personalizados y responsivos
├── js/
│   ├── main.js                    \# Lógica de Validación de Contacto (JavaScript Nativo)
│   └── vue\_app.js                 \# Lógica de Noticias y Newsletter (Vue.js)
├── index.html                     \# Estructura Principal del Portal Web
└── README.md

```
```
