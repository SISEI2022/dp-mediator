# Mediator - Caso práctico

### Intención

Define un objeto que encapsula la forma en la que múltiples objetos interactúan. El Mediador promueve bajo acoplamiento protegiendo la referenciación explícita de los objetos entre sí, permitiendo que puedas variar esta interacción de manera independiente.

### Clasificación

Patrón conductual

### Vista Estructural

![image](https://user-images.githubusercontent.com/55771796/174451683-4ba06ce9-3f4b-4e3c-a975-ff37c060dd39.png)

### Vista Dinámica

![image](https://user-images.githubusercontent.com/55771796/174451694-05570de4-2497-40ec-b650-b95a586e64b7.png)

### Ejemplo Real

Mediante la implementación del patrón de diseño Mediator desarrollaremos una aplicación modular, la cual tendrá como punto central un Mediador, que funcionará como punto central de comunicación entre todos los módulos, eliminando la dependencia directa que existe entre los módulos para el funcionamiento.

Simularemos un conjunto de módulos que procesen ventas por Internet, el proceso se muestra a continuación:

![image](https://user-images.githubusercontent.com/55771796/174451793-882b5511-ce53-461d-b090-5e05463fc19b.png)


![image](https://user-images.githubusercontent.com/55771796/174451748-f1f62d8d-86cf-45ee-883f-d386e09bd1c0.png)

![image](https://user-images.githubusercontent.com/55771796/174451773-e475bf06-09ac-49f2-94de-67f9a47af4ed.png)

![image](https://user-images.githubusercontent.com/55771796/174451853-3a3f36ca-8fe7-4033-824f-491fbf28d62c.png)







### Ejecucion

```
gradle run
```
