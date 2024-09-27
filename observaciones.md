Chicas, felicitaciones por la entrega de su trabajo. Sé que fue un TP muy, muy complejo y me alegra ver que mas alla de las dificultades hay un buen entendimiento de js y los temas principales que vimos en este modulo. 

Hay muchas consignas incumplidas en este trabajo, y lamento que no hayan escrito mas seguido para que pudiera guiarlas en algunas cosas. En principio, la primera sensación que me da la lectura de este código es que hay muchas cosas aquí que no vimos, o vimos con poca profundidad, y me sorprende su uso aquí. No puedo sacar conclusiones a partir de la sola lectura del código, pero sí espero que tengan esto en cuenta: No están en este curso para hacer TPs solo por tenerlos entregados, eso es un desperdicio de su tiempo y el mío. Espero que estén en este curso para aprender a programar. 

Eso significa que muchas veces escribirán código del que no se sientan orgullosas en un futuro, pero eso es parte de aprender. Entregar código que no entienden del todo, código que no podrían escribir solas en un futuro, no les enseña nada. Este punto no forma parte de la corrección estrictamente hablando, ya que es sólo una intuición mía, pero dado que los TPs me importan muy poco, y me importa muchisimo que aprendan, espero al menos que reflexionen sobre este punto: qué aprendieron con este TP?. Si hay código entregado que no entienden, hubo una oportunidad malgastada. 

Si esta decisión ocurrió por falta de tiempo es super comprensible: se que este trabajo les exigió muchisimo. Espero que en el proximo TP puedan demostrarme lo que son capaces de hacer con tiempo y ganas.

Con respecto a los puntos de evaluación, 

- Respeta la consigna

Cumplido en general. 

- Estructura correcta de documento HTML

Cumplido. Ocasionalmente tienen etiquetas mal cerradas -un mal casi inevitable cuando trabajamos con tantos divs- y algunas otras cositas a mejorar que les dejo anotadas. Presten atención a los for de los label - no los usan bien. Les dejé algunos comentarios al respecto. 

- Respeta el diseño dado

Cumplido. 

- Respeta el funcionamiento

Cumplido con excepciones. Las mas importantes, y que les recomiendo arreglar antes de publicar este codigo o agregarlo a sus portfolios: 

- Apenas se carga la pagina no se ven las operaciones que tienen en el local storage. Busquen la funcion que tienen que muestra esas operaciones y ejecutenla apenas carga la pagina. 

- Los filtros no funcionan bien. Al select de las categorías le falta la opción "todas", por lo que siempre se esta aplicando al menos una categoría. En ningún momento puedo ver todas las operaciones. 

- El balance no se actualiza al agregar nuevas operaciones o editarlas. La funcion que actualiza el balance deberia ejecutarse cada vez que agregamos o editamos. 

- No se actualiza el select de las categorias si editamos una. 

- la pagina se refresca al editar operaciones. Hay un e.preventDefault que les esta faltando. 

- Respeta el flujo de pantallas

Cumplido. 

- Responsive funciona correctamente

Cumplido a medias, la seccion mas importante - la lista de operaciones - es ilegible en mobile. 

- Código bien indentado

Cumplido. 

- Buenos nombres de funciones y variables

Cumplido con excepciones, les dejo comentadas un par. 

- Funciones pequeñas

Cumplido a medias, hay muchas cosas que deberian estar en una funcion auxiliar. 

- Nombres de branchs adecuados

Cumplido

- Lógica clara y simple

No cumplido en ciertas ocasiones, hay muchisimas decisiones para mi incomprensibles, como retornar arrays, o hacer una funcion que reciba un array como parametro, algo muy confuso especialmente para la etapa en la que estan. 

- Buen uso estructuras de datos (arrays y objetos)

Correcto, aunque noto usos de temas como bracket notation que no vimos y dudo que entiendan del todo. 

- Buen uso de estructuras de control (condicionales y bucles)

Correcto

- Buen uso de métodos funcionales de array (map, filter, reduce, etc)

No logrado para el filter, se los dejé anotado. Recuerden que en el filter retornamos la condicion que deben cumplir los elementos, no el elemento en sí. 

- Reutilización de lógica / funciones

Bien

- Commits con mensajes adecuados

Cumplido en general

- Un PR por funcionalidad, fix o mejora

Cumplido

- PRs con buenos títulos

Cumplido!

### Nota final: 8
