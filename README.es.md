# Frontend Mentor – Solución al NFT Preview Card Component

Esta es mi solución al desafío **NFT Preview Card Component** de [Frontend Mentor](https://www.frontendmentor.io/).  
El reto me ayudó a mejorar mis **habilidades en HTML y CSS**, construyendo una tarjeta moderna y responsiva de producto NFT con interacciones hover y una interfaz limpia.

## Tabla de Contenidos
- [Descripción General](#descripción-general)  
- [El Desafío](#el-desafío)  
- [Diseño](#diseño)  
- [Enlaces](#enlaces)  
- [Mi Proceso](#mi-proceso)  
- [Construido Con](#construido-con)  
- [Lo Que Aprendí](#lo-que-aprendí)

## Descripción General
Este proyecto es un **componente estático de vista previa de una tarjeta NFT** que muestra un NFT ficticio llamado *Equilibrium #3429*.  
La tarjeta muestra la imagen del NFT, el precio en ETH, el tiempo restante de disponibilidad y la información del creador.

El componente incluye:
- Un diseño limpio y minimalista  
- Efecto gradiente en la imagen al pasar el cursor  
- Cambio de color en el título y en el nombre del creador al hacer hover  
- Layout responsivo centrado vertical y horizontalmente  
- Sombras sutiles y bordes redondeados que resaltan la tarjeta sobre un fondo oscuro  

## El Desafío
Los usuarios deberían poder:

- Visualizar el diseño correctamente según el tamaño de la pantalla del dispositivo  
- Ver **efectos hover** en la imagen del NFT (superposición con gradiente cian)  
- Ver **efectos hover** en el título y en el nombre del creador (cambio de color del texto)  
- Navegar fácilmente gracias a una jerarquía visual clara  

## Diseño
### Diseño Desktop
![Desktop Design](./design/desktop-design.jpg)

### Estados Activos
![Active States](./design/active-states.jpg)

### Diseño Mobile
<img src="./design/mobile-design.jpg" width="200px" alt="Mobile design layout">

## Enlaces
- [GitHub Repository](https://github.com/mlopezl/my-version-of-ntf-preview-card-component-for-frontend-mentor)  
- [Live Demo](https://mlopezl.github.io/my-version-of-ntf-preview-card-component-for-frontend-mentor/)

## Mi Proceso
1. Comencé estructurando la tarjeta usando **HTML semántico** junto con la convención de nombres BEM para una mejor organización.  
2. Importé la fuente **Outfit** desde Google Fonts para igualar el diseño original.  
3. Construí el layout del componente usando **Flexbox** y **CSS Grid** para alinear las secciones internas.  
4. Definí una **paleta completa de colores mediante variables CSS** para mantener los estilos limpios y escalables.  
5. Añadí **estados hover** a la imagen, al título y al nombre del creador para reforzar la interactividad.  
6. Ajusté los espacios, bordes y sombras para coincidir con la estética del diseño original.  

## Construido Con
- HTML5  
- CSS3  
- Flexbox  
- CSS Grid  
- Variables CSS  
- Google Fonts (Outfit)

## Lo Que Aprendí
- Cómo usar **variables CSS** para manejar un sistema completo de colores y mantener la coherencia visual.  
- Cómo aplicar **efectos de superposición** con `linear-gradient()` y `background-image` para estados hover.  
- Cómo combinar **Flexbox y Grid** para centrar componentes de forma fluida en distintos dispositivos.  
- Cómo la **convención de nombres BEM** mejora la escalabilidad y la legibilidad del código.  
- Cómo los pequeños detalles visuales — sombras, bordes redondeados y espaciado — impactan fuertemente en el resultado final.
