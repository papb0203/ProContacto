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
        <img src="https://github.com/papb0203/ProContacto/blob/a66537b57277af5bf459af3ad6708ea4e8e1b623/Parte%201%2C%20punto%203.png" alt="Ejemplo 1 del ejercicio 3" width="500">
      </p>
      
   <p>2. Realizar un request POST a la URL anterior, y con body:</p>
   <pre>
      	{

	"name":"Tu nombre", 
	"email":tunombre.tuapellido@procontacto.com.mx"
	}
   </pre>
   <p>Lo cual se puede evidenciar en la siguiente imagen que se realizó</p>
   <p align="center">
        <img src="https://github.com/papb0203/ProContacto/blob/87813e96334ce08a42aa1522ebb0c545fec5bb21/Parte%202%2C%20punto3.png" alt="Ejemplo 2 del ejercicio 3" width="500">
      </p>	
   <p>3. Realizar nuevamente un request GET a la URL:https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json</p>
   <p align="center">
        <img src="https://github.com/papb0203/ProContacto/blob/87813e96334ce08a42aa1522ebb0c545fec5bb21/Parte%203%2C%20punto%203.png" alt="Ejemplo 3 del ejercicio 3" width="500">
      </p>
      <h3>¿Qué diferencias se observan entre las llamadas el punto 1 y 3?</h3>
      <p>En el punto 1 se pueden mirar toda la información de los aspirantes en el JSON, después en el punto 2 cuando se realiza el POST se ha agregado la información al JSON y se puede evidenciar esto en el punto 3 cuando ya aparece mi información.</p>
    
</section>

<section id="ejercicio-4">
  <h2>Ejercicio 4</h2>
  <p>Para este ejercicio se realizaron una serie de módulos en Trailhead, a los cuales se pueden acceder con este URL de mi perfil público: 				 
   https://www.salesforce.com/trailblazer/paulapenuela8434</p>
</section>

<section id="ejercicio-5">
  <h2>Ejercicio 5</h2>
  <p>En este ejercicio se van a explicar algunos objetos de Salesforce:</p>
  <ol>
  <li><b>Lead</b></li>
    <ul>
      <li>Este objeto es utilizado para representar a los prospectos o clientes potenciales que aún no han sido calificados como oportunidades de venta. Estos objetos tienen información básica sobre personas u organizaciones que han mostrado interés en los productos o servicios de una empresa. Este objeto se relaciona con Account, Contact,Opportunity.</li>
    </ul>
      <li><b>Account</b></li>
    <ul>
      <li>Este objeto es utilizado para representar una cuenta o una empresa con la que una empresa o una organización tiene una relación comercial. Estos objetos se utilizan para almacenar información sobre clientes, prospectos, socios comerciales y otras identidades con las que se interactúa. Este objeto se relaciona con Contact, Opportunity, Case, Asset.</li>
    </ul>
      <li><b>Contact</b></li>
    <ul>
      <li>Este objeto es utilizado para representar información sobre individuos o contactos comerciales, como clientes, socios, proveedores o empleados. Estos objetos pueden tener campos estándar o campos personalizados. Y tienen relaciones con Account y Opportunity.</li>
    </ul>
      <li><b>Opportunity</b></li>
    <ul>
      <li>Este objeto es utilizado para representar una oportunidad de negocio o venta potencial. Contiene información sobre una posible venta, el valor estimado de la venta, la etapa del proceso de ventas, entre otros. Este objeto tiene relación con Account,Contact y Product.</li>
    </ul>
      <li><b>Product</b></li>
    <ul>
      <li>Este objeto es utilizado para representar los productos o servicios que una empresa ofrece a sus clientes. Tiene relación con Pricebook, Opportunity, Asset y Quote..</li>
    </ul>
      <li><b>PriceBook</b></li>
    <ul>
      <li>Este objeto se utiliza para gestionar la información sobre los libros de precios de productos o servicios que se ofrecen a los clientes. Contiene los productos o servicios con sus precios correspondientes. Este objeto tiene relación con Opportunity y Quote. </li>
    </ul>
      <li><b>Quote</b></li>
    <ul>
      <li>Este objeto es utilizado para crear cotizaciones o propuestas comerciales para los clientes. Tiene relación con Opportunity,Account y Contact.</li>
    </ul>
      <li><b>Asset</b></li>
    <ul>
      <li>Este objeto se utiliza para realizar seguimiento de activos, como productos físicos o servicios, que son propiedad de una empresa o una organización. Este objeto tiene relación con Account,Contact y Product.</li>
    </ul>
      <li><em><b>Case</b></em></li>
    <ul>
      <li>Este objeto es utilizado para gestionar y dar seguimiento a las solicitudes o problemas al cliente. Este objeto tiene relación con Account y Contact.</li>
    </ul>
      <li><b>Article</b></li>
    <ul>
      <li>Este objeto se utiliza para gestionar artículos o contenido que se puede utilizar en la base de conocimientos o portal de autoservicio de una organización. Este objeto tiene relación con ninguno de estos.</li>
    </ul>
</ol>
<p align="center">
  Diagrama de clases
</p>
<p align="center">
  <img src="" alt="Imagen">
</p>

</section>

<section id="ejercicio-6">
  <h2>Ejercicio 6</h2>
  <p>Preguntas sobre Salesforce:</p>
  <h3>Soluciones de Salesforce</h3>
  <li><em>¿Qué es Salesforce?</em>
      <p>Es un sistema de CRM que contiene una gran cantidad de funciones estándar, o productos y funciones que no necesitan configuración y que puede utilizar para dirigir una empresa.</p>
    </li>
    <li><em>¿Qué es Sales Cloud?</em>
      <p>Es una plataforma de gestión de ventas que tiene Salesforce, la cual permite a las empresas optimizar los procesos de ventas, aumentar la eficiencia y mejorar la relación con los clientes.</p>
    </li>
    <li><em>¿Qué es Service Cloud?</em>
      <p>Es una herramienta de Salesforce para mejorar la experiencia del cliente a través de la gestión de casos y el soporte al cliente, ayudando a las empresas para aumentar su eficacia, su productividad y de esta manera mejorar la relación con sus clientes.</p>
    </li>
    <li><em>¿Qué es Health Cloud?</em>
      <p>Es una solución que creo Salesforce para la gestión de la atención médica que ayuda a coordinar y personalizar la atención del paciente, mejorar la eficiencia y la productividad con una amplia gama de herramientas y funcionalidades.</p>
    </li>
      <li><em>¿Qué es Marketing Cloud?</em>
      <p>Es una plataforma de marketing digital que permite a las empresas gestionar todas sus actividades de marketing en una sola plataforma integrada, adicionalmente ayuda a las empresas a crear y coordinar campañas de marketing personalizadas y efectivas.</p>
    </li>
    <h3>Funcionalidades de Salesforce</h3>
    <li><em>¿Qué es un RecordType?</em>
      <p>Es una forma de categorizar y personalizar los registros de un objeto, lo cual permite personalizar los campos y la estructura de cada registro y de esta manera facilita la automatización de los procesos empresariales.</p>
    </li>
     <li><em>¿Qué es un ReportType?</em>
      <p>Es una forma de definir cómo se relacionan los datos de diferentes objetos en un informe, permitiendo crear informes personalizados que pueden combinar datos de múltiples objetos en una sola vista.</p>
    </li>
    <li><em>¿Qué es un Page Layout?</em>
      <p>Es una forma de definir la apariencia y el comportamiento de los campos en una página de registro de un objeto.</p>
    </li>
    <li><em>¿Qué es un Compact Layout?</em>
      <p>Es una forma de definir qué campos se muestran en un resumen de registro, lo que permite a los usuarios ver de forma rápida y eficiente la información más importante sobre un registro en particular.</p>
    </li>
     <li><em>¿Qué es un Compact Layout?</em>
      <p>Es una forma de definir qué campos se muestran en un resumen de registro, lo que permite a los usuarios ver de forma rápida y eficiente la información más importante sobre un registro en particular.</p>
    </li>
     <li><em>¿Qué es un Perﬁl?</em>
      <p>Un perfil es un conjunto de permisos y configuraciones que determinan qué pueden hacer los usuarios en una organización. Los perfiles se utilizan para controlar el acceso a objetos, campos, funciones y datos en Salesforce.</p>
    </li>
    <li><em>¿Qué es un Rol?</em>
      <p>Un rol es una forma de controlar el acceso a los datos de la organización mediante la creación de una jerarquía de acceso a los datos. Esta jerarquía permite a los usuarios ver y editar los registros según su posición en la jerarquía.</p>
    </li>
     <li><em>¿Qué es un Validation Rule?</em>
      <p>Es una regla que se utiliza para garantizar que los datos ingresados en un registro cumplan ciertos requisitos antes de que se puedan guardar en la base de datos.</p>
    </li>
    <li><em>¿Qué diferencia hay entre una relación Master Detail y Lookup?</em>
      <p>Se encuentran 4 principales diferencias entre Master Detail y Lookup, las cuales son:
      
-	Dependencia de registro: En el caso de Master Detail el registro secundario depende del registro maestro, lo cual implica que si se elimina el registro maestro se eliminan todos los registros asociados a él, mientras que en el caso de Lookup los registros secundarios no dependen del registro maestro y pueden existir independientemente del registro maestro. 

-	Campos requeridos: En el caso de Master Detail los campos obligatorios del registro maestro se convierten en campos obligatorios en el registro secundario, mientras que en la relación Lookup los campos requeridos en el registro maestro no tienen que ser campos requeridos en el registro secundario.

-	Herencia de permisos: En el caso de Master Detail los permisos de los registros secundarios heredan los permisos del registro maestro, mientras que en la relación Lookup los permisos no se heredan.

-	Rol del propietario: En el caso de Master Detail el registro secundario siempre hereda el rol de propietario del registro maestro, lo cual implica que el registro secundario pertenece al mismo usuario o equipo del registro maestro, mientras que en la relación Lookup el registro secundario puede tener el rol de propietario diferente al del registro maestro.

</p>
    </li>
    <li><em>¿Qué es un Sandbox?</em>
      <p>Es un entorno de pruebas y desarrollo separado de la instancia de producción, la cual se utiliza para realizar pruebas, experimentar con nuevas funcionalidades, desarrollar nuevas aplicaciones y personalizar la configuración sin afectar a la instancia de producción.</p>
    </li>
    <li><em>¿Qué es un ChangeSet?</em>
      <p>Se utiliza para recopilar y organizar todos los componentes que se han modificado, como objetos personalizados, campos, perfiles, permisos, flujos de trabajo, informes, entre otros.</p>
    </li>
    <li><em>¿Para qué sirve el import Wizard de Salesforce?</em>
      <p>Es una herramienta que se utiliza para importar grandes cantidades de datos en una instancia de Salesforce. Es una forma rápida y sencilla de cargar datos desde fuentes externas, como hoja de cálculo de Excel, archivos CSV y archivos de Microsoft.</p>
    </li>
     <li><em>¿Para qué sirve la funcionalidad Web to Lead?</em>
      <p>Es  una herramienta que permite a las empresas capturar y gestionar automáticamente las solicitudes de soporte de los clientes de su sitio web, también se pueden crear casos de soporte.</p>
    </li>
    <li><em>¿Para qué sirve la funcionalidad Omnichannel?</em>
      <p>Es una herramienta que permite a las empresas administrar múltiples canales de comunicación y mejorar la experiencia del cliente.</p>
    </li>
     <li><em>¿Para qué sirve la funcionalidad Chatter?</em>
      <p>Es una herramienta de colaboración y comunicación que permite a los usuarios compartir información, discutir ideas y colaborar en proyectos dentro de la plataforma Salesforce.</p>
    </li>
    
   <h3>Conceptos generales</h3>
   <li><em>¿Qué signiﬁca SaaS?</em>
      <p>Es un modelo de distribución de software en el que el proveedor del servicio aloja y mantiene la aplicación en sus servidores y los usuarios acceden a ella a través de internet utilizando un navegador web.</p>
    </li>
    <li><em>¿Salesforce es Saas?</em>
      <p>Sí, ya que Salesforce proporciona una plataforma en línea que permite a las empresas gestionar y automatizar sus proceso de ventas, marketing y atención al cliente.</p>
    </li>
    <li><em>¿Qué signiﬁca que una solución sea Cloud?</em>
      <p>Cuando una solución es cloud significa que está basada en la nube, lo cual significa que se ejecuta en servidores remotos en lugar de en la computadora local del usuario.</p>
    </li>
   <li><em>¿Qué signiﬁca que una solución sea On-Premise?</em>
      <p>Significa que está instalada y se ejecuta en los servidores locales de la empresa o de los usuarios, en lugar de estar alojada en la nube. Lo cual significa que la empresa es responsable de adquirir, instalar, configurar, mantener y actualizar los servidores y software necesarios para que la aplicación funcione.</p>
    </li>
     <li><em>¿Qué es un pipeline de ventas?</em>
      <p>Es una representación visual de las diferentes etapas que sigue un cliente potencial desde que se convierte en un lead hasta que finalmente se convierte en un cliente.</p>
    </li>
    <li><em>¿Qué es un funnel de ventas?</em>
      <p>Un funnel de ventas también es conocido como un embudo de ventas debido a que se hace una semejanza a que se empieza con una gran cantidad de clientes potenciales entrando en la parte superior y un número cada vez menor de ellos avanzando en el proceso de ventas, hasta llegar a la conversión. Por lo tanto un funnel de ventas es una representación visual del proceso de ventas que sigue un cliente potencial desde su primer contacto con una empresa hasta la conversión en un cliente.</p>
    </li>
    <li><em>¿Qué signiﬁca Customer Experience?</em>
      <p>Se refiere a la percepción general que un cliente tiene de todas las interacciones que ha tenido con una empresa a lo largo del tiempo, desde el primer contacto hasta la postventa y el soporte al cliente.</p>
    </li>
    <li><em>¿Qué signiﬁca omnicanalidad?</em>
      <p>Es una estrategia de experiencia del cliente que implica la integración y coordinación de múltiples canales de comunicación y puntos de contacto para brindar una experiencia coherente y unificada al cliente.</p>
    </li>
     <li><em>¿Qué signiﬁca que un negocio sea B2B?¿Qué signiﬁca que un negocio sea B2C?¿Qué es un KPI?</em>
      <p>Que un negocio sea B2B significa que son empresas que venden productos o servicios a otras empresas. Cuando un negocio es B2C significa que son empresas que venden productos o servicios directamente a los consumidores. Y los KPI son medidas específicas utilizadas para evaluar el desempeño de una empresa, departamento, proceso o empleado.</p>
    </li>
    <li><em>¿Qué es una API y en qué se diferencia de una Rest API?</em>
      <p>Una API es un conjunto de protocolos que permiten que diferentes aplicaciones y sistemas se comuniquen entre sí y compartan información y funcionalidades. Y la diferencia con una Rest API es que esta utiliza una arquitectura basada en estándares web, mientras que otros tipo de APIs pueden tener diferentes arquitecturas y protocolos de comunicación.</p>
    </li>
    <li><em>¿Qué es un Proceso Batch?</em>
      <p>Es una forma de procesar grandes volúmenes de registros de forma programática en lotes, en lugar de procesarlos uno por uno.</p>
    </li>
    <li><em>¿Qué es Kanban?</em>
      <p>Es una técnica visual y flexible de gestión de proyectos y procesos que permite una mejor planificación, seguimiento y mejora continua del trabajo.</p>
    </li>
    <li><em>¿Qué es un ERP?</em>
      <p>Es una software de gestión empresarial que integra y automatiza una amplia variedad de procesos y funciones de negocio, tales como finanzas, contabilidad, compras, ventas, producción, inventario, recursos humanos, entre otros.</p>
    </li>
    <li><em>¿Salesforce es un ERP?</em>
      <p>Salesforce se centra principalmente en la gestión de las relaciones con los clientes y en la mejora de la experiencia del cliente, en lugar de la gestión integral de la empresa, por lo tanto no se representa como un ERP. </p>
    </li>
    
</section>

<section id="ejercicio-7">
  <h2>Ejercicio 7</h2>
  <p>Para esta sección práctica se realizó primero un GET en POSTMAN al siguiente URL: https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts.json, esto con el fin de encontrar mi 
  ID el cual es:- NeiZ_MqBZFRqIDE24QR. Posteriormente, se adiciona un campo al objeto Contact llamado idprocontacto y se realizaron estos códigos con el fin de desarrollar un trigger que 
  modifique y adicione el email cuando vaya a registrar o cambiar algún contacto. Los códigos son los siguientes:  </p>

  
