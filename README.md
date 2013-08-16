# Translation of the Ruby on Rails Tutorial (4.0 version)

Esto repositorio contiene el codigo funte  HTML por [Rails 4.0 version of the Ruby on Rails Tutorial](http://railstutorial.org/), con el proposito de permitir la traduccion de esto tutorial en otro idioma aparte la [*lingua franca*](http://en.wikipedia.org/wiki/Lingua_franca). 

## Para Empiezar

Por traducir el Tutorial de Ruby On Rails, simplemente 'fork' esto repositorio, clonalo en tu maquina local, y empieza a traducir en el tuyo idioma. Si tu quiere trabajar con otro traductores (que sin duda es algo que yo fomentaria), agregalo como colaboradores al repositorio donde estas trabajando. En cualquier momento tu eres libre de poner el resultado en una URL de tu elegion. Una vez que está arriba y listo para el consumo público, enviar URI a `admin@railstutorial.org` y yo voy a enviar el link a eso desde el principal sitio de 'Rails Tutorial'.

Puesto que a menudo hacen correcciones pequeñas al libro, yo recomiendo el 'merging' (agregar los cambios) en el 'master branch' (el ramo principal del repositorio) de vez en cuando. Si te das cuentas que el 'merging' la fusión provoca demasiados conflictos, tu puede omitir este paso optionale.

## Codigo Fuente

El repositorio contiene codigo fuente HTML por cada capítulo de 'Ruby on Rails Tutorial', así como dos CSS archivos por le estilo y el directorio de las imágenes donde estan todos las imágenes del libro. Tenga en cuenta que la imagen de los URI en los archivos HTML son *relativo*, exemplo, aparecen como

    images/figures/foo.png

sin diagonal inicial. Eso porque cuando tu ves los archivos HTML localmente todas las imágenes cargano correctamente. 

Para obtener una versión completamente desplegado del libro, tu puede cambiar la ruta de las imágenes desde relativo a absoluto, tal como
    /images/figures/foo.png

Si esto resulta ser el caso, Recomiendo escribir un script para crear la justa version en produccion. Tu tiene que encontrar la siguiente linea de codigo

```ruby
text.gsub!('"images/', '"/images/')
```

para ser útil en este contexto.

## Licencia

*Ruby on Rails Tutorial, 2nd Edition*. Copyright &copy (Derecho de Autor) ; 2013 de Michael Hartl.

El codigo fuente HTML de el libro 'Ruby On Rails Tutorial' que está disponible bajo el [Creative Commons Attribution-ShareAlike 3.0 Unported License](http://creativecommons.org/licenses/by-sa/3.0/), que permite la traducción del libro, siempre y cuando te dan la atribución al autor original ([Michael Hartl](http://michaelhartl.com/)) y distribuir la traducción bajo la misma licencia.
