# Arquitectura de aplicaciones#


Describe los patrones y las técnicas que se utilizan para diseñar y desarrollar aplicaciones. La arquitectura le proporciona un plan y las prácticas recomendadas que debe seguir para diseñar una aplicación bien estructurada.
Los patrones de diseño de software pueden ayudarlo a crear una aplicación.

Puede vincularse con otros para crear arquitecturas de aplicaciones más generales. En lugar de volver a crear toda la infraestructura completa, puede usar los patrones de diseño que ya existen, lo cual además garantiza que todo funcione como es debido.
En una arquitectura de aplicaciones, habrá servicios de frontend y de backend.El desarrollo de frontend se refiere a la experiencia del usuario con la aplicación, mientras que el de backend implica proporcionar acceso a los datos, los servicios y otros sistemas que permiten el funcionamiento de la aplicación.

## Tipos de Arquitecturas de aplicaciones##

La capacidad para brindar nuevos servicios y funciones a los clientes con rapidez es una de las características competitivas fundamentales que puede ofrecer una empresa y que marcan la diferencia. Si las empresas agilizan el desarrollo, pueden lanzar características nuevas con mayor frecuencia, así como implementar las actualizaciones en cuanto descubren un punto vulnerable.

En la actualidad, las principales arquitecturas de aplicaciones, basadas en las relaciones entre los servicios, son la arquitectura monolítica y N-tier (con conexión directa), los microservicios (sin acoplamiento) y las arquitecturas basadas en eventos y orientadas al servicio (de bajo acoplamiento).

### Arquitectura en capas o N-tier ###

Es un tipo de arquitectura tradicional que suele utilizarse para diseñar aplicaciones en las instalaciones y empresariales, y que por lo general se asocia con las aplicaciones heredadas.
En esta arquitectura, hay varias capas o niveles (a menudo tres, pero puede haber más) que componen la aplicación, y cada una cumple una función particular. 

Las capas ayudan a gestionar las dependencias y a ejecutar funciones lógicas. En una arquitectura en capas, estas se organizan de forma horizontal, por lo que solo pueden utilizar las funciones de las capas inferiores.

#### Arquitectura monolítica ####

Los monolitos son otro tipo de arquitectura asociado con los sistemas heredados; son pilas de aplicaciones únicas que contienen todas las funciones dentro de cada aplicación. Tienen conexión directa, tanto en la interacción entre los servicios como en la manera en que se desarrollan y distribuyen. 
Esto significa que al actualizar o ajustar un solo aspecto de una aplicación monolítica, no solo habrá una repercusión en ella, sino también en la infraestructura subyacente. 

Un solo cambio en el código de la aplicación implica volver a lanzarla por completo. Por eso las actualizaciones y las nuevas versiones suelen darse una o dos veces al año y no deben incluir características nuevas, sino solo el mantenimiento general.

##### Arquitectura de microservicios #####

Los Microservicios no son solo un tipo de arquitectura, sino también un modo de abordar la escritura del software. Con ellos, las aplicaciones se dividen en sus elementos más pequeños, que son independientes entre sí. Cada uno de dichos elementos o procesos es un microservicio.

Los microservicios se encuentran distribuidos y tienen un nivel bajo de acoplamiento, para no influir en los demás. Esta arquitectura aporta beneficios tanto de escalabilidad dinámica como de tolerancia a fallos: los servicios individuales se pueden ampliar según sea necesario, sin necesidad de una infraestructura pesada o pueden realizar una conmutación por error sin afectar otros servicios.

El objetivo de usar una arquitectura de microservicios es distribuir un software de calidad con mayor rapidez. Puede desarrollar múltiples microservicios de forma simultánea, sin necesidad de volver a diseñar o implementar toda la aplicación después de realizar cambios, ya que los servicios se implementan de forma independiente.


APUNTES CLASE 


![[Pasted image 20230821191101.png]]

Tecnologías para el desarrollo de una aplicación web 
 trabar con git en visual studio code
 hacer el comid del apunte de clase
COMANDOS DIARIOS 

git add
git commit -m se agrego 01
git push

