# Elements Centering | _Centrado de elementos_

> ## Centrando div perteneciente a una jerarquía de div's
 
Cuando queremos centrar div's nos encontramos frente a una tarea que parece sonar sencilla pero se vuelve un tanto _tricky_; sobre todo, si hablamos de la tarea de querer centrar un div que está dentro de un padre, y éste, dentro de otro padre... y así subiendo cuantas jerarquías nos imaginemos!\
En principio, vamos a tomar ejemplos sencillos con el fin de poder **entender el concepto** y las razones detrás del por qué debemos hacerlo de tal o cuál manera.

    <div class="container">
        <div class="outer_div">
            <div class="inner_div"></div>
        </div>
    </div>

Supongamos que tenemos una estructura como la que aparece en el fragmento de código de arriba. Nuestra tarea es centrar, primero, **HORIZONTALMENTE** nuestro _inner\_div_.\
Bien, veamos primero el resultado final de esto y luego vamos a ver el código CSS.\

![div_centrado_horizontal](readme_content/)