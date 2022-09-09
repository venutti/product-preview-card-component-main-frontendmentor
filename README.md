# Frontend Mentor - Product preview card component

Esta es una solución al [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Los desafíos de Frontend Mentor ayudan a mejorar las skills al codear construyendo proyectos realistas.

## Tabla de Contenidos

- [Resumen](#resumen)
  - [El desafío](#el-desafío)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Mi proceso](#mi-proceso)
  - [Construido con](#construido-con)
  - [Lo que aprendí](#lo-que-aprendí)
  - [Desarrollo continuo](#desarrollo-continuo)

## Resumen

### El desafío

Los usuarios deberían poder:

- Ver el layout más óptimo, independientemente de la pantalla de su dispositivo
- Ver 'hover states' para elementos interactivos

### Screenshot

![image](https://user-images.githubusercontent.com/87911089/189269637-5e850494-ce33-4501-afa5-a360cd2d0540.png)


### Links

- [GitHub](https://github.com/venutti/product-preview-card-component-main-frontendmentor)
- [GitHub Pages](https://venutti.github.io/product-preview-card-component-main-frontendmentor/)

## Mi proceso

### Construido con

- Etiquetas HTML5 semánticas
- Variables de CSS
- Flexbox
- Desarrollo Mobile-first


### Lo que aprendí

El uso de la propiedad *background*, en especial las siguientes:
```css
.img-product {
    background-image: url("./images/image-product-mobile.jpg");
    background-size: cover;
}
```
Y el uso de MediaQueries para cambiar el layout dependiendo del tamaño del dispositivo:
```css
@media (min-width: 800px) {
    .img-product {
        background-image: url("./images/image-product-desktop.jpg");
    }
}
```

### Desarrollo continuo

Reveer el concepto de entregar un *componente*, y de ampliar el uso de texto y espaciado *responsive*.
