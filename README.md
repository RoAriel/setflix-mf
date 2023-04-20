  

# Setflix

  

  

Proyecto para el curso de [**Desarrollo Web**](https://www.coderhouse.com/online/desarrollo-web-online) de [**Coderhouse**](https://www.coderhouse.com/).

  

  

La idea es maquetar una web de contenido multimedia el cual estará dedicado a series y películas.

  

  

## Desarrollo

  

Las tecnologías utilizadas para el desarrollo de esta web serán:

  

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

Otra opcion de vista para ver como queda [**SETFLIX**](https://setflix-mf.000webhostapp.com/) es a taves del servidor de [**hosting**](https://ar.000webhost.com).


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
