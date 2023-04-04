# Evaluación práctica ProContacto
<!DOCTYPE html>
<html>
<nav>
  <ul>
    <li><a href="#ejercicio-1">Ejercicio 1</a></li>
    <li><a href="#ejercicio-2">Ejercicio 2</a></li>
    <li><a href="#ejercicio-3">Ejercicio 3</a></li>
    <li><a href="#ejercicio-4">Ejercicio 4</a></li>
    <li><a href="#ejercicio-5">Ejercicio 5</a></li>
    <li><a href="#ejercicio-6">Ejercicio 6</a></li>
    <li><a href="#ejercicio-7">Ejercicio 7</a></li>
  </ul>
</nav>

<!-- Aquí iría el contenido -->

<section id="ejercicio-1">
  <h2>Ejercicio 1</h2>
  <p>Para este ejercicio se realizó la instalación de los respectivos programas como visual studio code, git y git bash. </p>
</section>

<section id="ejercicio-2">
  <h2>Ejercicio 2</h2>
  <p>Para este ejercicio se van a responder algunas preguntas sobre el protocolo HTTP, las cuales son las siguientes:</p>
  <ul style="list-style-type: square;">
    <li>
      <h3>¿Qué es un servidor HTTP?</h3>
      <p>Es un lenguaje capaz de interpretar y responder requests de clientes del internet.</p>
    </li>
    <li>
      <h3>¿Qué son los verbos HTTP? Mencionar los más conocidos</h3>
      <p>Son el conjunto de métodos de petición que son utilizados para saber qué operaciones realizar. Los más conocidos son Get, Post, Delete, Hea,Put.</p>
    </li>
    <li>
      <h3>¿Qué es un request y un response en una comunicación HTTP? ¿Qué son los headers?</h3>
      <p>El request es la solicitud que envía el cliente al servidor para solicitar un recurso y el response es el mensaje o respuesta que envía el servidor al cliente enviándole la información del recuro solicitado. Los headers es una información que se puede adicionar en los request o response para agregar información adicional.</p>
    </li>
    <li>
      <h3>¿Qué es un queryString? (En el contexto de una url)</h3>
      <p>Un queryString son una serie de palabras que se utilizan con el fin de agregar información adicional a una solicitud HTTP, estas palabras se deben agregar después del (?) en el URL.</p>
    </li>
    <li>
      <h3>¿Qué es el responseCode? ¿Qué signiﬁcado tiene los posibles valores devueltos?</h3>
      <p>El responseCode es un número de 3 dígitos que nos va a decir el estado de la respuesta HTTP. Se pueden tener los siguientes responseCode:

-       100 s: Son respuestas informativas para indicar que la solicitud enviada continua

-       200 s: Estos códigos envían respuestas afirmativas, en donde dicen que las solicitudes fueron procesadas y procesadas.

-       300 s: Estos códigos son de redireccionamiento, lo cual indica que el servidor necesita realizar otra acción para lograr realizar esta solicitud.

-       400 s: Estos códigos nos indican que está sucediendo un error en el cliente, lo cual nos significa que sucede un problema con la solicitud.

-       500 s: Estos códigos nos indican que está sucediendo un error en el servidor, lo cual nos indica que la solicitud fue recibida, pero que sucede un problema es con el servidor.</p>
    </li>
    <li>
      <h3>¿Cómo se envía la data en un Get y cómo en un POST?</h3>
      <p>En un Get los datos se envían en la misma dirección URL como un queryString, mientras que en el POST los datos se envían en el cuerpo del mensaje de HTTP.</p>
    </li>
    <li>
      <h3>¿Qué verbo http utiliza el navegador cuando accedemos a una página?</h3>
      <p>Utiliza el verbo GET para poder acceder a una página.</p>
    </li>
    <li>
      <h3>Explicar brevemente qué son las estructuras de datos JSON y XML dando ejemplo de   estructuras posibles</h3>
      <p>JSON y XML son estructuras de datos que son utilizados para representar datos estructurados en un formato que sea legible por maquinas.</p>
      <p>JSON:</p>
      <pre>
      	{
	“name”: “paula”,
	“edad”: 20,
	“email”: “papb0203@gmail.com”
	}
	</pre>
       <p>XML:</p>
       <pre><code>
      	 &lt;usuario&gt;
    	 &lt;nombre&gt;Paula Peñuela&lt;/nombre&gt;
   	 &lt;edad&gt;20&lt;/edad&gt;
   	 &lt;ciudad&gt;Bogotá D.C.&lt;/ciudad&gt;
	&lt;/usuario&gt;
	</code></pre>
	</li>
     <li>
      <h3>Explicar brevemente el estándar SOAP</h3>
      <p>Es un protocolo de comunicación que es utilizado para intercambiar información estructurada en la web utilizando XML.</p>
    </li>
    <li>
      <h3>Explicar brevemente el estándar REST Full</h3>
      <p>El estándar RestFul es un estilo arquitectónico que es utilizado para el diseño de aplicaciones web que es basado en el uso de protocolo HTTP y URI, además utiliza el formato JSON o XML para transferir información.</p>
    </li>
     <li>
      <h3>11.	¿Qué son los headers en un request? ¿Para qué se utiliza el key Content-type en un header?</h3>
      <p>Los headers  en un request  se utilizar para enviar información adicional para la solicitud . El key Content-type es un  header que es utilizado para indicar el tipo de contenido que se envía en un request o response, es para indicar si el contenido es un texto plano, HTML,JSON o XML. </p>
    </li>
</section>

<section id="ejercicio-3">
  <h2>Ejercicio 3</h2>
  <p>Para este ejercicio se realizaron una serie de pasos para realizar un request GET y POST de una URL, esto se realizó en POSTMAN. Los pasos que se realizaron son:</p>
  <p>1. Realizar un request GET a la URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json</p>
   <p align="center">
        <img src="https://github.com/papb0203/ProContacto/blob/main/Get1%20punto%203.png" alt="Ejemplo 1 del ejercicio 3" width="500">
      </p>
      
   <p>2. Realizar un request POST a la URL anterior, y con body:</p>
   <pre>
      	{

	"name":"Tu nombre", 
	"email":tunombre.tuapellido@procontacto.com.mx"
	}
   </pre>
   <p>Lo cual se puede evidenciar en la siguiente imagen que se realizó</p>
   <p>3. Realizar nuevamente un request GET a la URL:https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json</p>
   <p align="center">
        <img src="https://github.com/papb0203/ProContacto/blob/main/Get3%20punto%203.png" alt="Ejemplo 3 del ejercicio 3" width="500">
      </p>
      <h3>¿Qué diferencias se observan entre las llamadas el punto 1 y 3?</h3>
      <p>En el punto 1 se pueden mirar toda la información de los aspirantes en el JSON, después en el punto 2 cuando se realiza el POST se ha agregado la información al JSON y se puede evidenciar esto en el punto 3 cuando ya aparece mi información.</p>
    
</section>

<section id="ejercicio-4">
  <h2>Ejercicio 4</h2>
  <p>Contenido de la sección 4</p>
</section>

<section id="ejercicio-5">
  <h2>Ejercicio 5</h2>
  <p>Contenido de la sección 5</p>
</section>

<section id="ejercicio-6">
  <h2>Ejercicio 6</h2>
  <p>Contenido de la sección 6</p>
</section>

<section id="ejercicio-7">
  <h2>Ejercicio 7</h2>
  <p>Contenido de la sección </p>
</section>

