![CSS3_logo](readme_content/css3_icon_logo.png)

# CSS Básico - _(ES)_

## Prácitca de **display**

>## Display
La propiedad **display** junto a los valores con los que puede ser seteada: _inline, inline-block, block_ o _float_, permite definir la ubicación de elementos de manera individual.

* `display: inline`\
    Es la configuración por default usada por elementos como **\<span\>**, **\<b\>** e **\<i\>** entre otros, para tratar con la **renderización de texto** dentro de un tag contenedor o _parent_, con un ancho (_width_) que no conocemos.
    Lo particular de display es que, si lo usamos por ejemplo, para renderizar texto, nos permite que esto sea como en la vida real donde se escriben las palabras una seguida a la otra.\
    **NOTA**: los elementos _inline_ son automáticamente llevados a la línea inferior siguiente cuando éstos exceden el ancho del contenedor padre.

* `display: block`\
  En contraste con los elementos _inline_, la propiedad _block_ considera como **bloque** a toda una línea (considerando que esa línea tiene el mismo ancho que su contenedor).\
  Por default el tag **\<div\>** es un elemento de bloque.
  **NOTA**: si además de especificar este tipo de display a un \<div\>, especificamos su propio _width_, veremos que nada tiene que ver el ancho de este contenedor al ancho del contenido. Siempre se considerará a cada elemento como un bloque; tenga este el mismo ancho que el contenedor padre, o no.
  