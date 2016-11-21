## BIBLIOTECA EVENTBUS ##

Es una herramienta cuya finalidad es lanzar y  capturar eventos entre clases. Está basada en el patrón  
bus de eventos, y consiste en que uno o varios elementos se subscriben a su canal. Cada uno de estos  
elementos se programan con un método en especifico y esperan el evento para realizar el étodo que se  
les asigno.  

**Ventajas y desventajas de EventBus**

    *Flexibilidad:* con EventBus se pueden realizar numerosas funcionalidades, se podría incluso  
crear una forma de trabajar sobre estos eventos. La desventaja de esto es que al hacer uso de Eventbus,  
este nos provee de herramientas que omiten el uso de herramientas que vienen por default en los programas  
y se podria poner como centro de la aplicación a Eventbus.  

    *Simplicidad:* En tres paso se puede usar esta herramienta. En cualquier parte se llama al método post  
de la instancia de EventBus y se propaga un evento. Esta herramienta nos permite hacer uso de sus metodos  
desde cualquier parte del programa , solo hay que especificar en que hilo se quiere la respuesta.  

    *Agilidad:* ahorramos muchas líneas de código, clases y lógica de interacción que, al fin y al cabo  
(menor tiempo de desarrollo). Solo hay que tener cuidado ya que si algo falla ese tiempo de desarrollo, se  
puede convertir en tiempo de busqueda de errores.  

Eventbus nos permite comunicarnos mediante los lanzamientos de solicitudes a diferentes partes de nuestro  
programa, por medio de los hilos.  

