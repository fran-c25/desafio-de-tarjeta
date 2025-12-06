# Frontend Mentor - Blog preview card solution
<!-- Frontend Mentor - Solución de tarjeta de vista previa de blog -->

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
<!-- Esta es una solución al desafío de tarjeta de vista previa de blog en Frontend Mentor. Los desafíos de Frontend Mentor te ayudan a mejorar tus habilidades de codificación construyendo proyectos realistas. -->

## Overview

Este proyecto es una tarjeta de vista previa de blog responsive, creada como parte de un desafío de Frontend Mentor. El objetivo fue practicar maquetación con HTML y CSS, enfocándome en crear un diseño pixel-perfect y responsive.

### The challenge

Los usuarios deberían poder:

- Ver el diseño óptimo según el tamaño de pantalla de su dispositivo (375px y 1440px)
- Ver estados hover y focus para todos los elementos interactivos en la página
- Navegar usando solo el teclado

### Screenshot

![Mobile Screenshot](./assets/captura-de-pantalla-mobile.png)
![Desktop Screenshot](./assets/captura-de-pantalla-desktop.png)


### Links
<!-- Enlaces -->

- Solution URL: [Add solution URL here](https://your-solution-url.com)
<!-- - URL de la solución: [Añade la URL de tu solución aquí](https://your-solution-url.com) -->

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)
<!-- - URL del sitio en vivo: [Añade la URL de tu sitio en vivo aquí](https://your-live-site-url.com) -->

### Built with
- Marcado HTML5 semántico
- Propiedades personalizadas de CSS (variables CSS)
- Flexbox
- CSS Grid
- Mobile-first workflow
- Google Fonts (Figtree)

### What I learned

Durante este proyecto, reforcé mis conocimientos en:

**Variables CSS**: Utilicé custom properties para mantener un sistema de colores consistente:

```css
:root {
    --yellow-color: hsl(47, 88%, 63%);
    --white-color: hsl(0, 0%, 100%);
    --gray-color: hsl(0, 0%, 42%);
}
```

**CSS Grid**: Implementé Grid para estructurar el layout del body y la tarjeta:

```css
body {
    display: grid;
    grid-template-rows: 1fr auto;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
}
```

**Estados hover**: Agregué interactividad al título con efectos hover:

```css
h1:hover {
    color: var(--yellow-color);
}
```

**Enfoque Mobile-first**: Diseñé primero para móviles y luego agregué media queries para tablets (768px) y desktop (1440px), lo que resultó en un código más limpio y mantenible.

### Continued development

En futuros proyectos, planeo enfocarme en:

- **Accesibilidad**: Mejorar el uso de ARIA labels y asegurar que todos los elementos interactivos sean navegables con teclado
- **Animaciones CSS**: Agregar transiciones suaves y micro-interacciones para mejorar la experiencia de usuario
- **Metodología BEM**: Implementar una convención de nombres más estructurada para mis clases CSS
- **CSS Grid avanzado**: Explorar layouts más complejos con grid-template-areas

### Useful resources

- [CSS Grid Generator](https://cssgrid-generator.netlify.app/) - Esta herramienta me ayudó a visualizar y crear el layout de Grid de manera más eficiente
- [Google Fonts](https://fonts.google.com/) - Utilicé la fuente Figtree para darle personalidad al diseño

## Author

- GitHub - [Fran-c25](https://github.com/fran-c25)
- Frontend Mentor - [@fran-c25](https://www.frontendmentor.io/profile/fran-c25)


