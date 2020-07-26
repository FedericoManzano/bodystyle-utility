# Utility Bodystyle

[![Documentación](https://img.shields.io/badge/bodystyle-v3.5.0-green.svg)](https://bodystyle.000webhostapp.com)
[![Licencia](https://img.shields.io/badge/MIT-3.5.0-blue.svg)](https://github.com/FedericoManzano/bodystyle/blob/master/LICENCE)
[![Npm](https://img.shields.io/badge/NPM-3.5.0-blue.svg)](https://www.npmjs.com/package/body-utility)

## Descripción 

En este repositorio se separan los utilitarios de la librería [bodystyle]() para disponer unicamente del apartado de utilitarios de la librería.

## Contenido 
- [Descarga](https://github.com/FedericoManzano/utility-bodystyle#descarga)
- [Bordes](https://github.com/FedericoManzano/utility-bodystyle#bordes)
- [Margin](https://bodystyle.000webhostapp.com/inicio/#/documentacion/margin)
- [Medidas](https://bodystyle.000webhostapp.com/inicio/#/documentacion/medidas)
- [Overflow](https://bodystyle.000webhostapp.com/inicio/#/documentacion/overflow)
- [Texto](https://bodystyle.000webhostapp.com/inicio/#/documentacion/texto)
- [Sass](https://bodystyle.000webhostapp.com/inicio/#/documentacion/sass)


## Descarga

Podemos agregar el CDN de los utilitarios directamente en la cabecera del html para disponer de las funcionalidades.

```html
<!DOCTYPE html>
<head>

    <!-- META obligatorio para poder utilizar la libreria -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- Link con el CDN de los estilos css  -->
    <link rel="stylesheet" href="https://rawcdn.githack.com/FedericoManzano/utility-bodystyle/5776691724b2bbbd985af06c57bab9541780aa60/dist/css/utulitarios.min.css">

</head>
```

O podemos añadir a los utilitarios como una dependencia de nuestr proyecto a través de los gestores de paquetes.

```txt
npm i body-utility
yarn add body-utility
```

Si lo que queremos es el código fuente de este repositorio lo podemos hacer con el comando

```txt
git clone https://github.com/FedericoManzano/utility-bodystyle
```

## Bordes

Las clases CSS correspondientes a los bordes comienzan con `.bor-` y luego definimos si queremos bordes con radio o bordes pintados de algún color.

### Clase CSS de ejemplo
```css
.box-ej {
    width: 300px;
    height: 300px;
    background-color: black;
}
```

### Ejemplos de radios
```html
<!-- Bordes en (PX) -->
<div class="box-ej bor-rad-10"></div>
<!-- Bordes en (%) -->
<div class="box-ej bor-rad-por-10"></div> <!-- 1 A 50 %-->
<!-- Figura redonda -->
<div class="box-ej bor-rad-por-50"></div>
<!-- Figura  redonda a los lados -->
<div class="box-ej bor-pill"></div>
```

### Ejemplos pintados

```html
<!-- Bordes en (PX) -->
<div class="box-ej bor-10"></div>
<div class="box-ej bor-10"></div>
<div class="box-ej bor-50"></div>
```

Para más información ver la documentación: [https://bodystyle.000webhostapp.com/inicio/#/documentacion/bordes](https://bodystyle.000webhostapp.com/inicio/#/documentacion/bordes)

## Margin 

