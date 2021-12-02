# GIFTED 🎁
Gifted es una aplicacion diseñada para evitar quebraderos de cabeza a la hora de hacer un regalo a un ser querido, es basicamente una red social 
en la cual puedes seguir a tus amigos o familiares y ver su lista de regalos deseados. Gracias a Gifted podreis evitar regalos no deseados y 
acertar siempre a la hora de hacer un regalo .
## Pagina web 🌍
Nuestra pagina web cuenta con 4 pestañas diferentes: Inicio, Contactenos, Descargar y el carrito de compra
1. **Inicio 🛫**
    * En esta pestaña es donde encontramos toda la documentacion y explicacion de los servicios de Gifted, encontraemos una descripcion
    del producto, los diferentes servicios como el de hacer un amigo invisible colectivo a traves de la web.
    El servicio de amigo invisible consiste en un juego en el cual un grupo de personas se hacen regalos sin saber quien de ese grupo ha sido el
    que se lo ha regalado.
    La funcionalidad de crear el amigo invisble consiste en que un grupo de personas , que quieran realizar dicha actividad, se conectan 
    a Gifted y la propia web les genera el reparto de personas para el amigo invisible.
    
    ![imagendeinicioGifted](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/GiftedInicio.PNG)
    
    Al final de la pagina , encontraremos la seccion de contactos, redes sociales, licencias, informacion sobre la legislacion, servicios y 
    una breve descripcion aparte del selector de idioma.
    
    ![imagendeinicioGifted](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/Inicio2Gifted.PNG)
    
    
2. **Contactenos 📞**
    * Aqui encontraremos un formulario para realizar cualquier consulta o informar sobre algun problema a nuestros tecnicos, deberas introducir tus 
      datos para enviar la consulta y sera atendida con la mayor brevedad posible.
      Tambien dispone de un telefono de contacto, correo electronico y direccion en google maps de la ubicacion de nuestra sede.
     
      ![imagendeContactanosGifted]( https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/ContactenosGifted.PNG)
      
      
3. **Descargar ⬇️**
    * Esta ventana simplemente tiene una unica funcionalidad que es la de descargar nuestra aplicacion directamente en su dispositivo
  
       ![imagendeContactanosGifted](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/DescargaGifted.PNG)
 
4. **Carrito de compra 🛒**
    * Aqui podremos revisar los regalos que tenemos seleccionados y el informe de pedido, en el cual podremos ver cuanto tiempo queda hasta 
      la entrega del producto.
      
      ![imagendeContactanosGifted](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/CarritoGifted.PNG)
      
      
## Botones personalizados 👨‍💻 

   * En gifted cada detalle cuenta, por ello tenemos una gran variedad de botones personalizados hechos en html/css, aqui les dejamos el codigo CSS:


~~~
.buttonCustom{
border-radius: 5px;
point-events: auto;
cursor:pointer;
background-color: aliceblue;
border: none;
padding: 1.5rem 3rem;
margin:0;
font family:inherit;
font-size: inherit;
position:relative;
display: inline-block;
}
~~~

## Defensa Proyecto 🛡️
* En los siguientes apartados vamos a explicar como hemos realizado la creacion de Gifted y sus diferentes sistemas internos.

**Inicio del servicio**
* Para comenzar debemos iniciar nuestro servicio Odoo, para ello utilizaremos los siguientes comandos: 
~~~
sudo systemctl start odoo14
~~~
* Una vez inciado , comprobamos que efectivamente se ha iniciado el servicio con el siguiente comando
~~~
sudo systemctl status odoo14
~~~
* El servicio inciado correctamente ha de tener este aspecto
![ImagenServicioOdoo]()

**Descargar**
* El codigo de nuestra ventana descargar.

![ImagenCodigoVentanaDescarga](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/CodigoDescargar.png)

**Manejo del trabajo y organizacion**
* Al tener mucha carga de trabajo y muchas tareas que realizar, es conveniente la creacion de un tablero de trabajo para 
poder organizar de manera visual las diferentes tareas u objetivos que tenemos que cumplir
En la foto se puede observar el tablero y las tareas pendientes.

![ImagenTableroTrabajo](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/TableroGifted.png)

**Calendario**
* La creacion de un calendario es algo indispensable para poder tener una buena vision en el tiempo de todas tus actividades
  recordatorios, eventos y reuniones.
  
  ![ImagenCalendario](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/CalendarioGifted.png)
  
**Eventos**
* En Gifted tenemos diferentes eventos, como por ejemplo el evento de navidad el cual tiene inicio desde las 2:00 am del 
    1 de diciembre hasta el 31 de diciembre.
    
    ![ImagenEventoNavidad1](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/EventoNavidad1.png)
    
    ![ImagenEventoNavidad2](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/EventoNavidad2.png)
   
   
**Chat interno**
* En Gifted hemos desarrollado un sistema de "chat" entre usuarios y entre empleados, para facilitar la comunicacion 
    entre nuestros desarrolladores y para que los usuarios puedan comunicarse con nuestros tecnicos y solucionar sus
    diferetenes dudas o problemas a la hora de usar nuestros servicios.
    
    ![ImagenChatGifed](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/SistemaChatGifted.png)
    
**Gestion Base de datos**
* La gestion de la informacion es algo esencial, por lo tanto hemos de crear diferentes copias de seguridad (Backup) de todos nuestros
   datos para, en caso de error, podamos recuperar hasta la ultima copia de seguridad
   
   ![GestionBaseDatos](https://github.com/IkerFernandez21/gifted/blob/patch-1/Documentacion/SistemaBaseDatosGifted.png)
   
   En este caso tenemos nuestra base de datos actual operativa y tambien tenemos la copia de dicha base de datos.
   Al crear copias de seguiridad tenemos que tener en cuenta la seguridad, ya que son datos sensibles de usuarios
   , cuentas y contraseñas entre otros datos.
   Por ello debemos encriptar toda la copia de seguirdad y asi garantizar que es imposible que al abrir esos archivos 
   se pueda leer la informacion contenida en ellos.
   
    
  


