Javascript Q&A

• ¿Cual es la diferencia entre las funciones sincronas y asincronas?

> Las funciones sincronas suceden de manera procedural/lineal, funcionan a presente y dan respuestas inmediatas.
> Mientras que las funciones asincronas no esperan las instrucciones pero continuan ejecutandose brindando una respuesta a futuro(Promesa).

> Las funciones sincronas al ser procedurales tienen un tiempo de ejecucion mayor, ya que las asincronas permiten la realizacion de varias tareas en paralelo al no necesitarse las unas a las otras para lograr su funcionalidad.
--------------------------------------------------------------------------------------------------------------------------
• ¿Por qué Fetch es la forma preferida de enviar una solicitud de red a través del navegador web?

> El metodo Fetch proporciona una interfaz, la cual es facil obtener los datos mediante un HTTP request ya que se basa unicamente en request & response, es mas improbable que de un error de estado ya que si la API esta bien construida, el fetch siempre devolvería datos, por ende solamente se presentaria un "error" en caso de que no se haya podido conseguir la información.
--------------------------------------------------------------------------------------------------------------------------
• Si el navegador encuentra el HTML mal estructurado, ¿qué puede ocurrir?

> Esto depende del navegador pero es posible que no se muestre la pagina en lo absoluto, brindando un codigo de error 404. O que el navegador intente renderizar los elementos no de la manera correcta.
--------------------------------------------------------------------------------------------------------------------------
• ¿Existe otra opción, además de las llamadas "Promises" explícitas, para manejar código asíncrono en JavaScript?

> Podríamos usar callbacks o async/awaits especificamente
--------------------------------------------------------------------------------------------------------------------------
• Explique la función y la sintaxis del método forEach() del array.

> El forEach va iterando sobre cada elemento de un arreglo, es decir, si tenemos un

/*
const arregloFrutas = ['manzana', 'banana', 'pera'];

arregloFrutas.forEach((fruta) => console.log(fruta));
*/

> Esto devolvera por consola cada una de las frutas en una linea distinta, ya que se ejecuta la seccion de codigo por cada elemento del arreglo.
--------------------------------------------------------------------------------------------------------------------------

• ¿Existe alguna forma de evitar que se produzca un evento?

> En el caso de que el evento nos arroje un resultado por defecto, deberemos utilizar o un return false o un preventDefault()
--------------------------------------------------------------------------------------------------------------------------


