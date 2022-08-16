# <h1 align = "center">Salesforce-DEV-TEST 🖥️ <h1>
<br>

## 📍EJERCICIO 2

1. El servidor HTTP es una pieza de software capaz de comprender URLs (direcciones web) y HTTP (el protocolo que tu navegador usa para obtener las páginas web).

2. Los verbos HTTP son aquellos que indican que acción queremos realizar sobre el servidor. Los más conocidos son GET y POST, usados en formularios HTML, por ejemplo.

3. En una comunicación HTTP un request es la petición que el usuario realiza y un response es la respuesta que el servidor le envía y es desplegada por el navegador. Los header son aquellos que indican tanto en el response como el request lenguaje, codificación, tipo de datos (XML, JSON, etc), etc.

4. Un query string es aquello que en la URL luego de un signo de interrogación, es enviado al servidor.

5. El responseCode es el mensaje que envía el servidor al cliente tras haber recibido una petición o HTTP request. Los distintos valores devueltos pueden significar: Respuestas informativas (100–199), Respuestas satisfactorias (200–299), Redirecciones (300–399), Errores de los clientes (400–499) y errores de los servidores (500–599).

6. La data en un GET se envía por medio de la URL, es decir, si el usuario llena un formulario sus datos enviados aparecerán en la URL. En cambio, por medio del método POST esos datos enviados por el usuario no son visibles en la URL.

7. Cuando accedemos a un sitio web el navegador utiliza el verbo GET.

8. XML es un lenguaje de marcado (como dice en realidad en su nombre) utilizado para el intercambio de información entre sistemas con sintaxis similar a HTML. El formato de este estándar está basado en texto para representar información estructurada: datos, documentos, configuración, etc.<br>JSON es una forma de representar objetos (como también se indica en su nombre). Ejemplos de posibles estructuras de XML y JSON:

#### <h4 align = "center" >POSIBLE ESTRUCTURA JSON</h4>
```JSON
{
    “pieza”: {
        “tipo”: “A”
        “nombre”: “Tornillo”,
        “descripcion”: “Cilindro mecánico con una cabeza utilizado en la fijación temporal de unas piezas con otras”,
        “caracteristica”: {
            “tipo”: “metal”
            “tamanyo”: 10
        },
        “vacio”: “”
     }
}
```
#### <h4 align = "center">POSIBLE ESTRUCTURA XML</h4>
```XML
<pieza tipo="A">
    <nombre>Tornillo</nombre>
    <descripcion>Cilindro mecanico con una cabeza utilizado en la fijación temporal de unas piezas con otras 
    </descripcion>
    <caracateristica>
        <tipo>metal</tipo>
        <tamanyo>10</tamanyo>
    </caracateristica>
    <vacio></vacio>
</pieza>
```

9. SOAP es un estándar basado en XML para la transmisión de mensajes en HTTP y otros protocolos de Internet.

10. El estándar REST (Representational State Transfer) es un estilo de arquitectura de software para realizar una comunicación cliente-servidor y RESTful es la implementación de dicha arquitectura.

11. Los header en un request permiten al cliente y al servidor enviar información adicional junto a una petición o respuesta. El content type se usa para indicar al cliente o navegador qué clase de archivo o medio le está enviando el servidor.

## 📍EJERCICIO 3

1. La diferencia que se observa entre las llamadas 1 y 3 es que al haber un POST de por medio donde el usuario (yo) ingreso mis datos, estos se almacenan y al volver a solicitar un request de tipo GET en la response del server encontrare los datos ingresados anteriormente. Esto sucede ya que las request de tipo GET del usuario son re recolección de información y las request de tipo POST del usuario son de envió de datos.

## 📍EJERCICIO 4

* Soluciones aquí, https://trailblazer.me/id/fdimarco1
<br>

## 📍EJERCICIO 5

1. un Lead es el objeto predeterminado que se crea cuando se recibe nueva información de contacto en su base de datos.

2. Un Account representa una cuenta individual, que es una organización o persona involucrada con su negocio (como clientes, competidores y socios).

3. Un Contact representa a un contacto, que es una persona asociada a una cuenta. 4)Una Opportunity representa una oportunidad, que es una venta o trato pendiente.

5. Un Product representa un producto que vende una empresa. Este objeto tiene varios campos que se usan solo para programaciones de cantidad e ingresos (por ejemplo, anualidades). Los cronogramas están disponibles solo para organizaciones que han activado las funciones de productos y cronogramas. Si estas funciones no están habilitadas, los campos de programación no aparecen en DescribeSObjectResult y no puede consultar, crear o actualizar los campos.

6. Un Pricebook representa un libro de precios que contiene la lista de productos que vende una organización.

7. Un Quote representa una cotización, que es un registro que muestra los precios propuestos para productos y servicios. Las cotizaciones se pueden crear y sincronizar con oportunidades, y se pueden enviar por correo electrónico como archivos PDF a los clientes.

8. Un Asset representa un artículo de valor comercial, como un producto vendido por una empresa o un competidor, que ha comprado un cliente.

9. Un Case representa un caso, que es un asunto o problema del cliente.

10. Un Article es un objeto utilizado para asociar un artículo con categorías de datos de un grupo de categorías de datos o para consultar las selecciones de categoría de un artículo.

#### <h4 align = "center">RELACIONES ENTRE OBJETOS</h4>

<div align = "center">
    
<img src = "https://i.postimg.cc/jqvZtYzB/relaciones.png)](https://postimg.cc/LhYz37QV" width = 70% alt = "relaciones">

</div>
    
## 📍EJERCICIO 6

### Soluciones Salesforce
A) Salesforce es una plataforma de gestión de las relaciones con los clientes (CRM) basada en la nube.<br>
B) Sales Cloud es una aplicación que permite a los usuarios tener acceso a su información dondequiera que se encuentren, siempre y cuando tengan un PC conectado o una aplicación móvil basada en Internet.<br>
C) Service Cloud es un software de servicio al cliente.<br>
D) Health Cloud es un sistema CRM de TI de salud que incorpora relacion doctor-paciente y servicios de administración de registros.<br>
E) Marketing cloud es una plataforma de marketing digital de Salesforce que incluye herramientas para el marketing por correo electrónico, el marketing a través de redes sociales, el marketing para dispositivos móviles, la publicidad online y la automatización del marketing.<br>

### Conceptos Generales
A) SaaS significa Software as a Service (Sofware como un Servicio).<br>
B) Si, Salesforce es SaaS.<br>
C) Las soluciones Cloud son soluciones que se alojan en servidores externos a la empresa a los que se ingresa mediante internet.<br>
D) Si la solución es de tipo On-premise significa que la solución será la instalación de un programa realizada de manera local, en las instalaciones de la empresa y obligando a esta a crear una infraestructura informática compleja con servidores que requieren mantenimiento.<br>
E) Un pipeline de ventas es el proceso de actividades y estrategias que necesita un vendedor para acelerar el ciclo de ventas, transformando clientes potenciales (aquellos que acaban de conocer tu marca o servicio) en clientes.<br>
F) Un funnel de ventas es la forma en que una empresa planea y establece procesos para ponerse en contacto con los diferentes usuarios y así llegar a cumplir un objetivo final, que bien puede ser la conversión de clientes, lograr un registro, cerrar una venta, entre otros.<br>
G) Customer experience significa experiencia del cliente.<br>
H) Omnicanalidad es una estrategia de comunicación utilizada para estar en contacto con los prospectos o clientes a través de diferentes canales (email, redes sociales, sitio web, etc.). El uso de los diferentes canales debe hacerse bajo una misma estrategia para llegar al consumidor en el momento indicado.<br>
I) B2B (business to business) es el modelo de negocio en el que se realizan transacciones comerciales entre empresas. En cambio, en el modelo B2C (business to consumer) esas transacciones se efectúan entre negocios —de cualquier magnitud— y los consumidores.<br>
Un KPI (Key Perfonce Indicator) es un indicador que mide el nivel de desempeño de nuestras acciones frente a los objetivos establecidos previamente en nuestra estrategia.<br>
J) Una API (Application programming interface) es el código que determina el funcionamiento de un programa informático que sirve para canalizar información de una parte de un software a otra. la API sigue el formato de aplicación a aplicación, mientras que REST sigue una estructura diferente: Cliente-Servidor.<br>
K) Un proceso de produccion por lotes, o batch, no es más que la producción de una cantidad limitada de un tipo de producto cada vez. Cada lote recibe una identificación, como número o código. Además, cada lote exige un plan de producción específico.<br>
L) Kanban es una metodología para gestionar el trabajo la cual consiste en lo visual. está compuesto por tres columnas: “Por hacer”, “En proceso” y “Hecho”.<br>
M) ERP (Enterprise Resource Planning) es un tipo de software que las organizaciones utilizan para gestionar las actividades empresariales diarias, como la contabilidad, el aprovisionamiento, la gestión de proyectos, la gestión de riesgos, el cumplimiento y las operaciones de la cadena de suministro.<br>
N) Salesforce no es un ERP.

### Funcionalidades Salesforce
A) Un record type es una funcionalidad te permite tener diferentes procesos de negocios, valores de lista de selección y diseños de página para diferentes usuarios según el perfil.<br>
B) Un report type es una funcionalidad que te permite crear reportes y mostrar diferentes tipos de información en base a lo que se quiere. Existen 4 tipos y son: Tabular, Summary, Matrix y Joined.<br>
C) Page layout es una funcionalidad que nos permite customizar el diseño y organizacion de páginas de edición y detalle de registros.<br>
D) Compact layout muestra los campos clave de un registro de un vistazo en la aplicación móvil Salesforce, Lightning Experience y en las integraciones de Outlook y Gmail.<br>
E) Un perfil define como acceden los usuarios a objetos y datos y que pueden hacer en la aplicación.<br>
F) Un rol es opcional y sólo pueden ser asignados una vez el usuario haya establecido un perfil.<br>
G) Un Validation Rule se encarga de verificar que los datos que un usuario ingresa en un registro cumplen con los estándares especificados antes que el usuario pueda guardad ese registro.<br>
H) La diferencia que puedo establecer entre las relaciones de objetos Lookup y Master-Detail es que en las relaciones lookup los objetos que se relacionan son independientes entre sí y ocupan lugar en la interfaz del usuario mientras que en las relaciones master-detail el objeto secundario (detail) no tiene esa libertad ya que depende del objeto principal (master).<br>
I) Sandbox es una copia de la organizacion en un entorno aislado que puede usar para distintos fines, como pruebas y capacitación. Los sandbox están completamente aislados de su organización de producción de Salesforce.<br>
J) Un change set permite enviar personalizaciones de una organizacion de salesforce a otra.<br>
K) Import Wizard convierte en una tarea más sencilla el importe de datos para muchos objetos estándar de Saleforce, incluyendo cuentas, contactos, guias, soluciones, miembros de campaña y cuentas de personas.<br>
L) Salesforce lead es el proceso de usar un formulario de un sitio web para capturar la información de un visitante y guardar esa información como un nuevo lead en Salesforce.<br>
M) Web to case es una característica innovadora que te ayuda a recopilar solicitudes de atención al cliente directamente desde el sitio web de su empresa y generar automáticamente hasta 5000 casos nuevos por día.<br>
N) Omnichannel es una funcionalidad de Salesforce, la cual una vez habilitada se puede configurar de forma que permite que un agente, bajo una misma pantalla, pueda recibir casos que hayan entrado a la plataforma a traves de un correo electronico, un chat, etc.<br>
O) Chatter es una funcionalidad de Salesforce de colaboración en tiempo real que permite a sus usuarios trabajar juntos, comunicarse y compartir información.

## 📍EJERCICIO 7
```Apex
global class calloutContact { //Llamada al web service donde obtengo mi mail
    @future(callout = true)
    public static void method1 (ID s1)  {
    Http http = new Http();
    HttpRequest request = new HttpRequest();
    request.setEndpoint('https://procontacto-reclutamiento-default-rtdb.firebaseio.com/contacts/-N8irHtLhYJe4rDSsYRr.json');
    request.setMethod('GET');
    HttpResponse response = new HTTP().send(request);
    System.debug(response);
        if (response.getStatusCode() == 200) {
    // Deserialize the JSON string into collections of primitive data types.
    Map<String, Object> results = (Map<String, Object>)JSON.deserializeUntyped(response.getBody());
    // Cast the values 
    String emailfacu = (String) results.get('email');
    System.debug('Received the following email:');
    System.debug(emailfacu);   
    Contact ctc = [SELECT Email, idprocontacto__c, Id FROM Contact WHERE Id=:s1];
    ctc.Email = emailfacu;
    upsert ctc;
        }  
    }
}

trigger contactTrigger on Contact (before update, after insert) { //Trigger que se ejecuta
        Map<Id,Contact> contactList = new Map<Id,Contact>(
        [SELECT Id, Email, idprocontacto__c FROM Contact WHERE Id IN :Trigger.New]);
        for (Contact a :Trigger.New) {   
            if (contactList.get(a.Id).idprocontacto__c != '-N8irHtLhYJe4rDSsYRr') {
                   calloutContact.method1(contactList.get(a.Id).Id);
            }
        }
}
```






