  

# Setflix

  

  

Proyecto para el curso de [**Desarrollo Web**](https://www.coderhouse.com/online/desarrollo-web-online) de [**Coderhouse**](https://www.coderhouse.com/).

  

  

La idea es maquetar una web de contenido multimedia el cual estará dedicado a series y películas.
Dicho sitio en su principio sera responsive para pantallas 320px 768px y 1024px pero siempre puede mejorar!

  

  

## Desarrollo

  

Las tecnologías utilizadas para el desarrollo de esta web serán:

  
- Figma para maquetar la idea en una primer instancia [**SETFLIX Wireframe**](https://www.figma.com/file/wj6afU14zTfSsQXi0i84hX/setflix?node-id=2%3A161&t=NUY6WXbiyLqNJITq-1)

- HTML

  

- CSS

  

- Flex

  

- Grid

  

- Bootstrap

  

- Preprocesador : [Sass](#id1)

  

Futuras tecnologías serán agregadas y documentadas aquí.

  

  

## Github-page

  

Podes ver como va quedando el proyecto armado [**SETFLIX**](https://roariel.github.io/setflix-mf/)

## Hosting

Podes ver el proyecto deployado por [InfinityFree](https://www.infinityfree.net/) aca: [**SETFLIX**](http://setflix.infinityfreeapp.com/)

# Sass

  

Para poder modificar el estilo que tiene el proyecto vas a tener que seguir unos pasos:

  

1. Si es la primera vez que vas a usar Sass tenes que instalar [**Node**](https://nodejs.org/es) como primer paso.

  

2. Seguido a la instalación tenes que abrir una terminal y clonar el repositorio.

  

3. En la ruta donde esta el proyecto clonado, ejecuta las siguientes lineas para poder comenzar a editar lo que gustes:

```
npm init

npm install -g sass

sass --watch ./scss/style.scss ./css/style.css
```

### Importante:
Lo mencionado en el punto 3 solo se hace la primera vez que vamos a correr sass, luego solo sera necesario ejecutar

```
sass --watch ./scss/style.scss ./css/style.css
```
Tenes que dejar la terminal siempre abierta para que sass pueda ir compilando los cambios que agregues dentro del .css 
