# Notas clase 2

## Vínculos o enlaces
> Para insertar un vínculo o enlace en HTML 
> utilizamos el elemento "a"

<a href="URL">texto</a>

<a href="URL" target="_blank">texto</a>

> El atributo Target se utiliza para abrir un enlace en una nueva pestaña

## Imágenes en html
> Primero mencionaremos sitios para descargar imágenes y luego algún que otro sitio para generación de imágenes

    íconos  
        https://www.flaticon.com/ 
        https://www.iconfinder.com/
        https://www.svgrepo.com/

    fotografías
        https://unsplash.com/es
        https://www.pexels.com/es-es/
        https://www.freepik.es/  

> Sitios para generar imágenes por IA

    https://openart.ai/
    https://app.leonardo.ai/  
    https://grok.com/


### Accesibilidad
> Cuando insertamos una imagen podemos configurar el atributo "alt" 
> Este atributo (texto alternativo) Se utiliza específicamente para personas con alguna discapacidad visual, por ejemplo visitantes ciegos

### Combinando elementos
> ¿cómo harías si quisieras insertar el logo de una empresa y que este logo funcione como enlace al sitio web de esa empresa?
> Deberíamos anidar una imagen dentro de un enlace

<a href="url">
    <img src="path">
</a>

## Estructura de un documento html
> Cuando creemos una página HTML siempre tenemos que tener en cuenta la estructura que debe tener un documento
> En el caso en que no tengamos esta estructura base, nuestro documento estará mal formado

<!DOCTYPE html>
<html lang="en">
    <head>
        Elementos NO visuales
    </head>
    <body>
        Elementos visuales
    </body>
</html>

> Si un documento está mal informado tendrá una penalización a nivel posicionamiento orgánico (SEO & SEM)

    SEO: Search Engine Optimization  
    SEM: Search Engine Marketing  

## Enunciados

> Los enunciados sirven para posicionar el tema de la página (buscadores)
> Éstos tienen jerarquías que van desde el nivel 1 <h1> hasta el nivel 6
